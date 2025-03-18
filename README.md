# Ứng Dụng Tính Tiền Trọ

Đây là một ứng dụng web đơn giản giúp quản lý và tính toán tiền trọ hàng tháng. Ứng dụng được xây dựng với HTML, CSS, JavaScript và sử dụng localStorage để lưu trữ dữ liệu.

## Tính năng

- Tính toán tiền trọ hàng tháng bao gồm: tiền phòng, tiền điện, tiền nước, tiền mạng và các khoản phát sinh khác
- Tự động tính tiền điện dựa trên chỉ số điện cũ và mới
- Tự động điền thông tin từ kỳ trước để tiết kiệm thời gian nhập liệu
- Lưu trữ lịch sử các khoản thanh toán
- Hiển thị dữ liệu theo thứ tự thời gian mới nhất
- Cho phép xóa các bản ghi
- Giao diện thân thiện, responsive trên các thiết bị khác nhau

## Cách sử dụng

1. **Mở trang web**: Mở file index.html trên trình duyệt hoặc truy cập website nếu đã được triển khai
2. **Nhập thông tin tiền trọ**:
   - Kỳ thanh toán: Ứng dụng tự động đề xuất tháng trước
   - Giá điện/số: Giá điện trên một số điện tiêu thụ
   - Tiền phòng: Giá thuê phòng cố định
   - Chỉ số điện cũ và mới: Để tính tiền điện
   - Tiền nước: Phí nước cố định hoặc theo mét khối
   - Tiền mạng: Phí internet
   - Phát sinh: Các khoản phát sinh khác (nếu có)
3. **Tính toán**: Nhấn nút "Tính toán" để xem tổng tiền trước khi lưu
4. **Lưu thông tin**: Nhấn nút "Lưu" để lưu thông tin vào lịch sử
5. **Xem lịch sử**: Phần "Lịch sử tiền trọ" hiển thị các khoản đã lưu
6. **Xóa dữ liệu**: Nhấn nút "Xóa" để xóa một bản ghi

## Đặc điểm kỹ thuật

- **Lưu trữ dữ liệu**: Sử dụng localStorage để lưu trữ dữ liệu trên trình duyệt
- **Framework**: Sử dụng Bootstrap 5 cho giao diện người dùng
- **Thư viện**: jQuery để xử lý DOM và sự kiện
- **Tính năng tự động**: 
  - Tự động điền kỳ là tháng trước
  - Tự động điền chỉ số điện cũ bằng chỉ số điện mới của kỳ trước
  - Tự động cập nhật tiền điện và tổng tiền khi thay đổi dữ liệu

## Cài đặt

1. Tải xuống toàn bộ mã nguồn
2. Mở file index.html trên trình duyệt web
3. Không cần cài đặt thêm các thư viện vì đã sử dụng CDN

## Lưu ý

- Dữ liệu được lưu trữ trong localStorage của trình duyệt, vì vậy dữ liệu sẽ bị mất nếu xóa cache hoặc sử dụng thiết bị khác
- Ứng dụng hoạt động hoàn toàn ở phía client, không cần kết nối internet (ngoại trừ lần đầu để tải Bootstrap và jQuery từ CDN)