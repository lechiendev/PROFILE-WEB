# PROFILE

Project này chủ yếu mang tính chất của một trang web giới thiệu bản thân bao gồm việc làm hiện tại và thông tin liên lạc.Vui lòng không bán source code dưới mọi hình thức vì đây là code được share free bởi LVCDEV.Đây chỉ là một phần trong dự án tổng thể BLOG-WEB lên một số chức năng có thể không hoạt động.Nếu cần full source code vui lòng liên hệ admin code : https://www.facebook.com/profile.php?id=100050086957031

## Cài Đặt

Link source code sẽ được share tại trang cá nhân của admin những nguồn khác có thể là share lại nếu thấy ai bán vui lòng báo cáo lại với admin.Sau khi nhận được link tải hãy truy cập vào đường link(sẽ có 2 dạng 1 là qua google drive 2 là github).
-Với link Google drive chỉ việc bấm vô link và tải về bạn sẽ nhận được 1 file Profile-web.zip(hoặc tương tự) giờ chỉ việc vô quản lí tập tin và giải nén nó ra thôi và làm theo hướng dẫn trên trang cá nhân của mình là được nha :3
-Với link github thì chắc hẳn ai biết tới link dạng này cũng thuộc dạng dev có trình độ rồi lên mình không cần giải thích gì thêm!
Đối với cách chỉnh sửa code cũng sẽ có tại đây hoặc liên hệ qua facebook của admin để được hỗ trợ một cách tốt nhất.Sau đây sẽ là một số bước để các bạn có thể tùy chỉnh code theo ý thích:
### Bước 1;
Truy cập vô thư mục img và đưa ảnh của bạn vào.Đừng quên xóa hình ảnh có sẵn trước khi thêm ảnh của bạn vào.Sau đó đổi tên bức ảnh của bạn thành logo.jpg(nhớ phải thêm ảnh có dạng đuôi jpg)
### Bước 2:
Đối với hình ảnh thêm vào không có đuôi file .jpg thì bạn vui lòng kiểm tra xem đuôi file là gì và thực hiện theo các bước dưới đây để hình ảnh có thể hiện thị được tốt nhất:

#### Bước 1:
Truy cập vô tệp index.html
#### Bước 2:
Tìm tới phần có chú thích như sau <!--Information--> nằm tại dòng 25 trong file index.html
#### Bước 4:
Tìm tới dòng code số 27 <img src="../img/logo.jpg" lt="logo-lvc" id="logo">
Thay đôi phần src thành đường dẫn đúng của file(Nếu ảnh đó không được thêm vào thư mục img)
Khi nó đã nẳm trong thư mục img vui lòng chỉnh sửa đoạn code trên như sau:
<img src="../img/logo.đuôi file của bạn" lt="logo-tên viết tắt của bạn" id="logo">
Vậy là hình ảnh đã hoạt động bình thường

### Bước 3:
Dành cho bạn nào muốn thay đổi hình nền hiển thị.Trong mã nguồn sẽ bao gồm 2 hình nền động và tĩnh hãy làm theo các bước dưới đây để có thể thay đổi hình nền của trang web theo ý thích của bạn:

#### Đối với hình nền động
#### Bước1: 
Vô thư mục video tìm tới file background.mp4 và xóa nó đi sau nó thêm video mà bạn muốn thay vào và nhớ xem đuôi file là gì
#### Bước 2:
Vào file index.html và tìm tới dòng số 46 <source src="./video/background.mp4" type="video/mp4"> và chỉnh sửa background.mp4 thành tên và đuôi file video của bạn cần
#### Đối với hình nền tĩnh:
#### Bước 1:
Vô thư mục img tìm và xóa file cyberpunk.jpg sau đó thêm ảnh của bạn vào lưu ý bạn cần nhớ đuôi file của ảnh và phải là ảnh ngang có kích thước:
+ 4:3
+ 16:9
+ 16:10
+ 21:9
+ 3:2
Tức là tỷ lệ của màn hình máy tính để đảm bảo hiển thị tốt trên cả máy tính và điện thoại cũng như ipad 
# lưu ý :
hình nền tĩnh không hiển thị ngay khi truy cập vào website trên máy tính mà sẽ cần thao tác kéo lăn chuột từ người dùng sẽ hiện ra hình nền tĩnh cùng với thông tin giới thiệu nếu bạn không thích điều này có thể xóa dòng code kia đi cũng được có thể sẽ gây ra lỗi nếu có vui lòng liên hệ lại admin để kịp thời xử lý 
#### Bước 2:
Vô file profile.css và tìm tới dòng số 6 "background-image: url(./img/cyberpunk.jpg);" ở đây bạn càn xóa chữ cyberpunk.jpg và chỉnh thành tên và đuôi file của bạn theo đúng định dạng namefile.đuôi file.Vậy là xong rồi


### Bước 3:
Tìm vào file index.html và di chuyển tới dòng số 28 <div class="lvcdev">---LVC-DEV---</div> đây sẽ là tên hiển thị trên trang web bạn có thể thay đổi ---LVC-DEV--- thành tên mà bạn muốn hiển thị
### Bước 4:
Tìm tới dòng số 33 , 34 ,35 
           <p class="top">Work</p>
           <p class="work">Cyber Security</p>
           <p class="work">Front end Developer</p>
Chỉnh lần lượt các chữ Work , Cyber Security ,  Front end Developer thành công việc , topic  mà bạn muốn theo thứ tự : 
           <p class="top">Topic</p>
           <p class="work">Công việc 1 </p>
           <p class="work">Công việc 2 </p>
### Bước 5:
Tìm tới dòng số 39 40 41
            <p class="top">Contact</p>
            <p class="contact">0389766525</p>
            <p class="contact">levanchien042008@gmail.com</p>
Chỉnh lần lượt các chữ Contact, 0389766525 ,  levanchien042008@gmail.com thành thông tin liên lạc  , topic  mà bạn muốn theo thứ tự :
           <p class="top">Topic </p>
           <p class="work">Thông tin liên lạc số  1 </p>
           <p class="work">Thông tin liên lạc số 2 </p>
### Vậy là đã hoàn hiện code dành riêng cho bạn ngoài ra bạn có thể tùy ý thay đổi code nếu muốn
### Lưu ý:
#### 1
Đây là một source chỉ code thuần html và css lên sẽ ít tính năng hơn lên nếu nó được các bạn ủng hộ thì tôi sẽ lên thêm nhiều project có kết hợp thêm cả JS để cho anh em tùy sức sáng tạo và nhìn sẽ bắt mắt hơn nhiều :3
#### 2
Nhớ tải các trình chỉnh sửa code để tùy chỉnh code một cách tối ưu nhất tránh việc trỉnh sửa code bằng các tính năng có sẵn trên máy!
#### 3
Sau khi hoành thành các bước chỉnh sửa code vui lòng save code (lưu file) để chắc ăn tránh trường hợp code chưa được lưu đã vội vã đóng trình chỉnh sửa code khiến cho code không được lưu lại


## Đóng Góp

Chúng tôi rất hoan nghênh đóng góp từ các bạn. Xin vui lòng xem [Hướng dẫn Đóng Góp](CONTRIBUTING.md) để biết thêm chi tiết.

## Giấy Phép

Dự án này được phân phối dưới giấy phép [LVCDEV](LICENSE.md). Xem tệp LICENSE.md để biết thêm thông tin.
