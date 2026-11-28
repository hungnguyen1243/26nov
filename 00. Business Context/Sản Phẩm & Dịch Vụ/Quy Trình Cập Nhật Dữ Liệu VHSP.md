---
tags: [product-data, workflow, salepro, zalo]
status: operating-procedure-draft
updated: 2026-11-27
---

# Quy Trình Cập Nhật Dữ Liệu VHSP

> Quy ước làm việc từ giao diện SalePro và thông tin cập nhật do Trúc cung cấp. SalePro là nơi kiểm tra giỏ căn hiện tại; ghi chú này mô tả cách lưu và đối chiếu, không thay thế hệ thống nguồn.

## Nguyên tắc chọn nơi lưu

- **SalePro:** hiện trạng giỏ căn để tra cứu trực tiếp. Trạng thái căn có thể đổi; kiểm tra lại ngay trước khi báo khách/đặt giữ.
- **Nguồn trong Business Context:** bản gốc do công ty phát hành như bảng giá, CSBH, TMB, pháp lý, tài liệu bàn giao và tiến độ.
- **Obsidian:** chỉ lưu chỉ mục, cách hiểu đã đối chiếu, thay đổi quan trọng, lịch sử phiên bản và câu hỏi còn thiếu.
- **Inbox:** bản tin Zalo, ảnh chụp, file mới hoặc nội dung chưa phân loại. Trúc đưa vào đây và gọi Codex xử lý; việc thả file không tự kích hoạt.

## Giỏ căn SalePro

Không chép toàn bộ hàng trăm mã căn vào ghi chú Obsidian mỗi ngày. Khi cần theo dõi một mã hoặc thay đổi đáng kể, ghi tối thiểu:

| Trường | Cách ghi |
|---|---|
| Mã căn | Mã hiển thị trong SalePro |
| Thời điểm kiểm tra | Ngày, giờ, múi giờ |
| Trạng thái | Đúng nhãn hệ thống tại lúc kiểm tra; không diễn giải thành cam kết |
| Giá niêm yết / giá TTS / giá vay | Ghi riêng từng loại, kèm đơn vị và điều kiện hiển thị |
| Loại hình, diện tích đất/xây dựng | Chép đúng nhãn và đơn vị |
| Hướng, phân khu, bàn giao | Chép theo chi tiết mã căn |
| CSBH áp dụng | Phiên bản/ngày mà SalePro hiển thị; đối chiếu PDF gốc |
| Nguồn | SalePro, URL nếu được phép, ảnh/file chụp và thời điểm |
| Ghi chú | Khác biệt với lần trước hoặc điểm cần xác minh |

Khi bấm vào mã căn, chụp/ghi phần chi tiết và thời điểm check nếu có thay đổi hoặc cần chứng minh nội bộ. Nút “Check căn/Lock căn” là thao tác trên hệ thống công ty: chỉ Trúc thực hiện theo quyền và quy trình SalePro; Codex không thao tác thay.

## Thông tin nhỏ giọt từ Zalo

1. Chỉ đưa vào Inbox nội dung làm thay đổi thông tin sản phẩm: giá, trạng thái căn, CSBH, pháp lý, bàn giao, tiến độ hoặc thông báo chính thức.
2. Lưu ảnh chụp/tệp gốc khi cần giữ bằng chứng; ghi ngày giờ nhận, nhóm/người gửi theo vai trò nếu cần, chủ đề và mã căn liên quan.
3. Gắn trạng thái `NGUỒN CUNG CẤP` nếu mới là tin nhắn; không biến thành dữ kiện đã xác minh.
4. Đối chiếu SalePro, PDF/thông báo gốc hoặc người phụ trách. Ghi rõ nguồn nào mới hơn và phạm vi áp dụng.
5. Cập nhật ghi chú chỉ mục/lịch sử khi có thay đổi; giữ các snapshot có giá trị lịch sử, không ghi đè bằng tin nhắn mới.
6. Bỏ qua hội thoại cá nhân, tin không liên quan, dữ liệu khách và thông tin liên hệ. Không lưu danh sách khách, số điện thoại hoặc ảnh hồ sơ khách trong repo GitHub.

## Bảng giá Excel

Giữ XLSX gốc bất biến tại `Nguồn/Bảng Giá/`. Khi Trúc yêu cầu xử lý, tạo bản tra cứu mới có ngày, không tự đồng bộ mỗi lần file đổi. Với bảng dài, dùng CSV/TSV làm dữ liệu tra cứu và Markdown làm trang hướng dẫn/tổng hợp; không ép toàn bộ bảng vào một note. So sánh mã căn, số dòng, giá và trạng thái mẫu trước khi chấp nhận bản xuất.

## Nhịp kiểm tra

- Trước khi tư vấn một căn cụ thể: kiểm tra lại SalePro ngay lúc đó và ghi giờ kiểm tra trong ghi chú tư vấn nội bộ phù hợp.
- Khi nhận CSBH mới: xác định phiên bản, ngày, nhóm giao dịch và căn áp dụng; cập nhật sổ phiên bản.
- Khi nhận ảnh/video tiến độ: giữ tệp gốc, ghi ngày chụp và khu vực; không suy diễn tiến độ tổng thể từ ảnh đơn lẻ.
- Định kỳ dọn Inbox: bản đã xử lý cần liên kết tới nơi lưu cuối; bản trùng/không dùng có thể bỏ khỏi Inbox theo quyết định của Trúc.

## Trạng thái xác minh

`MỚI` → `ĐANG ĐỐI CHIẾU` → `CHỜ TRÚC DUYỆT` → `ĐÃ ĐỐI CHIẾU` → `ĐÃ LƯU`.

Ghi **ĐÃ ĐỐI CHIẾU** chỉ khi có nguồn gốc và mốc kiểm tra; với trạng thái còn hàng/giữ căn, kết quả chỉ đúng tại thời điểm check.

## Liên kết

- [[Chuẩn Hóa Hồ Sơ VHSP]]
- [[Saigon Park — Tóm Tắt Tài Liệu Sản Phẩm]]
- [[Nguồn Tài Liệu Sản Phẩm Trên Máy]]
- [[_MOC Sản Phẩm & Dịch Vụ]]
