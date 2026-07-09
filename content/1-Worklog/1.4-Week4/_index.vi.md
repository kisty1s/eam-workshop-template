---
title: "Worklog Tuần 4"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.4. </b> "
---

Tuần thực tập thứ tư chuyển trọng tâm sang quản trị hệ thống và cấu hình triển khai môi trường trên AWS. Nội dung cốt lõi bao gồm khởi tạo và thiết lập hệ điều hành Linux trên các instance Amazon EC2, triển khai Web Server sẵn sàng cho môi trường production và runtime ứng dụng. Ngoài ra, các tác vụ tích hợp thực tế cũng được thực hiện để thiết lập kết nối luồng dữ liệu an toàn giữa lớp ứng dụng và các công cụ cơ sở dữ liệu cơ bản.

### Mục tiêu tuần 4:
* Thiết lập, cấu hình và quản lý môi trường hệ điều hành Linux trên Amazon EC2.
* Triển khai các Web Server hoạt động và các môi trường runtime cần thiết để lưu trữ các ứng dụng web.
* Hiểu các nguyên lý cơ bản của lưu trữ cơ sở dữ liệu và cấu hình các tham số truy cập mạng cho các hệ thống cơ sở dữ liệu.
* Thiết lập thành công kết nối dữ liệu an toàn và đáng tin cậy giữa lớp ứng dụng và cơ sở dữ liệu.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| :--- | :--- | :--- | :--- | :--- |
| Sáu | - Nghiên cứu các giao thức cấu hình cơ bản để thiết lập các bản phân phối Linux trên Amazon EC2.<br>- Thực hành thiết lập kết nối thiết bị đầu cuối từ xa an toàn qua SSH tới các instance EC2.<br>+ Tài liệu hóa các luồng lệnh dòng lệnh thiết yếu để khởi tạo hệ thống. | 11/05/2026 | 11/05/2026 | Mã nguồn dự án, Thảo luận nhóm, <https://cloudjourney.awsstudygroup.com/> |
| Bảy | - Thực hiện cập nhật trình quản lý gói (package manager) và các nâng cấp hệ thống thiết yếu trên máy chủ Linux.<br>- Tìm hiểu cách điều chỉnh cấu hình máy chủ và quản lý quyền của người dùng trong môi trường Linux.<br>+ Lên danh sách các gói phần mềm cần thiết cho việc triển khai. | 12/05/2026 | 12/05/2026 | Mã nguồn dự án, Thảo luận nhóm, <https://cloudjourney.awsstudygroup.com/> |
| CN | - Cài đặt và cấu hình các Web Server tiêu chuẩn (như Nginx hoặc Apache) trên instance EC2.<br>- Tìm hiểu cách cấu hình các đường định tuyến lưu lượng truy cập đầu vào cho các cổng web (Cổng 80/443).<br>+ Xác minh tính khả dụng của trang đích mặc định của Web Server. | 13/05/2026 | 13/05/2026 | AWS Management Console, Thảo luận nhóm, <https://cloudjourney.awsstudygroup.com/> |
| Hai | - Thiết lập và cài đặt các runtime ứng dụng cần thiết (như Java JDK hoặc Python runtime) trên Linux.<br>- Cấu hình các biến môi trường hệ thống để phù hợp với các tham số chạy ứng dụng.<br>+ Kiểm tra việc chạy tệp ứng dụng mẫu để xác minh cài đặt runtime. | 14/05/2026 | 14/05/2026 | Mã nguồn dự án, Thảo luận nhóm, <https://cloudjourney.awsstudygroup.com/> |
| Ba | - Nghiên cứu công cụ cơ sở dữ liệu và các quy tắc kết nối trong cấu hình cơ sở hạ tầng đám mây.<br>- Thực hành triển khai hoặc chuẩn bị các dịch vụ cơ sở dữ liệu và thiết lập các security group để chấp nhận kết nối từ xa.<br>+ Ghi lại các giao thức bảo mật an toàn để quản lý cổng lưu trữ cơ sở dữ liệu. | 15/05/2026 | 15/05/2026 | Mã nguồn dự án, Thảo luận nhóm, <https://cloudjourney.awsstudygroup.com/> |
| Tư | - Cấu hình các thuộc tính ứng dụng và tham số driver để liên kết runtime của ứng dụng với cơ sở dữ liệu.<br>- Giải quyết các ràng buộc tường lửa và rào cản của Security Group giữa máy chủ backend và máy chủ dữ liệu.<br>+ Kiểm tra độ ổn định của kết nối và thực hiện các truy vấn dữ liệu cơ bản. | 16/05/2026 | 16/05/2026 | AWS Management Console, Terminal, <https://cloudjourney.awsstudygroup.com/> |
| Năm | - Xem lại toàn bộ quá trình thiết lập môi trường Linux, các chỉ số hiệu suất runtime và các kết nối toàn vẹn dữ liệu.<br>- Tổng hợp nhật ký triển khai, khắc phục các lỗi cấu hình và tài liệu hóa các thuộc tính hệ thống.<br>+ Hoàn thiện báo cáo tóm tắt hàng tuần và chuẩn bị mục tiêu triển khai cho tuần tiếp theo. | 17/05/2026 | 17/05/2026 | AWS Management Console, Thảo luận nhóm, <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 4:
* Tích lũy kinh nghiệm quản trị hệ thống trong việc thiết lập và kiểm soát môi trường Linux trên Amazon EC2.
* Triển khai thành công Web Server hoạt động và cấu hình đúng các lớp runtime kỹ thuật trên máy chủ đám mây.
* Thiết lập thành thạo các liên kết mạng và thuộc tính kết nối các mô-đun ứng dụng backend với cơ sở dữ liệu.
* Giải quyết các phụ thuộc truyền thông môi trường, chuẩn bị một cơ sở máy chủ lưu trữ đáng tin cậy cho các bài kiểm tra khả năng mở rộng sắp tới.

### Kế hoạch cho tuần tiếp theo:
* Chuyển trọng tâm sang các kiến trúc có tính khả dụng cao bằng cách khám phá cấu trúc Load Balancer và Auto Scaling.
* Thực hành cấu hình Elastic Load Balancing (ELB) và Auto Scaling Groups (ASG) để quản lý tải máy chủ.
* Thực hiện các bài kiểm tra áp lực hiệu suất hệ thống để xác minh khả năng tự động mở rộng quy mô hạ tầng dưới tải cao.
