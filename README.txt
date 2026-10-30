QR 30s — Website tạo mã QR tự làm mới

Cách chạy:
1. Giải nén file ZIP.
2. Mở index.html bằng Chrome, Edge hoặc Firefox.
3. Dán URL (bắt đầu bằng https:// hoặc http://), bấm “Tạo mã QR”.
4. QR sẽ được tải lại sau mỗi 30 giây. Quét QR luôn mở cùng URL.

Lưu ý:
- Đây là phiên bản chạy hoàn toàn ở phía trình duyệt, không cần backend.
- Để tạo ảnh QR, trang dùng dịch vụ bên ngoài api.qrserver.com; URL được gửi tới dịch vụ đó để tạo ảnh QR.
- Do nội dung URL không đổi, hình QR có thể giống hệt nhau sau mỗi lần làm mới. Tham số cache-busting chỉ yêu cầu tải lại ảnh, không làm thay đổi nội dung QR.
- Đây không phải QR bảo mật, không có token hết hạn hay cơ chế ngăn tái sử dụng.
