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

Sự kiện **FCAJ Community Day - Agentic AI Showcase & Hackathon Demo Day** (số tháng 07/2026) là buổi tổng kết và trình diễn chuyên sâu các giải pháp Trí tuệ nhân tạo dạng tác nhân (Agentic AI) đột phá được xây dựng trong khuôn khổ cuộc thi **Agentic AI Build Week (AABW)**. Sự kiện quy tụ đông đảo các nhóm kỹ sư, sinh viên xuất sắc và các chuyên gia công nghệ từ AWS Việt Nam nhằm đưa các mô hình AI vượt ra khỏi quy mô ứng dụng thử nghiệm (toy projects) để trở thành các hệ thống thương mại hóa sẵn sàng triển khai trên môi trường Production của doanh nghiệp.

Có mặt trực tiếp tại hội trường văn phòng AWS Việt Nam, mình đã được hòa mình vào không khí công nghệ sôi động, trực tiếp lắng nghe các phiên thuyết trình kiến trúc (Architecture Pitch), quan sát những phần phản biện sắc bén từ hội đồng chuyên gia và chứng kiến tận mắt các màn Live Demo thực chiến ngay tại chỗ từ 4 đội thi tiêu biểu (**OneTeam**, **3KA**, **Plan V**, và **Signal Scout**). Sự kiện mang lại trải nghiệm cận cảnh về cách ứng dụng **Amazon Bedrock AgentCore**, **SageMaker**, **YOLO**, **Langfuse** cùng các dịch vụ Cloud-Native trên AWS để giải quyết những bài toán doanh nghiệp thực tế.

## 3. Nội dung chính các dự án báo cáo

### 3.1. OneTeam - AI-Powered Conversational Ordering Agent (KFC Bot Agent)

*   **Bối cảnh & Thách thức thực tế (The Trigger & Problem):**
    *   Nhóm khởi đầu bằng việc phân tích bài học từ vụ thử nghiệm AI Drive-thru của McDonald's tại hơn 100 điểm bán tại Mỹ: Việc xử lý gọi món qua hội thoại tự nhiên là một **bài toán hệ thống thực sự** (real system problem) đầy thách thức. AI không chỉ dừng lại ở việc trả lời câu hỏi mà phải hiểu đúng danh mục sản phẩm, số lượng, biến thể món ăn, quy tắc voucher, trạng thái giỏ hàng và xử lý lỗi chính xác, vì bất kỳ sai sót nào cũng dẫn đến thiệt hại tài chính trực tiếp.
    *   Hỗ trợ khách hàng truyền thống qua nhân viên chat không thể mở rộng linh hoạt theo ca trực hay các đợt bùng nổ lượng truy cập (traffic spikes). Việc ép khách hàng phải chuyển đổi ứng dụng hoặc tải ứng dụng mới để đặt hàng tạo ra rào cản lớn (friction), khiến khách hàng bỏ ngang luồng mua sắm (lost momentum & lost order).
*   **Giải pháp (KFC Bot Agent):**
    *   Nhóm mang tới hội trường giải pháp Trợ lý AI đặt hàng đa kênh (Multi-channel Conversational Ordering Agent) hoạt động mượt mà trên Zalo OA, WhatsApp, Messenger... Khách hàng có thể tương tác và chốt đơn ngay trong ứng dụng nhắn tin họ đang dùng mà không cần chuyển app hay tạo tài khoản mới.
*   **Cơ chế hoạt động Agentic (Goal -> Plan -> Tools -> Act -> Verify):**
    *   Mô hình ngôn ngữ đảm nhận vai trò thấu hiểu ý định, trong khi các công cụ (Tools) quyết định dữ liệu thực tế thông qua 5 bước nghiêm ngặt: (1) Hiểu ý định đặt hàng -> (2) Lập kế hoạch các bước -> (3) Tìm kiếm dữ liệu kinh doanh tin cậy -> (4) Cập nhật giỏ hàng & áp dụng khuyến mãi -> (5) Xác nhận dữ liệu với giỏ hàng thực tế.
    *   Tư duy kiến trúc *"Design Once | Deploy Everywhere"*: Thêm kênh giao tiếp mới chỉ cần bổ sung Adapter, thêm hệ thống kinh doanh mới chỉ cần bổ sung Connector, thêm năng lực xử lý mới chỉ cần thêm Tool mà không phải viết lại toàn bộ hệ thống.
