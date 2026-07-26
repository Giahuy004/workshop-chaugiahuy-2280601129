---
title: "Event 3"
date: 2024-01-01
weight: 3
chapter: false
pre: " <b> 4.3. </b> "
---


# Bài thu hoạch "AWS Agentic AI Build Week (AABW) Hackathon & Tech Sharing"

### Mục Đích Của Sự Kiện

- Tham gia cuộc thi và chuỗi workshop phát triển ứng dụng **Agentic AI** chuyên sâu do **Amazon Web Services (AWS)** tổ chức.
- Tiếp cận các công nghệ trí tuệ nhân tạo thế hệ mới (GenAI, Multi-Agent Systems, Agentic AI Core) và tích hợp các dịch vụ hàng đầu của AWS (Amazon Bedrock, SageMaker, Lambda, API Gateway).
- Học hỏi các giải pháp công nghệ thực chiến từ 4 bài thuyết trình của các nhóm phát triển: Giám sát mật độ đám đông tự động, ứng dụng hỗ trợ Solution Architect, phân tích tín hiệu chiến lược doanh nghiệp và chatbot đặt hàng đa kênh.
- Rèn luyện kỹ năng thực chiến với áp lực thời gian ngắn (Hackathon), tối ưu chi phí hạ tầng Cloud và trình bày giải pháp trước các chuyên gia AWS.

### Quy Mô & Diễn Giả

- **Đối tác phối hợp tổ chức:** Amazon Web Services (AWS) Việt Nam, First Cloud Journey (FCJ/FCAJ), AWS User Group Việt Nam và All Builders Welcome (AABW).
- **Đối tượng tham gia:** Các sinh viên, kỹ sư điện toán đám mây và chuyên gia AI lập đội và thi đấu liên tục trong tuần lễ *Agentic AI Build Week*.
- **Các nhóm diễn giả & Bài thuyết trình:**
  - **Chủ đề 1:** S.H.E.P.H.E.R.D – Smart Human-flow Evaluation, Prediction, Hazard Detection, Response, and Dispatch
    - *Diễn giả:* Đội 3KA
  - **Chủ đề 2:** Solution Architect Professional AI Native App – Tự động hóa thiết kế kiến trúc Cloud
    - *Diễn giả:* Nhóm Plan V (Phạm Tiến Thuận, Phát Huỳnh, Hoàng Long, Lê Minh Nghĩa, Trần Đại Vĩ, Nguyễn An)
  - **Chủ đề 3:** Signal Scout – Phát hiện sớm các tín hiệu tái cấu trúc & thay đổi chiến lược doanh nghiệp
    - *Diễn giả:* Nhóm Dream AI Team (Lê Tấn Lực, Đỗ Hoàng Hiếu, Triệu Quốc Hào, Nguyễn Văn Duy Khiêm, Nguyễn Công Minh, Nguyễn Trần Minh Quân)
  - **Chủ đề 4:** OneTeam & KFC Bot Agent – Trải nghiệm đặt hàng đa kênh với AI Agent
    - *Diễn giả:* Nhóm OneTeam (Anh Duy, Trần Đông, Đoàn Trung, Minh Việt, Anshul Roy)

---

### Nội Dung Nổi Bật

#### 1. S.H.E.P.H.E.R.D – Smart Human-flow Evaluation & Dispatch
Nhóm 3KA mang đến dự án giám sát và điều phối đám đông thông minh:
- **Bài toán & Động lực:** Giám sát thủ công luồng đám đông tại các lối vào, hàng đợi và khu vực hội trường lớn thường chậm trễ, khó mở rộng và dễ bỏ sót sự cố.
- **Tính năng cốt lõi:** Chuyển đổi dữ liệu camera thời gian thực thành thông tin vận hành, đo lường mật độ đám đông, đánh giá tình trạng hàng đợi, dự báo nguy cơ quá tải và tự động tạo cảnh báo sớm để điều phối nhân sự.
- **Kiến trúc công nghệ:** Kết hợp Computer Vision (YOLO + ByteTrack), Amazon SageMaker, Amazon Bedrock AgentCore + Strands Agent (Multi-Agent System gồm *Autonomous Monitor* và *Operator Copilot*) và React Monitoring Dashboard.
- **Thách thức & Trải nghiệm Hackathon:** Xử lý độ trễ suy luận AI, duy trì luồng video trực tiếp ổn định, thức đêm debug mã nguồn đến 3 giờ sáng và phân chia vai trò hiệu quả trong nhóm.

