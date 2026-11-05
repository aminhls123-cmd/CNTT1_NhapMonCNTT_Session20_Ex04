# Bài 4 : Rủi ro đánh cắp mật khẩu từ trình duyệt

## 1. Bảng so sánh bảo mật
| Tiêu chí | Google Chrome | Bitwarden |
| :--- | :--- | :--- |
| Chống Infostealer | **Kém** (Mã độc dễ trích xuất file `Login Data`) | **Tuyệt đối** (Dữ liệu đã mã hóa cục bộ) |
| Zero-Knowledge | **Không** (Google lưu trữ và quản lý khóa) | **Có** (Server không thể đọc dữ liệu) |
| Đồng bộ chéo | Đồng bộ qua tài khoản Google | Đồng bộ mã hóa đa nền tảng |

## 2. Lập luận chọn Bitwarden
- Bảo mật tuyệt đối: Dữ liệu mã hóa bằng AES-256 trên thiết bị trước khi lên đám mây, vô hiệu hóa mã độc Infostealer.
- Đánh đổi xứng đáng: Thao tác nhập Master Password chậm hơn vài giây nhưng đổi lại sự an toàn tuyệt đối, tránh rủi ro mất toàn bộ tài khoản công ty.
