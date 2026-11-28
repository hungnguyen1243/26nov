# Trúc Võ Realty — Obsidian Business Brain

> Vault cá nhân để quản lý kiến thức doanh nghiệp, dữ liệu Vinhomes Saigon Park, quy trình tư vấn, nội dung và vận hành của Trúc Võ Realty.

Repo `26nov` được dùng làm lịch sử phiên bản cho các ghi chú đã chọn lọc. Repo đang ở chế độ private. Vault Obsidian trên máy là nơi làm việc chính; GitHub không thay thế các nguồn PDF, Excel hay hệ thống SalePro.

## Bắt đầu nhanh

1. Mở vault bằng Obsidian.
2. Đọc [Cây Thư Mục & Quy Trình Sử Dụng](MOC/C%C3%A2y%20Th%C6%B0%20M%E1%BB%A5c%20%26%20Quy%20Tr%C3%ACnh%20S%E1%BB%AD%20D%E1%BB%A5ng.md) để biết nơi lưu và luồng xử lý.
3. Đọc các hồ sơ nền theo thứ tự:
   - [Mô Hình Kinh Doanh](00.%20Business%20Context/00_Mo_Hinh_Kinh_Doanh.md)
   - [Chân Dung CEO](00.%20Business%20Context/01_Chan_Dung_CEO.md)
   - [Định Vị Thương Hiệu](00.%20Business%20Context/02_Dinh_Vi_Thuong_Hieu.md)
   - [Brand Voice](00.%20Business%20Context/03_Brand_Voice.md)
4. Với thông tin mới, đặt tài liệu vào `01. Inbox/`, rồi yêu cầu xử lý cụ thể. Tệp mới không tự được phân loại hoặc chuyển đổi.

## Bản đồ vault

| Thư mục | Vai trò | Ví dụ nội dung |
|---|---|---|
| `00. Business Context/` | Hồ sơ chuẩn về doanh nghiệp, khách hàng, thương hiệu, sản phẩm | Mô hình kinh doanh, định vị, thông tin VHSP |
| `01. Inbox/` | Điểm nhận tài liệu và tin mới chưa xử lý | Zalo, bảng giá, TMB, ảnh mẫu nhà |
| `02. Projects/` | Công việc có mục tiêu và đầu ra cụ thể | [Chuẩn Hóa Hồ Sơ VHSP](02.%20Projects/Chu%E1%BA%A9n%20H%C3%B3a%20H%E1%BB%93%20S%C6%A1%20VHSP.md), dự án chuyển nhượng, xưởng video |
| `03. Areas/` | Hoạt động duy trì thường xuyên | CRM, thương hiệu, nội dung, phân tích |
| `04. Resources/` | Tài liệu nghiên cứu và nội dung tái sử dụng | Playbooks, Case Study, Góc Nhìn, People, dữ liệu VHSP |
| `05. Archive/` | Tài liệu cũ hoặc công việc đã đóng cần giữ lịch sử | Bản chính sách cũ, dự án hoàn tất |
| `50. Triển Khai 90 Ngày/` | Lộ trình, giáo án và nghiệm thu triển khai | Lộ trình 8 tuần, checklist, biên bản bàn giao |
| `MOC/` | Trang mục lục và sơ đồ điều hướng | [Sơ đồ tổng thể](MOC/B%E1%BA%A3n%20%C4%90%E1%BB%93%20T%E1%BB%95ng%20Th%E1%BB%83%20Project.md) |
| `Companies/`, `People/`, `Meetings/`, `Decisions/` | Hồ sơ thực thể và quyết định | Dùng theo quy ước trong vault; dữ liệu cá nhân không đẩy lên Git |
| `.agents/skills/` | 16 quy trình AI theo nhiệm vụ | Thương hiệu, khách hàng, nội dung, CRM, nghiên cứu, đo lường |
| `.obsidian/` | Cấu hình giao diện và plugin Obsidian | Cấu hình cục bộ; plugin/theme/icon không được đóng gói đầy đủ trong Git |

