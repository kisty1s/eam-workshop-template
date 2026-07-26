---
title: "Event 4: FCAJ Community Day - Agentic AI Showcase & Hackathon Demo Day"
date: 2026-07-26
weight: 4
chapter: false
pre: " <b> 4.4. </b> "
---

## Thông tin sự kiện

| Nội dung | Chi tiết |
| --- | --- |
| Thời gian | Chủ Nhật, ngày 26/07/2026 |
| Địa điểm | Văn phòng AWS Việt Nam, Tầng 26, Tòa nhà Bitexco Financial Tower |
| Hình thức tham gia | Tham gia trực tiếp tại sự kiện |
| Vai trò | Người tham dự |
| Chủ đề chính | Agentic AI Systems, Amazon Bedrock AgentCore, Multi-Channel Conversational Ordering, Computer Vision & Crowd Analytics, Automated Cloud Architecture, Corporate Signal Intelligence |
| Các dự án báo cáo | **OneTeam** (KFC Bot Agent), **Team 3KA** (Project S.H.E.P.H.E.R.D), **Team Plan V** (SA Professional AI Native App), **Team Signal Scout** (Signal Scout Platform) |

## 2. Tổng quan

Sự kiện **FCAJ Community Day - Agentic AI Showcase & Hackathon Demo Day** (số tháng 07/2026) là một buổi chia sẻ vô cùng đặc biệt và giàu cảm hứng. Tại đây, mình có cơ hội trực tiếp ngồi dưới hội trường văn phòng AWS Việt Nam để lắng nghe các anh chị vừa hoàn thành cuộc thi **Agentic AI Build Week (AABW) Hackathon** lên sân khấu báo cáo, thuyết trình và chia sẻ lại toàn bộ hành trình làm sản phẩm thực chiến của mình.

Trong suốt buổi sáng, các anh chị nhóm thi đã lần lượt đứng trên sân khấu để trình bày kiến trúc hệ thống (Architecture Pitch), chia sẻ những kinh nghiệm xương máu sau 24 giờ làm việc liên tục và thực hiện các màn Live Demo trực tiếp ngay trước mắt người nghe. Được trực tiếp theo dõi các anh chị trình diễn cách ứng dụng **Amazon Bedrock AgentCore**, **SageMaker**, **YOLO**, **Langfuse** cùng các dịch vụ AWS Cloud-Native giúp mình học hỏi được rất nhiều bài học thực tế mà sách vở hay lý thuyết thông thường khó có được.

## 3. Nội dung chính các dự án báo cáo

### 3.1. OneTeam - AI-Powered Conversational Ordering Agent (KFC Bot Agent)

*   **Bối cảnh & Thách thức thực tế (The Trigger & Problem):**
    *   Đứng trên sân khấu, các anh chị nhóm OneTeam mở đầu bài thuyết trình bằng việc phân tích một bài học rất thực tế từ vụ thử nghiệm AI Drive-thru của McDonald's tại Mỹ: Việc xử lý gọi món qua hội thoại tự nhiên là một **bài toán hệ thống thực sự** (real system problem) đầy phức tạp. AI không chỉ trả lời câu hỏi thông thường mà phải hiểu chính xác danh mục món ăn, số lượng, biến thể, quy tắc áp mã giảm giá, trạng thái giỏ hàng và xử lý lỗi chuẩn xác, vì bất kỳ sai sót nào cũng dẫn đến thiệt hại tài chính trực tiếp cho cửa hàng.
    *   Các anh chị cũng chỉ ra rằng việc hỗ trợ qua nhân viên chat không thể mở rộng theo ca trực hay các đợt bùng nổ đơn hàng, trong khi bắt khách hàng tải app mới để đặt hàng lại tạo ra rào cản lớn khiến họ dễ bỏ ngang (lost momentum).
*   **Giải pháp (KFC Bot Agent):**
    *   Từ bài toán đó, các anh chị giới thiệu giải pháp Trợ lý AI đặt hàng đa kênh (KFC Bot Agent) chạy trực tiếp trên các ứng dụng nhắn tin quen thuộc như Zalo OA, WhatsApp, Messenger. Khách hàng có thể nhắn tin đặt món và chốt đơn ngay lập tức mà không cần chuyển app hay tạo tài khoản mới.