*   **Hạ tầng AWS & Hiệu quả Chi phí:**
    *   Tận dụng **Amazon Bedrock AgentCore** làm lớp nền tảng giúp cắt giảm tới **60% mã nguồn hạ tầng** (infra code).
    *   Khi quan sát màn Live Demo trực tiếp tại chỗ, mình rất ấn tượng với độ trễ xử lý phản hồi cực nhanh (End-to-end latency chỉ từ **3 - 5 giây** từ lúc gửi tin nhắn đến khi nhận phản hồi trên Zalo).
    *   Chi phí vận hành tối ưu vượt trội: Chỉ **$0.006 / đơn hàng** (tính trên quy mô 500 đơn/ngày); tổng chi phí hạ tầng khoảng **$88 / tháng** (trong đó chi phí truy vấn Bedrock chiếm 75%).
    *   **Thành tích:** Dự án xuất sắc giành giải Nhất (First Place) tại cuộc thi AABW Hackathon trong sự tán thưởng của toàn bộ hội trường!

### 3.2. Team 3KA - Hành trình Hackathon 24h & Dự án S.H.E.P.H.E.R.D

*   **Bối cảnh & Thách thức (Problem & Inspiration):**
    *   Trực tiếp lắng nghe phần chia sẻ của nhóm 3KA, mình cảm nhận được tinh thần nhiệt huyết của các bạn khi trình bày bài toán thực tế: Ban quản lý địa điểm sự kiện/tòa nhà gặp rất nhiều khó khăn khi phải giám sát đồng thời lối ra vào, hàng đợi, gian hàng và luồng di chuyển của đám đông. Phương pháp giám sát thủ công mang tính bị động, chậm trễ, khó mở rộng và dễ bỏ sót sự cố khi mật độ gia tăng đột biến.
*   **Giải pháp S.H.E.P.H.E.R.D (Smart Human-flow Evaluation, Prediction, Hazard Detection, Response, and Dispatch):**
    *   Dự án chuyển đổi các luồng video camera thông thường thành dữ liệu vận hành trực quan thời gian thực.
    *   Năng lực cốt lõi: Nhận diện và theo dõi con người, đo lường mật độ đám đông, ước tính trạng thái hàng đợi, phát hiện sớm dấu hiệu ùn tắc, dự báo áp lực quá tải, tạo cảnh báo chủ động và đề xuất hành động điều phối cho nhân viên.
*   **Kiến trúc Kỹ thuật & Tầng AI Tác nhân (Agentic AI Layer):**
    *   *Xử lý Thị giác máy tính (Computer Vision):* Sử dụng **YOLO + ByteTrack** để phát hiện và truy vết đối tượng thời gian thực; **Amazon SageMaker** đảm nhận vai trò thực thi suy luận mô hình (cloud inference).
    *   *Agentic AI Layer:* Kết hợp **Amazon Bedrock AgentCore + Strands Agent** xây dựng nên 2 thành phần:
        *   *Autonomous Monitor:* Tự động phân tích chỉ số đám đông liên tục, phát hiện nguy cơ ùn tắc và phát cảnh báo chủ động.
        *   *Operator Copilot:* Trợ lý cho phép nhân viên vận hành truy vấn bằng ngôn ngữ tự nhiên, trả về câu trả lời ngắn gọn kèm số liệu thời gian thực và công cụ đề xuất hướng xử lý.
    *   *Dashboard:* Giao diện giám sát xây dựng trên React được Demo trực tiếp trên màn hình lớn.
*   **Bài học thực chiến Hackathon 24h:**
    *   Nhóm gây xúc động khi chia sẻ chân thực hành trình 24 giờ thức trắng, vượt qua rào cản "không có nền tảng AI vững chắc" và "lần đầu làm việc với AWS". Bài học đắt giá rút ra: *"Sự hiện diện đã là một nửa chiến thắng"* và *"Một sản phẩm hoàn thiện quy mô nhỏ luôn đánh bại một ý tưởng lớn nhưng dở dang"*.

### 3.3. Team Plan V - Solution Architect Professional AI Native App

*   **Bối cảnh & Thách thức:**
    *   Phần báo cáo của nhóm Plan V nhận được sự đồng cảm lớn từ các kỹ sư trong hội trường khi đánh trúng vào nỗi đau thực tế: Các Kiến trúc sư Giải pháp (Solution Architect - SA) thường mất hàng giờ đồng hồ đọc tài liệu yêu cầu (BRD/PRD) thủ công, bắt đầu thiết kế sơ đồ từ trang trắng, tự viết mã IaC và đưa ra các ước tính chi phí đám mây mang tính cảm tính dưới áp lực thời gian gấp gáp từ khách hàng.
