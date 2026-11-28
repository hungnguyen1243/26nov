---
tags: [moc, huong-dan, folder-map]
updated: 2026-11-28
---

# Cây Thư Mục & Quy Trình Sử Dụng

> Bản đồ làm việc cho vault cá nhân Trúc Võ Realty. README là trang mở đầu; tài liệu này giải thích chi tiết nơi lưu, luồng xử lý và quy tắc cập nhật.

## Cây thư mục chính

```text
26nov / Trúc Võ Realty
├── README.md                         Trang bắt đầu và workflow tổng
├── AGENTS.md                         Quy tắc làm việc cho Codex
├── MOC/                              Các trang điều hướng
│   ├── Bản Đồ Tổng Thể Project.md    Sơ đồ hệ thống Mermaid
│   └── Content Calendar.md           Điều hướng lịch nội dung
├── 00. Business Context/             Nguồn chuẩn doanh nghiệp và sản phẩm
│   ├── 00_Mo_Hinh_Kinh_Doanh.md      Hồ sơ doanh nghiệp + mô hình kinh doanh
│   ├── 01_Chan_Dung_CEO.md
│   ├── 02_Dinh_Vi_Thuong_Hieu.md
│   ├── 03_Brand_Voice.md
│   └── Sản Phẩm & Dịch Vụ/
│       ├── Saigon Park — Tóm Tắt Tài Liệu Sản Phẩm.md
│       ├── VHSP — Số liệu vận hành.md     Bản nhận số liệu, đang chờ đối chiếu
│       ├── CSBH — Bộ tài liệu nguồn.md
│       ├── Quy Trình Cập Nhật Dữ Liệu VHSP.md
│       └── Nguồn/                    Nguồn gốc lưu ngoài Git
│           ├── Bảng Giá/             XLSX gốc, theo ngày/phiên bản
│           ├── Tổng Mặt Bằng/        PDF TMB gốc
│           ├── Pháp Lý/              Văn bản pháp lý gốc
│           └── Tiến Độ/              Ảnh/video gốc, có ngày chụp
├── 01. Inbox/                        Tài liệu mới, chưa phân loại
│   ├── README.md                     Quy trình xử lý Inbox
│   ├── [Mẫu] Cập Nhật VHSP.md        Mẫu nhận bảng giá/Zalo/nguồn mới
│   └── tmb_raw/                      PDF/ảnh thô, bị loại khỏi Git
├── 02. Projects/                     Việc có mục tiêu và ngày kết thúc
│   ├── Chuẩn Hóa Hồ Sơ VHSP.md       Project chuẩn hóa dữ liệu sản phẩm
│   ├── Căn Hộ Chuyển Nhượng Vinhomes Grand Park.md
│   └── Xưởng Video AI/               Project sản xuất video (nếu còn hoạt động)
├── 03. Areas/                        Vận hành duy trì liên tục
│   ├── Brand & Content/              Định hướng và trụ cột nội dung
│   ├── Sales Pipeline & CRM/         Quy trình CRM, pipeline, mẫu theo dõi
│   └── Analytics & Reporting/        Tracking, báo cáo, CSKH
├── 04. Resources/                    Tài liệu tham khảo và dùng lại
│   ├── Case-Study/                   Tình huống theo dự án gốc
│   │   ├── _MOC Case Study.md         Mục lục, quy tắc nguồn và hạn dùng
│   │   └── CASE-VHSP-02.md            Case nháp, chưa xác minh bài báo
│   ├── Doi-Thu/                      Hồ sơ quan sát đối thủ
│   │   └── Loan Cần Giờ.md            Chỉ số/nội dung chờ bằng chứng
│   ├── Market & Competitor Research/ Nghiên cứu thị trường/đối thủ
│   ├── Goc-Nhin/                     Ý kiến/nhận định chờ xác minh
│   │   └── 04 — Câu hỏi thực địa...   Ngân hàng câu hỏi, chưa xác minh
│   ├── Playbooks/                    Hướng dẫn tư vấn, nội dung, quy trình
│   │   └── 5 Phút & 20 Hỏi Đáp.md     Bản nháp, chưa xác minh số liệu
│   ├── VHSP-Du-Lieu/                 CSV, thẻ căn, báo cáo và nhật ký CSBH
│   ├── People/                       CRM cục bộ, loại khỏi Git
│   │   ├── QUY-UOC-DU-LIEU-NGUOI.md  Quy tắc nguồn và bảo mật
│   │   ├── _TEMPLATE-nguoi.md        Mẫu hồ sơ trống
│   │   └── _MOC.md                  Bảng theo dõi Dataview
│   ├── Meetings/                     Biên bản cục bộ, loại khỏi Git
│   │   └── _TEMPLATE-gap.md          Mẫu biên bản trống
│   ├── Feedback & Chứng Thực/        Phản hồi đã ẩn danh, case study được duyệt
│   ├── VEai — *.md                   Nội dung Venice AI, chưa xác minh
│   └── Templates/ và Frameworks/     Mẫu và khung dùng lại
├── 05. Archive/                      Việc/tài liệu đã đóng, giữ lịch sử
├── 50. Triển Khai 90 Ngày/           Lộ trình và checklist nghiệm thu
│   ├── Giáo Án 5 Buổi Chuyển Giao.md
│   └── Trúc Võ Realty — Bản Đồ Project.excalidraw
├── People/                           Thư mục mẫu cũ; CRM mới lưu trong 04. Resources/People/
├── Companies/                        Hồ sơ doanh nghiệp/đối tác liên quan
├── Meetings/                         Thư mục cũ; biên bản mới lưu trong 04. Resources/Meetings/
├── Decisions/                        Quyết định vận hành đã chốt
├── .agents/skills/                   Quy trình AI theo từng nhiệm vụ
├── .claude/skills/                   Tương thích với Claude Code
└── .obsidian/                        Cấu hình Obsidian và plugin
```

