---
title: "Event 1: AWS First Cloud Journey Community Day"
date: 2026-06-06
weight: 1
chapter: false
pre: " <b> 4.1. </b> "
---

## Thông tin sự kiện

| Thông tin | Nội dung |
| --- | --- |
| Thời gian | Ngày 06/06/2026 |
| Địa điểm | Tầng 26, Tòa nhà Bitexco Financial Tower |
| Hình thức tham gia | Tham gia trực tiếp |
| Vai trò | Người tham dự |
| Chủ đề chính | Cloud Computing, DevOps, Security, AI, WebSocket, Teamwork và định hướng nghề nghiệp trong lĩnh vực công nghệ thông tin |
| Danh sách diễn giả | Tran Trung Vinh - System Administrator at Central Retail Group;<br>Bảo Huỳnh - Junior Cloud Native Developer, Endava Vietnam;<br>Lê Hoàng Gia Đại, Nguyễn Quốc Bảo, Trương Huy Phước, Việt Phát |

## 1. Mục đích tham gia sự kiện

AWS First Cloud Journey Community Day là một buổi hội thảo chuyên môn giá trị cao được thiết kế nhằm giúp sinh viên và người mới bắt đầu học kỹ thuật đám mây thu hẹp khoảng cách giữa lý thuyết học thuật và thực tiễn ngành. Bằng cách tập hợp các chuyên gia đang hoạt động trong lĩnh vực công nghệ doanh nghiệp, sự kiện đã cung cấp cho người tham dự một cái nhìn toàn diện về cách các công nghệ hiện đại—như AWS, Docker, Machine Learning, WebSocket, GraphRAG và các quy trình DevOps—được tích hợp và triển khai trong môi trường sản xuất thực tế.

Mục tiêu chính của tôi khi tham dự sự kiện bao gồm:
*   **Mở rộng kiến thức vượt ra ngoài lớp học:** Đi xa hơn các khái niệm lý thuyết cơ bản để hiểu sâu về triển khai ứng dụng nâng cao, tuân thủ bảo mật hệ thống và kiến trúc đám mây thời gian thực.
*   **Quan sát các phương pháp thực tiễn tốt nhất trong ngành (Best Practices):** Học hỏi trực tiếp từ cách các chuyên gia CNTT giàu kinh nghiệm phân tích các vấn đề kỹ thuật phức tạp, đề xuất giải pháp cấp doanh nghiệp và chia sẻ các bài học kinh nghiệm thực tế.
*   **Xây dựng lộ trình phát triển nghề nghiệp:** Đạt được những hiểu biết sâu sắc về lộ trình thăng tiến nghề nghiệp trong lĩnh vực Cloud và DevOps nhằm điều chỉnh các năng lực hiện tại của bản thân phù hợp với kỳ vọng của doanh nghiệp.

## 2. Nội dung chính của sự kiện

Ngày hội cộng đồng bao gồm một chuỗi các buổi chia sẻ chuyên sâu và đa dạng. Mặc dù mỗi bài thuyết trình hướng tới một lĩnh vực công nghệ riêng biệt, tất cả đều thống nhất xung quanh một mục tiêu duy nhất: xây dựng năng lực kỹ thuật toàn diện, đa tầng cho những người thực hành AWS hiện đại.

### 2.1. Docker - Công nghệ Containerization (Đóng gói ứng dụng)

Phiên chia sẻ này giới thiệu các khái niệm cốt lõi của công nghệ container hóa và nhấn mạnh vai trò không thể thay thế của Docker trong vòng đời phát triển, kiểm thử và triển khai phần mềm hiện đại. Diễn giả đã cung cấp một phân tích so sánh giữa Công nghệ ảo hóa truyền thống (Virtualization) và Container hóa (Containerization), làm nổi bật lý do tại sao container nhẹ hơn đáng kể, hiệu quả tài nguyên hơn và có khả năng mở rộng linh hoạt hơn cho các cơ sở hạ tầng cloud-native hiện đại.

*   **Nhận thức cốt lõi (Key Insight):** Docker không chỉ đơn thuần là một công cụ chạy các ứng dụng cô lập; nó là xương sống của các đường ống tích hợp liên tục và triển khai liên tục (CI/CD) trong các quy trình DevOps hiện đại. Bằng cách đóng gói mã nguồn, các thư viện hệ thống, cấu hình và các phụ thuộc thời gian chạy (runtime dependencies) vào các container thống nhất, các nhóm kỹ sư có thể loại bỏ lỗi kinh điển "chạy được trên máy tôi" giữa môi trường cục bộ, máy chủ staging và môi trường sản xuất (production).
*   **Liên kết với AWS (AWS Alignment):** Việc thành thạo Docker đóng vai trò là nền tảng tiên quyết để làm việc với các dịch vụ điều phối (orchestration) nâng cao trên AWS, chẳng hạn như Amazon ECS (Elastic Container Service) và Amazon EKS (Elastic Kubernetes Service).

