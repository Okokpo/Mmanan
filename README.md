# DemoBank — GitHub Pages

Website ngân hàng **mô phỏng** chạy hoàn toàn bằng HTML/CSS/JavaScript.

## Tính năng
- Đăng ký bằng số điện thoại 10 chữ số + email + mật khẩu, không cần CCCD.
- Đăng nhập bằng email hoặc số điện thoại.
- Tổng quan số dư và thống kê.
- Chuyển khoản giữa các tài khoản DemoBank trên cùng trình duyệt.
- Nạp tiền bằng yêu cầu chờ Admin duyệt.
- Lịch sử nhận/chuyển/nạp tiền.
- Thông báo giao dịch.
- **DemoBank AI**: phân tích câu hỏi tự nhiên bằng JavaScript, kết hợp dữ liệu tài khoản hiện tại (số dư, lịch sử, yêu cầu nạp, thông báo) để tạo câu trả lời phù hợp.
- Admin duyệt/từ chối yêu cầu nạp tiền.
- Responsive cho điện thoại và máy tính.
- Dữ liệu lưu bằng `localStorage`.

## Chạy GitHub Pages
1. Tạo repository trên GitHub.
2. Upload `index.html`, `style.css`, `script.js`, `README.md` vào thư mục gốc.
3. Vào **Settings → Pages**.
4. Chọn branch `main` và thư mục `/(root)` rồi Save.

## Mật khẩu Admin demo
`0944379685_vuok`

## Lưu ý quan trọng
Đây **không phải ngân hàng thật** và không xử lý tiền thật. Không nhập mật khẩu/thông tin tài chính thật.

Đây là bản frontend demo: mật khẩu Admin nằm trong JavaScript và dữ liệu nằm trong localStorage nên không có tính bảo mật của hệ thống production. AI hiện là trợ lý cục bộ, không gọi API AI bên ngoài.

Ngoài ra, chuyển khoản giữa tài khoản chỉ chia sẻ dữ liệu khi các tài khoản dùng chung cùng trình duyệt/origin. Muốn đồng bộ giữa nhiều thiết bị cần backend + database thật.
