# Cac-cau-lenh-tao-sua-xoa-file-va-folder-tren-ubuntu
Các câu lệnh tạo sửa xóa file và folder trên ubuntu


#1 Các câu lệnh làm việc với file

- Gồm có 4 thao tác chính:
<ul>
<li>Cách tạo file và ghi nội dung cho file</li>
<li>Cách đổi tên file</li>
<li>Cách copy file</li>
<li>Cách xóa file</li>
</ul>

##1.1 Cách tạo file.

- Để tạo 1 file ta dùng lệnh vi(của trình soạn thảo vi có sẵn trong linux):

**vi Tên_file_muốn_tạo**

<img src="http://prntscr.com/8n8vqw">

- Ấn **i (INSERT)** để thêm vào thông tin cho file

<img src="http://prntscr.com/8n8w7l">

- Lưu file vào bằng lệnh **wq!**

- Để kiểm tra xem file đã tồn tại chưa ta dùng lệnh **ls**

<img src="http://prntscr.com/8n8wi7">

- Xem nội dung của file ta dùng lệnh **cat tên_file**, hoặc ta cũng có thể dùng lệnh **tail** hoặc **head** cũng tưng tự.

<img src="http://prntscr.com/8n8wwu">

##1.2 Di chuyển file(hoạc đổi tên file).
- Để di chuyển file bạn dùng lệnh **mv(move)**:

<img src="http://prntscr.com/8n90kr">

- Hoặc dùng để đổi tên file ta cũng sẽ sử dụng lệnh **mv**:

**mv tên_file_cũ tên_file_mới**

<img src="http://prntscr.com/8n8xua">

- Ở đây file đã được chuyển từ tên file_demo thành file_demo_new

##1.3 Cách copy file

- Để copy file bạn sử dụng lệnh **cp (copy)**:
 
**cp tên_file_cũ tên_file_mới**

<img src="http://prntscr.com/8n8z73">

##1.4 Cách xóa file

- Để xóa file ta dùng lệnh **rm(remove)**:

**rm tên_file_cần_xóa**

<img src="http://prntscr.com/8n91i3">

#2. Các câu lệnh làm việc với Folder.

- Gồm có 4 thao tác chính:
<ul>
<li>Cách tạo folder</li>
<li>Cách truy cập vào folder</li>
<li>Cách copy folder</li>
<li>Cách xóa folder</li>
</ul>

##2.1 Các tạo folder

- Để tạo một thư mục ta sử dụng lệnh **mkdir( make directory)**

**mkdir tên_thư_mục_cần_tạo**

<img src="http://prntscr.com/8n93kt">

##2.2  Truy cập vào thư mục.

- Để truy cập vào thư mục ta dùng lệnh **cd(change directory)**:

**cd đường_dẫn_đến_thư_mục**

<img src="http://prntscr.com/8n94xy">

- Để biết thư mục hiện hành bạn đang ở, ta dùng lệnh **pwd(print working directory)**
- Để giảm đi 1 tầng của thư mục ta dùng lệnh cd ..
- Để trở lại thư mục user bạn gõ cd ~

<img src="http://prntscr.com/8n96kb">

###Lệnh **ls(list)**

- Các tùy chọn của lệnh **ls**:
<ul>
<li>**ls** là để xem toàn bộ file nhưng chỉ hiển thị tên file, và không bao gồm các file và folder được ẩn.</li>
<img src="http://prntscr.com/8n9891">
<li>**ls -a** là để xem toàn bộ file và thư mục bao gồm các file và thư mục bị ẩn.</li>
<img src="http://prntscr.com/8n98ue">
<li>**ls -l** là xem toàn bộ file/folder kèm theo thông tin chi tiết của file/folder  đó nhưng không bao gồm các file/folder  ẩn.</li>
<img src="http://prntscr.com/8n98oi">
<li>**ls -al** là xem toàn bộ file/folder với thông tin chi tiết và bao gồm các file/folder bị ẩn.</li>
<img src="http://prntscr.com/8n993u">
</ul>



