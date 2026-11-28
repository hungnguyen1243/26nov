---
tags: [inbox, workflow]
---

# Inbox — Quy trình tiếp nhận

Đưa file mới hoặc bản nháp vào đây, rồi nhắn Codex tên file và yêu cầu xử lý. Thả file vào thư mục chưa tự kích hoạt xử lý.

## Trách nhiệm
- Trúc: cung cấp bối cảnh/mục đích sử dụng và duyệt thông tin nhạy cảm.
- Codex: phân loại, lập chỉ mục nguồn, trích xuất bản nháp, đánh dấu khoảng trống và đề xuất nơi lưu.

## Khi nào chuyển khỏi Inbox
Chỉ chuyển sau khi ghi được nguồn, ngày/phiên bản, chủ đề, mục đích và trạng thái xác minh. PDF/XLSX/ảnh gốc chuyển vào `00. Business Context/Sản Phẩm & Dịch Vụ/Nguồn/`; bản tra cứu đã duyệt chuyển vào ghi chú sản phẩm; nội dung tham khảo/VEai vào `04. Resources`; công việc có mục tiêu và hạn vào `02. Projects`; nội dung vận hành dài hạn vào `03. Areas`.

## Trạng thái
- `MỚI`: chưa đọc.
- `ĐANG XỬ LÝ`: đang trích xuất/đối chiếu.
- `CẦN BỔ SUNG`: thiếu nguồn, ngày, phạm vi hoặc bối cảnh.
- `CHỜ DUYỆT`: bản nháp đã có nguồn nhưng chưa được Trúc duyệt.
- `ĐÃ XÁC MINH`: đã đối chiếu với tài liệu gốc, ghi vị trí nguồn và ngày kiểm tra.
- `ĐÃ LƯU`: bản cuối đã đặt đúng thư mục và có liên kết ngược về nguồn.

Không gọi là xác minh chỉ vì nội dung đọc được trong file; số liệu cần truy về trang/sheet/ô và điều kiện áp dụng.

## Bảo vệ dữ liệu
Không đưa thông tin khách hàng định danh, mật khẩu, token hoặc credential vào Inbox của repo/GitHub. Ẩn danh trước khi dùng làm ví dụ.

Mẫu cho dữ liệu SalePro/Zalo: [[Cập Nhật VHSP — mẫu Inbox]]. Quy trình đối chiếu: [[Quy Trình Cập Nhật Dữ Liệu VHSP]].

