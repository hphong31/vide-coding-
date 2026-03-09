# Student Management System

## Thông tin cá nhân

* **Họ tên:** Dương Hồng Phong
* **Môn học:** Phát triển ứng dụng
* **Bài tập:** Xây dựng hệ thống quản lý sinh viên bằng AI

---

# Giới thiệu

Đây là một **web application đơn giản dùng để quản lý sinh viên**.

Hệ thống cho phép người dùng thực hiện các chức năng sau:

* Thêm sinh viên
* Sửa thông tin sinh viên
* Xóa sinh viên
* Xem danh sách sinh viên
* Tìm kiếm sinh viên theo tên
* Thống kê dữ liệu
* Xuất dữ liệu ra file CSV

---

# Tech Stack

### Backend

* Python
* Flask

### Database

* SQLite

### Frontend

* HTML
* CSS

---

# Tools sử dụng

Trong quá trình phát triển hệ thống có sử dụng công cụ AI:

* ChatGPT

---

# Chức năng hệ thống

## 1. Quản lý sinh viên

Thông tin sinh viên bao gồm:

| Field      | Description     |
| ---------- | --------------- |
| student_id | Mã sinh viên    |
| name       | Họ tên          |
| birth_year | Năm sinh        |
| major      | Ngành học       |
| gpa        | Điểm trung bình |
| class_id   | Lớp             |

---

## 2. Quản lý lớp

Thông tin lớp học:

| Field      | Description    |
| ---------- | -------------- |
| class_id   | Mã lớp         |
| class_name | Tên lớp        |
| advisor    | Cố vấn học tập |

---

## 3. Tìm kiếm

Hệ thống cho phép người dùng **tìm kiếm sinh viên theo tên** để dễ dàng tra cứu thông tin.

---

## 4. Thống kê

Hệ thống hiển thị các thông tin thống kê:

* Tổng số sinh viên
* GPA trung bình
* Số lượng sinh viên theo từng ngành

---

## 5. Xuất dữ liệu

Người dùng có thể **xuất danh sách sinh viên ra file CSV** để lưu trữ hoặc sử dụng cho mục đích khác.

---

# Cách chạy project

## 1. Cài đặt thư viện

```
pip install flask
```

## 2. Tạo database

```
python init_db.py
```

## 3. Chạy ứng dụng

```
python app.py
```

## 4. Truy cập web

Mở trình duyệt và truy cập:

```
http://127.0.0.1:5000
```

---

# Cấu trúc project

```
student-management-system
│
├── app.py
├── init_db.py
├── students.db
├── README.md
│
└── templates
    ├── index.html
    ├── add_student.html
    ├── edit_student.html
    └── stats.html
```

---

# Commit History

Repository được phát triển theo các bước:

1. **MVP: basic student CRUD system**
2. **Feature: add class, search, statistics, export CSV**
3. **Docs: improve README**
