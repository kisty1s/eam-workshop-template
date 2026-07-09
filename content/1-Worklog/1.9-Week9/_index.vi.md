---
title: "Worklog Tuần 9"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.9. </b> "
---

Tuần thực tập thứ chín chuyển tiếp từ phát triển tính năng chức năng sang thiết kế kiến trúc hệ thống và lập kế hoạch triển khai đám mây. Trọng tâm chính được đặt vào việc mô hình hóa cấu trúc bố cục hạ tầng ứng dụng trên AWS và củng cố toàn bộ các bản thiết kế kỹ thuật. Ngoài ra, tài liệu thiết kế hệ thống toàn diện cũng được hoàn thiện để chuẩn bị khung vững chắc cho các hoạt động lưu trữ môi trường thực tế sắp tới.

### Mục tiêu tuần 9:
* Thiết kế bố cục kiến trúc cơ sở hạ tầng đám mây toàn diện để triển khai hệ thống trên AWS.
* Soạn thảo, tinh chỉnh và hoàn thiện tài liệu thiết kế kiến trúc kỹ thuật đầy đủ.
* Chuẩn bị các cấu hình hậu cần, mạng và môi trường cần thiết cho các giai đoạn triển khai thực tế.
* Đảm bảo sự sẵn sàng về cấu trúc bằng cách ánh xạ trực tiếp các mô-đun phần mềm tới các tài nguyên máy chủ đám mây đích.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| :--- | :--- | :--- | :--- | :--- |
| Sáu | - Phân tích các thành phần phần mềm, công cụ cơ sở dữ liệu và các mô-đun chat đã được triển khai trong các tuần trước.<br>- Đánh giá các ràng buộc tài nguyên và nhu cầu mạng cho việc lập bản đồ đám mây.<br>+ Tài liệu hóa các yêu cầu cấp cao cho bố cục triển khai. | 12/06/2026 | 12/06/2026 | Mã nguồn dự án, Thảo luận nhóm |
| Bảy | - Bắt đầu phác thảo các sơ đồ kiến trúc hệ thống cấu trúc nhắm mục tiêu thực thi trên AWS.<br>- Xác định vị trí tối ưu cho các subnet mạng, instance tính toán và lớp lưu trữ.<br>+ Tạo các bản phác thảo sớm cho bản thiết kế cơ sở hạ tầng. | 13/06/2026 | 13/06/2026 | Tài liệu AWS, Thảo luận nhóm |
| CN | - Tích hợp các cấu hình có tính khả dụng cao trước đó (Load Balancer, Auto Scaling) vào kế hoạch kiến trúc.<br>- Bản đồ hóa các chính sách định tuyến lưu lượng an toàn để cô lập các thành phần API quản trị.<br>+ Ghi chú các điểm tích hợp bảo mật trong đường dẫn mạng. | 14/06/2026 | 14/06/2026 | Tài liệu AWS, Thảo luận nhóm |
| Hai | - Cấu trúc khung kỹ thuật cho Tài liệu Thiết kế Kiến trúc chính thức.<br>- Chi tiết hóa các thông số chức năng của các thành phần AWS đã chọn bao gồm EC2, S3, VPC và IAM.<br>+ Soạn thảo các phân đoạn mô tả cho các khối bố cục cốt lõi. | 15/06/2026 | 15/06/2026 | Mã nguồn dự án, Thảo luận nhóm |
| Ba | - Xem lại, tinh chỉnh và tập hợp tất cả các sơ đồ kiến trúc và phân đoạn văn bản vào một tệp duy nhất.<br>- Hoàn thiện toàn bộ tài liệu thiết kế kiến trúc theo hướng dẫn của dự án.<br>+ Hoàn thành các xác minh kỹ thuật của các tiêu chí tài liệu. | 16/06/2026 | 16/06/2026 | Mã nguồn dự án, Thảo luận nhóm |
| Tư | - Bắt đầu các giao thức chuẩn bị thực tế để khởi chạy hệ thống vật lý trên đám mây.<br>- Kiểm toán các kịch bản tự động hóa triển khai cần thiết, các tham số môi trường và thiết lập tên miền.<br>+ Lập ra một danh sách kiểm tra rõ ràng cho các mục tiêu khởi chạy runtime. | 17/06/2026 | 17/06/2026 | AWS Management Console, Thảo luận nhóm |
| Năm | - Hoàn thiện các tham số triển khai và phân bổ tài nguyên để đảm bảo kiểm soát chi phí vận hành.<br>- Xem lại trạng thái đồng bộ hóa tài liệu với nhóm phát triển để loại bỏ các khoảng trống cấu hình.<br>+ Hoàn thành nhật ký báo cáo và phác thảo các mục tiêu thực thi cho giai đoạn tiếp theo. | 18/06/2026 | 18/06/2026 | AWS Management Console, Thảo luận nhóm |

### Kết quả đạt được tuần 9:
* Mô hình hóa và phác thảo thành công kiến trúc triển khai hệ thống hoàn chỉnh tối ưu cho việc thực thi trên AWS.
* Biên soạn và hoàn thiện tài liệu thiết kế kiến trúc kỹ thuật toàn diện.
* Hoàn thành các đợt kiểm toán môi trường thiết yếu và nhật ký chuẩn bị để hỗ trợ lưu trữ hệ thống thực tế an toàn.
* Định hình mã triển khai phù hợp với các bản thiết kế kiến trúc, thiết lập sự sẵn sàng về mặt cấu trúc cho các hoạt động triển khai.

### Kế hoạch cho tuần tiếp theo:
* Hoàn thiện và điều chỉnh các mô hình phân tích hệ thống và sơ đồ thiết kế phần mềm tổng thể.
* Chuẩn hóa các tài liệu kỹ thuật và đảm bảo đồng bộ hóa chính xác giữa lược đồ thiết kế, kiến trúc đám mây và cấu hình mã nguồn.
* Tái cấu trúc các cấu trúc cơ sở dữ liệu và căn chỉnh mô hình cấu trúc với bộ tài liệu dự án.
