---
title: "Event 3"
date: 2024-01-01
weight: 3
chapter: false
pre: " <b> 4.3. </b> "
---


# Event Summary "AWS Agentic AI Build Week (AABW) Hackathon & Tech Sharing"

### Purpose of the Event

- Participate in the intensive **Agentic AI** hackathon and workshop series organized by **Amazon Web Services (AWS)**.
- Explore next-generation Artificial Intelligence technologies (GenAI, Multi-Agent Systems, Agentic AI Core) and integrate leading AWS cloud services (Amazon Bedrock, SageMaker, Lambda, API Gateway).
- Learn production engineering solutions from 4 presentation groups: Automated crowd density monitoring, Solution Architect support tools, corporate strategy signal detection, and multi-channel conversational ordering bots.
- Sharpen practical engineering skills under high time pressure (Hackathon), optimize Cloud infrastructure costs, and pitch solutions to AWS experts.

### Scale & Speakers

- **Co-organizing Partners:** Amazon Web Services (AWS) Vietnam, First Cloud Journey (FCJ/FCAJ), AWS User Group Vietnam, and All Builders Welcome (AABW).
- **Participants:** Cloud engineers, AI developers, and students forming teams for intense building during the *Agentic AI Build Week*.
- **Speakers & Presentation Topics:**
  - **Topic 1 (PP: `Hackathon_Journey_3KA.pptx`):** S.H.E.P.H.E.R.D – Smart Human-flow Evaluation, Prediction, Hazard Detection, Response, and Dispatch
    - *Speakers:* Team 3KA
  - **Topic 2 (PP: `SA_Professional_Native_App.pptx`):** Solution Architect Professional AI Native App – Automated Cloud Architecture Design
    - *Speakers:* Team Plan V (Pham Tien Thuan, Phat Huynh, Hoang Long, Le Minh Nghia, Tran Dai Vi, Nguyen An)
  - **Topic 3 (PP: `SignalScout.pptx`):** Signal Scout – Early Corporate Strategic Change & Restructuring Signal Detection
    - *Speakers:* Dream AI Team (Le Tan Luc, Do Hoang Hieu, Trieu Quoc Hao, Nguyen Van Duy Khiem, Nguyen Cong Minh, Nguyen Tran Minh Quan)
  - **Topic 4 (PP: `OneTeam_CommunityDay.pptx`):** OneTeam & KFC Bot Agent – Multi-Channel AI Conversational Ordering Experience
    - *Speakers:* Team OneTeam (Anh Duy, Tran Dong, Doan Trung, Minh Viet, Anshul Roy)

---

### Highlights

#### 1. S.H.E.P.H.E.R.D – Smart Human-flow Evaluation & Dispatch
Team 3KA presented an intelligent crowd monitoring and operator dispatch system:
- **Problem & Motivation:** Venue operators struggle to manually monitor crowd density across multiple entrances, queues, and halls simultaneously.
- **Core Capabilities:** Transforms camera feeds into real-time operational data, measures crowd density, evaluates queue status, predicts overcrowding risks, and automatically issues early alerts to dispatch personnel.
- **Technical Architecture:** Combines Computer Vision (YOLO + ByteTrack), Amazon SageMaker, Amazon Bedrock AgentCore + Strands Agent (Multi-Agent System featuring *Autonomous Monitor* and *Operator Copilot*), and a React Monitoring Dashboard.
- **Hackathon Challenges:** Managing AI inference latency, maintaining live video stream stability, late-night debugging until 3 AM, and effective role delegation within the team.

#### 2. Solution Architect Professional AI Native App
Team Plan V introduced an AI Native app assisting Solution Architects in automating cloud architecture design:
- **Problem & Motivation:** Solution Architects spend excessive time manually reading BRD/PRD documents line-by-line, drawing diagrams from scratch, and calculating complex cloud estimates.
- **Core Capabilities:** Parses natural language to extract a Requirements Catalogue in minutes, drafts enterprise-grade cloud architecture options, automatically generates editable Drawio / AWS Diagrams, and estimates cloud costs for region `ap-southeast-1`.
- **Impact:** Automates initial architecture draft generation, produces IaC code automatically, and provides instant AWS cost estimations alongside architecture diagrams.

