# Xampp_tutorial

XAMPP là 1 gói phần mềm mã  nguồn mở rất phổ biến, được sử dụng để thiết lập môi trường phát triển web cục bộ trên máy tính cá nhân. Đây là 1 công cụ hữu ích cho các nhà phát triển web, giúp họ dễ dàng cài đặt và quản lý 1 máy chủ web trên máy tính cá nhân mà không cần phải kết nối với internet.

1 XAMPP là gì
- X: Cross-platform (đa nền tảng ), có nghĩa là XAMPP có thể chạy trên nhiều hệ điều hành khác nhau, bao gồm windows, linux, và macOS
- A: apache, 1 máy chủ web phổ biến nhất thế giới, dùng để phục vụ các trang web
- M: MySQL hoặc MariaDB, 1 hệ quản trị cơ sở dữ liệu quan hệ (RDBMS) dùng để lưu trữ và quản lý dữ liệu.
- P: PHP, 1 ngôn ngữ lập trình phía máy chủ được sử dụng rộng rãi để phát triển các ứng dụng web rộng.
P: Perl, 1 ngôn ngưx lập trình kịch bản hỗ trợ quản lý hệ thống và phát triển web.

2 Các thành phần chính của XAMPP

- apache:
	+ là máy chủ web xử lý các yêu cầu HTTP từ trình duyệt và trả về các trang web
	+ apache được tích hợp sẵn trong XAMPP, giúp bạn dễ dàng chạy trang web máy tính của mình
- MySQL/MariaDB
	+ MySQL là hệ quản trị cơ sở dữ liệu, dùng để lưu trữ dữ liệu của ưungs dụng web
	+ mariaDB là 1 nhánh của MySQL và là phần mềm quản trị cơ sở dữ liệu mặc định trong các phiên ản XAMPP mới hơn.
- PHP 
	+ PHP là 1 ngôn ngữ lập trình được thiết kế đăc biệt cho phát triển web. XAMPP tích hợp sẵn PHP để bạn có thể viết và chạy các ứng dụng web động
- Perl 
	+ là 1 ngôn ngữ lập trình kịch bản, cũng được hỗ trợ trong XAMPP. Mặc dù ít phổ biến hơn PHP, Perl vẫn được sử dụng trong 1 sô tình huống nhất đinh, đặc việt là trong quản trị hệ thống và xử lý văn bản.
- phpMyAdmin
	+ phpMyAdmin là 1 công cụ quản trị cơ sở dữ liệu MySQL/MariaDB thông qua giao diện web. Nó giúp bạn dễ dàng thựuc hiện các tác vụ như tạo cơ sở dữ liệu, thêm bảng, quản lý dữ liệu mà không cần phải sử dụng dòng lệnh
- Fille FTP Server:
	+ 1 máy chủ FTP (File transfer protocol) đi kèm với XAMPP, giúp bạn quản lý các tệp trên máy chủ web của mình.
- Tomcat
	+ apache tomcat là 1 máy chủ web mã nguồn mở, được sử dụng triển khai các ứng dụng web Java. Tomcat không phải lúc nào cũng đc cài đặt mặc định, nhưng bạn có thể thêm nó nếu cần phát triển các ưngs dụng Java
 + 
3 Nhược điểm

- không phải là môi trường sản xuất: xampp đc thiết kế để sử dụng trong môi trường phát triên, không phải trong môi trường sản xuất (production). Nó thiếu các tính năng bảo mật và tối ưu hóa mà bạn cần cho 1 máy chủ thực tế.
- Hiệu suất: trong 1 số trường hợp, XAMPP có thể không hoạt động tối ưu hoặc không tương thích hoàn toàn với môi trường sản xuất thực tế, dẫn đến các vấn đè khi triển khai ứng dụng lên máy chủ

4 Cách chuyển từ XAMPP sang máy chủ thực tế
  
Sau khi phát triênr ứng dụng web trên XAMPP, bạn cần chuyển nó sang 1 máy chủ thực tế (production server) 
- chuyển các tệp web từ XAMPP lên máy chủ: bạn có thể sử dụng FTP hoặc các công cụ tương tự để tải các tệp lên máy chủ thực tế.
- chuyển cơ sở dữ liệu: sử dung công cụ phpAdmin để xuất cơ sở dữ liệu từ XAMPP và nhập nó vào cơ sở dữ liệu trên máy chủ thực tế.
- kiểm tra câus hình: đảm bảo rằng tất cả các cấu hình như đường dẫn, quuyền truy cập, và cấu hình máy chủ đã được điều chỉnh phù hợp cho môi trường sản xuất.
