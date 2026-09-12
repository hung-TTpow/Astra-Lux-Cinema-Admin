
# 🎬 Astra Lux Cinema

Astra Lux Cinema là website đặt vé xem phim trực tuyến, được xây dựng nhằm mô phỏng quy trình hoạt động của một hệ thống rạp chiếu phim hiện đại.

Dự án được phát triển bởi Nguyễn Lâm Hữu Hùng và Nguyễn Vũ Đăng Thành với mục tiêu vừa học lập trình, vừa xây dựng một sản phẩm thực tế có thể đưa vào CV và tiếp tục mở rộng thành ứng dụng Android trong tương lai.

---

## 📌 Giới thiệu dự án

Website hướng đến việc cung cấp trải nghiệm cho người dùng:

- Xem danh sách phim đang chiếu.
- Xem phim sắp chiếu.
- Xem thông tin chi tiết phim.
- Xem lịch chiếu.
- Chọn rạp, suất chiếu và ghế.
- Đặt vé xem phim.
- Mua vé trực tuyến.
- Quản lý thông tin đặt vé.
- Xem lịch sử đặt vé.

Hệ thống sẽ được phát triển theo hướng có backend và cơ sở dữ liệu để xử lý dữ liệu người dùng, phim, lịch chiếu và đơn đặt vé.

---

## 🎯 Mục tiêu dự án

1. Xây dựng website đặt vé xem phim có giao diện hiện đại.
2. Học và áp dụng PHP để xây dựng backend.
3. Sử dụng MySQL để lưu trữ và quản lý dữ liệu.
4. Áp dụng HTML, CSS và JavaScript để xây dựng giao diện và tương tác.
5. Học cách làm việc nhóm bằng Git và GitHub.
6. Xây dựng quy trình phát triển phần mềm theo từng giai đoạn.
7. Hoàn thiện một dự án có thể trình bày trong CV và portfolio.
8. Định hướng phát triển phiên bản ứng dụng Android trong tương lai.

---

## 🛠️ Công nghệ sử dụng

### Frontend
- HTML5
- CSS3
- JavaScript
- Bootstrap (dự kiến, nếu cần)

### Backend
- PHP

### Database
- MySQL

### Môi trường phát triển
- XAMPP
- Apache
- phpMyAdmin

### Công cụ phát triển
- Visual Studio Code
- Git
- GitHub
- Figma (thiết kế giao diện nếu cần)

---

## 📂 Cấu trúc thư mục dự kiến

```text
Astra-Lux-Cinema/
│
├── index.php
├── config/
│   └── database.php
│
├── pages/
│   ├── movies.php
│   ├── movie-detail.php
│   ├── showtimes.php
│   ├── booking.php
│   └── contact.php
│
├── admin/
│   ├── index.php
│   ├── movies/
│   ├── showtimes/
│   └── bookings/
│
├── includes/
│   ├── header.php
│   ├── footer.php
│   └── auth.php
│
├── css/
│   └── style.css
│
├── js/
│   └── main.js
│
├── assets/
│   └── images/
│
├── database/
│   └── schema.sql
│
├── README.md
└── .gitignore
```

> Đây là cấu trúc dự kiến. Nhóm sẽ điều chỉnh trong quá trình phát triển để phù hợp với kiến trúc dự án.

---

## 👥 Thành viên phát triển

| Thành viên | Vai trò ban đầu |
|---|---|
| Nguyễn Lâm Hữu Hùng | Frontend HTML, cấu trúc trang, nội dung và tích hợp PHP |
| Nguyễn Vũ Đăng Thành | Frontend CSS, giao diện, bố cục và hỗ trợ tích hợp PHP |

> Vai trò có thể luân phiên trong các giai đoạn sau để cả hai thành viên đều hiểu và có khả năng phát triển toàn bộ hệ thống.

---

## 📋 Kế hoạch phát triển

