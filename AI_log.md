khong hien anh
khong dung duong dan
# Báo lỗi

## Một lỗi
- Bước tái hiện: Mở file `index.html` hoặc `ket-qua.html` bằng trình duyệt, trang hiển thị nhưng giao diện không nhận được định dạng CSS, vì liên kết stylesheet không hoạt động.
- Nguyên nhân: Trong cả hai file HTML, đường dẫn stylesheet đang là `css/style.css`, nhưng file thực tế nằm ở thư mục gốc là `style.css`. Ngoài ra, input email bị gõ sai `type="texr"`, làm browser không nhận đúng kiểu dữ liệu email.
- Sửa: Đổi thẻ `<link rel="stylesheet" href="style.css">` hoặc tạo thư mục `css` rồi đặt file vào đó; sửa `type="email"` cho ô nhập email và `type="submit"` cho nút gửi nếu cần submit form.
- Kiểm tra lại: Tải lại trang, CSS phải được áp dụng đúng, form liên hệ hoạt động như mong đợi và không còn lỗi định dạng cơ bản.
