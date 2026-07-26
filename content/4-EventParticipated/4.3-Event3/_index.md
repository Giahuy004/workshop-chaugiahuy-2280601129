---
title: "Event 3"
date: 2024-01-01
weight: 3
chapter: false
pre: " <b> 4.3. </b> "
---


# Event Summary "AWS Agentic AI Build Week (AABW) Hackathon & Tech Sharing"

### Event Overview

- **Event Name:** AWS Agentic AI Build Week (AABW) Hackathon & Tech Sharing
- **Date & Time:** July 08, 2026 - July 12, 2026
- **Location:** AWS Vietnam Office (Bitexco Financial Tower / Amazon Office) & Online
- **Organizers & Partners:** Amazon Web Services (AWS) Vietnam, First Cloud Journey (FCJ/FCAJ), AWS User Group & All Builders Welcome (AABW).
- **Objective:** Research, design, and build **Agentic AI** applications on AWS Cloud, compete in an intensive Hackathon, and present production engineering case studies from 4 presentation groups.

---

### PRESENTATION & GROUP BREAKDOWN (4 POWERPOINT PRESENTATIONS)

---

#### 📌 Group 1: S.H.E.P.H.E.R.D – Smart Human-flow Evaluation & Dispatch
*Presentation File:* `Hackathon_Journey_3KA.pptx`

- **Project Title:** **S.H.E.P.H.E.R.D** (Smart Human-flow Evaluation, Prediction, Hazard Detection, Response, and Dispatch)
- **Team (Team 3KA):** Capstone project prototype validated and scaled during the AABW Hackathon.
- **Problem & Motivation:** 
  - Venue operators struggle to manually monitor crowd density across multiple entrances, queues, and halls simultaneously.
  - Manual monitoring is reactive, slow to scale, and prone to missing critical overcrowding hazards.
- **Core Capabilities:**
  - Transforms raw camera feeds into real-time operational data: Detects & tracks people, measures crowd density, and estimates queue congestion.
  - Predicts overcrowding pressure, issues proactive alerts, and dispatches field operators automatically.
- **Technical Architecture:**
  - **Computer Vision & Tracking:** YOLO + ByteTrack.
  - **Cloud & AI Layer:** Amazon SageMaker, Amazon Bedrock AgentCore + Strands Agent (Multi-Agent System featuring *Autonomous Monitor* & *Operator Copilot* for natural-language queries).
  - **Frontend:** React Monitoring Dashboard.
- **Hackathon Challenges & Real Experiences:**
  - Managing AI inference latency, maintaining stable live video streams, and optimizing cloud compute costs.
  - Late-night debugging until 3 AM, drinking RedBull, and maintaining clear role delegation between design, coding, and pitching.
- **Key Takeaways:** *"Showing up is half the battle"* — focus on finishing a small working prototype rather than a large unfinished idea, and value community networking.

---

#### 📌 Group 2: Solution Architect Professional AI Native App
*Presentation File:* `SA_Professional_Native_App.pptx`

- **Project Title:** **Solution Architect Professional AI Native App**
- **Team (Team Plan V):** Pham Tien Thuan, Phat Huynh, Hoang Long, Le Minh Nghia, Tran Dai Vi, Nguyen An.
- **Problem & Motivation:** 
  - Enterprise clients frequently demand urgent AI system architectures (e.g., SOP/BRD/PRD documents).
  - Solution Architects must manually read documents line-by-line, start from a blank page, draw diagrams manually, and calculate cloud cost estimations.
- **Core Capabilities:**
  - Analyzes natural language and extracts a Requirements Catalogue in minutes.
  - Drafts hybrid-cloud aware architecture options aligned with corporate standards.
  - Generates editable Drawio diagrams and AWS architecture diagrams using official AWS icons.
  - Estimates directional AWS cloud costs for region `ap-southeast-1` and iteratively refines via a chat sidebar.
- **Impact & Optimization:**
  - Transitions from manual document reading and diagramming to an automated workflow.
  - Generates initial architecture drafts in minutes, produces IaC code automatically, and delivers instant AWS cost estimates alongside the architecture.

---

#### 📌 Group 3: Signal Scout – Early Corporate Strategic Change Detection
*Presentation File:* `SignalScout.pptx`

- **Project Title:** **Signal Scout** – Early Strategic Change & Restructuring Signal Detector
- **Team (Dream AI Team):** Le Tan Luc, Do Hoang Hieu, Trieu Quoc Hao, Nguyen Van Duy Khiem, Nguyen Cong Minh, Nguyen Tran Minh Quan.
- **Problem & Motivation:** 
  - Helps corporate strategy, risk management, and enterprise account teams detect early restructuring signals and strategic shifts from scattered data sources.
