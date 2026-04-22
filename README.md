# XÂY DỰNG WEBSITE BÁN GIÀY

## Thông tin sinh viên

- Họ tên: Nguyễn Trung Nghĩa
- MSSV: 170124532
- Lớp: DK24TTC5
- Email: Nguyentrungnghiaqtmk43@gmail.com
- Số điện thoại: 0907165582
- Đề tài: Xây dựng website bán giày

---

## Giới thiệu

Đây là đồ án xây dựng website bán giày sử dụng ASP.NET Core MVC.  
Website cho phép người dùng xem sản phẩm, xem chi tiết, thêm vào giỏ hàng, thêm vào danh sách yêu thích và đặt hàng.  
Ngoài ra, hệ thống còn có trang quản trị (Admin) để quản lý dữ liệu và đơn hàng.

---

## Cấu trúc thư mục

- setup/: chứa file database và hướng dẫn cài đặt
- src/: chứa source code chính
- progress-report/: chứa báo cáo tiến độ
- thesis/: chứa báo cáo đồ án
  - doc/: file Word
  - pdf/: file PDF
  - html/: bản web
  - abs/: slide
  - refs/: tài liệu tham khảo
- soft/: phần mềm liên quan (nếu có)
- docker/: cấu hình docker (nếu có)

---

## Công nghệ sử dụng

- ASP.NET Core MVC
- Entity Framework Core
- SQL Server
- Bootstrap
- HTML / CSS / JavaScript
- Razor View

---

## Chức năng đã thực hiện

### Người dùng

- Xem danh sách sản phẩm
- Xem chi tiết sản phẩm
- Hiển thị đánh giá (Rate)
- Hiển thị Size
- Tìm kiếm sản phẩm
- Phân trang sản phẩm
- Thêm vào giỏ hàng
- Cập nhật số lượng trong giỏ hàng
- Wishlist (Yêu thích)
- Đặt hàng
- Xem danh sách đơn hàng
- Xem chi tiết đơn hàng

---

### Admin

- Đăng nhập quản trị
- Thêm / sửa / xóa sản phẩm
- Quản lý danh mục (Category)
- Quản lý thương hiệu (Brand)
- Quản lý đơn hàng
- Xem chi tiết đơn hàng
- Cập nhật trạng thái đơn hàng
- Quản lý người dùng

---

### Quản lý dữ liệu

- Category – Danh mục sản phẩm
- Brand – Thương hiệu
- Product – Sản phẩm
- Cart – Giỏ hàng
- Wishlist – Danh sách yêu thích
- Order – Đơn hàng
- OrderDetail – Chi tiết đơn hàng
- User – Người dùng

---

## Hướng dẫn chạy chương trình

### 1. Cài đặt môi trường

- Visual Studio 2022
- SQL Server
- .NET 6 hoặc .NET 7

### 2. Cài đặt database

- Mở SQL Server
- Chạy file trong thư mục: `setup/database.sql`

### 3. Chạy project

- Mở thư mục `src/`
- Chạy project bằng Visual Studio
- Truy cập: https://localhost:xxxx

---

## Ghi chú

- Tài khoản Admin dùng để truy cập trang quản trị| admin@gmail.com, pass:111111
- Nếu không hiển thị dữ liệu, cần kiểm tra lại database
