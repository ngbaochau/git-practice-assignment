# Git Pull Request Practice  
This exercise is to practice the workflow with **Git** and **PullRequest (PR)**.

## Exercise 
You will:
1. **Fork this repo** to your personal GitHub account. 
2. **Clone the forked repo to your computer**. 
3. **Create a new branch**, edit the content and commit. 
4. **Push the branch to the forked repo**. 
5. **Create a Pull Request** to merge the code into the original repo.
---

## Detailed Instructions 

#  1. Fork Repo 
Click the **Fork** button in the upper right corner to create a copy of this repo on your GitHub. 

# 2. Clone Repo 
Open a terminal and run: 

-git clone https://github.com/ngbaochau/git-practice-assignment.git
-cd git-practice-assignment
------
## NOTE
Nếu bạn không thể tạo Pull Request (PR) trên GitHub, có một số lý do như là:
# 1. Đảm bảo bạn đã fork repo (nếu cần)
Nếu bạn không phải là người chủ sở hữu của repository, bạn cần fork repository đó vào tài khoản của mình trước khi có thể tạo PR.
•	Nếu bạn đang làm việc với một repository không phải của mình, hãy fork repo trước.
•	Sau khi fork xong, clone repository đã fork về máy tính của bạn, làm thay đổi trên nhánh và tạo Pull Request từ fork của bạn.
# 2. Kiểm tra branch 
Đảm bảo rằng bạn đang ở đúng nhánh mà bạn muốn tạo Pull Request.
•	Chạy lệnh sau để kiểm tra nhánh hiện tại: git branch
•	Nếu bạn chưa tạo nhánh mới từ nhánh chính (main hoặc master), bạn có thể làm như sau: git checkout -b feat/CM-your-feature
# 3. Push nhánh lên GitHub 
Nếu bạn đã tạo nhánh mới và thực hiện thay đổi, đừng quên push nhánh lên remote để có thể tạo PR.
•	Push nhánh của bạn lên GitHub: git push origin feat/CM-your-feature
# 4. Tạo Pull Request
Sau khi bạn đã push nhánh lên GitHub, làm theo các bước sau để tạo Pull Request:
1.	Truy cập vào repository của bạn trên GitHub.
2.	Chọn tab Pull requests.
3.	Nhấn nút New Pull Request.
4.	Chọn nhánh của bạn (nhánh đã push) so với nhánh chính (main hoặc master).
5.	Đảm bảo rằng bạn đang tạo PR từ nhánh của bạn và gửi PR vào nhánh chính của repo.
6.	Nhấn Create Pull Request và điền thông tin cần thiết.
