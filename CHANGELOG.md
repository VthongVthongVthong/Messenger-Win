# Changelog

All notable changes to this project will be documented in this file.

## [1.1.0] - 2026-04-30
### Added
- **Tính năng Bảo mật (Security Features):** 
  - Chặn hiển thị "Đã xem" (Block Read Receipts): Không cho người khác biết bạn đã đọc tin nhắn.
  - Chặn hiển thị "Đang nhập" (Block Typing Indicator): Ẩn trạng thái đang gõ phím của bạn.
  - Tích hợp trực tiếp vào Menu khay hệ thống (System Tray > Bảo mật), dễ dàng bật/tắt.
- **Tính năng Cập nhật tự động (Auto-Updater):**
  - Người dùng sẽ nhận được thông báo khi có bản cập nhật mới.
  - Cho phép tải về và cài đặt trực tiếp từ bên trong ứng dụng chỉ với một cú nhấp chuột, không cần tải thủ công file cài đặt mới.
  - Thêm nút "Kiểm tra cập nhật" trong Menu chuột phải ở khay hệ thống.

### Changed
- Cải thiện hệ thống bắt request mạng bằng `webRequest` API của Electron để can thiệp an toàn vào các tính năng bảo mật.
- Cấu hình lại `electron-builder` và `package.json` để hỗ trợ xuất bản và tải cập nhật từ GitHub Releases.
