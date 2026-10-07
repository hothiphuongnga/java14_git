# GITHUB

## DEMO GIT
- Khởi tạo dự án githun với file note.md
- `git --version` : kiểm tra phiên bản
- `git config --global user.name "your_name"` your_name để gì cũng được
- `git config --global user.email "your_github_email"`  email phải là mail tài khoản github
    - lệnh global để cấu hinhg thông tin cho máy chỉ làm 1 lần
- `git init` : khởi tạo sử dụng git cho dự án , mỗi dự án làm 1 lần
- `git remote add origin duong_dan_https` : kết nối folder trong máy với repo online
- Step 1: 
    - `git add .` : thêm tất cả file vào ds theo dõi
    - `git add <ten_file>` : thêm 1 file vào ds theo dõi
- Step 2: 
    - `git commit -m 'noi dung commit'` : chụp màn hình code ở thời điểm thao tác
        
- Step 3: 
    - `git push -u origin <ten_branch>` : chạy lần đầu tiên của branch
    - `git push` : chạy những lần còn lại

- `git branch` : kiểm tra nhánh hiện tại
- `git checkout <ten_branch>` : đổi qua nhánh khác
- `git checkout -b <ten_branch>` : vạo nhánh mới và chuyển qua nhánh mới , sẽ tạo nhánh mới từ nhánh mình đang đứng
- `git fetch` : xem các thay đổi trên onlineenilno (case: update nhánh mới để tiếng hành checkout)
- `git pull` : kéo code về từ online
        - git fetch  -> merge vào code hiện tại
- `git pull --no-rebase` : kéo code về bằng cách truyền thống , không viết lại lịch sử
- `git merge <ten_branch>`: đang đứng ở nhánh A, kéo code từ nhánh <ten_branch> về nhánh A 
    - nếu không có CONFLICT -> git push
    - có CONFLICT -> xử lý CONFLICT -> git add . , git commit , git push
- `git pull rebase`: `viết lại lịch sử`
    - [10:00] mình có commit lúc 10h : quên push -- CHƯA PUSH
    - [11:00] commit + push lên online
    - [12:00] mình commit + push -> banh -- CHƯA PUSH
    - CHẠY REBASE
    - [11:00] commit + push lên online
    - [10:00] mình có commit lúc 10h : quên push -- CHƯA PUSH
    - [12:00] mình commit + push -> banh -- CHƯA PUSH

- ` --force`: cưỡng chế ghi đè lên online , lấy local làm chuẩn , bỏ qua mọi khác biệt mà git cảnh báo



## Đăng nhập
- Username: admin
- Password: 123456

## Quên mật khẩu
- quên pass

## Đăng ký
- Username: admin
- Password: 123456
- Phone: 0999999999
- Email: admin@gmail.com

## Trang Home
- DS chức năng
- Header
- Sản phẩm bán chạy
## dev mới test source
- test
