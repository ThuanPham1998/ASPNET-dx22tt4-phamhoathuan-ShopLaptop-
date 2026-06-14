# Xây dựng Website Bán Laptop trên nền tảng ASP.NET MVC

## Giới thiệu

Đây là đồ án chuyên ngành với đề tài **Xây dựng Website Bán Laptop trên nền tảng ASP.NET MVC**.

Hệ thống được phát triển nhằm hỗ trợ hoạt động bán laptop trực tuyến, cho phép khách hàng tìm kiếm sản phẩm, đặt hàng và giúp quản trị viên quản lý sản phẩm, đơn hàng một cách hiệu quả.

---

## Thông tin sinh viên

* Họ và tên: **Phạm Hòa Thuận**
* Mã sinh viên: **170122021**
* Lớp: **DX22TT4**
* Trường: **Đại học Trà Vinh**
* Giảng viên hướng dẫn: **ThS. Đoàn Phước Miền**

---

## Công nghệ sử dụng

### Frontend

* HTML5
* CSS3
* Bootstrap
* JavaScript
* jQuery

### Backend

* ASP.NET MVC
* C#
* Entity Framework

### Database

* SQL Server

### Công cụ phát triển

* Visual Studio 2022
* SQL Server Management Studio (SSMS)

---

## Chức năng hệ thống

### Khách hàng

* Đăng ký tài khoản
* Đăng nhập
* Xem danh sách sản phẩm
* Xem chi tiết sản phẩm
* Tìm kiếm sản phẩm
* Thêm sản phẩm vào giỏ hàng
* Đặt hàng
* Xem lịch sử đơn hàng

### Quản trị viên

* Đăng nhập hệ thống quản trị
* Quản lý sản phẩm
* Quản lý hãng sản phẩm
* Quản lý đơn hàng
* Quản lý tài khoản

---

## Cấu trúc cơ sở dữ liệu

Các bảng chính:

* KhachHang
* HangSP
* SanPham
* GioHang
* DonHang
* DonHangChiTiet
* TinTuc

---

## Kiến trúc hệ thống

Dự án được xây dựng theo mô hình MVC:

Model
↓
View
↓
Controller
↓
SQL Server Database

---

## Hướng dẫn cài đặt

### Bước 1: Clone source code

```bash
git clone https://github.com/your-username/your-repository.git
```

### Bước 2: Mở project

Mở file:

```text
DoAn.sln
```

bằng Visual Studio 2022.

### Bước 3: Khôi phục cơ sở dữ liệu

* Mở SQL Server Management Studio.
* Restore file database hoặc chạy script SQL.
* Cập nhật chuỗi kết nối trong file:

```text
Web.config
```

### Bước 4: Chạy ứng dụng

Nhấn:

```text
F5
```

hoặc:

```text
Ctrl + F5
```

để chạy hệ thống.

---

## Một số giao diện hệ thống

### Trang chủ

![Trang chủ](images/home.png)

### Danh sách sản phẩm

![Sản phẩm](images/product.png)

### Chi tiết sản phẩm

![Chi tiết sản phẩm](images/detail.png)

### Giỏ hàng

![Giỏ hàng](images/cart.png)

### Trang quản trị
Đăng nhập theo đường link: https://localhost:44352/Admin/Login
User: Admin@gmail.com
Pass: 12345678 


---

## Kết quả đạt được

* Xây dựng thành công website bán laptop trực tuyến.
* Triển khai đầy đủ các chức năng cơ bản của hệ thống thương mại điện tử.
* Áp dụng mô hình ASP.NET MVC kết hợp Entity Framework và SQL Server.
* Hoàn thành các yêu cầu của đồ án chuyên ngành.

---

## Hướng phát triển

* Tích hợp thanh toán trực tuyến.
* Phát triển giao diện Responsive Mobile.
* Bổ sung Dashboard thống kê.
* Nâng cấp lên ASP.NET Core.
* Tích hợp AI gợi ý sản phẩm.

---