*   **Cơ chế hoạt động Agentic (Goal -> Plan -> Tools -> Act -> Verify):**
    *   Các anh chị giải thích chi tiết cơ chế hoạt động 5 bước: (1) Hiểu ý định đặt hàng -> (2) Lập kế hoạch các bước -> (3) Truy vấn dữ liệu kinh doanh tin cậy -> (4) Cập nhật giỏ hàng & áp dụng ưu đãi -> (5) Xác nhận dữ liệu với giỏ hàng thực tế.
    *   Tư duy kiến trúc *"Design Once | Deploy Everywhere"*: Thêm kênh nhắn tin mới chỉ cần gắn Adapter, thêm hệ thống kinh doanh chỉ cần nối Connector, và thêm năng lực chỉ cần bổ sung Tool mà không cần làm lại từ đầu.
*   **Hạ tầng AWS & Hiệu quả Chi phí:**
    *   Nhờ tận dụng **Amazon Bedrock AgentCore**, các anh chị đã tiết kiệm tới **60% mã nguồn hạ tầng** (infra code).
    *   Ngồi bên dưới theo dõi màn Live Demo của các anh chị khi gửi tin nhắn đặt món trực tiếp trên Zalo OA, mình thật sự ấn tượng khi thấy AI phản hồi và xử lý giỏ hàng cực nhanh, độ trễ chỉ mất từ **3 - 5 giây**.
    *   Mô hình chi phí các anh chị tính toán cũng rất tối ưu: Chỉ khoảng **$0.006 / đơn hàng**; tổng chi phí hạ tầng tầm **$88 / tháng** (trong đó Bedrock chiếm 75%).
    *   **Thành tích:** Phần trình bày xuất sắc và thực tế đã giúp các anh chị giành giải Nhất (First Place) cuộc thi AABW Hackathon trong tiếng vỗ tay thán phục của toàn bộ hội trường!

### 3.2. Team 3KA - Hành trình Hackathon 24h & Dự án S.H.E.P.H.E.R.D

*   **Bối cảnh & Thách thức (Problem & Inspiration):**
    *   Khi các anh chị nhóm 3KA bước lên sân khấu, không khí hội trường trở nên rất gần gũi và truyền cảm hứng. Các anh chị chia sẻ về bài toán giám sát an ninh sự kiện: Ban quản lý tòa nhà hay địa điểm sự kiện gặp rất nhiều khó khăn khi phải theo dõi đồng thời lối ra vào, hàng đợi, các gian hàng và luồng di chuyển đám đông. Giám sát thủ công vừa bị động, tốn sức vừa dễ bỏ sót sự cố khi người tham dự tăng đột biến.
*   **Giải pháp S.H.E.P.H.E.R.D:**
    *   Dự án giúp biến các luồng video camera thường thành chỉ số vận hành thời gian thực: Nhận diện và theo dõi con người, đo lường mật độ đám đông, ước tính trạng thái hàng đợi, phát hiện sớm nguy cơ ùn tắc và tự động phát cảnh báo cho nhân viên điều phối.
*   **Kiến trúc Kỹ thuật & Tầng AI Tác nhân (Agentic AI Layer):**
    *   *Computer Vision:* Kết hợp **YOLO + ByteTrack** để phát hiện và truy vết đối tượng; **Amazon SageMaker** đảm nhận vai trò thực thi suy luận mô hình trên Cloud.
    *   *Agentic AI Layer:* Các anh chị kết hợp **Amazon Bedrock AgentCore + Strands Agent** để tạo ra Autonomous Monitor (tự động phân tích và phát cảnh báo ùn tắc) và Operator Copilot (trợ lý hội thoại cho phép nhân viên truy vấn số liệu thực tế bằng ngôn ngữ tự nhiên).
    *   *Dashboard:* Giao diện React được các anh chị chiếu Demo trực quan ngay trên màn hình lớn.
*   **Bài học thực chiến 24h:**
    *   Ngồi nghe các anh chị tâm sự về hành trình 24 giờ thức trắng làm sản phẩm, từ lúc không có nhiều nền tảng về AI đến lần đầu làm quen với AWS, mình cảm thấy rất đồng cảm. Bài học các anh chị rút ra và nhắn gửi lại cho người nghe vô cùng thấm đía: *"Sự hiện diện đã là một nửa chiến thắng"* và *"Một sản phẩm hoàn thiện quy mô nhỏ luôn đánh bại một ý tưởng lớn nhưng dở dang"*.

