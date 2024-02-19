# INT3105_1 #week1
Kiến trúc phần mềm
Sinh viên thực hiện :Giang Bảo Minh - MSSV: 21020353
# 1. Docker, Docker-compose là gì ?
## Docker
- Docker là một nền tảng phần mềm cung cấp cho lập trình viên giải pháp xây dựng, triển khai và vận hành ứng dụng dễ dàng, nhanh chóng thông qua việc sử dụng những container trên nền tảng công nghệ ảo hóa
- Containers cho phép bạn đóng gói tất cả các thành phần cần thiết để chạy một ứng dụng, bao gồm mã nguồn, thư viện, biến môi trường và các phụ thuộc khác, trong một gói đóng gói duy nhất.

## Docker-compose
- Docker-compose là công cụ giúp xác định và quản lý nhiều container trong một ứng dụng phức tạp.
- Docker-compose sử dụng một file YAML để xác định các dịch vụ, mạng, khối lượng và các tham số khác cho ứng dụng của bạn.

# 2. Linux VS Unix VS BSD hay *nix? macOS thuộc loại nào?

## Unix
- Unix là một hệ điều hành đa nhiệm và đa người dùng được phát triển vào những năm 1970.
- Hệ điều hành Unix được cấu trúc theo mô hình gồm kernel (hạt nhân) và shell.
- Kernel là trái tim của hệ điều hành Unix, điều khiển và quản lý tài nguyên, bộ nhớ, phần cứng và các tệp tin hệ thống. Nó cũng đảm nhận vai trò phân bổ thời gian cho các chương trình để xử lý thông tin và thực hiện các lệnh từ người dùng.
- Shell là giao diện dòng lệnh của Unix, nằm giữa Kernel và người dùng. Khi người dùng nhập lệnh, Shell diễn giải và tìm kiếm chương trình tương ứng, sau đó yêu cầu Kernel thực thi lệnh.

## Linux
- Linux được phát triển dựa vào hệ điều hành Unix và được phát hành miễn phí.
- Linux sử dụng hạt nhân nguyên khối gọi là Linux kernel, có nhiệm vụ kiểm soát các tiến trình, kết nối mạng, truy cập vào các thiết bị ngoại vi và hệ thống file.
- Linux sử dụng giao diện người dùng(shell) là một giao diện dòng lệnh. CLI shell là các giao diện người dùng dựa trên văn bản, sử dụng văn bản cho việc xuất và nhập.
- Linux cung cấp một môi trường ổn định, có tính linh hoạt cao và có thể chạy trên nhiều nền tảng phần cứng khác nhau.
## BSD
- BSD là một hệ điều hành dẫn xuất từ UNIX.
- BSD bao gồm nhiều biến thể như FreeBSD, OpenBSD, NetBSD và một số hệ điều hành khác.

## *nix
- *nix: thuật ngữ "Unix-like" hay "*nix" là một thuật ngữ được sử dụng để chỉ các tất cả các hệ điều hành dựa trên Unix, bao gồm Unix, Linux, BSD và cả macOS.
- Hệ điều hành nix đã trở thành một lựa chọn phổ biến cho các môi trường cá nhân, doanh nghiệp và máy chủ.
## macOS
- macOS(Macintosh operating system) là hệ điều hành do Apple phát triển, là hệ điều hành dựa trên Unix.
- hệ điều hành mạnh mẽ, đáng tin cậy cho Mac, phục vụ người dùng cá nhân và doanh nghiệp.
- macOS thuộc loại hệ điều hành Unix

# 3. Alpine vs Ubuntu ?
## Kích thước:
- Alpine được thiết kế với mục tiêu tối ưu kích thước và hiệu suất,ử dụng thư viện C glibc thay vì thư viện libc của GNU, giúp giảm kích thước hệ thống và tài nguyên tiêu thụ
- Ubuntu có kích thước lớn hơn và sử dụng glibc, điều này cho phép hỗ trợ rộng hơn cho các ứng dụng và gói phần mềm.
## Bảo mật:
- Alpine chú trọng đến bảo mật và an toàn. Nó sử dụng một số cơ chế an ninh như PaX và Executable Space Protection (mprotect), làm giảm khả năng tấn công từ các lỗ hổng bảo mật.
- Ubuntu cũng có các biện pháp bảo mật nhưng không tập trung mạnh mẽ như Alpine.
## Mục tiêu:
- Alpine thường được sử dụng rộng rãi trong các môi trường nhúng, máy chủ và container. Phù hợp với triển khai các ứng dụng Docker và các hệ thống nhỏ gọn.
- Ubuntu có mục tiêu phổ quát hơn và thích hợp cho các máy tính cá nhân, máy chủ và môi trường làm việc thông thường.
# 4. VNC
- VNC (Virtual Network Computing) là một giao thức và phần mềm cho phép bạn từ xa điều khiển và truy cập vào một máy tính từ một máy tính khác thông qua mạng.
- VNC sử dụng giao thức RFB để truyền tải hình ảnh và tương tác người dùng giữa máy tính điều khiển và máy tính được điều khiển.
- VNC bao gồm máy chủ (server) và khách hàng (client) để thiết lập kết nối và điều khiển từ xa.
- Có nhiều ứng dụng VNC như TightVNC, RealVNC và UltraVNC để triển khai kết nối VNC.
- Bảo mật là một yếu tố quan trọng trong việc sử dụng VNC từ xa, vì vậy nên sử dụng VPN hoặc SSH để tăng cường bảo mật.
