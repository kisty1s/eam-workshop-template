---
title: "Worklog Tuần 10"
date: 2024-01-01
weight: 2
chapter: false
pre: " <b> 1.10. </b> "
---

Tuần thực tập thứ mười tập trung vào việc tinh chỉnh các mô hình hệ thống, chuẩn hóa tài liệu kỹ thuật cốt lõi và thực hiện kiểm toán căn chỉnh cấu trúc. Các nhiệm vụ chính bao gồm hoàn thiện tất cả các sơ đồ phân tích và thiết kế hệ thống để phản ánh chính xác các tính năng đã triển khai. Ngoài ra, tài liệu kỹ thuật toàn diện của dự án cũng được chuẩn hóa và đồng bộ hóa với cả kiến trúc đám mây AWS đã triển khai và mã nguồn production.

### Mục tiêu tuần 10:
* Hoàn thiện và điều chỉnh tất cả các mô hình phân tích hệ thống và sơ đồ thiết kế phần mềm.
* Chuẩn hóa bộ tài liệu kỹ thuật của dự án để đáp ứng các tiêu chuẩn công nghiệp và học thuật.
* Đồng bộ hóa tài liệu thiết kế hệ thống với các bản thiết kế kiến trúc triển khai thực tế trên AWS.
* Thiết lập tính nhất quán tham chiếu chéo chính xác giữa các tài liệu kỹ thuật và mã nguồn triển khai.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| :--- | :--- | :--- | :--- | :--- |
| Sáu | - Xem lại tất cả các sơ đồ phân tích hệ thống hiện có bao gồm Use Case và Class diagram.<br>- Xác định các điểm khác biệt về mặt kiến trúc giữa lược đồ thiết kế ban đầu và mã hiện tại.<br>+ Tài liệu hóa các phân đoạn thiết kế cần điều chỉnh đồ họa. | 19/06/2026 | 19/06/2026 | Mã nguồn dự án, Thảo luận nhóm |
| Bảy | - Tái cấu trúc và hoàn thiện các mô hình phân tích hệ thống cấu trúc và sơ đồ tương tác.<br>- Đảm bảo các sơ đồ tuần tự (sequence diagram) mô tả chính xác các hành vi lọc tài sản đa tiêu chí.<br>+ Xuất các khối sơ đồ đã cập nhật vào kho lưu trữ dự án. | 20/06/2026 | 20/06/2026 | Mã nguồn dự án, Thảo luận nhóm |
| CN | - Kiểm toán các lược đồ quan hệ cơ sở dữ liệu và cập nhật Sơ đồ quan hệ thực thể (ERD).<br>- Xác minh rằng các bảng theo dõi chữ ký và các thuộc tính nhật ký trò chuyện được mô hình hóa chính xác.<br>+ Cập nhật các định nghĩa từ điển dữ liệu trong tệp thiết kế. | 21/06/2026 | 21/06/2026 | Mã nguồn dự án, Thảo luận nhóm |
| Hai | - Bắt đầu quy trình chuẩn hóa cho tài liệu kỹ thuật tổng thể của dự án.<br>- Sắp xếp các chương kỹ thuật, mô tả hợp đồng API và các tham số môi trường.<br>+ Soạn thảo các phân đoạn giới thiệu cho bộ tài liệu kỹ thuật chuẩn hóa. | 22/06/2026 | 22/06/2026 | Mã nguồn dự án, Thảo luận nhóm |
| Ba | - Chuẩn hóa các hướng dẫn vận hành hệ thống, các bước triển khai và thiết lập kết nối cơ sở dữ liệu.<br>- Xem lại toàn bộ tài liệu kỹ thuật để loại bỏ các lỗi định dạng và cấu trúc.<br>+ Hoàn thiện các định nghĩa kỹ thuật cho các mô-đun hệ thống backend. | 23/06/2026 | 23/06/2026 | Mã nguồn dự án, Thảo luận nhóm |
| Tư | - Đồng bộ hóa tài liệu kỹ thuật đã biên soạn với các bản thiết kế kiến trúc triển khai AWS.<br>- Xác minh rằng các đường dẫn subnet mạng, cấu hình EC2 và vai trò S3 khớp với các tài liệu.<br>+ Đảm bảo tính nhất quán cấu trúc trên các bố cục triển khai đám mây. | 24/06/2026 | 24/06/2026 | Tài liệu AWS, Thảo luận nhóm |
| Năm | - Kiểm toán và đồng bộ hóa các thông số kỹ thuật của tài liệu với mã nguồn thực tế của kho lưu trữ.<br>- Bản đồ hóa các tuyến endpoint API đang hoạt động và cấu trúc tham số với các thông số kỹ thuật đã viết.<br>+ Hoàn thiện nhật ký báo cáo và phác thảo các mục tiêu xác minh hệ thống cho tuần tới. | 25/06/2026 | 25/06/2026 | Mã nguồn dự án, Thảo luận nhóm |

### Kết quả đạt được tuần 10:
* Tinh chỉnh và hoàn thiện thành công toàn bộ các mô hình phân tích hệ thống cấu trúc và sơ đồ thiết kế phần mềm.
* Biên soạn và chuẩn hóa bộ tài liệu kỹ thuật dự án thống nhất.
* Đạt được sự đồng bộ hóa hoàn toàn giữa tài liệu thiết kế và kiến trúc triển khai đám mây AWS.
* Xác minh tính liên kết hoàn toàn giữa các thông số kỹ thuật bằng văn bản và mã nguồn triển khai thực tế.

### Kế hoạch cho tuần tiếp theo:
* Chuyển sang các giai đoạn xác minh hệ thống bằng cách thực hiện kiểm tra tích hợp đầu-cuối toàn diện.
* Tối ưu hóa các mô-đun chức năng đã triển khai và tái cấu trúc các tham số hiệu suất mã nguồn.
* Xem lại trạng thái codebase, giải quyết các lỗi hệ thống còn tồn đọng và chuẩn bị cơ sở hạ tầng cho các đánh giá nghiệm thu.