### 2.2. Hệ thống phát hiện xâm nhập mạng dựa trên Machine Learning (NIDS) trên AWS

Xoay quanh các mô hình bảo mật không gian mạng hiện đại, buổi chia sẻ này đã đi sâu vào việc bảo mật các ứng dụng web chống lại các mối đe dọa đang phát triển bằng cách sử dụng AWS WAF (Web Application Firewall) kết hợp với trí tuệ nhân tạo. Diễn giả đã trình diễn cách AWS WAF hoạt động như một lớp phòng thủ biên để giảm thiểu các lỗ hổng tiêu chuẩn trong Top 10 OWASP, bao gồm SQL Injection, Cross-Site Scripting (XSS), botnet tự động và các cuộc tấn công brute-force.

*   **Nhận thức cốt lõi (Key Insight):** Các tường lửa dựa trên quy tắc tĩnh truyền thống, mặc dù hiệu quả đối với các chữ ký đe dọa lịch sử đã được xác định trước, nhưng vốn dĩ gặp khó khăn trong việc giảm thiểu các cuộc tấn công zero-day mới hoặc các hoạt động bất thường đa hình. Để vượt qua những hạn chế này, phiên thảo luận đã đề xuất tích hợp AWS WAF với các mô hình Học máy (Machine Learning) để xây dựng một Hệ thống phát hiện xâm nhập mạng (NIDS) mạnh mẽ, có khả năng liên tục học hỏi từ dữ liệu đo lường mạng đang hoạt động (network telemetry) để xác định các hành vi bất thường.
*   **Xu hướng Bảo mật (Security Shift):** Bảo mật đám mây đang chuyển dịch nhanh chóng từ các biện pháp phòng thủ tĩnh dựa trên chữ ký truyền thống sang các mô hình phản ứng tự động dựa trên hành vi, mang tính dự báo và động.

### 2.3. Từ IT Helpdesk đến Senior Sysadmin

Buổi định hướng nghề nghiệp này đã cung cấp những hướng dẫn thực tế và dễ tiếp cận dựa trên hành trình cá nhân của diễn giả từ hỗ trợ kỹ thuật cấp thấp (IT Helpdesk) đến quản lý các hạ tầng doanh nghiệp phức tạp với tư cách là Quản trị viên hệ thống cấp cao (Senior System Administrator).

*   **Nhận thức cốt lõi (Key Insight):** Tiến lên các vai trò hạ tầng cấp cao đòi hỏi một tư duy hướng tới sự ổn định bền bỉ, phương pháp khắc phục sự cố (troubleshooting) nâng cao, thói quen ghi chép tài liệu hệ thống, quy trình giám sát toàn diện và sự cẩn trọng tối đa (ví dụ: thực thi các chính sách an toàn nghiêm ngặt và không bao giờ thử nghiệm trực tiếp trên môi trường production mà không có kế hoạch khôi phục đã được xác minh).
*   **Sự thay đổi mô hình (The Paradigm Shift):** Diễn giả nhấn mạnh sự thay đổi tư duy quan trọng cần có khi chuyển từ môi trường On-Premise truyền thống, cứng nhắc sang Điện toán đám mây (Cloud), tập trung vào khả năng mở rộng đàn hồi, tối ưu hóa chi phí trả tiền theo nhu cầu sử dụng (pay-as-you-go), tận dụng các dịch vụ được quản lý hoàn toàn (fully managed services) và sử dụng Cơ sở hạ tầng dưới dạng mã (Infrastructure as Code - IaC). Sự phát triển trong lĩnh vực điện toán đám mây yêu cầu một kỹ sư phải củng cố các kiến thức nền tảng vững chắc của họ về hệ điều hành (đặc biệt là Linux), các giao thức mạng và viết tập lệnh tự động hóa trước khi quản lý các lớp trừu tượng cấp cao hơn.

### 2.4. Multiplayer in the Cloud - Kết nối các Godot Client với AWS WebSockets

Phiên chia sẻ chuyên sâu về kỹ thuật này đã khám phá thiết kế kiến trúc của truyền thông hai chiều thời gian thực bằng cách kết nối các client game Godot thông qua các giao thức AWS WebSocket. Diễn giả đã thực hiện một phân tích đánh giá kỹ thuật (trade-off analysis) giữa các giao thức truyền thông dữ liệu tiêu chuẩn—như UDP/ENet, WebSocket và HTTP Polling—nêu bật các ưu điểm, hạn chế và trường hợp sử dụng tối ưu cho từng loại.