*   **Giải pháp SA Professional AI Native App:**
    *   Ứng dụng AI Native hỗ trợ SA: Tự động phân tích yêu cầu dạng ngôn ngữ tự nhiên hoặc tài liệu có cấu trúc -> Phác thảo các phương án kiến trúc Hybrid-Cloud tối ưu theo chuẩn doanh nghiệp.
    *   Tự động khởi tạo sơ đồ kiến trúc có thể chỉnh sửa trên **Draw.io** và các sơ đồ biểu tượng AWS chuẩn (AWS Architecture Icons).
    *   Tự động xuất bảng ước tính chi phí dịch vụ AWS (directional cost estimates) áp dụng cho region `ap-southeast-1`.
    *   Chỉ ra các điểm còn thiếu trong yêu cầu (requirement gaps), giả định và khuyến nghị kiến trúc; cho phép tinh chỉnh linh hoạt qua Chat Sidebar với hướng dẫn tùy chỉnh theo từng dự án.
*   **Tác động thực tế (Impact):**
    *   Xem trực tiếp phần Live Demo, mình thấy ứng dụng giúp chuyển đổi từ việc đọc tài liệu thủ công -> Xây dựng danh mục yêu cầu chuẩn hóa chỉ trong vài phút.
    *   Thay thế trang trắng -> Cung cấp bản thảo kiến trúc chất lượng cao kèm dự toán chi phí AWS và mã IaC tự động để nghiệm thu ngay.

### 3.4. Team Signal Scout - Hệ thống Phát hiện Tín hiệu Thay đổi Chiến lược Doanh nghiệp

*   **Bối cảnh & Thách thức:**
    *   Nhóm Signal Scout mang đến góc nhìn sắc bén về tình báo chiến lược doanh nghiệp, nơi các đội ngũ xây dựng chiến lược, quản trị rủi ro và tình báo cạnh tranh gặp khó khăn trong việc kết nối các nguồn thông tin phân mảnh (thay đổi nhân sự, tái cấu trúc, thông tin thị trường) thành một bức tranh chiến lược toàn diện có bằng chứng xác minh.
*   **Giải pháp Signal Scout:**
    *   Nền tảng AI thu thập và xác minh bằng chứng tự động (kết hợp **Apify** và **TinyFish**), phát hiện sớm các tín hiệu tái cấu trúc, phân tích các chỉ số tài chính/vận hành và trình diễn kết quả qua Executive Dashboard.
    *   Hệ thống hỗ trợ ban lãnh đạo đưa ra các quyết định Duy trì (Maintain), Thích ứng (Adapt) hoặc Đẩy mạnh (Accelerate) với độ minh bạch cao, có căn cứ bằng chứng rõ ràng.
*   **Kiến trúc & Tối ưu Chi phí Hạ tầng AWS (Cost Breakdown):**
    *   Kiến trúc tích hợp toàn diện trên AWS: **Amazon Bedrock**, **AgentCore Short-Term Memory & Runtime**, **AWS WAF**, **Amplify Hosting**, **CloudWatch**, **Secrets Manager**, **DynamoDB**, **Lambda**, **Route 53**, **CloudTrail**, **S3 Intelligent-Tiering**, **API Gateway HTTP**, **Cognito**, kết hợp công cụ giám sát LLM **Langfuse**.
    *   Tại hội trường, phần phân tích mô hình chi phí chi tiết theo 3 kịch bản: Min (khoảng $81/tháng), Mid (khoảng $94/tháng), Max (khoảng $359/tháng) đã nhận được đánh giá cao từ các chuyên gia AWS về tính khả thi tài chính khi triển khai thực tế.

## 4. Kiến thức & Bài học rút ra

