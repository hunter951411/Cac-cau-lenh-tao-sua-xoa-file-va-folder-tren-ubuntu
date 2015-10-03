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

<img src="http://i.imgur.com/ixYG90e.png">

- Ấn **i (INSERT)** để thêm vào thông tin cho file

<img src="http://i.imgur.com/bhh9IKL.png">

- Lưu file vào bằng lệnh **wq!**

- Để kiểm tra xem file đã tồn tại chưa ta dùng lệnh **ls**

<img src="http://i.imgur.com/VN4OUNx.png">

- Xem nội dung của file ta dùng lệnh **cat tên_file**, hoặc ta cũng có thể dùng lệnh **tail** hoặc **head** cũng tưng tự.

<img src="http://i.imgur.com/zMKmOFU.png">

##1.2 Di chuyển file(hoạc đổi tên file).
- Để di chuyển file bạn dùng lệnh **mv(move)**:

<img src="http://i.imgur.com/tgNhkii.png">

- Hoặc dùng để đổi tên file ta cũng sẽ sử dụng lệnh **mv**:

**mv tên_file_cũ tên_file_mới**

<img src="http://i.imgur.com/OnAlqhE.png">

- Ở đây file đã được chuyển từ tên file_demo thành file_demo_new

##1.3 Cách copy file

- Để copy file bạn sử dụng lệnh **cp (copy)**:
 
**cp tên_file_cũ tên_file_mới**

<img src="http://i.imgur.com/PZxChWo.png">

##1.4 Cách xóa file

- Để xóa file ta dùng lệnh **rm(remove)**:

**rm tên_file_cần_xóa**

<img src="http://i.imgur.com/lGrK3zF.png">

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

<img src="http://i.imgur.com/PUap3vN.png">

##2.2  Truy cập vào thư mục.

- Để truy cập vào thư mục ta dùng lệnh **cd(change directory)**:

**cd đường_dẫn_đến_thư_mục**

<img src="http://i.imgur.com/1WIAgDc.png">

- Để biết thư mục hiện hành bạn đang ở, ta dùng lệnh **pwd(print working directory)**
- Để giảm đi 1 tầng của thư mục ta dùng lệnh cd ..
- Để trở lại thư mục user bạn gõ cd ~

<img src="http://i.imgur.com/AaTz2z8.png">

###Lệnh **ls(list)**

- Các tùy chọn của lệnh **ls**:
<ul>
<li>**ls** là để xem toàn bộ file nhưng chỉ hiển thị tên file, và không bao gồm các file và folder được ẩn.</li>
<img src="http://i.imgur.com/QFhmX3r.png">
<li>**ls -a** là để xem toàn bộ file và thư mục bao gồm các file và thư mục bị ẩn.</li>
<img src="http://i.imgur.com/CxVvaFp.png">
<li>**ls -l** là xem toàn bộ file/folder kèm theo thông tin chi tiết của file/folder  đó nhưng không bao gồm các file/folder  ẩn.</li>
<img src="http://i.imgur.com/h1jbm35.png">
<li>**ls -al** là xem toàn bộ file/folder với thông tin chi tiết và bao gồm các file/folder bị ẩn.</li>
<img src="http://i.imgur.com/DP5npw4.png">
</ul>

##2.3 Cách copy folder

- Lệnh cp cũng có thể copy các folder với nhau giống như với file:

**cp -r tên_thư_mục_cũ tên_thư_mục_mới**

- **-r** nghĩa là bạn sẽ copy toàn bộ flie và thư mục chứa trong đó

<img src="http://i.imgur.com/Zy8LtVS.png">

##2.4 Di chuyển và xóa thư mục.

- Di chuyển và xóa thư mục cũng tương tự như di chuyển và xóa thư mục với file:

**mv thư_mục_cần_chuyển thư_mục_chuyển_đến**

**rm -rf tên_thư_mục_cần_xóa**

<img src="http://i.imgur.com/6bc14B1.png">

**Chú ý**:Khi đã xóa bạn sẽ không thể nào restore lại như window

**Nguồn: Internet**