```
[Godot Game Clients] <---> [Amazon API Gateway (WebSocket)] <---> [AWS Lambda] <---> [Amazon DynamoDB]
                                                                        |
                                                                [Amazon CloudWatch]
```

*   **Nhận thức cốt lõi (Key Insight):** Kiến trúc sản xuất thực tế được trình diễn đã tận dụng Amazon API Gateway để duy trì các kết nối trạng thái (stateful connections) liên tục với các client, AWS Lambda để xử lý logic nghiệp vụ backend dựa trên sự kiện (event-driven) một cách bất đồng bộ, Amazon DynamoDB để lưu trữ trạng thái kết nối thời gian thực với độ trễ tối thiểu và Amazon CloudWatch để ghi log và phân tích tập trung.
*   **Giá trị kiến trúc (Architecture Value):** Kiến trúc này cung cấp một ví dụ cụ thể về mô hình thiết kế Serverless có khả năng mở rộng cao, cho phép các ứng dụng thời gian thực (như phòng chờ game, hệ thống trò chuyện hoặc bảng điều khiển trực tuyến) mở rộng quy mô một cách linh hoạt mà không tốn chi phí quản lý hoặc cấu hình các máy chủ ảo truyền thống.

### 2.5. Nghệ thuật làm việc nhóm hiệu quả (Effective Teamwork)

Nhận thức rằng kỹ thuật phần mềm vốn có tính chất cộng tác, phiên chia sẻ này đã chuyển trọng tâm sang khía cạnh con người trong công nghệ, phác thảo bốn trụ cột cơ bản cần thiết để tối đa hóa tốc độ của nhóm kỹ sư và sự thành công của dự án:
*   **Mục tiêu chung:** Đảm bảo mọi thành viên trong nhóm đều có các mục tiêu chung, rõ ràng.
*   **Phân bổ nguồn lực tối ưu:** Giao các nhiệm vụ kỹ thuật phù hợp cho từng cá nhân dựa trên thế mạnh cốt lõi của họ.
*   **Giao tiếp cởi mở & Lắng nghe chủ động:** Thiết lập sự an toàn về mặt tâm lý cho các vòng phản hồi mang tính xây dựng và minh bạch.
*   **Trách nhiệm cá nhân:** Duy trì tư duy làm chủ đối với các sản phẩm bàn giao cá nhân.
*   **Hệ sinh thái công cụ khuyến nghị:** Phiên thảo luận đã giới thiệu các bộ quản lý dự án agile và truyền thông hiện đại—bao gồm ClickUp, Trello, Slack, Google Workspace và Discord—để theo dõi tiến độ một cách có hệ thống, tổ chức các sprint và tập trung hóa tài liệu kỹ thuật. Điều này rất thực tế cho cả các dự án nhóm học thuật lẫn thực tập tại doanh nghiệp.

### 2.6. GraphRAG - Xây dựng các ứng dụng GraphRAG sử dụng Amazon Bedrock và Amazon Neptune

Phiên chia sẻ cuối cùng đã giới thiệu các xu hướng tiên tiến trong Generative AI, cụ thể là khám phá GraphRAG—một mô hình tiên tiến kết hợp RAG (Retrieval-Augmented Generation) truyền thống với các Đồ thị tri thức cấu trúc (Knowledge Graphs).

*   **Nhận thức cốt lõi (Key Insight):** RAG truyền thống tìm kiếm ngữ cảnh bằng cách sử dụng độ tương đồng vector trên các phân đoạn tài liệu (document chunks), điều này thường không hiệu quả khi các câu hỏi của người dùng yêu cầu suy luận đa bước (multi-hop reasoning) sâu sắc trên các điểm dữ liệu có tính kết nối cao. GraphRAG giải quyết vấn đề này bằng cách cấu trúc thông tin dưới dạng một mạng lưới kết nối giữa các nút (thực thể) và các cạnh (mối quan hệ).
*   **Ngăn xếp triển khai (Implementation Stack):** Diễn giả đã giới thiệu cách xây dựng các kiến trúc phức tạp này bằng cách sử dụng Amazon Bedrock để điều phối các Mô hình ngôn ngữ lớn (LLM) nền tảng cùng với Amazon Neptune làm công cụ cơ sở dữ liệu đồ thị được quản lý. Điều này nhấn mạnh rằng các nền tảng đám mây hiện đại đã phát triển vượt xa các nhà cung cấp lưu trữ và tính toán cơ bản, hiện đang hoạt động như các hệ sinh thái toàn diện để triển khai các hệ thống AI thông minh hướng dữ liệu ngữ nghĩa.

