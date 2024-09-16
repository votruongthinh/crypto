## tao Repository

git init
=> tao ra nhanh chinh

### git init -b main

=> tao repo local vs nhanh chinh co ten main

### git remote add arigin + <url repo>

lien ket repo local vs repo remote

## Ko đưa thư mực node_modules lên repo remote

=> Node_modueles chiếm dung lượng rất lớn
=> Node_modules có thể cài lại thông qua câu lệnh : npm i

### file .gitignore quy định những thư mục hay file ko đc phép đẩy lên repo remote

=> .gitignore nằm ở thư mục root

### git status

=> Kiểm tra sự thay đổi của các file trong dự án

### git add

=> Thêm file vào trong staging

### git add . => dùng để thêm tất cả các file ở trong thư mực hiện tại vào trong staging

### git add -A => dùng để thêm tất cả các file ở trong dự án vào trong staging

### git add <đường dẫn file> => Chỉ thêm file cụ thể vào trong staging

### working directory (file màu đỏ)

### staging (file màu xanh)

=> lúc này file sẵn sàng để đưa lên repo remote

### config git (chỉ chạy duy nhất 1 lần)

### git config --global user.name "name"

### git config --global user.email "abc@gmail"

### git commit -m "message"

=> dùng để gắn message vào trong những file đang ở staging đc phép đưa lên repo remote
=> mỗi commit có một mã sha (id)

### git log

=> Kiểm tra lịch sử commit

### git push -u origin <tên nhánh>

=> đưa code lên repo remote
=> từ lần push code thứ 2 : git push

### Đưa file từ staging về lại working

git reset

git restore -S . (Đưa tất cả các file đang ở staging về working)

git restore -S <url file> (Chỉ đưa duy nhất file về working)
