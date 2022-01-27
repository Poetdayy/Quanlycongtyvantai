1. Hướng dẫn cài đặt 
         - Để sử dụng phần mềm cần phải có môi trường chạy Java. 
         - Ngoài ra có 1 thư viện thêm đi kèm như : MySQL connector. 
         - Tải về hệ quản trị cơ sở dữ liệu MySQL Server 2018.
2. Xác định các yêu cầu cài đặt 
    Yêu cầu phần mềm : 
         - Có thư viện jre, mysql connector.
         - Phần mềm MySQL Server phiên bản 2018 trở lên.
         - Hệ điều hành : bất cứ hệ điều hành nào, ưu tiên Windows.
    Yêu cầu phần cứng : 
         - Không yêu cầu cấu hình phần cứng cao.
         - Khuyên dùng máy tính có RAM từ 2GB trở nên để có trải nghiệm tốt nhất.
3. Hướng dẫn chi tiết các bước cài đặt 
•  Tải về MySQL Server tại https://dev.mysql.com/downloads/mysql/, có thể cài đặt 1 công cụ trực quan hóa để quan sát cơ sở dữ liệu tốt hơn ( ví dụ XAMPP hoặc Workbench). Sau đó import file cơ sở dữ liệu trong thư mục database vào cơ sở dữ liệu.
•  Sử dụng và chỉnh sửa username trong class testConnect.java mật khẩu phù hợp với mật khẩu mà đã được đặt cho MySQL server. 
•  Tải về thư viện MySQL connector từ 8.0 trở lên, có thể tải thư viện tại 
https://mvnrepository.com/artifact/mysql/mysql-connector-java/8.0.22 
•  Import tất cả vào thư viện trong Project sau đó bắt đầu chạy. 
   3.1. Hướng dẫn cài đặt thư viện JavaFx cho IntelliJ.
   	+ Bước 1: Vào New Project chọn File / New / Project, chọn JavaFx Application
	+ Bước 2: Vào mục Run -> Edit Configurations, chọn Add VM-Options, thêm đường dẫn javafx-sdk vào
--module-path /path/to/javafx-sdk-17/lib
 --add-modules javafx.controls,javafx.fxml
	+ Bước 3: Chọn Apply -> Ok 
   3.2. Hướng dẫn liên kết đến MySQL server trong IntelliJ.
 	+ Bước 1: Đầu tiên chúng ta mở một Project lên và nhấn vào tab Database ở bên phải như hình vẽ rồi bấm vào dấu “+” để tạo một kết nối đến hệ quản trị cơ sở dữ liệu.
+ Bước 2: Chọn Data Source rồi chọn MySQL ( hoặc có thể tạo 1 class Connect database và tạo một phải test kiểm tra kết nối )
+ Bước 3: Tiếp theo chúng ta điền các thông tin được yêu cầu.
•	Tên của liên kết
•	Hostname (nếu trên một máy thì là localhost)
•	Cổng kết nối mặc định là 3306
•	Username và password mà bạn thiết lập lúc cài đặt MySQL Server
•	Tên database
+ Bước 4: Trước khi bấm vào Test Connection và Ok (phải tải driver file về trước)
+ Bước 5: Sau khi download file driver chúng ta sẽ bấm vào Test Connection và  Connection và OK để kiểm tra kết nối.
•	Nếu thấy công cụ hiển thị thông báo với tích xanh là được .
•	Trường hợp không kết nối được, kiểm tra lại các thông tin nhập bên trên và kiểm tra MySQL Service có đang hoạt động không.


Cài đặt xong thì bấm vào run chương trình và sử dụng các chức năng
