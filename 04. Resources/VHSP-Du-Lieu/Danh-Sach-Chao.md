# Danh sách chào VHSP

Nguồn dữ liệu bảng chào: [[salepro-index.json]] (snapshot sheet đầu tiên của SalePro ngày 2026-11-27). 591 mã được giữ cho bảng chào; liên kết mở thẻ đối chiếu nếu mã có trong cả hai nguồn. Mã chỉ có trong Excel hiện dạng chữ và chưa có thẻ TMB. Hai cơ sở giá được xếp hạng riêng.

## Rẻ nhất theo đơn giá

Hiển thị tối đa 10 mã rẻ nhất trong mỗi cơ sở: `gia_tts` và `gia_niem_yet`.

```dataviewjs
const data = JSON.parse(await dv.io.load("04. Resources/VHSP-Du-Lieu/salepro-index.json")).items;
const cards = new Map();
for (const p of dv.pages("\"04. Resources/VHSP-Du-Lieu/The-CaN\"")) cards.set(p.ma_can, p.file.link);
for (const base of ["gia_tts", "gia_niem_yet"]) {
  const rows = data.filter(p => p.co_so_don_gia === base)
    .sort((a, b) => a.don_gia_tr_m2 - b.don_gia_tr_m2).slice(0, 10);
  dv.header(3, base);
  dv.table(["Mã căn", "Phân khu", "Đơn giá (triệu/m²)", "Giá niêm yết (đồng)", "Giá TTS (đồng)", "Cơ sở đơn giá"],
    rows.map(p => [cards.get(p.ma_can) ?? `${p.ma_can} (chưa có thẻ TMB)`, p.phan_khu, p.don_gia_tr_m2, p.gia_niem_yet, p.gia_tts ?? "chua_co", p.co_so_don_gia]));
}
```

## 10 lô đắt nhất theo đơn giá

Hiển thị tối đa 10 mã đắt nhất trong mỗi cơ sở giá, xếp riêng theo `gia_tts` và `gia_niem_yet`.

```dataviewjs
const data = JSON.parse(await dv.io.load("04. Resources/VHSP-Du-Lieu/salepro-index.json")).items;
const cards = new Map();
for (const p of dv.pages("\"04. Resources/VHSP-Du-Lieu/The-CaN\"")) cards.set(p.ma_can, p.file.link);
for (const base of ["gia_tts", "gia_niem_yet"]) {
  const rows = data.filter(p => p.co_so_don_gia === base)
    .sort((a, b) => b.don_gia_tr_m2 - a.don_gia_tr_m2).slice(0, 10);
  dv.header(3, base);
  dv.table(["Mã căn", "Phân khu", "Đơn giá (triệu/m²)", "Giá niêm yết (đồng)", "Giá TTS (đồng)", "Cơ sở đơn giá"],
    rows.map(p => [cards.get(p.ma_can) ?? `${p.ma_can} (chưa có thẻ TMB)`, p.phan_khu, p.don_gia_tr_m2, p.gia_niem_yet, p.gia_tts ?? "chua_co", p.co_so_don_gia]));
}
```

## Toàn bộ LK_G và SL_G

Gồm toàn bộ mã LK_G/SL_G trong snapshot Excel, kể cả mã chưa có trong sổ TMB.

```dataviewjs
const data = JSON.parse(await dv.io.load("04. Resources/VHSP-Du-Lieu/salepro-index.json")).items;
const cards = new Map();
for (const p of dv.pages("\"04. Resources/VHSP-Du-Lieu/The-CaN\"")) cards.set(p.ma_can, p.file.link);
const rows = data.filter(p => ["LK_G", "SL_G"].includes(p.loai_hinh))
  .sort((a, b) => a.loai_hinh.localeCompare(b.loai_hinh) || a.don_gia_tr_m2 - b.don_gia_tr_m2);
dv.table(["Mã căn", "Loại hình", "Phân khu", "Đơn giá (triệu/m²)", "Giá niêm yết (đồng)", "Giá TTS (đồng)", "Cơ sở đơn giá"],
  rows.map(p => [cards.get(p.ma_can) ?? `${p.ma_can} (chưa có thẻ TMB)`, p.loai_hinh, p.phan_khu, p.don_gia_tr_m2, p.gia_niem_yet, p.gia_tts ?? "chua_co", p.co_so_don_gia]));
```