### Giai đoạn 1 — Nền tảng PHP & Frontend
- [ ] Cài đặt và cấu hình XAMPP.
- [ ] Tạo project PHP.
- [ ] Tạo cấu trúc thư mục dự án.
- [ ] Xây dựng Header và Navigation.
- [ ] Xây dựng trang chủ bằng PHP.
- [ ] Tạo khu vực phim đang chiếu.
- [ ] Tạo khu vực phim sắp chiếu.
- [ ] Xây dựng Footer.
- [ ] Thiết kế giao diện bằng CSS.

### Giai đoạn 2 — Database & PHP cơ bản
- [ ] Thiết kế cơ sở dữ liệu MySQL.
- [ ] Tạo database và các bảng.
- [ ] Kết nối PHP với MySQL.
- [ ] Hiển thị danh sách phim từ database.
- [ ] Hiển thị thông tin chi tiết phim.
- [ ] Xây dựng chức năng thêm, sửa, xóa phim cơ bản.

### Giai đoạn 3 — Người dùng & Đặt vé
- [ ] Đăng ký tài khoản.
- [ ] Đăng nhập và đăng xuất.
- [ ] Quản lý thông tin tài khoản.
- [ ] Hiển thị danh sách rạp.
- [ ] Hiển thị lịch chiếu.
- [ ] Chọn suất chiếu.
- [ ] Chọn ghế.
- [ ] Đặt vé.
- [ ] Lưu thông tin đặt vé vào database.
- [ ] Xem lịch sử đặt vé.

### Giai đoạn 4 — Quản trị & Hoàn thiện
- [ ] Xây dựng trang quản trị.
- [ ] Quản lý phim.
- [ ] Quản lý rạp và phòng chiếu.
- [ ] Quản lý lịch chiếu.
- [ ] Quản lý đơn đặt vé.
- [ ] Tích hợp thanh toán hoặc mô phỏng thanh toán.
- [ ] Kiểm thử hệ thống.
- [ ] Deploy website.
- [ ] Viết tài liệu dự án.

### Giai đoạn 5 — Định hướng Android
- [ ] Xây dựng ứng dụng Android.
- [ ] Xây dựng API phục vụ ứng dụng.
- [ ] Kết nối Android với backend.
- [ ] Đồng bộ dữ liệu người dùng và đặt vé.
- [ ] Kiểm thử trên thiết bị Android.

---

## 🌿 Quy tắc làm việc với Git

### Branch chính

- `main`: Phiên bản ổn định của dự án.

### Branch phát triển

Mỗi thành viên làm việc trên branch riêng:

- `feature/hung-php-structure`
- `feature/thanh-frontend-ui`

Khi phát triển tính năng mới, tạo branch theo quy ước:

```text
feature/ten-tinh-nang
fix/ten-loi
refactor/ten-thay-doi
```

### Quy trình làm việc

```text
Tạo branch
    ↓
Code và kiểm tra trên máy
    ↓
Commit
    ↓
Push lên GitHub
    ↓
Tạo Pull Request
    ↓
Thành viên còn lại review
    ↓
Merge vào main
```

### Quy định commit

- Mỗi thành viên tối thiểu **3 commit có ý nghĩa mỗi tuần**.
- Không commit trực tiếp vào `main`.
- Mỗi commit nên tập trung vào một thay đổi cụ thể.
- Không commit các file không cần thiết như `vendor`, file tạm hoặc thông tin bí mật.
- Không đưa mật khẩu database thật lên GitHub.

Ví dụ:

```text
feat: create PHP project structure
feat: add cinema navigation
style: add base cinema theme
feat: connect PHP to MySQL
feat: display movie list
fix: correct booking form validation
docs: update project README
```

---

## 📅 Thời gian phát triển

Nhóm dành **2 ngày mỗi tuần** để học và phát triển dự án.

Mỗi tuần sẽ:
- Thống nhất task.
- Phân công người thực hiện.
- Cập nhật tiến độ.
- Commit và push code.
- Review Pull Request.
- Tổng kết kết quả cuối tuần.

---

## 📄 Trạng thái dự án

🚧 Dự án đang trong giai đoạn khởi tạo và xây dựng nền tảng PHP.

---

## 📜 License

Dự án được xây dựng cho mục đích học tập, thực hành và phát triển portfolio cá nhân.