Đọc [AGENTS.md](AGENTS.md) trước khi thực hiện thay đổi lớn. Quy tắc đó xác định nguồn cần đọc, phạm vi AI được phép xử lý và những việc cần Trúc duyệt.

## Dữ liệu Vinhomes Saigon Park

Tài liệu sản phẩm được chia thành nguồn, bản tra cứu và dữ liệu cập nhật:

- [Quy Trình Cập Nhật Dữ Liệu VHSP](00.%20Business%20Context/S%E1%BA%A3n%20Ph%E1%BA%A9m%20%26%20D%E1%BB%8Bch%20V%E1%BB%A5/Quy%20Tr%C3%ACnh%20C%E1%BA%ADp%20Nh%E1%BA%ADt%20D%E1%BB%AF%20Li%E1%BB%87u%20VHSP.md): cách tiếp nhận, đối chiếu và cập nhật.
- `00. Business Context/Sản Phẩm & Dịch Vụ/`: hồ sơ sản phẩm, bộ tài liệu CSBH và ghi chú nguồn.
- `04. Resources/VHSP-Du-Lieu/`: sổ lô CSV, báo cáo đối chiếu, danh sách chào, nhật ký trong ngày, dữ liệu mẫu nhà và thư mục `The-CaN/` chứa thẻ căn.
- `01. Inbox/`: vùng nhận XLSX SalePro, PDF TMB/CSBH và ảnh mẫu nhà trước khi xử lý.

### Quy tắc sử dụng dữ liệu

- SalePro là nơi kiểm tra tình trạng căn hiện tại. Giá và trạng thái trong ghi chú chỉ phản ánh thời điểm được ghi; cần kiểm tra lại trước khi tư vấn.
- Không trộn chính sách Chủ đầu tư với Hợp đồng chuyển nhượng, hoặc phương án Giãn xây với Thô & Hoàn thiện.
- Giữ nguyên bảng nguồn Excel/PDF. CSV và Markdown là bản tra cứu, cần ghi ngày, nguồn và phạm vi đối chiếu.
- Ảnh tiến độ cần ngày chụp và khu vực; ảnh phối cảnh không tự chứng minh hiện trạng.
- Tin Zalo được xem là thông tin do người cung cấp cho tới khi đối chiếu với nguồn phù hợp.
- Nội dung Venice AI được gắn `VEai`; coi là đầu vào tham khảo cho tới khi xác minh.

## Luồng xử lý tài liệu

```text
Tài liệu mới
    ↓
01. Inbox — giữ nguồn, ghi ngày nhận
    ↓
Đối chiếu PDF / Excel / SalePro / nguồn chính thức
    ↓
Ghi bản tra cứu và liên kết nguồn
    ↓
Trúc duyệt dữ liệu thương mại, pháp lý và nội dung công khai
    ↓
Chuyển sang Business Context / Projects / Areas / Resources
```

Trạng thái tham khảo: `MỚI` → `ĐANG ĐỐI CHIẾU` → `CHỜ TRÚC DUYỆT` → `ĐÃ ĐỐI CHIẾU` → `ĐÃ LƯU`. Chỉ đánh dấu đã đối chiếu khi có nguồn và vị trí kiểm tra như trang PDF, sheet/ô XLSX, URL hoặc thời điểm xem SalePro.

## Nhịp vận hành

### Hằng ngày

- Kiểm tra căn trực tiếp trên SalePro trước khi giới thiệu.
- Chỉ ghi 5–10 căn vào `04. Resources/VHSP-Du-Lieu/Gio-Trong-Ngay.md` khi đã kiểm tra; ghi giờ kiểm, giá và lý do chọn.
- Tin Zalo liên quan dự án được ghi vào `01. Inbox/Zalo_Daily_Drop.md`, kèm thời điểm nhận và người/nhóm cung cấp nếu biết.
- Không đưa thông tin nhận diện khách vào ghi chú hoặc repo Git.

### Hằng tuần

