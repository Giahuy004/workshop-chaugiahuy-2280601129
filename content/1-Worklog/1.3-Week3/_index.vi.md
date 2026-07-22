---
title: "Worklog Tuần 3"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.3. </b> "
---

### Mục tiêu tuần 3:
* Tìm hiểu dịch vụ lưu trữ S3, các loại lưu trữ khối/tập tin EBS/EFS và cơ sở dữ liệu RDS/DynamoDB.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | Tìm hiểu hệ thống lưu trữ Amazon S3 (Simple Storage Service). Nghiên cứu về Storage Classes (Standard, IA, Glacier), Bucket Policies, Lifecycle rules và Object Versioning. | 04/05/2026 | 04/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | Phân biệt lưu trữ khối (Block Storage) EBS với lưu trữ tệp tin (File Storage) EFS. Học cách mount EBS và EFS vào EC2 instances. | 05/05/2026 | 05/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | Nghiên cứu về Cơ sở dữ liệu quan hệ Amazon RDS (Multi-AZ, Read Replicas) và Cơ sở dữ liệu phi quan hệ Amazon DynamoDB. | 06/05/2026 | 06/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | Thực hành bài Lab: Thiết lập một Static Website trên Amazon S3. Tạo một RDS database (MySQL/PostgreSQL) và kết nối thử nghiệm từ máy ảo EC2 vào RDS. | 07/05/2026 | 07/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 6 | Cấu hình Lifecycle Policy trên S3 để tự động di chuyển các file cũ sang lưu trữ lạnh Glacier sau 30 ngày và xóa sau 90 ngày nhằm tối ưu chi phí. | 08/05/2026 | 08/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | Xem lại trong tuần đã học và làm được những gì rồi note lại | 09/05/2026 | 09/05/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 3:
* Host thành công một website tĩnh trên Amazon S3
* Kết nối an toàn giữa EC2 và RDS Database thông qua Security Group
* Hiểu cách cấu hình Lifecycle Policies để tối ưu hóa chi phí lưu trữ tệp tin dài hạn
* Làm quen với việc truy xuất dữ liệu từ DynamoDB bằng CLI
