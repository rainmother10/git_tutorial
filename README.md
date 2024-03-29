# Hướng dẫn sử dụng Git

## Giới thiệu về Git

Git là một hệ thống quản lý phiên bản phân tán, được sử dụng rộng rãi trong quản lý mã nguồn và dự án phần mềm. Với Git, bạn có thể theo dõi các thay đổi trong mã nguồn của mình, thực hiện các phiên bản khác nhau và làm việc song song với nhiều người khác nhau trên cùng một dự án.

## Kiến trúc của Git

Git hoạt động dựa trên một kiến trúc phân tán, mỗi máy tính có thể lưu trữ toàn bộ lịch sử thay đổi của dự án. Các phiên bản của mã nguồn được lưu trữ dưới dạng các "commit", và mỗi commit đều có thể được truy cập thông qua một "hash".

## Các thuật ngữ

### 1. Repository (Kho)

Repository là nơi lưu trữ toàn bộ dữ liệu và lịch sử thay đổi của dự án.

### 2. Commit

Commit là một bản ghi về các thay đổi trong mã nguồn của bạn. Mỗi commit đi kèm với một thông điệp mô tả những thay đổi đó.

### 3. Branch (Nhánh)

Branch là một phiên bản song song của dự án, cho phép bạn phát triển tính năng mới hoặc sửa lỗi mà không làm ảnh hưởng đến phiên bản chính.

### 4. Merge (Hợp nhất)

Merge là quá trình kết hợp các thay đổi từ một nhánh vào nhánh khác.

## Các lệnh cơ bản

Dưới đây là một số lệnh cơ bản trong Git:

1. `git init`: Khởi tạo một repository mới.
2. `git clone <url>`: Sao chép một repository từ một địa chỉ URL đã cho.
3. `git add <file>`: Thêm file vào index để chuẩn bị commit.
4. `git commit -m "message"`: Tạo một commit mới với thông điệp mô tả thay đổi.
5. `git push`: Đẩy các commit mới lên repository từ local repository.

## Demo

Dưới đây là một ví dụ về việc sử dụng Git:



