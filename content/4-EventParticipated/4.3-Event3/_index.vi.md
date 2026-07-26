---
title: "Event 3"
date: 2024-01-01
weight: 3
chapter: false
pre: " <b> 4.3. </b> "
---


# Bài thu hoạch "AWS Agentic AI Build Week (AABW) Hackathon & Tech Sharing"

### Tổng Quan Sự Kiện

- **Tên sự kiện:** AWS Agentic AI Build Week (AABW) Hackathon & Tech Sharing
- **Thời gian:** 08/07/2026 - 12/07/2026
- **Địa điểm:** Văn phòng AWS Việt Nam (Tòa nhà Bitexco / Văn phòng Amazon) & Trực tuyến
- **Đơn vị tổ chức & Đối tác:** Amazon Web Services (AWS) Việt Nam, First Cloud Journey (FCJ/FCAJ), AWS User Group & All Builders Welcome (AABW).
- **Mục đích:** Nghiên cứu, thiết kế và phát triển các ứng dụng Trí tuệ nhân tạo đại diện (**Agentic AI**) trên nền tảng AWS Cloud, thử thách sáng tạo qua kỳ Hackathon chuyên sâu và chia sẻ các bài toán công nghệ thực chiến từ 4 nhóm phát triển.

---

### CHI TIẾT BÀI THUYẾT TRÌNH & NỘI DUNG TỪNG NHÓM (4 POWERPOINT PRESENTATIONS)

---

#### 📌 Nhóm 1: S.H.E.P.H.E.R.D – Smart Human-flow Evaluation & Dispatch
*Tệp trình bày:* `Hackathon_Journey_3KA.pptx`

- **Tên dự án:** **S.H.E.P.H.E.R.D** (Smart Human-flow Evaluation, Prediction, Hazard Detection, Response, and Dispatch)
- **Đội ngũ phát triển (Đội 3KA):** Dự án Capstone được thử nghiệm và mẫu hóa thực chiến trong kỳ AABW Hackathon.
- **Bài toán & Động lực phát triển:** 
  - Đội ngũ quản lý hội trường/sự kiện gặp nhiều khó khăn khi giám sát thủ công luồng đám đông tại các lối vào, hàng đợi và khu vực hội trường lớn cùng lúc.
  - Giám sát thủ công thường mang tính phản ứng chậm, khó mở rộng, dễ bỏ sót sự cố ùn tắc và nguy hiểm.
- **Tính năng cốt lõi:**
  - Chuyển đổi dữ liệu camera thông thường thành thông tin vận hành thời gian thực: Nhận diện & theo dõi người (Detect & Track), đo lường mật độ đám đông và đánh giá tình trạng hàng đợi.
  - Dự báo nguy cơ quá tải, tự động tạo cảnh báo sớm và đưa ra đề xuất điều phối nhân sự xử lý.
- **Kiến trúc công nghệ:**
  - **Computer Vision & Tracking:** YOLO + ByteTrack.
  - **Cloud & AI Layer:** Amazon SageMaker, Amazon Bedrock AgentCore + Strands Agent (Multi-Agent System gồm *Autonomous Monitor* và *Operator Copilot* hỗ trợ truy vấn ngôn ngữ tự nhiên).
  - **Frontend:** React Monitoring Dashboard.
- **Thách thức & Trải nghiệm thực tế:**
  - Xử lý độ trễ suy luận AI (inference latency), duy trì luồng video trực tiếp ổn định và tối ưu hóa hạ tầng Cloud.
  - Kỷ niệm làm việc cường độ cao: Debug mã nguồn đến 3 giờ sáng, dùng RedBull, phân chia vai trò rõ ràng giữa thiết kế, lập trình và thuyết trình.
- **Bài học rút ra:** *"Showing up is half the battle"* - dấn thân tham gia, tập trung hoàn thiện một sản phẩm nhỏ chạy tốt hơn ý tưởng lớn dở dang, và coi trọng các kết nối cộng đồng.

---

#### 📌 Nhóm 2: Solution Architect Professional AI Native App
*Tệp trình bày:* `SA_Professional_Native_App.pptx`

- **Tên dự án:** **Solution Architect Professional AI Native App**
- **Đội ngũ phát triển (Nhóm Plan V):** Phạm Tiến Thuận, Phát Huỳnh, Hoàng Long, Lê Minh Nghĩa, Trần Đại Vĩ, Nguyễn An.
- **Bài toán & Động lực phát triển:** 
  - Khách hàng thường yêu cầu thiết kế hệ thống AI khẩn cấp (ví dụ xử lý tài liệu SOP/BRD/PRD).
  - Kỹ sư giải pháp (Solution Architect) phải đọc tài liệu thủ công dòng theo dòng, bắt đầu từ trang trắng, tạo sơ đồ IaC và dự toán chi phí phức tạp.
- **Tính năng cốt lõi:**
  - Phân tích ngôn ngữ tự nhiên và trích xuất Yêu cầu dự án (Requirements Catalogue) chỉ trong vài phút.
  - Phác thảo các phương án kiến trúc đám mây đa dạng (Hybrid-cloud aware), phù hợp với tiêu chuẩn doanh nghiệp.
  - Tự động sinh sơ đồ kiến trúc chỉnh sửa được trên Drawio và sơ đồ AWS sử dụng biểu tượng AWS chính thức.
  - Tính toán dự toán chi phí AWS Cloud hướng nam cho vùng `ap-southeast-1` và tinh chỉnh tương tác qua Chat Sidebar theo từng dự án.
- **Tác động & Tối ưu hóa (Impact):**
  - Giảm thiểu thời gian đọc và tạo sơ đồ thủ công.
  - Tự động hóa việc sinh mã IaC và đưa ra dự toán chi phí AWS tức thời bên cạnh sơ đồ kiến trúc.

---

#### 📌 Nhóm 3: Signal Scout – Early Corporate Strategic Change Detection
*Tệp trình bày:* `SignalScout.pptx`

- **Tên dự án:** **Signal Scout** – Early Strategic Change & Restructuring Detector
- **Đội ngũ phát triển (Nhóm Dream AI Team):** Lê Tấn Lực, Đỗ Hoàng Hiếu, Triệu Quốc Hào, Nguyễn Văn Duy Khiêm, Nguyễn Công Minh, Nguyễn Trần Minh Quân.
- **Bài toán & Động lực phát triển:** 
  - Giúp các đội ngũ chiến lược doanh nghiệp, quản trị rủi ro và quản lý tài khoản B2B phát hiện sớm các tín hiệu tái cấu trúc và thay đổi chiến lược từ các dữ liệu phân tán.
- **Mô hình Kinh doanh & Tính năng (Value Creation Canvas):**
  - Nền tảng tự phục vụ (Self-service Dashboard) thu thập và xác thực bằng chứng tái cấu trúc doanh nghiệp.
  - Phân tích các chỉ số tài chính/vận hành, xây dựng kịch bản báo cáo và cảnh báo rủi ro tự động với minh chứng minh bạch.
- **Kiến trúc & Phân tích Chi phí Cloud:**
  - Tích hợp các công nghệ: AWS Bedrock, AgentCore Short-Term Memory, LangFuse, TinyFish, Apify, Lambda, API Gateway, DynamoDB, Amplify Hosting, S3 Intelligent-Tiering, WAF, Secrets Manager, Cognito.
  - Chi tiết chi phí vận hành hạ tầng AWS theo 3 kịch bản:
    - **Min:** ~$17 / tháng (Bedrock $2.54, Memory $1.50, WAF $8.00...).
    - **Mid:** ~$35 / tháng.
    - **Max:** ~$130 / tháng.
    - **Tổng chi phí hệ thống (bao gồm Apify, TinyFish, Langfuse):** $81 – $359 / tháng.

---

#### 📌 Nhóm 4: OneTeam – KFC Bot Agent / Colonel AI (Multi-Channel AI Agent)
*Tệp trình bày:* `OneTeam_CommunityDay.pptx`

- **Tên dự án:** **KFC Bot Agent / Colonel AI** – Multi-Channel AI Conversational Ordering Agent
- **Đội ngũ phát triển (Nhóm OneTeam):** Anh Duy, Trần Đông, Đoàn Trung, Minh Việt, Anshul Roy.
- **Bài toán & Động lực phát triển:** 
  - Trải nghiệm đặt hàng qua hội thoại (Conversational Ordering) không hề dễ dàng (Rút kinh nghiệm từ case study thử nghiệm AI Drive-thru của McDonald's phải dừng lại sau khi thử tại 100 cửa hàng Mỹ do AI xử lý sai logic).
  - Khách hàng đang nhắn tin trên Zalo/Messenger/WhatsApp bị buộc phải tải ứng dụng mới, chuyển trang hoặc đăng ký tài khoản khiến gián đoạn mạch đặt hàng (Friction / Lost Order).
- **Giải pháp & Kiến trúc Tool Call Execution:**
  - Đặt hàng trực tiếp trên Zalo OA, Messenger mà không cần rời khung chat, không cần tải app hay tạo tài khoản mới.
  - Thực thi Agent qua 5 bước: Understand Intent -> Plan Steps -> Search Data -> Update Cart & Apply Vouchers -> Confirm against Real Cart.
  - Thiết kế kiến trúc một lần, mở rộng đa kênh (Design Once, Deploy Everywhere) thông qua các lớp Adapter & Connector.
- **Các con số ấn tượng (Impact Numbers):**
  - **$0.006 / đơn hàng:** Chi phí tính toán trên AWS Calculator (với quy mô 500 đơn/ngày).
  - **$88 / tháng:** Tổng chi phí hạ tầng hàng tháng (trong đó AWS Bedrock chiếm 75%).
  - **3–5 giây:** Độ trễ phản hồi toàn trình (Message sent → reply received).
  - **-60% mã nguồn hạ tầng:** Rút ngắn lượng code hạ tầng nhờ sử dụng AWS AgentCore.

---

### BÀI HỌC KINH NGHIỆM RÚT RA TỪ SỰ KIỆN

1. **Tinh thần sẵn sàng (Showing Up):** Dấn thân tham gia cuộc thi là bước đi quan trọng nhất để học hỏi và bứt phá giới hạn kỹ thuật của bản thân.
2. **Ưu tiên sản phẩm hoàn thiện (Execution Over Scope):** Một sản phẩm mẫu (working prototype) cốt lõi chạy mượt mà luôn có giá trị vượt trội so với ý tưởng lớn nhưng dở dang.
3. **Chuyển dịch từ Chatbot sang Agent (A Chatbot Replies, An Agent Acts):** Chatbot chỉ dừng lại ở câu trả lời văn bản, trong khi AI Agent thực thụ phải có khả năng gọi Tools, truy xuất cơ sở dữ liệu thực tế và thực hiện hành động chính xác.
4. **Tối ưu chi phí & Kiến trúc hạ tầng ngay từ đầu:** Xây dựng giải pháp AI phải đi kèm với bài toán kinh tế thực tế ($0.006/đơn hàng hoặc thiết kế kịch bản Min/Mid/Max).

---

### BỘ ẢNH MINH HỌA CÁC BÀI THUYẾT TRÌNH & SỰ KIỆN

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

> Tuần lễ AWS Agentic AI Build Week đã mang đến cái nhìn toàn diện từ 4 nhóm phát triển xuất sắc. Sự kiện không chỉ giúp làm chủ các công nghệ AI Agent mới nhất trên AWS mà còn rèn luyện tư duy thiết kế hệ thống tối ưu chi phí cho các bài toán thực tế.
