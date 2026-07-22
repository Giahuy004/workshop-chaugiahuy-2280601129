---
title: "Week 10 Worklog"
date: 2024-01-01
weight: 2
chapter: false
pre: " <b> 1.10. </b> "
---

### Week 10 Objectives:
* Deploy DynamoDB tables, initialize t3.medium virtual machines to run AI models, and set up CloudWatch for monitoring.

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | Create high-speed NoSQL Amazon DynamoDB database. Design the database table structure to store user scan and analysis history. | 22/06/2026 | 22/06/2026 | |
| 3 | Configure Amazon EC2 virtual machine (or ECS) using `t3.medium` instances, placed within a completely isolated network Sandbox environment (no internet gateway) to run the AI model. | 23/06/2026 | 23/06/2026 | |
| 4 | Establish internal connection from Backend to the EC2 AI server via VPC Endpoints to ensure secure internal data transmission. | 24/06/2026 | 24/06/2026 | |
| 5 | Configure Amazon CloudWatch to view AI model execution logs and measure network traffic for system analysis. | 25/06/2026 | 25/06/2026 | |
| 6 | Connect the Git repository containing the team's Hugo source code with AWS Amplify service to automatically host the cybersecurity report website. Replace the default website icons. | 26/06/2026 | 26/06/2026 | |
| 7 | Implement cost optimization policy: Shut down the EC2 `t3.medium` instance and scale down VPC Endpoints immediately after test sessions conclude to reduce costs from $33.00/month to $2.50. | 27/06/2026 | 27/06/2026 | |

### Week 10 Achievements:
* Initialized the data storage table on DynamoDB, ready to receive and log data.
* Successfully launched the AI server inside the secure network zone.
* Established smooth internal transmission paths between services without routing through the public internet.
* Displayed AI application logs and performance metrics visually on CloudWatch.
* Hosted the Web Admin website online stably on the AWS Amplify environment.
* Fully optimized the operating costs of the AI server according to the plan.
