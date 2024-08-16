# Terms

Repository (Repo)
Branch
Conflict
Local
Remote

# Commands
- git init //Biến dự án thành một git Repository
- git status //Sẽ thấy được các thay đổi trong dự án của mình
- git add {file.} //Đưa vào vùng cbi trước khi commit(có thể chỉ định file)
- git add . //Thêm tất cả cá thay đổi vào vùng cbi
- git reset //
- git commit -m 'note' //Lưu các thay đổi đã cbi trước đấy
- git log //List các commit 
- git log --oneline //gọn hơn
- git checkout {branch name}// Chuyển sang branch đấy
- git branch //Xem danh sách cách nhánh có trong repository
- git branch {branch name} //Tạo một branch mới 
- git checkout -b {branch name} //Tạo và chuyển sang một branch mới
- git merge {branch name} //Đồng bộ nhưng gì thay đổi ở branch khác
- git branch -d {branch name} //Xóa một branch
- git push {remote name} {branch name}//đẩy repository hiện tại lên github
- git remote add {name (origin)} {remote name} //Đặt tên cho remote đấy, thường là origin 
-> git push {name (origin)} {branch name} //Đẩy lên nhanh hơn
- git fetch origin 
- git checkout -b {branch name} {remote name/branch name}
