# my-new-project

Bài tập thực hành tạo dự án mới trên GitHub.

## Mục tiêu
- Luyện tập thao tác tạo Repository mới trên GitHub
- Đồng bộ Local Repository với Remote Repository
- Sử dụng thành thạo các lệnh git add / commit / push

## Ý nghĩa các câu lệnh Git đã sử dụng

### 1. git init
Khởi tạo Local Repository (kho lưu trữ cục bộ) trong thư mục hiện tại.
Git tạo thư mục ẩn .git để theo dõi mọi thay đổi.

### 2. git remote add origin <URL>
Liên kết Local Repository với Remote Repository trên GitHub.
origin là tên mặc định đại diện cho URL đó.

### 3. git add README.md
Đưa file README.md vào Staging Area (vùng chờ) — chuẩn bị cho commit tiếp theo.

### 4. git commit -m "Add README.md file"
Ghi lại các thay đổi vào lịch sử Git kèm message mô tả.
Mỗi commit là một "ảnh chụp" (snapshot) của dự án tại thời điểm đó.

### 5. git push origin main
Đẩy các commit từ Local Repository lên Remote Repository.
- origin: tên remote đích
- main: tên nhánh đang push

## Tác giả
- Học viên: .....................
- Lớp: .....................
- Ngày: 29/09/2026