Các thư mục `workspace/`, `.pnpm-store/`, `Media Lib/`, `node_modules/`, `.git/` và cache là công cụ/đầu ra máy; không dùng làm nơi ghi tri thức. Không commit `.env`, token, mật khẩu, dữ liệu khách hàng định danh hay CRM thô lên GitHub; repo hiện private. Hồ sơ trong `People/`, `04. Resources/People/` và `04. Resources/Meetings/` bị loại khỏi Git; chỉ quy ước, MOC và mẫu trống được theo dõi.

## Chọn đúng nơi lưu

| Nếu nội dung là… | Lưu vào… | Ví dụ |
|---|---|---|
| Quy tắc ổn định về thương hiệu/mô hình | `00. Business Context/` | Định vị, phân khúc, giọng viết |
| Tệp nguồn công ty | `00. Business Context/Sản Phẩm & Dịch Vụ/Nguồn/` | XLSX, PDF CSBH, pháp lý, ảnh tiến độ |
| File mới chưa biết dùng vào đâu | `01. Inbox/` | Tin Zalo, bản giá mới, tài liệu mới |
| Việc có đầu ra và ngày hoàn tất | `02. Projects/` | Chuẩn hóa hồ sơ sản phẩm |
| Quy trình lặp lại, không có điểm kết thúc | `03. Areas/` | CRM, sản xuất nội dung, đo lường |
| Nghiên cứu, hướng dẫn, nội dung tái sử dụng | `04. Resources/` | Phân tích đối thủ, playbook, VEai |
| Việc đã xong hoặc phiên bản hết hiệu lực | `05. Archive/` | Project đóng, CSBH cũ có giá trị lịch sử |

## Luồng làm việc hằng ngày