- Rà tin đã hết hạn, chuyển thông tin đã xác minh sang ghi chú thích hợp và liên kết nguồn.
- Kiểm tra thay đổi trước khi đồng bộ GitHub.

## Skills và cách dùng AI

Thư mục `.agents/skills/` có 16 quy trình chuyên biệt. Gọi skill phù hợp với nhiệm vụ, ví dụ `customer-persona`, `discovery-call-script`, `sales-script`, `objection-handler`, `content-copywriter`, `video-script`, `tuan-thu-nganh-vn` hoặc `do-luong-tracking`.

AI có thể đọc, phân loại, đối chiếu, phát hiện thiếu dữ liệu và soạn nháp. AI không tự khóa căn, đổi trạng thái căn, gửi tin, đăng nội dung, chạy quảng cáo hoặc đưa kết luận pháp lý. Các nội dung thương mại và công khai cần Trúc duyệt.

## GitHub, dữ liệu riêng tư và bản sao lưu

- Repo `26nov` hiện đặt private. Trước khi chia sẻ quyền truy cập, kiểm tra `git status` và danh sách file sẽ commit.
- Các đường dẫn `01. Inbox/tmb_raw/`, `01. Inbox/salepro/`, `01. Inbox/mau-nha/` và PDF trong `Nguồn/` được loại khỏi Git. Tệp vẫn có thể tồn tại cục bộ trong vault.
- `.env`, `.env.local`, token, mật khẩu, danh sách khách, hồ sơ định danh và biên bản có thông tin cá nhân không được commit.
- `04. Resources/People/` và `04. Resources/Meetings/` chỉ theo dõi quy ước, MOC và mẫu trống; dữ liệu thật nằm ngoài Git.
- Cấu hình Obsidian được theo dõi có chọn lọc. Khi mở vault trên máy khác, có thể cần cài lại plugin, theme và icon.
- GitHub không thay bản sao lưu riêng. Sao lưu vault và tệp nguồn quan trọng ở ổ khác theo quy trình cá nhân.

### Đồng bộ thay đổi

Mở terminal tại thư mục gốc của repo:

```bash
git status
git add -A
git diff --cached --stat
git commit -m "Cap nhat vault"
git push origin main
```

Đọc danh sách staged sau `git add -A`; `.gitignore` giảm rủi ro nhưng không thay việc kiểm tra trước khi commit.

## Tài liệu chính

- [Cây Thư Mục & Quy Trình Sử Dụng](MOC/C%C3%A2y%20Th%C6%B0%20M%E1%BB%A5c%20%26%20Quy%20Tr%C3%ACnh%20S%E1%BB%AD%20D%E1%BB%A5ng.md)
- [Sơ đồ tổng thể Mermaid](MOC/B%E1%BA%A3n%20%C4%90%E1%BB%93%20T%E1%BB%95ng%20Th%E1%BB%83%20Project.md)
- [Quy trình cập nhật VHSP](00.%20Business%20Context/S%E1%BA%A3n%20Ph%E1%BA%A9m%20%26%20D%E1%BB%8Bch%20V%E1%BB%A5/Quy%20Tr%C3%ACnh%20C%E1%BA%ADp%20Nh%E1%BA%ADt%20D%E1%BB%AF%20Li%E1%BB%87u%20VHSP.md)
- [Project chuẩn hóa hồ sơ VHSP](02.%20Projects/Chu%E1%BA%A9n%20H%C3%B3a%20H%E1%BB%93%20S%C6%A1%20VHSP.md)
- [Case Study MOC](04.%20Resources/Case-Study/_MOC%20Case%20Study.md)
- [MOC Sales Pipeline & CRM](03.%20Areas/Sales%20Pipeline%20%26%20CRM/_MOC%20Sales%20Pipeline%20%26%20CRM.md)
- [Lộ trình triển khai](50.%20Tri%E1%BB%83n%20Khai%2090%20Ng%C3%A0y/00%20%E2%80%94%20L%E1%BB%99%20Tr%C3%ACnh%208%20Tu%E1%BA%A7n.md)
