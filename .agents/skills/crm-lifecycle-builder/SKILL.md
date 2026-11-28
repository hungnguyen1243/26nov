---
name: crm-lifecycle-builder
description: "Thiết kế hệ thống CRM và vòng đời khách hàng gồm dữ liệu cần lưu, phân nhóm, trạng thái, chăm sóc, nuôi dưỡng, chuyển đổi, tái mua, bán thêm, giữ chân và kích hoạt lại. Dùng khi cần xây hoặc chuẩn hóa CRM, thiết kế luồng email/tin nhắn/gọi điện, giảm bỏ sót lead hoặc tăng giá trị vòng đời khách hàng."
ten-viet: "Xây CRM & Vòng Đời Khách Hàng"
nhom: "08. Chăm Sóc & Giữ Khách"
ten-goc: "Xây dựng CRM và vòng đời khách hàng"
---

> TODO: Viết lại cho bất động sản Việt Nam; thêm đầy đủ thang lead nóng/ấm/lạnh, quy tắc chuyển trạng thái và SLA phản hồi lead nóng 15 phút.

# Xây CRM & Vòng Đời Khách Hàng

## Đầu vào

- Hành trình khách hàng, sản phẩm, chu kỳ mua và mục tiêu CRM.
- Dữ liệu khách hàng hiện có, hệ thống/công cụ và quy trình bán hàng.
- Chính sách đồng ý nhận tin, bảo mật và thời gian phản hồi.

## Thang nhiệt lead và SLA

- **Lead nóng:** Có nhu cầu cụ thể, chủ động hỏi giá/chính sách, đặt lịch xem hoặc muốn được tư vấn để ra quyết định. Phản hồi trong **15 phút** trong giờ trực.
- **Lead ấm:** Đã xác định nhóm sản phẩm hoặc mục tiêu nhưng chưa có thời điểm ra quyết định rõ. Chuyển thành nóng khi khách yêu cầu báo giá, lịch xem, phương án tài chính hoặc bước giao dịch cụ thể.
- **Lead lạnh:** Mới tìm hiểu chung hoặc chưa phản hồi sau các lần liên hệ hợp lệ. Chuyển thành ấm khi khách thể hiện nhu cầu, ngân sách, khu vực hoặc thời gian dự kiến.
- Mỗi lần đổi thang nhiệt phải ghi lý do, thời điểm, người phụ trách và lần chăm sóc tiếp theo trong CRM.

## Quy trình

1. Chốt mục tiêu theo từng giai đoạn vòng đời.
2. Chuẩn hóa đối tượng dữ liệu, trường bắt buộc và nguồn tạo dữ liệu.
3. Xây trạng thái lead/khách hàng, gắn thang nóng/ấm/lạnh và điều kiện chuyển trạng thái.
4. Thiết kế phân nhóm theo hồ sơ, hành vi, giá trị và mức sẵn sàng.
5. Xác định kích hoạt, thông điệp, kênh, thời điểm và chủ sở hữu.
6. Xây luồng tiếp nhận, nuôi dưỡng, chuyển bán hàng và theo sau.
7. Xây luồng onboarding, sử dụng, tái mua, bán thêm và kích hoạt lại.
8. Thiết lập SLA, gồm phản hồi lead nóng trong 15 phút, quy tắc tránh trùng, quyền truy cập và xử lý lỗi.
9. Gắn KPI theo giai đoạn và thiết kế thử nghiệm.
10. Kiểm tra tính khả thi với công cụ và năng lực đội ngũ.

## Đầu ra

- Sơ đồ vòng đời và trạng thái.
- Từ điển dữ liệu CRM tối thiểu.
- Quy tắc phân nhóm và chuyển trạng thái.
- Ma trận kích hoạt–thông điệp–kênh–thời điểm.
- Luồng chăm sóc và điểm bàn giao.
- KPI, SLA, phân quyền và quy tắc chất lượng dữ liệu.

## Bảo vệ dữ liệu

Chỉ thu thập dữ liệu cần thiết; không đưa dữ liệu nhận dạng cá nhân vào công cụ AI nếu chưa được phép; luôn tôn trọng lựa chọn từ chối nhận tin.

---

## Ghi kết quả vào đâu

> [!important] Không ghi vào vault thì coi như chưa làm
> Kết quả chỉ hiện trong khung chat sẽ mất khi đóng phiên. Hệ thống chỉ thông minh bằng đúng dữ liệu được ghi lại.

| | |
|---|---|
| **Thư mục** | `03. Areas/Sales Pipeline & CRM/` |
| **Tên file** | `Vòng Đời Khách Hàng.md` |
| **Bắt buộc** | Link tới `Hành Trình Khách Hàng` và các `PK*` |

Sau khi ghi xong, báo lại cho người dùng **đường dẫn đầy đủ** của file vừa tạo để họ mở kiểm tra.