### 3.3. Team Plan V - Solution Architect Professional AI Native App

*   **Bối cảnh & Thách thức:**
    *   Đến phần thuyết trình của nhóm Plan V, các anh chị đã chạm đúng "nỗi đau" thực tế của rất nhiều kỹ sư trong hội trường: Các Kiến trúc sư Giải pháp (Solution Architect - SA) thường mất hàng giờ liền đọc tài liệu yêu cầu (BRD/PRD) thủ công, tự vẽ sơ đồ kiến trúc từ trang giấy trắng, tự viết mã IaC và đưa ra các con số dự toán chi phí đám mây mang tính cảm tính dưới áp lực thời gian gấp gáp từ khách hàng.
*   **Giải pháp SA Professional AI Native App:**
    *   Các anh chị mang tới một ứng dụng AI Native hỗ trợ SA: Tự động đọc và phân tích tài liệu yêu cầu -> Tự động phác thảo các phương án kiến trúc Hybrid-Cloud chuẩn doanh nghiệp.
    *   Khởi tạo sơ đồ kiến trúc chỉnh sửa được trên **Draw.io** với bộ biểu tượng AWS chuẩn (AWS Architecture Icons).
    *   Xuất bảng dự toán chi phí dịch vụ AWS theo thời gian thực cho region `ap-southeast-1`.
    *   Tự động chỉ ra các điểm còn thiếu trong yêu cầu (requirement gaps) và cho phép SA tinh chỉnh tương tác qua khung Chat Sidebar.
*   **Tác động thực tế (Impact):**
    *   Nhìn các anh chị thao tác Demo trực tiếp trên màn hình, chỉ trong vài phút từ một file yêu cầu thô ứng dụng đã xuất ra đầy đủ sơ đồ kiến trúc, mã IaC và bảng dự toán chi phí chuẩn chỉnh, người nghe bên dưới ai cũng phải gật gù công nhận tính hữu ích của sản phẩm.

### 3.4. Team Signal Scout - Hệ thống Phát hiện Tín hiệu Thay đổi Chiến lược Doanh nghiệp

*   **Bối cảnh & Thách thức:**
    *   Các anh chị nhóm Signal Scout mang đến một bài báo cáo rất chỉn chu về tình báo chiến lược: Các đội ngũ quản trị rủi ro và chiến lược doanh nghiệp gặp khó khăn trong việc kết nối các nguồn thông tin phân mảnh (thay đổi nhân sự cấp cao, tin tức tái cấu trúc, biến động thị trường) thành một bức tranh tổng thể có bằng chứng xác minh.
*   **Giải pháp Signal Scout:**
    *   Nền tảng AI tự động thu thập và xác minh bằng chứng (kết hợp **Apify** và **TinyFish**), phát hiện sớm tín hiệu tái cấu trúc và trình diễn dữ liệu trực quan trên Executive Dashboard, giúp ban lãnh đạo đưa ra quyết định Duy trì (Maintain), Thích ứng (Adapt) hoặc Đẩy mạnh (Accelerate).
*   **Kiến trúc & Tối ưu Chi phí Hạ tầng AWS (Cost Breakdown):**
    *   Các anh chị trình bày sơ đồ kiến trúc tích hợp toàn diện trên AWS: **Amazon Bedrock**, **AgentCore**, **AWS WAF**, **Amplify**, **CloudWatch**, **DynamoDB**, **Lambda**, **Route 53**, kết hợp công cụ theo dõi LLM **Langfuse**.
    *   Đặc biệt, phần phân tích chi tiết bảng chi phí hạ tầng theo 3 kịch bản sử dụng (từ Min khoảng $81/tháng đến Max khoảng $359/tháng) được các anh chị giải thích rất rõ ràng, nhận được nhiều lời khen ngợi từ các chuyên gia AWS ngồi phía dưới về tư duy quản trị chi phí (FinOps).

## 4. Kiến thức & Bài học rút ra

