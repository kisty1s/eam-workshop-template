---
title: "Worklog Tuần 8"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.8. </b> "
---

Tuần thực tập thứ tám tập trung vào việc triển khai các tính năng cấp doanh nghiệp, các tiện ích báo cáo và hệ thống hỗ trợ người dùng thông minh. Các hoạt động phát triển cốt lõi bao gồm xây dựng quy trình ký điện tử, biểu mẫu đánh giá mức độ hài lòng của khách hàng (CSAT), bộ theo dõi tiến độ và các mô-đun xuất bản tài liệu. Hơn nữa, một hộp thoại hỗ trợ trò chuyện được hỗ trợ bởi AI cũng đã được tích hợp cùng với hệ thống trò chuyện trực tiếp để quản trị viên can thiệp trực tiếp.

### Mục tiêu tuần 8:
* Triển khai thực hiện ký điện tử, theo dõi các chữ ký đang chờ xử lý và tính năng tải lên chữ ký tùy chỉnh.
* Xây dựng các tiện ích quy trình làm việc có cấu trúc bao gồm bộ theo dõi tiến độ trực quan, bảng phản hồi CSAT và cơ sở dữ liệu Câu hỏi thường gặp tự phục vụ.
* Phát triển các công cụ xuất dữ liệu hỗ trợ cả hai định dạng PDF và Excel phục vụ mục đích kiểm toán quản trị.
* Tích hợp giao diện thoại hỗ trợ kết hợp sử dụng phản hồi tự động của Gemini AI và các kênh trò chuyện trực tiếp của quản trị viên.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| :--- | :--- | :--- | :--- | :--- |
| Sáu | - Nghiên cứu các tiêu chuẩn triển khai chữ ký điện tử và các chỉ số bảo mật tệp tin.<br>- Lập trình các mô-đun cơ sở để thực thi và tải lên chữ ký kỹ thuật số một cách an sau.<br>+ Thiết lập các lược đồ dữ liệu cục bộ để lưu trữ các thuộc tính chữ ký. | 07/06/2026 | 07/06/2026 | Mã nguồn dự án, Thảo luận nhóm |
| Bảy | - Phát triển hành vi xử lý để truy vấn và bắt buộc thực thi các chữ ký đang chờ xử lý trong các yêu cầu của hệ thống.<br>- Thiết kế và xây dựng giao diện trình theo dõi tiến độ quy trình làm việc trực quan cho các hành động của người dùng.<br>+ Kiểm tra quá trình chuyển đổi trạng thái bên trong thành phần theo dõi tiến độ. | 08/06/2026 | 08/06/2026 | Mã nguồn dự án, Thảo luận nhóm |
| CN | - Xây dựng biểu mẫu đánh giá mức độ hài lòng của khách hàng (CSAT) và các mô-đun cơ sở dữ liệu Câu hỏi thường gặp tự phục vụ.<br>- Triển khai các endpoint API backend để ghi lại các đánh giá của người dùng và truy xuất các câu trả lời tĩnh của Câu hỏi thường gặp.<br>+ Thực hiện kiểm tra tính hợp lệ dữ liệu đối với điểm hài lòng đã gửi. | 09/06/2026 | 09/06/2026 | Mã nguồn dự án, Thảo luận nhóm |
| Hai | - Nghiên cứu các thư viện báo cáo để tạo các bảng dữ liệu và cấu hình tài liệu di động.<br>- Triển khai các tính năng xuất dữ liệu cho phép quản trị viên tải các bảng xuống định dạng Excel.<br>+ Xác minh ánh xạ cột và định dạng ô trong các bảng Excel được tạo ra. | 10/06/2026 | 10/06/2026 | Mã nguồn dự án, Thảo luận nhóm |
| Ba | - Lập trình tiện ích báo cáo hệ thống để xuất dữ liệu ứng dụng có cấu trúc sang tài liệu PDF.<br>- Tiến hành nghiên cứu ban đầu về việc tích hợp API Gemini AI vào các framework giao diện trò chuyện.<br>+ Tài liệu hóa định dạng dữ liệu truyền đi của yêu cầu và phản hồi API cho mô hình AI. | 11/06/2026 | 11/06/2026 | Tài liệu AWS, Mã nguồn dự án |
| Tư | - Kết nối và tích hợp trợ lý Gemini AI vào hộp thoại hỗ trợ của ứng dụng.<br>- Lập trình cơ chế định tuyến dự phòng để chuyển tiếp một phiên tự động sang kênh trò chuyện trực tiếp.<br>+ Kiểm tra các mẫu phản hồi và hành vi hiển thị đối thoại. | 12/06/2026 | 12/06/2026 | Mã nguồn dự án, Thảo luận nhóm |
| Năm | - Xây dựng bảng điều khiển không gian làm việc trò chuyện trực tiếp được thiết kế riêng cho các quản trị viên hệ thống để can thiệp.<br>- Thực hiện kiểm tra hồi quy từ đầu đến cuối trên tất cả các chữ ký, xuất file và giao diện trò chuyện AI.<br>+ Tổng hợp các khối mã hệ thống và chuẩn bị các biểu đồ căn chỉnh kiến trúc cho tuần tới. | 13/06/2026 | 14/06/2026 | Mã nguồn dự án, Thảo luận nhóm |

### Kết quả đạt được tuần 8:
* Triển khai thành công hệ thống chữ ký điện tử toàn diện có tính năng thực thi trực tiếp, kích hoạt theo dõi các chữ ký đang chờ xử lý và hỗ trợ tải lên.
* Tích hợp các công cụ theo dõi tiến trình hoạt động, các nút FAQ tự phục vụ và các đường dẫn thu thập đánh giá CSAT có cấu trúc.
* Cung cấp các tiện ích báo cáo dữ liệu ổn định cho phép tạo các tệp PDF và Excel sạch từ các trạng thái ứng dụng.
* Triển khai thành công hộp thoại hỗ trợ tương tác được cung cấp bởi Gemini AI và được hỗ trợ bởi một cổng trò chuyện trực tiếp chức năng.

### Kế hoạch cho tuần tiếp theo:
* Chuyển sang các bản thiết kế kiến trúc hệ thống bằng cách thiết kế các topo triển khai cụ thể cho việc thực thi trên AWS.
* Biên soạn và hoàn thiện các tài liệu kiến trúc triển khai toàn diện dựa trên các thông số kỹ thuật của dự án.
* Phác thảo các tham số thực thi thực tế để chuẩn bị các mô-đun hệ thống backend cho các thử nghiệm lưu trữ thực tế.
