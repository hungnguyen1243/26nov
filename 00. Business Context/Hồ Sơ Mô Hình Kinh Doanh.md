---
tags: [identity, business-parameters]
created: 2026-09-09
---

# ⚙️ Hồ Sơ Mô Hình Kinh Doanh — Trúc Võ Realty

> Sáu tham số điều khiển mọi khuyến nghị của hệ thống (giữ lead bao lâu, đọc số theo nhịp nào, thiết kế phễu kiểu gì, giữ khách bằng cách nào). Đọc file này **trước** mọi khuyến nghị có ngưỡng thời gian, nhịp đo hoặc thiết kế phễu. Nguồn: [[00_Mo_Hinh_Kinh_Doanh|Business Model Canvas — Trúc Võ Realty]].

---

## Sáu tham số

| # | Tham số | Giá trị |
|---|---|---|
| 1 | `loai-san-pham` | Dịch vụ có người phục vụ — tư vấn/môi giới bất động sản |
| 2 | `chu-ky-ban-ngay` | ~14 ngày (dao động thực tế 3-25 ngày tuỳ khách) |
| 3 | `nguoi-mua-la-nguoi-dung` | Có — người mua luôn là người trả tiền và người quyết định sử dụng. Mục đích sử dụng đa dạng: ở, cho thuê, kinh doanh, Airbnb, hoặc giữ chờ giá tốt để chuyển nhượng — ở cả 2 phân khúc |
| 4 | `mua-vu` / `thang-cao-diem` | Không theo mùa trong năm. Nhu cầu/giá biến động theo tiến độ mở bán và hoàn thiện từng phân khu của dự án (Vinhomes Saigon Park quy mô 1.080 ha, hoàn thiện dần theo từng khu) |
| 5 | `so-huu-diem-cham` | Phần lớn qua kênh trực tiếp của Trúc (tư vấn và chốt trực tiếp), không chủ yếu qua sàn/CTV khác |
| 6 | `mo-hinh-mua-lai` / `chu-ky-tieu-dung-ngay` | Có mua lại/mua thêm — không cố định theo lịch mà theo cột mốc: khi có phân khu/dự án mới mở bán, hoặc sau khi bán xong căn cũ. Một số khách mua đều mỗi năm; một số theo kế hoạch đầu tư riêng |

## Ngưỡng hệ thống tự tính từ `chu-ky-ban-ngay` (~14 ngày)

Theo công thức chuẩn của vault (xem CLAUDE.md mục 2b):

- **Giữ lead tối đa:** 1,5 × 14 ≈ **21 ngày**
- **Chạm lead nóng trong:** chu kỳ < 30 ngày → **15 phút**
- **Nhắc lại sau báo giá:** 5% ≈ trong ngày · 15% ≈ **~2 ngày** · 30% ≈ **~4 ngày**
- **Nhịp đọc số:** chu kỳ < 30 ngày → **hằng tuần**

⚠️ Vì chu kỳ bán thực tế dao động khá rộng (3-25 ngày) chứ không cố định, các ngưỡng trên là mức tham khảo trung bình — với khách chốt nhanh (gần 3 ngày) nên chủ động chạm sớm hơn mốc 15 phút nếu có thể; với khách kéo dài gần 25 ngày, nhịp nhắc lại có thể giãn ra một chút so với bảng trên.

## Ghi chú riêng của mô hình này

Vì phần lớn giao dịch chốt trực tiếp qua Trúc (không qua sàn/CTV trung gian) và mô hình mua lại gắn với **cột mốc mở bán phân khu** hơn là lịch cố định, nhịp chăm sóc khách cũ nên đồng bộ với **lịch mở bán/tiến độ dự án** — mỗi khi có phân khu mới hoặc tin tức tiến độ đáng chú ý là thời điểm tốt để chủ động liên hệ lại khách cũ (đặc biệt nhóm PK1 — khách đầu tư).

Giai đoạn 2 chưa làm — chạy `/ban-do-ai-sale-mkt` hoặc tiếp tục ngay trong buổi này để có Bản Đồ Ứng Dụng AI — Sale & Marketing.

## 🔗 Kết nối với
- [[00_Mo_Hinh_Kinh_Doanh|Business Model Canvas — Trúc Võ Realty]]
- [[00_Mo_Hinh_Kinh_Doanh|_MHKD Trúc Võ Realty — Tổng Quan]]