Một buổi sáng ngồi nghe các anh chị chia sẻ kinh nghiệm thực chiến giúp mình thu hoạch được rất nhiều bài học đắt giá:
*   **Sự hỗ trợ mạnh mẽ của AWS cho AI Agent:** Qua phần trình bày của các anh chị, mình hiểu rõ hơn vai trò của **Amazon Bedrock AgentCore** trong việc quản lý bộ nhớ (Short-Term Memory), môi trường chạy (Runtime) và kết nối công cụ, giúp kỹ sư giải phóng 60% thời gian dựng hạ tầng để tập trung làm tốt phần logic nghiệp vụ.
*   **Tư duy giải quyết bài toán hệ thống:** Một sản phẩm AI thành công không chỉ là trả lời tin nhắn hay, mà phải có quy trình lập kế hoạch, truy vấn dữ liệu tin cậy, thực thi Tool Calling và có bước kiểm tra (Verify) tính đúng đắn trước khi chốt hành động.
*   **Bài toán chi phí thực tế (FinOps):** Học từ cách các anh chị tính toán chi phí ($88/tháng hay $81-$94/tháng), mình nhận ra khi thiết kế hệ thống AI cho doanh nghiệp thì việc tối ưu lượng token và lựa chọn dịch vụ Serverless phù hợp là yếu tố sống còn.
*   **Bài học làm sản phẩm Hackathon:** Nghe các anh chị kể về hành trình 24 giờ làm dự án giúp mình thấm nhuần tư duy: phải khéo léo chọn phạm vi sản phẩm vừa sức (Scope it tiny), phân công công việc rõ ràng và tập trung hoàn thành một luồng tính năng cốt lõi chạy mượt mà thay vì ôm đồm quá nhiều thứ.

## 5. Liên hệ với dự án EAM Workspace

Những kiến trúc và bài học mà các anh chị chia sẻ trên sân khấu gợi mở cho mình rất nhiều ý tưởng hay có thể áp dụng vào dự án EAM Workspace (Hệ thống quản lý tài sản doanh nghiệp):
*   **Học tập nhóm OneTeam (KFC Bot Agent):** Xây dựng Trợ lý AI mượn/trả thiết bị đa kênh trên Zalo/Slack nội bộ. Nhân viên chỉ cần nhắn tin báo hỏng hoặc mượn tài sản, AI Agent sẽ tự kiểm tra kho, cập nhật trạng thái và gửi thông báo xác nhận ngay trong ứng dụng chat.
*   **Học tập nhóm Plan V (SA AI App):** Xây dựng tính năng tự động phác thảo sơ đồ hạ tầng tài sản IT và tính toán chi phí vận hành đám mây đi kèm cho từng tài sản trong hệ thống EAM.
*   **Học tập nhóm 3KA (S.H.E.P.H.E.R.D):** Ứng dụng AI Vision kết hợp camera kho để theo dõi vị trí thiết bị, phát hiện hiện tượng quá nhiệt và tự động gửi cảnh báo bảo trì cho kỹ thuật viên.
*   **Học tập nhóm Signal Scout:** Xây dựng bảng điều khiển Executive Dashboard phân tích lịch sử bảo trì, tần suất sử dụng và dữ liệu khấu hao để hỗ trợ ban giám đốc quyết định nên Thay thế, Bảo trì hay Thanh lý tài sản.

## 6. Kết luận

Buổi sáng tham dự **FCAJ Community Day - Agentic AI Showcase & Hackathon Demo Day** tại văn phòng AWS Việt Nam là một trải nghiệm thực tế vô cùng tuyệt vời. Được trực tiếp ngồi nghe các anh chị đi trước chia sẻ lại những bài học xương máu, xem các anh chị Demo sản phẩm và giải trình kiến trúc đã giúp mình mở rộng góc nhìn rất nhiều. Những kiến thức và cảm hứng từ sự kiện chắc chắn sẽ là hành trang quý giá giúp mình áp dụng vào việc học tập cũng như hoàn thiện dự án thực tập EAM Workspace một cách tốt nhất.

## 7. Hình ảnh sự kiện

Một số hình ảnh ấn tượng được ghi lại trong quá trình tham gia sự kiện tại AWS Việt Nam:

![FCAJ Community Day - Agentic AI Showcase](/images/4-EventParticipated/4.4-Event4/fcaj-community-day-1.png)

![FCAJ Community Day - Agentic AI Showcase](/images/4-EventParticipated/4.4-Event4/fcaj-community-day-2.png)

![FCAJ Community Day - Agentic AI Showcase](/images/4-EventParticipated/4.4-Event4/fcaj-community-day-3.png)

![FCAJ Community Day - Agentic AI Showcase](/images/4-EventParticipated/4.4-Event4/fcaj-community-day-4.jpg)