#### 2. Solution Architect Professional AI Native App
Nhóm Plan V giới thiệu ứng dụng hỗ trợ Kỹ sư giải pháp tự động hóa quy trình thiết kế Cloud:
- **Bài toán & Động lực:** Kỹ sư giải pháp (Solution Architect) mất nhiều thời gian đọc tài liệu BRD/PRD thủ công, vẽ sơ đồ từ trang trắng và tính toán chi phí cloud phức tạp.
- **Tính năng cốt lõi:** Phân tích ngôn ngữ tự nhiên để trích xuất Yêu cầu dự án (Requirements Catalogue) trong vài phút, phác thảo phương án kiến trúc đám mây chuẩn doanh nghiệp, tự động sinh sơ đồ Drawio / AWS Diagrams và dự toán chi phí cloud cho vùng `ap-southeast-1`.
- **Tác động (Impact):** Tự động hóa việc tạo bản thảo kiến trúc khởi đầu, xuất mã IaC tự động và đưa ra dự toán chi phí AWS tức thời bên cạnh sơ đồ kiến trúc.

#### 3. Signal Scout – Phát hiện sớm các tín hiệu thay đổi chiến lược doanh nghiệp
Nhóm Dream AI Team trình bày giải pháp phân tích tín hiệu doanh nghiệp bằng AI:
- **Bài toán & Động lực:** Giúp các đội ngũ chiến lược và quản trị rủi ro doanh nghiệp phát hiện sớm các tín hiệu tái cấu trúc từ các nguồn dữ liệu phân tán.
- **Mô hình kinh doanh & Tính năng:** Nền tảng tự phục vụ (Self-service Dashboard) thu thập và xác thực bằng chứng tái cấu trúc doanh nghiệp, phân tích các chỉ số tài chính/vận hành và cảnh báo rủi ro tự động.
- **Kiến trúc & Tối ưu chi phí Cloud:** Tích hợp AWS Bedrock, AgentCore Short-Term Memory, LangFuse, TinyFish, Apify, Lambda, API Gateway, DynamoDB... Chi tiết chi phí vận hành hạ tầng AWS theo 3 kịch bản Min ($17/tháng), Mid ($35/tháng) và Max ($130/tháng); tổng chi phí hệ thống $81 – $359/tháng.

