# Báo Cáo Thực Hành Kiểm Thử API Bằng Postman

## 1. Giới thiệu
- **Mục đích:** Nắm vững công cụ Postman để gửi các HTTP Requests và viết các kịch bản kiểm thử tự động cơ bản.
- **Nguồn API sử dụng:** JSONPlaceholder (`https://jsonplaceholder.typicode.com/`)

## 2. Kết quả thực hiện bài tập

### 2.1. Thực hiện GET Request (Lấy dữ liệu)
- **Mô tả:** Truy xuất danh sách người dùng từ API mở.
- **Method:** GET
- **Endpoint:** `https://jsonplaceholder.typicode.com/users`
- **Kết quả:** Trạng thái phản hồi thành công `200 OK`.
- **Hình ảnh minh họa:**
![Minh chứng GET Request](Screenshot%202026-05-27%20224525.png)

### 2.2. Thực hiện POST Request (Thêm dữ liệu)
- **Mô tả:** Gửi đi một đoạn dữ liệu JSON giả lập để tạo bài viết mới.
- **Method:** POST
- **Endpoint:** `https://jsonplaceholder.typicode.com/posts`
- **Kết quả:** Trạng thái phản hồi thông báo tạo mới thành công `201 Created`.
- **Hình ảnh minh họa:**
![Minh chứng POST Request](Screenshot%202026-05-27%20224754.png)

### 2.3. Tự động hóa kiểm thử (Test Scripts)
- **Mô tả:** Sử dụng kịch bản (Script) để tự động hóa việc kiểm tra tính đúng đắn của trạng thái phản hồi.
- **Kết quả chạy Test:** Trạng thái báo `PASS` xanh cho mã `201`.
- **Hình ảnh minh họa:**
![Minh chứng Test Script](Screenshot%202026-05-27%20225244.png)
