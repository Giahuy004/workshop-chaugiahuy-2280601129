---
title: "Week 9 Worklog"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.9. </b> "
---

### Week 9 Objectives:
* Create API Gateway endpoints, write Lambda Python code, and set up Amazon SQS queue.

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | Initialize Amazon API Gateway. Design the architecture of the routing APIs including `/upload` and `/get-result` endpoints. | 15/06/2026 | 15/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | Write Python source code for AWS Lambda to handle core logic when triggered by Web Frontend application requests via API Gateway. | 16/06/2026 | 16/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | Configure Amazon SQS (Simple Queue Service) to serve as a queue. Set up processing logic: If 100 users upload files simultaneously, the system automatically queues them to prevent overloading the analytical data. | 17/06/2026 | 17/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | Configure AWS Step Functions to manage complex queues and coordinate the workflow state of data processing from Lambda through SQS. | 18/06/2026 | 18/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 6 | Write Python code for Lambda to trigger automatic notification when a new file lands in the system's S3 bucket. | 19/06/2026 | 19/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | Test integration of the connected chain: API Gateway -> Lambda -> SQS & Step Functions. Turn off testing functions to optimize system resources. | 20/06/2026 | 20/06/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Week 9 Achievements:
* Defined the API Gateway endpoints on the staging environment.
* Ran the Lambda function smoothly on the test environment to handle basic logic.
* Maintained good load tolerance in the SQS queue, ensuring data streaming is not bottlenecked.
* Successfully built the state machine diagram to coordinate the Serverless flow automatically.
* Automatically detected and sent processing signals immediately upon new file uploads.
* Synced and verified the Serverless Backend flow.
