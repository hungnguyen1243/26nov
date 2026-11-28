---
loai: quy-uoc
tags: [people, privacy, crm]
updated: 2026-11-28
---
# Quy ước dữ liệu người

> Hồ sơ trong thư mục này là dữ liệu CRM cá nhân. Chỉ nhập điều khách tự nguyện cung cấp hoặc quan sát cần thiết cho việc tư vấn; không đưa hồ sơ thật lên GitHub. Repo hiện public.

## Đặt tên file

Dùng `Tên gọi được - mã ngắn.md`, ví dụ `Chị Hương - AS70.md` hoặc `Anh Dũng - gioi-thieu.md`. Không dùng họ tên đầy đủ trong tên file. Dùng tên gọi đủ để nhận biết trong công việc; nếu vẫn có thể nhận ra người từ bối cảnh, coi là dữ liệu định danh.

Số điện thoại nếu thật sự cần lưu thì che 3 số cuối, ví dụ `0903.xxx.789`. Không ghi CCCD trong CRM; chỉ xử lý giấy tờ định danh trong hồ sơ giao dịch được bảo vệ khi đã phát sinh giao dịch và có căn cứ phù hợp.

## Nhãn nguồn bắt buộc

Mọi câu nói, nhu cầu, tài chính, nhận định, lời hứa và quan sát về một người phải có nhãn cùng ngày khi biết:

- `TU-KHACH` — khách nói trực tiếp. Chỉ đặt ngoặc kép khi ghi nguyên văn theo ghi âm/ghi chép đáng tin; nếu chép lại từ trí nhớ, nói rõ.
- `QUA-DONG-NGHIEP` — người đồng nghiệp/sale khác cung cấp; ghi người/kênh và ngày nếu có.
- `QUAN-SAT` — việc quan sát trực tiếp, chỉ ghi điều cần thiết cho công việc.
- `SUY-LUAN` — giả thuyết của Trúc, không trình bày như sự thật; ghi cách cần kiểm tra.
- `CAN-XAC-MINH` — nguồn/chi tiết còn thiếu hoặc chưa đối chiếu; treo lại và hỏi đúng người.

Không có nhãn thì không ghi thông tin đó. Cùng nguyên tắc truy nguồn như giá và CSBH. Dữ liệu lấy từ bản nhập/ghi chú chưa có bằng chứng gốc phải thêm `CAN-XAC-MINH`, kể cả khi bản nhập gắn nhãn khác.

## Không ghi

- Nhận xét chung chung hoặc miệt thị như “khách khó tính”; ghi hành vi cụ thể, có liên quan và nguồn.
- Lời hứa không có ngày, người hứa, nội dung và trạng thái thực hiện.
- Giá nói miệng thiếu căn cứ, thời điểm và phiên bản CSBH.
- CCCD, thông tin sức khỏe, thông tin gia đình hoặc tài chính không cần thiết cho giao dịch.
- Thông tin người thứ ba nếu chưa cần và chưa có quyền ghi nhận/chia sẻ.

## Việc tiếp và trạng thái

Hồ sơ đang được tư vấn phải có `hen_tiep` đã thống nhất hoặc cần xác nhận. Nếu chưa có lịch tiếp theo, dùng `hen_tiep: null`, chuyển `trang_thai: treo` và ghi lý do có nhãn nguồn. Không tự đặt lịch thay khách.

Sau mỗi lần liên hệ thật, cập nhật ngày/kênh/kết quả và `lan_cuoi_gap`. Không tạo cuộc gặp, trích dẫn hay bước tiếp theo để lấp mẫu. `mat` chỉ dùng khi khách từ chối tiếp tục hoặc yêu cầu ngừng, kèm ngày và nguồn.

## Bảo mật Git

Hồ sơ người và biên bản có thể định danh trong `04. Resources/People/` và `04. Resources/Meetings/` bị loại khỏi Git. Chỉ `_TEMPLATE-nguoi.md`, `_TEMPLATE-gap.md`, `_MOC.md` và quy ước trống được theo dõi. Trước khi commit, kiểm tra cả `git status` lẫn `git check-ignore`; không đẩy hồ sơ CRM lên repo GitHub.
