---
title: "Worklog Tuần 6"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.6. </b> "
---

Tuần thực tập thứ sáu chuyển hướng sang các công nghệ container hóa và quy trình triển khai microservices hiện đại. Nội dung cốt lõi bao gồm tìm hiểu các kiến thức cơ bản về Docker, viết Dockerfile, xây dựng các container image tối ưu cho ứng dụng và triển khai chúng lên môi trường đám mây AWS. Ngoài ra, các tác vụ thực hành cũng được thực hiện để cấu hình và sử dụng AWS Command Line Interface (AWS CLI) nhằm quản lý cơ sở hạ tầng đám mây trực tiếp qua terminal.

### Mục tiêu tuần 6:
* Nắm vững các kiến thức cơ bản về container hóa và hiểu sự khác biệt về mặt kiến trúc giữa máy ảo và container.
* Tìm hiểu cách viết Dockerfile hiệu quả và xây dựng các image ứng dụng tiêu chuẩn.
* Triển khai các mô-đun ứng dụng đã container hóa vào cơ sở hạ tầng AWS.
* Cài đặt và cấu hình AWS CLI để hợp lý hóa các tác vụ quản trị tài nguyên cục bộ.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| :--- | :--- | :--- | :--- | :--- |
| Sáu | - Nghiên cứu các khái niệm về container hóa, các lợi thế và đặc điểm kiến trúc Docker.<br>- Cài đặt môi trường Docker Engine trên máy trạm phát triển cục bộ.<br>+ Tài liệu hóa các lệnh Docker cốt lõi để quản lý container. | 24/05/2026 | 24/05/2026 | Mã nguồn dự án, Thảo luận nhóm, <https://cloudjourney.awsstudygroup.com/> |
| Bảy | - Tìm hiểu cách soạn thảo Dockerfile hoạt động cho các thành phần runtime của ứng dụng.<br>- Nghiên cứu tối ưu hóa các lớp (layers) và kỹ thuật multi-stage build.<br>+ Viết mã kịch bản cấu hình Dockerfile thử nghiệm. | 25/05/2026 | 25/05/2026 | Mã nguồn dự án, Thảo luận nhóm, <https://cloudjourney.awsstudygroup.com/> |
| CN | - Thực hành xây dựng các Docker Image tùy chỉnh từ các Dockerfile đã chuẩn bị.<br>- Tìm hiểu về quy ước gắn thẻ (tagging) image, nhật ký kiểm tra và các cờ chạy container.<br>+ Khởi chạy một container instance cục bộ để xác minh các cấu hình backend. | 26/05/2026 | 26/05/2026 | Mã nguồn dự án, Thảo luận nhóm, <https://cloudjourney.awsstudygroup.com/> |
| Hai | - Nghiên cứu các mô hình triển khai để chạy các Docker container trên cơ sở hạ tầng đám mây AWS.<br>- Tìm hiểu cơ chế cơ bản của quản lý kho lưu trữ container (container registry).<br>+ Phác thảo các nút hạ tầng cần thiết cho việc thiết lập môi trường runtime. | 27/05/2026 | 27/05/2026 | Mã nguồn dự án, Thảo luận nhóm, <https://cloudjourney.awsstudygroup.com/> |
| Ba | - Thực hiện triển khai các container đích trên nền tảng tính toán AWS được chỉ định.<br>- Xác minh trạng thái sức khỏe của ứng dụng, các cổng truy cập mạng và điểm lưu trữ.<br>+ Tài liệu hóa nhật ký chạy container và các cột mốc vận hành. | 28/05/2026 | 28/05/2026 | AWS Management Console, Thảo luận nhóm, <https://cloudjourney.awsstudygroup.com/> |
| Tư | - Tải xuống và cài đặt gói AWS Command Line Interface (AWS CLI) trên hệ thống.<br>- Tìm hiểu cách thực hiện các thiết lập xác thực an sau bằng cách sử dụng IAM Access Key.<br>+ Thực hành chạy các truy vấn dựa trên terminal để kiểm tra kiểm soát môi trường đám mây. | 29/05/2026 | 29/05/2026 | AWS Management Console, Terminal, <https://cloudjourney.awsstudygroup.com/> |
| Năm | - Hoàn thành tất cả các tác vụ container hóa được yêu cầu và chuỗi thiết lập AWS CLI.<br>- Tổng hợp các kịch bản cấu hình, khắc phục các lỗi đường dẫn lệnh và xem lại các thiết lập.<br>+ Hoàn thiện tài liệu nhật ký và tổ chức lộ trình triển khai cho tuần tiếp theo. | 30/05/2026 | 31/05/2026 | AWS Management Console, Thảo luận nhóm, <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 6:
* Đạt được các kỹ năng thực hành toàn diện trong quy trình làm việc container hóa ứng dụng bằng Docker.
* Soạn thảo thành công các Dockerfile tối ưu và biên dịch các image ứng dụng hoạt động tốt.
* Triển khai các microservices được container hóa lên cơ sở hạ tầng AWS và xác minh các tham số vận hành.
* Thiết lập và cấu hình thành thạo môi trường AWS CLI để cho phép quản lý không gian làm việc từ xa.

### Kế hoạch cho tuần tiếp theo:
* Chuyển sang các giai đoạn triển khai hệ thống cốt lõi bằng cách triển khai các API CRUD quan trọng hỗ trợ màn hình quản trị backend.
* Triển khai logic lọc tài sản được phân loại theo các tham số cụ thể như bộ phận, trạng thái, từ khóa và nhân sự.
* Đi sâu vào các cấu trúc mạng AWS nâng cao và các dịch vụ truyền thông.
