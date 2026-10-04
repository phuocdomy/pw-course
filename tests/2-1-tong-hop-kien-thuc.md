# Bài 2: Tổng Hợp Kiến Thức Git & JavaScript basic
## 2.2: 3 vùng trong Git

Lệnh **git init** sẽ tạo ra 3 vùng: **working directory, staging area và repository**: 
- **working directory**: vùng mình đang làm việc
- **staging area**: kv trung gian để tập hợp những công việc đã sẵn sàng để commit
- **repository**: chứa commit (việc đã xong)

Chuyển từ **working area** sang **staging area**: 
- git add <tên file> 
- git add file_1 file_2
- **git add . **: đưa tất cả các file sang

Chuyển từ staging area sang repository:
- git commit -m

## 2.3: Kiểm tra trạng thái với git status
**git status**: kiểm tra trạng thái của repo hiện tại

- Repo chưa khởi tạo: fatal: "not a git repo", file sẽ có màu đỏ
- Repo mới khởi tạo: file sẽ có màu xanh lá
- Sau khi comnmit: file sẽ biến mất -> git status sẽ k thấy

## 2.4: Xem danh sách commits với git log
## 2.5: Cấu hình với git config
## 2.6: Git convention
## 2.7+8: Javascript 