- **Business Model & Capabilities (Value Creation Canvas):**
  - Self-service Executive Dashboard collecting and validating corporate change evidence.
  - Analyzes financial and operational metrics, builds report scenarios, and generates risk alerts with verifiable evidence.
- **Cloud Architecture & Cost Analysis:**
  - Integrated Stack: AWS Bedrock, AgentCore Short-Term Memory, LangFuse, TinyFish, Apify, Lambda, API Gateway, DynamoDB, Amplify Hosting, S3 Intelligent-Tiering, WAF, Secrets Manager, Cognito.
  - Detailed AWS cost breakdown across 3 scenarios:
    - **Min:** ~$17 / month (Bedrock $2.54, Memory $1.50, WAF $8.00...).
    - **Mid:** ~$35 / month.
    - **Max:** ~$130 / month.
    - **Total Operational Cost (incl. Apify, TinyFish, Langfuse):** $81 – $359 / month.

---

#### 📌 Group 4: OneTeam – KFC Bot Agent / Colonel AI (Multi-Channel AI Agent)
*Presentation File:* `OneTeam_CommunityDay.pptx`

- **Project Title:** **KFC Bot Agent / Colonel AI** – Multi-Channel AI Conversational Ordering Agent
- **Team (Team OneTeam):** Anh Duy, Tran Dong, Doan Trung, Minh Viet, Anshul Roy.
- **Problem & Motivation:** 
  - Conversational ordering is difficult (Inspired by McDonald's AI drive-thru trial cancellation across 100 US locations due to logic failures).
  - Users chatting on Zalo/Messenger/WhatsApp are forced to download new apps or switch flows, creating friction and causing lost orders.
- **Solution & Tool Call Execution Architecture:**
  - Multi-channel conversational ordering inside Zalo OA and Messenger without app switching or new account registration.
  - 5-step Tool Call Execution: Understand Intent -> Plan Steps -> Search Data -> Update Cart & Apply Vouchers -> Confirm against Real Cart.
  - Design Once, Deploy Everywhere via modular Adapters & Connectors.
- **Key Impact Numbers:**
  - **$0.006 / order:** Calculated via AWS Pricing Calculator (500 orders/day).
  - **$88 / month:** Total infrastructure cost (AWS Bedrock accounts for 75%).
  - **3–5s:** End-to-end latency (Message sent → reply received).
  - **-60% infra code:** Reduced infrastructure codebase by leveraging AWS AgentCore.

---

### LESSONS LEARNED ACROSS ALL GROUPS

1. **Showing Up:** Stepping up to participate in major hackathons is the most important step for personal and technical growth.
2. **Execution Over Scope:** A working core prototype delivers far more value than a grand unfinished concept.
3. **From Chatbot to Agent (A Chatbot Replies, An Agent Acts):** A chatbot merely replies with text, whereas a true AI Agent executes tools, queries live databases, and performs real actions.
4. **Cost-Aware Architecture:** Building AI solutions must be paired with real-world financial metrics ($0.006/order or Min/Mid/Max infrastructure budgeting).

---

### EVENT & PRESENTATION GALLERY

![AWS Group Photo at Amazon Office](/images/4-Event/event3_amazon_photo.png?width=45pc)
*Figure 1: Group photo with participants and AWS experts at the Amazon Web Services (AWS) office*

![S.H.E.P.H.E.R.D System Architecture](/images/4-Event/event3_architecture.png?width=45pc)
*Figure 2: [Group 1 - Hackathon Journey] S.H.E.P.H.E.R.D Agentic AI architecture (YOLO + AWS Bedrock)*

![Solution Architect AI Native App Workflow](/images/4-Event/event3_sa_native_app.png?width=45pc)
*Figure 3: [Group 2 - SA Professional Native App] Automated requirement extraction and cloud architecture generator*

![Signal Scout Architecture Canvas](/images/4-Event/event3_signal_scout.png?width=45pc)
*Figure 4: [Group 3 - Signal Scout] Strategic signal analysis architecture and AWS cost breakdown*

![KFC Bot Agent Multi-Channel Architecture](/images/4-Event/event3_kfc_bot_agent.png?width=45pc)
*Figure 5: [Group 4 - OneTeam] Multi-channel KFC Bot Agent ordering model and $0.006/order infrastructure metric*

> The AWS Agentic AI Build Week offered comprehensive insights across 4 outstanding project groups. The event provided hands-on experience mastering AWS Agentic AI services while building cost-optimized, production-ready system architectures.
