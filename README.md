# HỆ THỐNG BÁN HÀNG BÁNH MÌ MẸ TÔM TÉP

Sản phẩm cá nhân tham gia cuộc thi Vibe Coding (Phase 2).

## 1. Môn học / Dự án
- **Tên dự án**: Bánh mì Mẹ Tôm Tép
- **Quy mô**: Hệ thống quản lý và đặt hàng bánh mì cho quán nhỏ (20–30 đơn/ngày).

## 2. Các chức năng chính (Full Database CRUD Operations)
- **Tạo (Create)**: Thêm món ăn mới vào Cơ sở dữ liệu và Tạo đơn hàng mới từ giỏ hàng.
- **Đọc (Read)**: Lấy dữ liệu sản phẩm công khai từ Database render lên thực đơn giao diện.
- **Sửa (Update)**: Cập nhật thông tin tên, mô tả, giá bán món ăn trực tiếp vào Database.
- **Xóa (Delete)**: Gỡ bỏ món ăn hoặc xóa đơn khỏi hệ thống dữ liệu.

## 3. Công nghệ & Cơ sở dữ liệu sử dụng
- **Frontend**: HTML5, Tailwind CSS, JavaScript (ES6+).
- **Database & Storage**: Client-side Database Storage (JSON Database Schema / `localStorage` Persistence Engine).
- **Database Schema**:
  ```sql
  CREATE TABLE products (
      id INTEGER PRIMARY KEY AUTOINCREMENT,
      name TEXT NOT NULL,
      description TEXT,
      price INTEGER NOT NULL,
      image_url TEXT
  );