#### 3. Signal Scout – Early Corporate Strategic Change Detection
Dream AI Team presented an AI-powered strategic corporate signal analysis solution:
- **Problem & Motivation:** Helps corporate strategy and risk management teams detect early restructuring signals from scattered data sources.
- **Business Model & Capabilities:** Self-service Executive Dashboard collecting and validating corporate change evidence, analyzing financial/operational metrics, and issuing automated risk alerts.
- **Cloud Architecture & Cost Analysis:** Integrated AWS Bedrock, AgentCore Short-Term Memory, LangFuse, TinyFish, Apify, Lambda, API Gateway, DynamoDB... Detailed AWS infrastructure cost scenarios: Min ($17/month), Mid ($35/month), Max ($130/month); total operational cost from $81 – $359/month.

#### 4. OneTeam & KFC Bot Agent – Multi-Channel AI Conversational Ordering
Team OneTeam shared a frictionless multi-channel conversational ordering solution:
- **Problem & Motivation:** Conversational ordering often breaks user flow by forcing app downloads or context switches (inspired by McDonald's AI drive-thru trial cancellation due to logic errors).
- **Solution & Tool Call Architecture:** Multi-channel ordering (Zalo OA, Messenger, WhatsApp) directly inside chat windows via a 5-step Tool Call Execution (Understand Intent -> Plan Steps -> Search Data -> Update Cart & Apply Vouchers -> Confirm against Real Cart).
- **Key Metrics:** $0.006 / order cost (calculated for 500 orders/day), $88 / month total infrastructure cost (Bedrock accounts for 75%), 3–5s response latency, and 60% reduction in infrastructure code thanks to AWS AgentCore.

---

### Key Lessons Learned

- **Execution & Preparedness (Showing Up):** Stepping up to participate in major hackathons is the most important step for personal and technical growth.
- **Finished Prototype Over Scope (Execution Over Scope):** A working core prototype delivers far more value than a grand unfinished concept.
- **From Chatbot to AI Agent:** A chatbot merely replies with text (*A Chatbot Replies*), whereas a true AI Agent executes tools, queries live databases, and performs real actions (*An Agent Acts*).
- **Cost-Aware Infrastructure Design:** Building AI solutions must be paired with real-world financial metrics ($0.006/order or Min/Mid/Max infrastructure budgeting).

---

### Results & Key Achievements

#### Technical Skills & Industry Knowledge
- **Advanced Agentic AI & GenAI Capabilities:** Mastered integration of Agentic AI services and LLMs on AWS (Amazon Bedrock, SageMaker, AgentCore).
- **Cloud Architecture Design & Cost Optimization:** Gained hands-on experience designing scalable cloud architectures with real-world cost controls.
- **Real-Time Data & Computer Vision Processing:** Learned to combine computer vision models (YOLO, ByteTrack) with cloud inference pipelines.

#### Soft Skills & Personal Growth
- **High-Pressure Teamwork:** Collaborated effectively and maintained high team energy throughout the intensive Hackathon week.
- **Pitching & Project Management:** Practiced agile role delegation, 3-minute pitch preparation, and technical solution presentation in front of AWS judges.
- **Networking & Connections:** Built valuable relationships with AWS mentors, industry experts, and talented peers.

#### Team & Project Contributions
- Applied practical AI Agent design and cloud cost optimization perspectives into current team internship projects.
- Shared rapid prototyping lessons and open team collaboration practices with fellow interns.

---

### Event Gallery

![AWS Group Photo at Amazon Office](/images/4-Event/event3_amazon_photo.png?width=45pc)
*Figure 1: Group photo with fellow participants and experts at the Amazon Web Services (AWS) office*

![S.H.E.P.H.E.R.D System Architecture](/images/4-Event/event3_architecture.png?width=45pc)
*Figure 2: [Group 1 - Hackathon Journey] S.H.E.P.H.E.R.D Agentic AI architecture (YOLO + AWS Bedrock)*

![Solution Architect AI Native App Workflow](/images/4-Event/event3_sa_native_app.png?width=45pc)
*Figure 3: [Group 2 - SA Professional Native App] Automated requirement extraction and cloud architecture generator*

![Signal Scout Architecture Canvas](/images/4-Event/event3_signal_scout.png?width=45pc)
*Figure 4: [Group 3 - Signal Scout] Strategic signal analysis architecture and AWS cost breakdown*

![KFC Bot Agent Multi-Channel Architecture](/images/4-Event/event3_kfc_bot_agent.png?width=45pc)
*Figure 5: [Group 4 - OneTeam] Multi-channel KFC Bot Agent ordering model and $0.006/order infrastructure metric*

> The AWS Agentic AI Build Week was not only an intellectually challenging hackathon, but also a launching pad that elevated my technology mindset, enabled me to master cutting-edge Agentic AI solutions on AWS, and prepared me for professional software engineering.
