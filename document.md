Work flow
- Tạo thư mục dưới local
- Tạo repository trên github hoặc gitlab
*Kết nối local <-> server (github hoặc gitlab)
- git init (khởi tạo repo git dưới local)
- git checkout -b develop (Tạo nhánh develop mới và switched sang nhánh vừa tạo)
- git add . hoặc git add file_path (Add vào git stage để chuẩn bị commit)
- git commit -m "Nội dung commit" (Sau khi commit sẽ không có trạng thái thay đổi của các file đã được add)
- git remote add remoteName (origin) link repo (remoteName = origin)
    ex: git remote add origin https://github.com/baduc95fc/gittraining.git
    Link repo có 2 loại(2 giao thức):
        + SSH git@github.com:baduc95fc/gittraining.git
        + HTTPS https://github.com/baduc95fc/gittraining.git
- Kiểm tra remote bằng lệnh
git remote -v
Note: Có thể add nhiều remote vào 1 project 
 + fetch lấy code về
 + push đẩy code lên
- git remote set-url origin https://github.com/baduc95fc/gittraining.git (Thay đổi địa chỉ repo đã được đăng ký)
- git push origin develop (đẩy code lên github)