## 3. Bài học rút ra

Tham dự sự kiện này mang lại sự kết hợp sâu sắc giữa các hiểu biết về kỹ thuật, sự nghiệp và cá nhân:
*   **Nâng cao năng lực kỹ thuật:** Tôi đã củng cố hiểu biết của mình về vai trò của Docker trong tính đồng nhất môi trường (environment parity), khả năng của AWS trong việc mở rộng các kiến trúc serverless hướng sự kiện và sự dịch chuyển tất yếu sang bảo mật hành vi đa lớp. Các chủ đề nâng cao như GraphRAG và kết nối WebSocket minh họa cho sự rộng lớn của hệ sinh thái AWS trên nhiều lĩnh vực khác nhau.
*   **Lộ trình nghề nghiệp:** Câu chuyện chuyển đổi từ Helpdesk sang Sysadmin đã củng cố rằng sự phát triển nghề nghiệp bền vững trong Cloud và DevOps đòi hỏi sự nắm bắt vững chắc các kiến thức nền tảng cơ bản—cụ thể là quản trị Linux, mạng nâng cao, giám sát đo lường (telemetry monitoring), tự động hóa tập lệnh và kỹ năng ghi tài liệu sâu.
*   **Tích hợp kỹ năng mềm:** Tôi học được rằng năng lực kỹ thuật xuất sắc sẽ không hoàn thiện nếu thiếu sự cộng tác hiệu quả. Việc thực thi các mục tiêu chung, duy trì trách nhiệm giải trình tuyệt đối và sử dụng các công cụ quản lý dự án agile hiện đại là bắt buộc để bàn giao các dự án công nghệ cấp doanh nghiệp thành công.

## 4. Đóng góp cá nhân

Trong ngày hội cộng đồng, tôi đã thực hiện một số hoạt động có chủ ý nhằm tối đa hóa giá trị của việc tham dự:
*   **Ghi chép tài liệu tích cực:** Tôi đã ghi chép một cách hệ thống và có cấu trúc về các sơ đồ kiến trúc, tích hợp dịch vụ và các phương pháp thực hành tốt nhất trên AWS, đóng gói container và các mô-đun AI để làm tài liệu tham khảo chất lượng cao cho các báo cáo học thuật và thực tập của mình.
*   **Tổng hợp kiến thức:** Tôi chủ động đối chiếu các phương pháp thực tế được chia sẻ bởi các diễn giả doanh nghiệp với các khái niệm lý thuyết nền tảng mà tôi đã nghiên cứu trước đó trong chương trình AWS Study Group, từ đó xác định các lỗ hổng cụ thể trong kiến thức của mình.
*   **Điều chỉnh kế hoạch học tập thực tế:** Sau sự kiện, tôi đã chuyển đổi các ghi chú của mình thành một kế hoạch tự học có cấu trúc. Sắp tới, tôi sẽ ưu tiên thực hành thực tế trong việc đóng gói các ứng dụng nhiều tầng bằng Docker, triển khai các dịch vụ serverless microservices trên AWS và thử nghiệm các cấu hình bảo mật IAM và WAF cơ bản trong môi trường phòng lab cá nhân của mình.

## 5. Kết luận

Tóm lại, AWS First Cloud Journey Community Day là một trải nghiệm có tác động đặc biệt lớn, giúp mở rộng góc nhìn của tôi về tốc độ phát triển của bối cảnh điện toán đám mây hiện đại. Các phiên chia sẻ đã làm rõ cách các thành phần AWS riêng lẻ kết nối với nhau để giải quyết các thách thức phức tạp của doanh nghiệp, đồng thời xác định rõ ràng ma trận kỹ năng chính xác mà ngành công nghệ kỳ vọng vào năm 2026.

Sự kiện đã để lại cho tôi động lực to lớn để tiếp tục lộ trình phát triển kỹ thuật của mình, trang bị cho tôi sự rõ ràng về kỹ thuật và sự tập trung chiến lược cần thiết để hướng tới các vai trò sắp tới trong Kỹ thuật đám mây (Cloud Engineering), DevOps và Kiến trúc Backend.

## Hình ảnh sự kiện

Một số hình ảnh được ghi lại trong quá trình tham gia sự kiện:

![AWS First Cloud Journey Community Day](/images/4-EventParticipated/4.1-Event1/z7976498940486_4005b6c6d8361abe3f1b76bdf4dd74ef.jpg)
