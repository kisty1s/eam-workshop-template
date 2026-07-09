---
title: "Worklog Tuần 7"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.7. </b> "
---

Tuần thực tập thứ bảy chuyển trọng tâm sang việc triển khai tính năng backend cốt lõi và các thành phần mạng đám mây nâng cao. Các nhiệm vụ chính bao gồm phát triển các API CRUD nền tảng cần thiết cho các màn hình kiểm soát quản trị và triển khai logic lọc tài sản đa tiêu chí. Song song với việc phát triển hệ thống, các nghiên cứu toàn diện cũng được thực hiện trên các dịch vụ Mạng nâng cao của AWS để tối ưu hóa lưu lượng truy cập ứng dụng và định tuyến nội bộ.

### Mục tiêu tuần 7:
* Triển khai các API CRUD cốt lõi theo yêu cầu của tất cả các màn hình giao diện quản trị backend.
* Thiết kế và triển khai các khả năng lọc tài sản dựa trên danh mục, bộ phận, trạng thái, từ khóa và nhân sự được chỉ định.
* Đi sâu vào các dịch vụ Mạng nâng cao của AWS và các cấu trúc truyền thông.
* Đảm bảo đồng bộ hóa thích hợp giữa các endpoint backend và các phụ thuộc dữ liệu frontend.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| :--- | :--- | :--- | :--- | :--- |
| Sáu | - Phân tích các phụ thuộc dữ liệu và yêu cầu cho các màn hình quản trị hệ thống.<br>- Phác thảo cấu trúc cho các API CRUD quản lý tài sản cốt lõi.<br>+ Chuẩn bị lược đồ cơ sở dữ liệu cục bộ cho việc tích hợp endpoint. | 31/05/2026 | 31/05/2026 | Mã nguồn dự án, Thảo luận nhóm |
| Bảy | - Phát triển và triển khai các API Create, Read, Update, và Delete (CRUD) tiêu chuẩn.<br>- Đảm bảo các endpoint được phát triển tuân thủ các quy tắc thiết kế API REST tiêu chuẩn.<br>+ Thực hiện kiểm tra tính hợp lệ cục bộ ban đầu bằng Postman trên các endpoint cơ bản. | 01/06/2026 | 01/06/2026 | Mã nguồn dự án, Thảo luận nhóm |
| CN | - Nghiên cứu các tham số truy vấn backend và chiến lược tối ưu hóa lọc.<br>- Phác thảo logic lọc đa tiêu chí cần thiết cho các mô-đun kho lưu trữ tài sản.<br>+ Tài liệu hóa các yêu cầu kỹ thuật cho các điều kiện lọc. | 02/06/2026 | 02/06/2026 | Mã nguồn dự án, Thảo luận nhóm |
| Hai | - Lập trình các tính năng lọc tài sản để sắp xếp các phần tử theo danh mục, bộ phận và trạng thái.<br>- Tích hợp thêm các bộ xử lý lọc cho từ khóa văn bản và ID nhân sự được phân công.<br>+ Kiểm tra phản hồi truy vấn kết hợp bằng cách sử dụng các tập dữ liệu backend mẫu. | 03/06/2026 | 03/06/2026 | Mã nguồn dự án, Thảo luận nhóm |
| Ba | - Nghiên cứu hệ sinh thái các dịch vụ Mạng nâng cao có sẵn trên AWS.<br>- Tìm hiểu cách các dịch vụ mạng được quản lý tạo điều kiện cho định tuyến lưu lượng, bảo mật và liên kết tài nguyên.<br>+ Tài liệu hóa các cấu trúc mạng đám mây chính. | 04/06/2026 | 04/06/2026 | Tài liệu AWS, Thảo luận nhóm |
| Tư | - Phân tích các công cụ mạng đám mây cụ thể để xác định các dịch vụ có thể áp dụng cho việc tối ưu hóa bảo mật hệ thống.<br>- Thực hiện kiểm tra tích hợp giữa các API CRUD mới triển khai và các giao diện frontend.<br>+ Giải quyết các xung đột ánh xạ dữ liệu trên các bảng điều khiển quản trị. | 05/06/2026 | 05/06/2026 | Tài liệu AWS, Mã nguồn dự án |
| Năm | - Tổng hợp tất cả mã backend chức năng, các lớp lọc và cấu trúc định tuyến API.<br>- Tối ưu hóa các chuỗi truy vấn kho lưu trữ để tăng tốc độ phản hồi trên các phụ thuộc trang quản trị.<br>+ Hoàn thiện báo cáo nhật ký và phác thảo mục tiêu phát triển cho giai đoạn tiếp theo. | 06/06/2026 | 07/06/2026 | Mã nguồn dự án, Thảo luận nhóm |

### Kết quả đạt được tuần 7:
* Phát triển và triển khai thành công các API CRUD cốt lõi đáp ứng tất cả các phụ thuộc của màn hình quản lý.
* Triển khai logic lọc tài sản linh hoạt hỗ trợ các tham số danh mục, bộ phận, trạng thái, từ khóa và nhân sự cụ thể.
* Có được sự hiểu biết nâng cao về các mô hình Mạng AWS và các thành phần kết nối.
* Đảm bảo tích hợp dữ liệu mạnh mẽ giữa các mô-đun backend cốt lõi, tạo điều kiện cho các tính năng nâng cao của hệ thống.

### Kế hoạch cho tuần tiếp theo:
* Tiến lên với các tính năng cấp doanh nghiệp bằng cách triển khai chữ ký điện tử, bộ theo dõi tiến độ và bảng đánh giá CSAT.
* Xây dựng hệ thống Câu hỏi thường gặp tự phục vụ, các tiện ích xuất file PDF/Excel và hệ thống thực thi chữ ký.
* Nghiên cứu tích hợp AI bằng cách khám phá việc tích hợp trợ lý Gemini AI để tạo hộp thoại hỗ trợ tương tác.
