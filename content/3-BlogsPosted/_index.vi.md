---
title: "Các bài blogs đã đăng"
date: 2024-01-01
weight: 3
chapter: false
pre: " <b> 3. </b> "
---

Tại đây sẽ là phần liệt kê, giới thiệu các blogs mà các bạn đã đăng trên [AWS Study Group](https://www.facebook.com/groups/awsstudygroupfcj). Ví dụ:

###  [Blog 1 - VPC ENDPOINT — CHÌA KHÓA ĐỂ XÂY SANDBOX CÔ LẬP TRÊN AWS](3.1-Blog1/)
Chia sẻ kinh nghiệm thực tế khi thiết kế mạng VPC Sandbox không có Internet Gateway cho hệ thống phân tích mã độc. Bài viết giải thích sự khác nhau giữa Gateway Endpoint (miễn phí, cho S3/DynamoDB) và Interface Endpoint (trả phí, cho CloudWatch Logs), kèm theo 3 lỗi phổ biến mà nhóm đã gặp khi cấu hình và cách khắc phục.

###  [Blog 2 - S3 PRESIGNED URL — UPLOAD FILE AN TOÀN MÀ KHÔNG CẦN ĐI QUA SERVER](3.2-Blog2/)
Hướng dẫn kỹ thuật Presigned URL để upload file trực tiếp từ trình duyệt lên S3, vượt qua giới hạn 6MB của Lambda. Bao gồm code mẫu Python (Lambda) và JavaScript (Client), phân tích chi tiết các lỗi CORS, Content-Type mismatch, và bảng so sánh upload qua Lambda vs Presigned URL.

###  [Blog 3 - AWS CONFIG AUTO-REMEDIATION — TỰ ĐỘNG KHÓA S3 BUCKET TRONG 1 GIÂY](3.3-Blog3/)
Xây dựng cơ chế tự động phát hiện và khắc phục lỗi cấu hình bảo mật S3 bằng bộ ba AWS Config + EventBridge + Lambda. Bài viết hướng dẫn từng bước cài đặt rule giám sát, viết Lambda remediation, và mở rộng pattern cho Security Group, EBS encryption, và IAM Access Key rotation.