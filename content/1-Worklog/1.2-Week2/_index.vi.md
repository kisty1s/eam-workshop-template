---
title: "Worklog Tuần 2"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.2. </b> "
---

Tuần thực tập thứ hai tập trung mạnh mẽ vào hạ tầng mạng và tài nguyên tính toán trên AWS thông qua các bài thực hành thực tế. Nội dung cốt lõi bao gồm nghiên cứu Amazon VPC, cấu hình các lớp mạng public và private, và triển khai máy chủ ảo EC2. Ngoài ra, một loạt các bài tập thực hành cũng đã được hoàn thành để tối ưu hóa bố cục cơ sở hạ tầng và nhận thành công các tín dụng hỗ trợ từ AWS.

### Mục tiêu tuần 2:
* Nghiên cứu cơ sở hạ tầng Amazon VPC, bao gồm Subnet, Route Table và Internet Gateway.
* Cấu hình Public Subnet và Private Subnet để thiết lập một bố cục mạng an toàn và cô lập.
* Khởi chạy các instance Amazon EC2 và xác minh kết nối mạng đầu-cuối.
* Hoàn thành 5 bài thực hành thực tế để đủ điều kiện nhận hỗ trợ 200 USD AWS Credits.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| :--- | :--- | :--- | :--- | :--- |
| Sáu | - Nghiên cứu các khái niệm kiến trúc của Amazon VPC (Virtual Private Cloud).<br>- Tìm hiểu về các nguyên tắc cô lập mạng và định tuyến trong môi trường đám mây.<br>+ Ghi chú các định nghĩa cơ bản phục vụ triển khai thực tế. | 24/04/2026 | 24/04/2026 | Mã nguồn dự án, Thảo luận nhóm, <https://cloudjourney.awsstudygroup.com/> |
| Bảy | - Tìm hiểu cách thiết kế và phân chia Public Subnet và Private Subnet.<br>- Nghiên cứu chức năng của Route Table và Internet Gateway (IGW).<br>+ Phác thảo bố cục mạng cho thiết lập bài lab sắp tới. | 25/04/2026 | 25/04/2026 | Mã nguồn dự án, Thảo luận nhóm, <https://cloudjourney.awsstudygroup.com/> |
| CN | - Truy cập AWS Management Console để thực hành cấu hình các thành phần mạng.<br>- Thiết lập các Route Table tùy chỉnh và gắn Internet Gateway để cho phép lưu lượng truy cập từ bên ngoài.<br>+ Xác minh các đường định tuyến qua các subnet. | 26/04/2026 | 26/04/2026 | AWS Management Console, Thảo luận nhóm, <https://cloudjourney.awsstudygroup.com/> |
| Hai | - Nghiên cứu các khái niệm cốt lõi của dịch vụ Amazon EC2 (Elastic Compute Cloud).<br>- Tìm hiểu cách các máy chủ ảo hoạt động trong cấu trúc subnet public và private.<br>+ Tài liệu hóa các cấu hình cần thiết để khởi chạy thực tế các instance một cách an toàn. | 27/04/2026 | 27/04/2026 | Mã nguồn dự án, Thảo luận nhóm, <https://cloudjourney.awsstudygroup.com/> |
| Ba | - Thực hành triển khai và khởi chạy các instance Amazon EC2 trong VPC đã cấu hình.<br>- Thiết lập các Security Group cơ bản để quản lý các quy tắc truy cập đầu vào và đầu ra.<br>+ Xác minh trạng thái của các instance trên AWS Console. | 28/04/2026 | 28/04/2026 | AWS Management Console, Thảo luận nhóm, <https://cloudjourney.awsstudygroup.com/> |
| Tư | - Thực hiện kiểm tra kết nối mạng đến và đi từ các máy chủ ảo EC2 đã triển khai.<br>- Khắc phục sự cố định tuyến và đường truyền thông giữa các lớp mạng khác nhau.<br>+ Ghi lại các bước xác minh thành công và kết quả câu lệnh. | 29/04/2026 | 29/04/2026 | AWS Management Console, Terminal, <https://cloudjourney.awsstudygroup.com/> |
| Năm | - Thực hiện và hoàn thành các bài thực hành còn lại (Tổng cộng 5 bài thực hành Hands-on Labs).<br>- Đăng ký và nhận thành công hỗ trợ 200 USD AWS Credits vào tài khoản.<br>+ Tổng hợp các kiến thức đã học và chuẩn bị kế hoạch cho tuần tới. | 30/04/2026 | 03/05/2026 | Nền tảng AWS Lab, AWS Credits, <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 2:
* Nắm vững cấu hình cơ sở hạ tầng Amazon VPC, thiết lập thành công các Public/Private Subnet, Route Table và Internet Gateway.
* Triển khai thành công các máy chủ ảo Amazon EC2 và xác minh các đường truyền thông mạng đang hoạt động.
* Hoàn thành 5 bài lab thực hành AWS theo đúng lộ trình đào tạo đã đề ra.
* Được nhận 200 USD AWS Credits để duy trì và triển khai tài nguyên đám mây trong các tuần tiếp theo.

### Kế hoạch cho tuần tiếp theo:
* Chuyển trọng tâm sang các dịch vụ lưu trữ bằng cách đi sâu vào Amazon S3 (Simple Storage Service).
* Thực hành khởi tạo S3 Bucket, tải dữ liệu lên và quản lý quyền truy cập bucket.
* Tìm hiểu và cấu hình quản lý quyền truy cập của người dùng bằng cách sử dụng AWS Identity and Access Management (IAM) Users, Groups, và Roles.
