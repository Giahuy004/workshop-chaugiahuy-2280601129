---
title: "Blogs Posted"
date: 2024-01-01
weight: 3
chapter: false
pre: " <b> 3. </b> "
---

Here you will find a list and introduction of the blogs posted on [AWS Study Group](https://www.facebook.com/groups/awsstudygroupfcj). For example:

###  [Blog 1 - VPC ENDPOINTS — THE KEY TO BUILDING AN ISOLATED SANDBOX ON AWS](3.1-Blog1/)
A hands-on experience sharing about designing a VPC Sandbox network with no Internet Gateway for our malware analysis system. The post explains the differences between Gateway Endpoints (free, for S3/DynamoDB) and Interface Endpoints (paid, for CloudWatch Logs), along with 3 common configuration mistakes our team encountered and how we fixed them.

###  [Blog 2 - S3 PRESIGNED URL — SECURE FILE UPLOADS WITHOUT GOING THROUGH YOUR SERVER](3.2-Blog2/)
A technical guide on using Presigned URLs to upload files directly from the browser to S3, bypassing Lambda's 6MB limit. Includes sample code in Python (Lambda) and JavaScript (Client), detailed breakdowns of CORS and Content-Type mismatch errors, and a comparison table of Lambda upload vs Presigned URL.

###  [Blog 3 - AWS CONFIG AUTO-REMEDIATION — AUTOMATICALLY LOCK AN S3 BUCKET WITHIN 1 SECOND](3.3-Blog3/)
Building an automated mechanism to detect and fix S3 security misconfigurations using the trio of AWS Config + EventBridge + Lambda. The post provides step-by-step setup for monitoring rules, writing a Lambda remediation function, and extending the pattern to Security Groups, EBS encryption, and IAM Access Key rotation.