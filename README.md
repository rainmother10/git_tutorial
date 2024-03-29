# Hướng dẫn sử dụng Git

## Giới thiệu về Git
![](.//images/Git-Logo-2Color.png)
>Git là một hệ thống quản lý phiên bản phân tán, rất phổ biến trong quản lý mã nguồn và dự án phần mềm. Sử dụng Git giúp bạn theo dõi thay đổi trong mã nguồn, quản lý nhiều phiên bản và hợp tác với đội ngũ phát triển.


## Kiến trúc của Git

>Git hoạt động dựa trên một kiến trúc phân tán, mỗi máy tính có thể lưu trữ toàn bộ lịch sử thay đổi của dự án. Các phiên bản của mã nguồn được lưu trữ dưới dạng các "commit", và mỗi commit đều có thể được truy cập thông qua một "hash".

## Các thuật ngữ



### 1. Repository (Kho)
![](.//images/tải%20xuống.png)

Repository là nơi lưu trữ toàn bộ dữ liệu và lịch sử thay đổi của dự án.

### 2. Commit
![](.//images/taixuong1.png)

Commit là một bản ghi về các thay đổi trong mã nguồn của bạn. Mỗi commit đi kèm với một thông điệp mô tả những thay đổi đó.

### 3. Branch (Nhánh)
![](.//images/tải%20xuống%202.png)

Branch là một phiên bản song song của dự án, cho phép bạn phát triển tính năng mới hoặc sửa lỗi mà không làm ảnh hưởng đến phiên bản chính.

### 4. Merge (Hợp nhất)
![](.//images/01.png)

Merge là quá trình kết hợp các thay đổi từ một nhánh vào nhánh khác.

## Các lệnh cơ bản

>Dưới đây là một số lệnh cơ bản trong Git:

1. `git init`: Khởi tạo một repository mới.
2. `git clone <url>`: Sao chép một repository từ một địa chỉ URL đã cho.
3. `git add <file>`: Thêm file vào index để chuẩn bị commit.
4. `git commit -m "message"`: Tạo một commit mới với thông điệp mô tả thay đổi.
5. `git push`: Đẩy các commit mới lên repository từ local repository.

## DEMO
1. Cài đặt Git 
   
1.1 Cài đặt Git trên Ubuntu

`apt-get install git -y`

1.2 Cài đặt trên CentOS/RHEL

`yum install git -y`

2. Thiết lập chứng thực cá nhân

2.1 Cấu hình thiết lập tên, Email

`git config --global user.name "rain"`

`git config --global user.email "nguyentuanct411@gmail.com"`

2.2 Tự lưu passwd Github Repo sau commit đầu

`git config --global credential.helper cache`

2.3 Kiểm tra kết quả
```sh
lacoski@lacoski-PC:~$ cat ~/.gitconfig
[user]
	email = nguyentuanct411@gmail.com
	name = rainmother10
[credential]
	helper = cache

lacoski@lacoski-PC:~$ git config --list
user.email=nguyentuanct411@gmail.com
user.name=rain
credential.helper=cache`
```

# tham khảo
1 giới thiệu về git :<https://git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F>






