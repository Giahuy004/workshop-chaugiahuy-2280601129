---
title: "Week 11 Worklog"
date: 2024-01-01
weight: 2
chapter: false
pre: " <b> 1.11. </b> "
---

### Week 11 Objectives:
* Build automated Pipelines, write WAF anti-spam rules, and configure Auto-Remediation.

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | Build CI/CD automation workflow using AWS CodePipeline and AWS CodeBuild. Configure mechanism: Whenever any team member pushes new Backend code to GitHub, the system automatically pulls and updates it on the cloud. | 29/06/2026 | 29/06/2026 | |
| 3 | Deploy AWS WAF (Web Application Firewall) to protect the web application and API Gateway endpoints. | 30/06/2026 | 30/06/2026 | |
| 4 | Write Custom Rules and rate limiting mechanisms on AWS WAF to maximize protection for API endpoints. | 01/07/2026 | 01/07/2026 | |
| 5 | Build automated triggers using AWS Config combined with EventBridge. Write Auto-Remediation scripts: e.g., automatically lock down an S3 bucket in 1 second if someone accidentally sets it to Public. | 02/07/2026 | 02/07/2026 | |
| 6 | Configure advanced cleanup features on S3 Server storage: Schedule automatic deletion of all malware files in storage after 7 days of retention. | 03/07/2026 | 03/07/2026 | |
| 7 | Dry run the CI/CD pipeline and enable WAF to test system defense capabilities. After testing, reconfigure WAF to a cost-optimized mode ($0.50 instead of $7.00 if enabled 24/7). | 04/07/2026 | 04/07/2026 | |

### Week 11 Achievements:
* Successfully activated the automated deployment workflow for the development team.
* Configured the web application firewall to block basic security threats.
* Blocked incoming simulated spam requests flooding the <code>/upload</code> endpoint.
* Handled configuration drift remediation automatically and accurately in real-time.
* Ensured the storage repository remains clean and optimized in capacity periodically.
* Secured and automated the system.