1. **Nhận:** đặt nguồn mới vào `01. Inbox/`; điền mẫu nếu liên quan sản phẩm.
2. **Gọi xử lý:** nhắn Codex nêu mục tiêu: tóm tắt, trích bảng, so sánh bản cũ, kiểm tra thiếu dữ liệu hay cập nhật ghi chú nào.
3. **Phân loại:** xác định nguồn/ngày/phiên bản, độ tin cậy và phạm vi áp dụng.
4. **Đối chiếu:** số liệu giá dùng XLSX/SalePro; chính sách dùng PDF đúng phiên bản; pháp lý dùng văn bản gốc; tiến độ ghi ngày/địa điểm ảnh.
5. **Duyệt:** Trúc duyệt nội dung thương mại, pháp lý, giá, chính sách và nội dung công khai.
6. **Lưu:** giữ file gốc ở `Nguồn/`, bản tra cứu ở Business Context hoặc Resources, thêm liên kết ngược.
7. **Đóng:** đánh dấu Inbox đã lưu; project hoàn tất chuyển Archive; ghi quyết định quan trọng vào `Decisions/`.

Thả file vào Inbox không tự khởi chạy chuyển đổi. Khi Trúc gọi Codex, Codex giữ nguyên tệp nguồn và tạo bản tra cứu nhẹ có ngày, nguồn và kiểm tra đối chiếu. Không cho Codex tự đổi status thẻ căn; không trộn CSBH CĐT với HĐCN; tin Zalo không vào Business Context nếu chưa được Trúc duyệt.

## Quy tắc cho dữ liệu VHSP

- SalePro dùng để kiểm tra tình trạng căn tại thời điểm tra; ghi thời gian check. Không lưu một bản sao toàn bộ giỏ căn mỗi ngày.
- Tạo snapshot khi bảng giá thay đổi hoặc cần lịch sử; ghi mã căn, giá theo từng loại, trạng thái, ngày và nguồn.
- Tin Zalo là `NGUỒN CUNG CẤP` cho tới khi đối chiếu; không tự xem tin nhắn là chính sách chính thức.
- Giữ XLSX gốc; dùng CSV/TSV cho bảng dài và Markdown cho phần hướng dẫn, điểm thay đổi, nguồn và cảnh báo.
- Ảnh tiến độ luôn kèm ngày chụp/khu vực; phối cảnh và ảnh marketing không tự chứng minh hiện trạng.
- Ghi chú `VEai` là đầu vào tham khảo; chỉ chuyển ý đã xác minh và được duyệt vào nguồn chuẩn.

## Trạng thái dùng chung

`MỚI` → `ĐANG ĐỐI CHIẾU` → `CHỜ TRÚC DUYỆT` → `ĐÃ ĐỐI CHIẾU` → `ĐÃ LƯU`.

“Đã xác minh” luôn phải có nguồn và vị trí đối chiếu (trang PDF, sheet/ô, URL hoặc thời gian kiểm tra). Trạng thái hàng còn bán chỉ đúng tại thời điểm tra.

## Cách dùng skills

- Khám phá khách: `discovery-call-script`.
- Soạn cuộc gọi/tin nhắn tư vấn: `sales-script`.
- Làm rõ băn khoăn: `objection-handler`.
- Quy trình lead/CRM: `crm-lifecycle-builder`.
- Nội dung: `content-pillar-builder` → `content-copywriter` hoặc `video-script`.
- Kiểm duyệt trước công khai: `tuan-thu-nganh-vn`.

Skills tạo bản nháp; người có thẩm quyền duyệt trước khi gửi, đăng hoặc dùng số liệu thương mại.

## Ghi chú cá nhân

Dùng vault làm “bộ não ngoài” và GitHub private làm lịch sử phiên bản cho tài liệu đã chọn lọc. Không cần ghi tất cả mọi thứ: lưu cái giúp ra quyết định, làm lại quy trình, hoặc truy lại nguồn. Không đưa chat riêng, danh bạ hay dữ liệu khách nhận diện được vào kho Git.
