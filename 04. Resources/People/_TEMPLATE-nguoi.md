---
loai: nguoi
vai_tro: khach
trang_thai: moi
ngay_gap_dau: null
lan_cuoi_gap: null
hen_tiep: null
kenh_gap: null
nguon_gap: null
khu_quan_tam: []
loai_can_quan_tam: []
ngan_sach: null
da_co_gi: []
chua_biet_gi: []
dich_vu_can: []
nhan: []
---

# {{title}}

> Không ghi dữ liệu khách thật vào mẫu này. Mỗi dữ kiện cần nhãn nguồn và ngày; hồ sơ thật bị loại khỏi Git.

## Ba dòng tóm tắt
- `CAN-XAC-MINH`: [điều cần hỏi/đối chiếu]

## Họ đã nói (nguyên văn, có ngày)
- [YYYY-MM-DD] `TU-KHACH`: “...” — nguyên văn theo [ghi âm/ghi chép]; nếu nhớ lại, ghi rõ không phải trích nguyên văn.

## Nỗi sợ / rào cản
- `SUY-LUAN`: [giả thuyết] — cần kiểm tra bằng [câu hỏi/hành động].

## Đã giải thích gì
- [YYYY-MM-DD] `QUAN-SAT`: [đã gửi/đã trình bày nội dung gì, cho ai, nguồn tài liệu/phiên bản nào].

## Chưa giải thích gì
- `CAN-XAC-MINH`: [nội dung và việc tiếp theo].

## Đã hứa gì (kèm ngày)
- [YYYY-MM-DD] `QUAN-SAT`: [ai hứa điều gì, thời hạn, đã xác nhận/chưa xác nhận].

## Người cạnh tranh
- `CAN-XAC-MINH`: [chỉ ghi nhu cầu có liên quan; không suy đoán hoặc lưu thừa dữ liệu người thứ ba].

## Quan sát cần thiết
- [YYYY-MM-DD] `QUAN-SAT`: [hành vi cụ thể, liên quan buổi tư vấn]. Tránh mô tả ngoại hình/đồ dùng nếu không cần.

## Lịch sử gặp

```dataview
TABLE ngay, kenh, ket_qua, viec_tiep
FROM "04. Resources/Meetings"
WHERE contains(nguoi, this.file.link)
SORT ngay DESC
```
