---
title: "Worklog Tuần 5"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.5. </b> "
---

Tuần thực tập thứ năm chuyển trọng tâm sang kiến trúc hạ tầng có tính khả dụng cao, phân phối tải và tối ưu hóa hiệu suất hệ thống trên AWS. Nội dung cốt lõi bao gồm thực hiện nghiên cứu toàn diện và cấu hình thực tế về Elastic Load Balancing (ELB) và Auto Scaling Groups (ASG). Ngoài ra, các thử nghiệm triển khai hệ thống và đánh giá áp lực hiệu suất cũng được thực hiện để phân tích khả năng phục hồi cấu trúc dưới các mô phỏng lưu lượng truy cập cao.

### Mục tiêu tuần 5:
* Nghiên cứu sâu về vận hành và kiến trúc của các thành phần có tính khả dụng cao trên AWS.
* Thực hành cấu hình Elastic Load Balancing (ELB) để phân phối lưu lượng truy cập ứng dụng đầu vào trên nhiều instance.
* Thiết lập Auto Scaling Groups (ASG) để tự động điều chỉnh năng lực tính toán dựa trên tải hệ thống.
* Thực hiện kiểm tra triển khai thực tế và đánh giá hiệu suất mở rộng quy mô hệ thống tổng thể.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| :--- | :--- | :--- | :--- | :--- |
| Sáu | - Nghiên cứu các khái niệm về tính khả dụng cao (high availability), khả năng chống chịu lỗi (fault tolerance) và cân bằng tải (load balancing) trên AWS.<br>- Tìm hiểu về các loại Elastic Load Balancer (ALB, NLB, GLB).<br>+ Tài liệu hóa các tiêu chuẩn cơ bản để lựa chọn bộ cân bằng tải phù hợp. | 18/05/2026 | 18/05/2026 | Mã nguồn dự án, Thảo luận nhóm, <https://cloudjourney.awsstudygroup.com/> |
| Bảy | - Tìm hiểu cách cấu hình Application Load Balancer (ALB) thông qua AWS Console.<br>- Nghiên cứu cấu hình target group, health check và quy tắc định tuyến.<br>+ Phác thảo các instance đích cho thiết lập phân phối tải. | 19/05/2026 | 19/05/2026 | AWS Management Console, Thảo luận nhóm, <https://cloudjourney.awsstudygroup.com/> |
| CN | - Nghiên cứu cơ chế hoạt động của AWS Auto Scaling và Launch Template.<br>- Tìm hiểu về mở rộng quy mô theo chiều ngang (horizontal) so với chiều dọc (vertical) và các chính sách mở rộng động.<br>+ Xác định các quy tắc ngưỡng (CPU, bộ nhớ) cho các hành động scale-out và scale-in. | 20/05/2026 | 20/05/2026 | Mã nguồn dự án, Thảo luận nhóm, <https://cloudjourney.awsstudygroup.com/> |
| Hai | - Thực hành cấu hình Launch Template với các Amazon Machine Image (AMI) được chỉ định.<br>- Thiết lập Auto Scaling Group (ASG) tích hợp với ALB đã tạo trước đó.<br>+ Xác minh các ràng buộc số lượng instance ban đầu tối thiểu, mong muốn và tối đa. | 21/05/2026 | 21/05/2026 | AWS Management Console, Thảo luận nhóm, <https://cloudjourney.awsstudygroup.com/> |
| Ba | - Thực hiện triển khai thử nghiệm ứng dụng web trong cơ sở hạ tầng tự động mở rộng.<br>- Giám sát trạng thái đăng ký instance và các chỉ số sức khỏe (health) thông qua bảng điều khiển ALB.<br>+ Ghi lại các hành vi tài nguyên cơ bản trong các hoạt động tiêu chuẩn. | 22/05/2026 | 22/05/2026 | AWS Management Console, Thảo luận nhóm, <https://cloudjourney.awsstudygroup.com/> |
| Tư | - Thực hiện kiểm tra áp lực hiệu suất hệ thống bằng cách sử dụng các công cụ benchmark để mô phỏng sự gia tăng đột biến của lưu lượng truy cập.<br>- Phân tích cách Auto Scaling Group phản ứng với tải cao và kích hoạt khởi chạy các instance mới.<br>+ Đánh giá độ trễ mở rộng và tính toàn vẹn dữ liệu trong quá trình mở rộng tài nguyên. | 23/05/2026 | 23/05/2026 | AWS Management Console, Terminal, <https://cloudjourney.awsstudygroup.com/> |
| Năm | - Tổng hợp các chỉ số thử nghiệm, biểu đồ hiệu suất và nhật ký xác minh cân bằng tải.<br>- Tài liệu hóa các bước tối ưu hóa đã thực hiện và giải quyết các bất thường về cấu hình trong chính sách mở rộng.<br>+ Hoàn thiện báo cáo tiến độ hàng tuần và chuẩn bị mục tiêu tích hợp cho giai đoạn tiếp theo. | 24/05/2026 | 24/05/2026 | AWS Management Console, Thảo luận nhóm, <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 5:
* Có được sự hiểu biết vững chắc về các thiết kế đám mây có tính khả dụng cao, các phương pháp chống chịu lỗi và các quy tắc phân phối lưu lượng truy cập.
* Cấu hình thành công Application Load Balancer (ALB) với các target group tự động và kiểm tra sức khỏe nghiêm ngặt.
* Thiết lập thành thạo các Auto Scaling Group (ASG) sử dụng các launch template động để tự động hóa việc mở rộng quy mô instance.
* Hoàn thành thành công các thử nghiệm mô phỏng tải, xác minh khả năng tự phục hồi và tự động mở rộng của môi trường dưới tải cao.

### Kế hoạch cho tuần tiếp theo:
* Chuyển trọng tâm sang các công nghệ container hóa bằng cách đi sâu vào các kiến thức cơ bản về Docker.
* Thực hành viết Dockerfile, xây dựng container image và triển khai các ứng dụng container hóa trên AWS.
* Tìm hiểu về cấu hình AWS CLI (Command Line Interface) để quản lý cơ sở hạ tầng đám mây từ môi trường local.
