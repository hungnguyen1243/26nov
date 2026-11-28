---
tags: [project, vinhomes-saigon-park, product-data]
status: dang-lam
owner: Trúc
created: 2026-11-27
deadline: can-chot
---

# Chuẩn Hóa Hồ Sơ VHSP

## Mục tiêu
Tạo bộ tra cứu có nguồn gốc và ngày cập nhật rõ cho sản phẩm Vinhomes Saigon Park: giá/căn, chính sách, pháp lý và tiến độ. Tách PDF/XLSX/ảnh gốc khỏi bản Markdown nhẹ dùng để tìm và hỏi đáp.

## Người phụ trách
- Chủ dự án và người duyệt nội dung tư vấn: Trúc.
- Hỗ trợ trích xuất, so sánh phiên bản, soạn bản nháp: Codex khi Trúc đưa tài liệu trong Inbox và yêu cầu xử lý.

## Hạn
Chưa chốt. Chọn ngày nghiệm thu sau khi đưa đủ bảng giá, bộ pháp lý và ảnh tiến độ vào Inbox.

## Quy tắc nguồn
- Tệp gốc được giữ nguyên trong `00. Business Context/Sản Phẩm & Dịch Vụ/Nguồn/`.
- Bản Markdown là bản tra cứu, không thay thế PDF/XLSX/hợp đồng.
- Mỗi con số phải có tên tệp, ngày/phiên bản và sheet/trang/dòng liên quan nếu xác định được.
- Ghi nhãn `ĐÃ ĐỐI CHIẾU`, `NGUỒN CUNG CẤP`, `VEai`, hoặc `CẦN XÁC MINH`.
- Không đưa danh sách khách hàng, số điện thoại hay dữ liệu cá nhân vào GitHub.

## Cách xử lý bảng XLSX
1. Đưa bản gốc vào `Nguồn/Bảng Giá/` và ghi ngày nhận/phiên bản.
2. Đưa vào `01. Inbox/` rồi nhắn Codex xử lý; việc thả file vào thư mục không tự chạy chuyển đổi.
3. Giữ nguyên XLSX; trích cấu trúc, các cột quan trọng, phạm vi giá, điều kiện, ngày hiệu lực và các dòng cần kiểm tra.
4. Tạo ghi chú Markdown nhẹ `Bảng Giá VHSP — YYYY-MM-DD.md`; nếu bảng căn dài, tạo CSV/TSV tra cứu thay vì nhồi hàng trăm dòng vào Markdown.
5. So sánh số dòng, mã căn và tổng kiểm tra với XLSX. Ghi lại sheet/ô nguồn và thông báo các dòng lỗi/thiếu.
6. Chỉ đưa bản đã Trúc duyệt vào nguồn tra cứu chính; bản chưa duyệt ở Inbox.

## Cấu trúc nguồn
- `Nguồn/Bảng Giá/` — XLSX gốc và các phiên bản.
- `Nguồn/CSBH 19-11-2026/` — bốn PDF CSBH V12/V13/V06/V07.
- `Nguồn/Tổng Mặt Bằng/` — hai PDF TMB ngày 17–18/09/2026.
- `Nguồn/Pháp Lý/` — văn bản pháp lý/hợp đồng do người dùng cung cấp.
- `Nguồn/Tiến Độ/` — ảnh/video gốc, ghi ngày chụp và vị trí nếu biết.

## Tiêu chí hoàn tất
- [ ] Bảng giá có ngày, phiên bản, mã căn, trạng thái căn và điều kiện giá; mọi cột chưa biết được ghi rõ.
- [ ] Bảng Markdown/CSV khớp kiểm đếm với XLSX gốc và có dẫn sheet/ô.
- [ ] Mỗi bộ CSBH có ghi chú đúng phạm vi, điều kiện và trang nguồn; không gọi “hiện hành” nếu chưa xác nhận.
- [ ] Hồ sơ pháp lý liệt kê văn bản, cơ quan/pháp nhân, ngày, phạm vi và câu hỏi chưa được giải đáp; không tự kết luận pháp lý.
- [ ] Ảnh tiến độ được lập chỉ mục theo ngày chụp, địa điểm và nguồn; không suy ra tiến độ tổng thể từ một ảnh.
- [ ] Các ghi chú VEai vẫn tách riêng tới khi đối chiếu.
- [ ] Trúc duyệt bộ tra cứu trước khi dùng với khách.

## Tài liệu liên quan
- [[Saigon Park — Tóm Tắt Tài Liệu Sản Phẩm]]
- [[CSBH — Bộ tài liệu nguồn]]
- [[VEai — VHSP — CSBH 19.11.2026 (V12-V13-V06-V07)]]
- [[VEai — Sổ Theo Dõi Phiên Bản Chính Sách]]
- [[VEai — Cấu Trúc TMB & Xếp Hạng Quỹ Căn]]
- [[Nguồn Tài Liệu Sản Phẩm Trên Máy]]

## Việc cần Trúc bổ sung
- Bảng giá niêm yết XLSX bản mới nhất.
- Hồ sơ pháp lý gốc và/hoặc danh sách văn bản cần lập chỉ mục.
- Ảnh tiến độ kèm ngày chụp và khu vực.
- Ngày cần hoàn tất và người duyệt cuối (mặc định Trúc).

- [[Quy Trình Cập Nhật Dữ Liệu VHSP]]
- [[Cập Nhật VHSP — mẫu Inbox|Mẫu Inbox cập nhật]]

