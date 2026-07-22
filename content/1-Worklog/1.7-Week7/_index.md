---
title: "Week 7 Worklog"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.7. </b> "
---

### Week 7 Objectives:
* Set up Sandbox VPC, configure IAM OIDC permissions, create a shared repository, and configure budget alerts.

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | Meet as a team to align on the overall system architecture. Set up a shared GitHub Organization for source code management. Configure AWS Budgets to track paid services such as EC2 t3.medium, WAF, and VPC Endpoints. | 01/06/2026 | 01/06/2026 | |
| 3 | Set up account authorization via AWS IAM (OIDC) to prepare temporary token provisioning for future CI/CD pipelines. Initialize an isolated Amazon VPC network including subnets and internal VPC Endpoints. | 02/06/2026 | 02/06/2026 | |
| 4 | Create encryption keys on AWS KMS to protect all stored data. Enable AWS CloudTrail and GuardDuty system-wide for audit logging and security monitoring. | 03/06/2026 | 03/06/2026 | |
| 5 | Initialize the local Web Frontend (React) project. Configure the Web Admin environment using the Hugo framework with the `aafu` theme, customizing the template source code to link the team's repositories. | 04/06/2026 | 04/06/2026 | |
| 6 | Set up AWS Secrets Manager as a centralized vault for storing project credentials and API Keys. Configure AWS Config to track resource changes. | 05/06/2026 | 05/06/2026 | |
| 7 | Review incurred costs of the first week based on pricing tables. Ensure that test resources are optimized and properly shut down. Summarize Week 1 documentation. | 06/06/2026 | 06/06/2026 | |

### Week 7 Achievements:
* Successfully created the GitHub Organization and activated initial cost alerts on AWS.
* Prepared the core VPC network environment and completed initial OIDC connection setup.
* Successfully activated security monitoring services and configured KMS data encryption keys.
* Successfully launched the local Frontend framework and Hugo blog site.
* Secured all sensitive keys in storage, preventing exposure in the source code.
