---
title: "Week 4 Worklog"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.4. </b> "
---

### Week 4 Objectives:
* Design a secure, independent network architecture on the cloud.

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | Research Amazon VPC (Virtual Private Cloud). Learn about IP Subnetting (CIDR), Public Subnet, and Private Subnet. | 11/05/2026 | 11/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | Practice configuring Internet Gateway (IGW), NAT Gateway, and Route Tables for the created VPC. | 12/05/2026 | 12/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | Learn about the Application Load Balancer (ALB). Create a Target Group containing 2 EC2 instances in 2 different AZs and attach them to the ALB. | 13/05/2026 | 13/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | Research Amazon Route 53 domain name resolution service and Amazon CloudFront Content Delivery Network (CDN). | 14/05/2026 | 14/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 6 | Major practical Lab: Deploy a 2-Tier Architecture. Upload the entire Frontend source code to S3/CloudFront, and place the Backend source code and RDS Database inside a secure Private Subnet within the VPC. | 15/05/2026 | 15/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | Learn and differentiate the traffic control mechanisms of Security Groups (Stateful) and Network ACLs (Stateless). Resolve common network connection errors in the Lab. | 16/05/2026 | 16/05/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Week 4 Achievements:
* Drafted a network diagram consisting of 1 VPC, 2 Public Subnets, and 2 Private Subnets across 2 different Availability Zones to ensure High Availability.
* Configured the system so that servers in the Private Subnet cannot be accessed from the internet but can still access the internet to download updates via the NAT Gateway.
* Successfully distributed traffic evenly (Round-robin) to both servers when accessing the ALB's DNS.
* Understood how CloudFront caches static files from S3 to Edge Locations closest to users to accelerate Frontend website loading speed.
* Achieved documentation showing smooth end-to-end system integration; secured the database layer by isolating it completely from the public internet.
* Mastered debugging skills related to Networking and Firewalls on AWS.
