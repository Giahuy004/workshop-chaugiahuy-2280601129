---
title : "Configuring AWS Lambda"
date : 2024-01-01
weight : 6
chapter : false
pre : " <b> 5.5.6 </b> "
---

### Introduction

- In this section, you will create and configure Amazon API Gateway to provide a public API endpoint for the React application. API Gateway receives URLs from the frontend, routes the requests to AWS Lambda, and returns analysis predictions from the AI model back to the application.

### Accessing Amazon API Gateway

- Select **Create API**

![alt text](/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.6-API Gateway/image.png)

### Creating an HTTP API

- Select **Build -> Enter API Name -> Review and create -> Create**

![alt text](/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.6-API Gateway/image-1.png)

### Creating an Integration with AWS Lambda

- Under **Routes**, create routes `/upload` and `/get-result` integrated with the AWS Lambda function.

![alt text](/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.6-API Gateway/image-2.png)
![alt text](/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.6-API Gateway/image-3.png)
![alt text](/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.6-API Gateway/image-4.png)
![alt text](/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.6-API Gateway/image-5.png)
![alt text](/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.6-API Gateway/image-6.png)
![alt text](/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.6-API Gateway/image-7.png)
