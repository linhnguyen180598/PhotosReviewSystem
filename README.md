# Website chia sẻ hình ảnh Filmy
## Thông tin đề tài
**Học phần:** Các phương pháp phát triển phần mềm nhanh

**Đề tài đề xuất:** Xây dựng website chia sẻ hình ảnh

**Nhóm:** 6

**Thành viên:**
  - Nguyễn Đức Linh
  - Ngô Hải Nam
  - Đào Anh Vũ
  
**Ngôn ngữ sử dụng:**
  - Front-end: JavaScript, HTML, CSS
  - Back-end: Ruby (Ruby On Rails)

**Các tài liệu liên quan:**
  - [Product Backlog & Sprint Planning](https://docs.google.com/spreadsheets/d/13KR-gwnWPj--xxj4YbJIrc1VDAascocgh0uSKjQ81Rw/edit?usp=sharing
)
  - [Q&A](https://docs.google.com/spreadsheets/d/1A-DSyNagNyATmeWkIUS-xG-eRZ2nrp6k46toIko-oHg/edit?usp=sharing
)
  - [Biểu đồ Usecase](https://github.com/linhnguyen180598/PhotosReviewSystem/tree/master/Documents/Usecase%20Diagrams)
  - [Biểu đồ hoạt động](https://github.com/linhnguyen180598/PhotosReviewSystem/tree/master/Documents/Activity%20Diagrams)
  - [Biểu đồ tuần tự](https://github.com/linhnguyen180598/PhotosReviewSystem/tree/master/Documents/Sequence%20Diagrams)
  - [Biểu đồ ER](https://github.com/linhnguyen180598/PhotosReviewSystem/tree/master/Documents/ER%20Diagram)
  
**Tài liệu tham khảo:**
  - [Rails Tutorial](https://guides.rubyonrails.org/)
  - [Font Awesome](https://fontawesome.com/)
  - [Sprint Planning Template](https://teams.microsoft.com/l/file/E6DBE9A8-8BDF-4C47-AFB8-FF67078FE764?tenantId=06f1b89f-07e8-464f-b408-ec1b45703f31&fileType=xlsx&objectUrl=https%3A%2F%2Fhusteduvn.sharepoint.com%2Fsites%2FIT4556Q%2FClass%20Materials%2FSprint%20Planning%20Template.xlsx&baseUrl=https%3A%2F%2Fhusteduvn.sharepoint.com%2Fsites%2FIT4556Q&serviceName=teams&threadId=19:744efed5fb2049e4b0810078e35280ad@thread.tacv2&groupId=218367a3-2f6d-4313-b2bf-54920f999bde)
  - [Build Instagram by Rails](https://medium.com/luanotes/build-instagram-by-ruby-on-rails-part-1-fef7837ee399)
  - [Basic Writing And Formatting Syntax](https://help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax)
## Cài đặt ngôn ngữ, framework và các gems (extensions)
***Lưu ý: Hệ thống chỉ hỗ trợ môi trường Linux (Ubuntu) và macOS nên nếu bạn dùng Windows thì hãy cài đặt môi trường để chạy hoặc cài song song 2 hệ điều hành nếu muốn.***
  - [Cài đặt môi trường trên Windows](https://char.gd/blog/2017/how-to-set-up-the-perfect-modern-dev-environment-on-windows)
  - [Cài song song hai hệ điều hành](https://itsfoss.com/install-ubuntu-1404-dual-boot-mode-windows-8-81-uefi/)
 ###### 1. Install rbenv and Dependencies:
 ```
sudo apt update
sudo apt install autoconf bison build-essential libssl-dev libyaml-dev libreadline6-dev zlib1g-dev libncurses5-dev libffi-dev libgdbm5 libgdbm-dev
git clone https://github.com/rbenv/rbenv.git ~/.rbenv
echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bashrc
echo 'eval "$(rbenv init -)"' >> ~/.bashrc
source ~/.bashrc
```
###### 2. Installing Ruby with ruby-build:
```
rbenv install -l
rbenv install 2.6.3
rbenv global 2.6.3
```
###### 3. Installing Rails:
```
gem install rails -v 5.2.4
```
###### 4. Installing gems:
- Bundler
```
gem install bundler
```
- SQlite3
```
gem install sqlite3
```
- Yarn
```
curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
sudo apt update
sudo apt install yarn
```
- Node.js
```
sudo apt install nodejs
```
## Chạy server:
- Clone code:
```
git clone https://github.com/linhnguyen180598/PhotosReviewSystem.git
```
- Truy cập vào Folder Code:
```
cd PhotosReviewSystem
```
- Cài Gems:
```
bundle install
```
- Nối Database:
```
rake db:migrate
```
- Chạy Server
```
rails server
```
- Sau đó mở trình duyệt web và truy cập vào địa chỉ localhost:3000



 
 
  
  