Trực tiếp tham dự và theo dõi trọn vẹn sự kiện mang lại cho mình nhiều góc nhìn sâu sắc:
*   **Sự trưởng thành của Agentic AI trên AWS:** Các công cụ mới như **Amazon Bedrock AgentCore** giúp đơn giản hóa việc quản lý bộ nhớ (Short-Term Memory), môi trường thực thi (Runtime) và kết nối công cụ (Tools), giải phóng kỹ sư khỏi 60% công việc dựng hạ tầng thô để tập trung vào logic nghiệp vụ và trải nghiệm người dùng.
*   **Tư duy Hệ thống hơn là Chatbot đơn thuần:** Một hệ thống AI Agent thương mại thành công không chỉ dừng lại ở việc tạo ra các câu trả lời văn bản hay, mà phải có khả năng lập kế hoạch, truy vấn dữ liệu thực tế, thực thi hành động qua Tool Calling và có cơ chế kiểm tra/xác minh (Verify) tính đúng đắn trước khi chốt giao dịch.
*   **Tối ưu hóa Chi phí (FinOps) trong Kiến trúc AI:** Các bài báo cáo từ OneTeam ($88/tháng) và Signal Scout ($81 - $94/tháng) minh chứng rằng việc thiết kế kiến trúc AI Agent cho doanh nghiệp bắt buộc phải đi kèm với bài toán tối ưu chi phí token, quản lý tài nguyên tính toán và lựa chọn dịch vụ Serverless phù hợp.
*   **Bài học tinh thần Hackathon:** Trực tiếp lắng nghe chia sẻ từ các đội thi giúp mình cảm nhận rõ nét tinh thần làm việc dưới áp lực thời gian: phải xác định phạm vi sản phẩm vừa sức (Scope it tiny), phân công vai trò rõ ràng, tập trung hoàn thiện một luồng tính năng cốt lõi (End-to-End MVP) và liên tục thử nghiệm trên thực tế.

## 5. Liên hệ với dự án EAM Workspace

Nội dung báo cáo từ 4 dự án tại sự kiện FCAJ Community Day mang lại cho mình nhiều gợi ý kiến trúc đắt giá có thể áp dụng trực tiếp để nâng cấp hệ thống quản lý tài sản doanh nghiệp EAM Workspace:
*   **Tích hợp Trợ lý Đặt thiết bị / Yêu cầu tài sản qua Chatbot đa kênh (như KFC Bot Agent):**
    *   Cho phép nhân viên gửi yêu cầu mượn thiết bị, báo hỏng hoặc đặt lịch sử dụng tài sản ngay trên Zalo/Slack nội bộ mà không cần đăng nhập vào web app EAM. Hệ thống AI Agent sẽ tự động kiểm tra trạng thái tài sản trong CSDL, cập nhật giỏ mượn và gửi thông báo xác nhận.
*   **Tự động hóa Thiết kế Kiến trúc & Hạ tầng cho EAM (như SA Professional AI Native App):**
    *   Ứng dụng tư duy của Plan V để xây dựng công cụ phác thảo sơ đồ hạ tầng tài sản IT (Asset Infrastructure Mapping) tự động, giúp ban quản trị IT dễ dàng hình dung mối liên kết giữa các máy chủ, thiết bị mạng và ước tính chi phí vận hành Cloud của từng tài sản.
*   **Giám sát & Cảnh báo Bảo trì Tài sản bằng Computer Vision (như Project S.H.E.P.H.E.R.D):**
    *   Tận dụng mô hình AI Vision kết hợp IoT camera để tự động nhận diện vị trí thiết bị, phát hiện các hiện tượng quá nhiệt/ùn tắc thiết bị trong kho tài sản và phát cảnh báo chủ động (Proactive Alerts) cho đội ngũ bảo trì.
*   **Tình báo Tải tài sản & Đánh giá Rủi ro (như Signal Scout):**
    *   Kết nối các tín hiệu vận hành, lịch sử sửa chữa và dữ liệu khấu hao để xây dựng bảng điều khiển Executive Dashboard, hỗ trợ ban giám đốc đưa ra quyết định Thay thế, Bảo trì hay Thanh lý tài sản dựa trên bằng chứng minh bạch.

## 6. Kết luận

Tham dự sự kiện **FCAJ Community Day - Agentic AI Showcase & Hackathon Demo Day** trực tiếp tại văn phòng AWS Việt Nam là một trải nghiệm học tập thực tế vô cùng giá trị. Sự kiện là minh chứng rõ nét cho sự chuyển dịch mạnh mẽ của cộng đồng công nghệ sang kỷ nguyên Trí tuệ nhân tạo dạng tác nhân. Việc tận dụng hệ sinh thái AWS cùng với tư duy thiết kế kiến trúc chuẩn mực không chỉ giúp các nhóm phát triển rút ngắn thời gian xây dựng sản phẩm từ hàng tháng xuống 24 giờ, mà còn mở ra những tiềm năng to lớn trong việc tự động hóa và thông minh hóa các hệ thống phần mềm doanh nghiệp như EAM Workspace.

## 7. Hình ảnh sự kiện

Một số hình ảnh ấn tượng được ghi lại trong quá trình tham gia buổi Study Tour tại AWS Việt Nam:

![AWS Agentic AI Build Week](/images/4-EventParticipated/4.4-Event4/fcaj-community-day-4.jpg)
