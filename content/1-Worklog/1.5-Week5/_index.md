---
title: "Week 5 Worklog"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.5. </b> "
---

### Week 5 Objectives:
* Ensure stable system operations, automation, and compliance with engineering standards.

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | Learn about Amazon CloudWatch monitoring service. Configure monitoring for EC2 metrics such as CPU Utilization, Network In/Out. | 18/05/2026 | 18/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | Configure CloudWatch Alarms. Set up a scenario: If the server's CPU exceeds 80% for 5 minutes, the system will automatically send an email alert via Amazon SNS. | 19/05/2026 | 19/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | Research auditing and security: AWS CloudTrail (API log recording), AWS Config (resource configuration management), and AWS Secrets Manager (secure database password storage). | 20/05/2026 | 20/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | Learn about Auto Scaling Groups (ASG). Configure the minimum (Minimum = 1), desired (Desired = 2), and maximum (Maximum = 4) instances based on actual system load. | 21/05/2026 | 21/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 6 | Research the 6 Pillars of the AWS Well-Architected Framework: Operational Excellence, Security, Reliability, Performance Efficiency, Cost Optimization, Sustainability. | 22/05/2026 | 22/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | Summarize perimeter security services: AWS WAF (application-layer protection against DDoS and SQL Injection) and AWS Shield. Read preparation materials for the final week. | 23/05/2026 | 23/05/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Week 5 Achievements:
* Designed a visual Dashboard on CloudWatch to monitor system health in real-time.
* Successfully received an email notification test when using a benchmark command to simulate pushing EC2 CPU usage high.
* Enabled the Backend application to fetch the DB password automatically via Secrets Manager API instead of hardcoding it in the source code.
* Enabled the system to automatically launch a new EC2 instance when simulated traffic spiked and terminate it when the load decreased.
* Evaluated the entire architecture of last week's Lab against these framework pillars to self-assess and identify optimization points.
* Understood how to comprehensively protect web applications from common internet threats.
