---
title: "Worklog Tuần 11"
date: 2024-01-01
weight: 2
chapter: false
pre: " <b> 1.11. </b> "
---

Tuần thực tập thứ mười một tập trung vào xác minh hệ thống, tái cấu trúc mã và quy trình làm việc đảm bảo chất lượng. Các nhiệm vụ chính bao gồm thực hiện kiểm tra tích hợp đầu-cuối toàn diện trên tất cả các lớp phần mềm và tối ưu hóa các mô-đun backend đã triển khai trước đó. Ngoài ra, việc xem xét kỹ lưỡng mã nguồn cũng được thực hiện để gỡ lỗi các lỗi còn tồn đọng và chuẩn bị toàn bộ kiến trúc được lưu trữ trên đám mây cho giai đoạn nghiệm thu hệ thống chính thức sắp tới.

### Mục tiêu tuần 11:
* Thực hiện kiểm tra tích hợp toàn diện trên tất cả các mô-đun liên kết và các endpoint API của hệ thống.
* Tái cấu trúc, tối ưu hóa và hoàn thiện các chỉ số hiệu suất của tất cả các tính năng đã triển khai.
* Thực hiện xem xét mã nguồn một cách hệ thống và giải quyết các lỗi runtime hoặc bug còn tồn đọng.
* Dọn dẹp cấu hình môi trường để ổn định hệ thống cho quá trình đánh giá và nghiệm thu chính thức.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| :--- | :--- | :--- | :--- | :--- |
| Sáu | - Thiết kế các trường hợp kiểm thử tích hợp toàn diện bao gồm luồng dữ liệu người dùng đầu-cuối.<br>- Bản đồ hóa các phụ thuộc kiểm thử giao diện giữa các bảng điều khiển quản trị và các API CRUD cốt lõi.<br>+ Thiết lập các bộ sưu tập kiểm thử API tự động để đánh giá hành vi gateway. | 26/06/2026 | 26/06/2026 | Mã nguồn dự án, Thảo luận nhóm |
| Bảy | - Thực hiện kiểm tra tích hợp toàn bộ hệ thống để xác minh luồng thông tin trên các mô-đun ứng dụng.<br>- Xác minh rằng các luồng tệp tin chuyển đổi trôi chảy giữa ứng dụng frontend, logic backend và lưu trữ Amazon S3.<br>+ Tài liệu hóa các xác nhận kiểm thử thất bại và nhật ký stack trace. | 27/06/2026 | 27/06/2026 | Mã nguồn dự án, Thảo luận nhóm |
| CN | - Phân tích dữ liệu độ trễ và các chỉ số phản hồi cơ sở dữ liệu thu thập được trong các đợt kiểm thử tích hợp.<br>- Bắt đầu các chuỗi tái cấu trúc mã để tối ưu hóa hiệu suất truy vấn cơ sở dữ liệu và thuật toán lọc.<br>+ Hoàn thiện tái cấu trúc hiệu quả cho các bộ lọc đa tiêu chí phức tạp. | 28/06/2026 | 28/06/2026 | Mã nguồn dự án, Thảo luận nhóm |
| Hai | - Thực hiện tinh chỉnh hiệu suất kỹ lưỡng trên hộp thoại trò chuyện Gemini AI và các vòng lặp xử lý chữ ký web.<br>- Đảm bảo các tham số connection pooling được tối ưu hóa để xử lý nhiều yêu cầu song song một cách trơn tru.<br>+ Chạy các kiểm tra phản hồi cơ bản để xác nhận giảm độ trễ phản hồi của máy chủ. | 29/06/2026 | 29/06/2026 | Mã nguồn dự án, Thảo luận nhóm |
| Ba | - Tiến hành xem xét chéo hệ thống toàn bộ mã nguồn của kho lưu trữ dự án.<br>- Xác minh việc tuân thủ các quy tắc viết mã sạch, bắt lỗi chính xác và tính mô-đun của các package.<br>+ Tài liệu hóa các khối mã lỗi thời (deprecated) cần loại bỏ ngay lập tức. | 30/06/2026 | 30/06/2026 | Mã nguồn dự án, Thảo luận nhóm |
| Tư | - Cô lập, gỡ lỗi và giải quyết các lỗi ứng dụng còn tồn đọng được xác định trong các đợt xem xét.<br>- Xử lý các điểm nghẽn cú pháp và kiểm thử lại các bản vá để loại bỏ các lỗi suy thoái nền tảng không mong muốn.<br>+ Đảm bảo tất cả các đường dẫn mã thực thi an toàn mà không làm hỏng các endpoint đang hoạt động. | 01/07/2026 | 01/07/2026 | Mã nguồn dự án, Thảo luận nhóm |
| Năm | - Kiểm toán thiết lập cơ sở hạ tầng đám mây AWS đang hoạt động để xác minh tính ổn định và ranh giới chi phí.<br>- Tổng hợp tất cả các tài nguyên cần thiết, tệp seed cơ sở dữ liệu và gói cấu hình để chuẩn bị cho việc đánh giá hệ thống.<br>+ Hoàn thiện các nhật ký hàng tuần và tổ chức kế hoạch demo hệ thống cho tuần cuối cùng. | 02/07/2026 | 02/07/2026 | Mã nguồn dự án, Thảo luận nhóm |

### Kết quả đạt được tuần 11:
* Xác minh thành công hành vi hệ thống quy mô lớn bằng cách thực hiện kiểm tra tích hợp đầu-cuối trên tất cả các lớp kiến trúc.
* Hoàn thành các nhiệm vụ tối ưu hóa và tinh chỉnh lớn, tăng cường hiệu suất ứng dụng trên các màn hình quản lý.
* Kiểm toán mã nguồn kho lưu trữ production và giải quyết các lỗi runtime kiến trúc còn tồn đọng.
* Ổn định các biến triển khai, thiết lập sự sẵn sàng vận hành cho giai đoạn nghiệm thu hệ thống.

### Kế hoạch cho tuần tiếp theo:
* Hoàn thiện báo cáo thực tập toàn diện và tổ chức tất cả các tài liệu kỹ thuật liên quan.
* Cấu trúc các phân đoạn bài phát biểu thuyết trình và chuẩn bị bản demo trực tiếp hoạt động của hệ thống đã triển khai.
* Tổng hợp các cột mốc thực tập tổng thể, bàn giao các sản phẩm dự án và chính thức kết thúc chương trình thực tập.
