# EthanGrokVideoShopee - Releases

Repo này dùng cho hệ thống auto-update của EthanGrokVideoShopee.

## Cách hoạt động
- App sẽ kiểm tra file `version.json` ở nhánh `main`
- Nếu có version mới hơn → hiện nút cập nhật
- Bấm cập nhật → tải ZIP từ GitHub Releases → tự động cài đặt

## Cấu trúc
- `version.json` — Thông tin version mới nhất + download URL
- GitHub Releases — Nơi lưu file ZIP bản portable
