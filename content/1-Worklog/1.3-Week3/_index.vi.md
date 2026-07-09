---
title: "Worklog Tuần 3"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.3. </b> "
---

Tuần thực tập thứ ba chuyển trọng tâm từ các lớp mạng sang giải pháp lưu trữ đám mây và quản lý danh tính trên AWS. Nội dung cốt lõi bao gồm thực hiện nghiên cứu lý thuyết và thực hành thực tế trên kho lưu trữ đối tượng Amazon S3, cấu trúc bucket dữ liệu và quản lý quyền truy cập tài nguyên. Ngoài ra, các cấu hình nền tảng cũng đã được thực hiện bằng cách sử dụng AWS Identity and Access Management (IAM) để quản lý người dùng, nhóm và quyền truy cập một cách an toàn.

### Mục tiêu tuần 3:
* Nghiên cứu sâu về các khái niệm cốt lõi và tham số vận hành của Amazon S3 (Simple Storage Service).
* Thực hành khởi tạo S3 Bucket, tải dữ liệu đối tượng lên và cấu hình quyền truy cập bucket.
* Làm quen với bố cục cơ sở hạ tầng của AWS Identity and Access Management (IAM).
* Hiểu cách quản lý IAM User, Group và Role để duy trì quyền truy cập an toàn trên các tài nguyên AWS.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| :--- | :--- | :--- | :--- | :--- |
| Sáu | - Nghiên cứu tổng quan về dịch vụ lưu trữ đối tượng Amazon S3 và các đặc tính kiến trúc của nó.<br>- Tìm hiểu về tính khả dụng của dữ liệu, chỉ số độ bền và các lớp lưu trữ (storage classes).<br>+ Chuẩn bị tài liệu cho các bài thực hành lưu trữ. | 04/05/2026 | 04/05/2026 | Mã nguồn dự án, Thảo luận nhóm, <https://cloudjourney.awsstudygroup.com/> |
| Bảy | - Thực hành tạo các Amazon S3 Bucket tùy chỉnh thông qua AWS Management Console.<br>- Tìm hiểu về các quy tắc đặt tên toàn cầu và vị trí vùng (region) cho các bucket lưu trữ.<br>+ Kiểm tra các chức năng tải dữ liệu lên và lưu trữ tệp cơ bản. | 05/05/2026 | 05/05/2026 | AWS Management Console, Thảo luận nhóm, <https://cloudjourney.awsstudygroup.com/> |
| CN | - Nghiên cứu cơ chế phân quyền S3, bao gồm chặn truy cập công khai và chính sách bucket (bucket policy).<br>- Thực hành cấu hình quyền truy cập chi tiết để bảo mật các thư mục tệp.<br>+ Xác minh trạng thái truy xuất đối tượng dưới các quyền hạn được hạn chế. | 06/05/2026 | 06/05/2026 | AWS Management Console, Thảo luận nhóm, <https://cloudjourney.awsstudygroup.com/> |
| Hai | - Nghiên cứu kiến trúc nền tảng của AWS Identity and Access Management (IAM).<br>- Hiểu nguyên tắc đặc quyền tối thiểu và quản lý quyền truy cập trong các nền tảng đám mây.<br>+ Tài liệu hóa các định nghĩa chính về bảo vệ danh tính đám mây. | 07/05/2026 | 07/05/2026 | Mã nguồn dự án, Thảo luận nhóm, <https://cloudjourney.awsstudygroup.com/> |
| Ba | - Tìm hiểu cách khởi tạo và cấu hình các IAM User và IAM Group tùy chỉnh.<br>- Thực hành gán các chính sách bảo mật được quản lý để kiểm soát quyền của người dùng trên bảng điều khiển.<br>+ Kiểm tra quy trình tạo thông tin xác thực và đăng nhập của người dùng. | 08/05/2026 | 08/05/2026 | AWS Management Console, Thảo luận nhóm, <https://cloudjourney.awsstudygroup.com/> |
| Tư | - Nghiên cứu vai trò của IAM Role và cấu hình ủy quyền giữa dịch vụ với dịch vụ.<br>- Tìm hiểu cách kích hoạt liên lạc tài nguyên an toàn mà không cần sử dụng mã xác thực cố định.<br>+ Phác thảo cấu hình quyền cho tương tác giữa EC2 và S3. | 09/05/2026 | 09/05/2026 | AWS Management Console, Thảo luận nhóm, <https://cloudjourney.awsstudygroup.com/> |
| Năm | - Tổng hợp các kết quả thực tế liên quan đến vận hành Amazon S3 và cài đặt bảo mật IAM.<br>- Xem lại toàn bộ cấu trúc kiểm soát quyền truy cập đã thiết lập và ghi lại các cấu hình chính.<br>+ Hoàn thiện dữ liệu nhật ký và phác thảo các mục tiêu triển khai cho giai đoạn tiếp theo. | 10/05/2026 | 10/05/2026 | AWS Management Console, Thảo luận nhóm, <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 3:
* Có được kiến thức toàn diện về kiến trúc Amazon S3 và cơ chế lưu trữ dữ liệu.
* Khởi tạo thành thạo các Amazon S3 Bucket và triển khai cấu hình chi tiết cho quyền truy cập dữ liệu.
* Nắm vững các khái niệm vận hành IAM, bao gồm quản trị thành công IAM User, Group và Role.
* Xây dựng được tiêu chuẩn bảo mật đám mây đáng tin cậy để điều chỉnh tương tác tài nguyên và danh tính người dùng một cách an toàn.

### Kế hoạch cho tuần tiếp theo:
* Chuyển trọng tâm sang thiết lập môi trường bằng cách cấu hình các máy chủ Linux trên Amazon EC2.
* Thực hành cài đặt Web Server, runtime kỹ thuật và quản lý các tham số môi trường.
* Tìm hiểu và thiết lập kết nối ứng dụng tới các dịch vụ cơ sở dữ liệu cơ bản.