#### 4. OneTeam & KFC Bot Agent – Trải nghiệm đặt hàng đa kênh với AI Agent
Nhóm OneTeam chia sẻ giải pháp đặt hàng qua hội thoại không ma sát:
- **Bài toán & Động lực:** Trải nghiệm đặt hàng qua hội thoại thường bị gián đoạn do buộc người dùng phải tải ứng dụng mới hoặc rời khung chat (rút kinh nghiệm từ case study thử nghiệm AI Drive-thru của McDonald's dừng thử nghiệm do AI xử lý sai logic).
- **Giải pháp & Kiến trúc Tool Call:** Đặt hàng đa kênh (Zalo OA, Messenger, WhatsApp) trực tiếp trong khung chat qua 5 bước Tool Call Execution (Understand Intent -> Plan Steps -> Search Data -> Update Cart & Apply Vouchers -> Confirm against Real Cart).
- **Con số ấn tượng:** Chi phí $0.006 / đơn hàng (tính toán cho 500 đơn/ngày), $88 / tháng tổng chi phí hạ tầng (Bedrock chiếm 75%), độ trễ phản hồi 3–5 giây và giảm 60% mã nguồn hạ tầng nhờ AWS AgentCore.

---

### Bài Học Kinh Nghiệm Rút Ra

- **Tinh thần thực chiến & Sẵn sàng (Showing Up):** Dấn thân tham gia cuộc thi là bước đi quan trọng nhất để học hỏi và bứt phá giới hạn kỹ thuật của bản thân.
- **Ưu tiên sản phẩm hoàn thiện (Execution Over Scope):** Một sản phẩm mẫu (working prototype) cốt lõi chạy mượt mà luôn có giá trị vượt trội so với ý tưởng lớn nhưng dở dang.
- **Sự chuyển dịch từ Chatbot sang AI Agent:** Chatbot chỉ trả lời văn bản đơn thuần (*A Chatbot Replies*), trong khi AI Agent thực thụ phải có khả năng gọi Tools, kết nối dữ liệu thực và thực hiện hành động chính xác (*An Agent Acts*).
- **Tư duy thiết kế tối ưu chi phí hạ tầng:** Xây dựng giải pháp AI phải đi kèm với bài toán kinh tế thực tế ($0.006/đơn hàng hoặc thiết kế kịch bản Min/Mid/Max).

---

### Kết Quả Hoặc Giá Trị Đạt Được

#### Kỹ Năng Kỹ Thuật & Kiến Thức Ngành
- **Nâng cao năng lực Agentic AI & GenAI:** Master quy trình tích hợp các dịch vụ AI đại diện (Agentic AI) và LLM trên AWS (Amazon Bedrock, SageMaker, AgentCore).
- **Thiết kế kiến trúc Cloud & Tối ưu chi phí:** Thành thạo thiết kế kiến trúc hạ tầng Cloud có khả năng mở rộng cao, gắn liền với việc kiểm soát chi phí thực tế cho dự án AI.
- **Xử lý dữ liệu & Computer Vision thời gian thực:** Tiếp thu kỹ năng kết hợp các mô hình nhận diện (YOLO, ByteTrack) với hệ thống suy luận đám mây.

#### Kỹ Năng Mềm & Phát Triển Cá Nhân
- **Làm việc nhóm dưới áp lực cao (High-pressure Teamwork):** Phối hợp hiệu quả và duy trì năng lượng làm việc cùng đồng đội trong suốt tuần lễ Hackathon.
- **Kỹ năng thuyết trình & Quản lý dự án:** Rèn luyện kỹ năng phân chia vai trò, chuẩn bị bài pitching 3 phút và thuyết trình giải pháp kỹ thuật trước các chuyên gia AWS.
- **Mở rộng mạng lưới kết nối (Networking):** Tạo dựng mối quan hệ quý giá với các cố vấn (mentors) của AWS, chuyên gia công nghệ và các bạn sinh viên tài năng.

#### Đóng Góp Cho Nhóm/Dự Án
- Đưa các góc nhìn thực tế về thiết kế AI Agent và tối ưu chi phí hạ tầng vào các dự án thực tập của nhóm.
- Chia sẻ lại các bài học về quy trình phát triển sản phẩm nhanh (rapid prototyping) và tinh thần làm việc nhóm cởi mở với các thành viên khác.

---

### Một số hình ảnh khi tham gia sự kiện

![AWS Group Photo at Amazon Office](/images/4-Event/event3_amazon_photo.png?width=45pc)
*Hình 1: Chụp ảnh tập thể cùng các bạn sinh viên và chuyên gia tại văn phòng Amazon Web Services (AWS)*

![S.H.E.P.H.E.R.D System Architecture](/images/4-Event/event3_architecture.png?width=45pc)
*Hình 2: [Nhóm 1 - Hackathon Journey] Sơ đồ kiến trúc hệ thống Agentic AI S.H.E.P.H.E.R.D (YOLO + AWS Bedrock)*

![Solution Architect AI Native App Workflow](/images/4-Event/event3_sa_native_app.png?width=45pc)
*Hình 3: [Nhóm 2 - SA Professional Native App] Quy trình trích xuất yêu cầu và tự động thiết kế kiến trúc Cloud*

![Signal Scout Architecture Canvas](/images/4-Event/event3_signal_scout.png?width=45pc)
*Hình 4: [Nhóm 3 - Signal Scout] Sơ đồ phân tích tín hiệu chiến lược và kịch bản chi phí hạ tầng AWS*

![KFC Bot Agent Multi-Channel Architecture](/images/4-Event/event3_kfc_bot_agent.png?width=45pc)
*Hình 5: [Nhóm 4 - OneTeam] Mô hình đặt hàng đa kênh KFC Bot Agent (Zalo/Messenger) và chỉ số hạ tầng $0.006/đơn*

> Tuần lễ AWS Agentic AI Build Week không chỉ là một kỳ Hackathon thử thách trí tuệ và thể lực, mà còn là bệ phóng giúp em nâng tầm tư duy công nghệ, làm chủ các giải pháp Agentic AI hiện đại nhất trên AWS và tự tin bước vào môi trường phát triển phần mềm chuyên nghiệp.
