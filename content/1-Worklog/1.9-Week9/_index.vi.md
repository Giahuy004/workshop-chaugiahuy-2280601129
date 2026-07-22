---
title: "Worklog Tuần 9"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.9. </b> "
---

### Mục tiêu tuần 9:
* Tạo cổng API Gateway, viết mã Lambda Python và thiết lập hàng đợi SQS.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | Khởi tạo Amazon API Gateway. Thiết kế cấu trúc các cổng API điều hướng bao gồm đầu `/upload` và `/get-result`. | 15/06/2026 | 15/06/2026 | |
| 3 | Viết mã nguồn Python cho AWS Lambda để xử lý logic chính khi có yêu cầu gọi từ ứng dụng Web Frontend thông qua API Gateway. | 16/06/2026 | 16/06/2026 | |
| 4 | Cấu hình Amazon SQS (Simple Queue Service) để làm hàng đợi. Thiết lập logic xử lý: Nếu có 100 người upload file cùng lúc, hệ thống sẽ tự động xếp hàng chúng lại để tránh "ngập" dữ liệu phân tích. | 17/06/2026 | 17/06/2026 | |
| 5 | Thiết lập AWS Step Functions để quản lý hàng đợi phức tạp và điều phối luồng trạng thái xử lý dữ liệu từ Lambda qua SQS. | 18/06/2026 | 18/06/2026 | |
| 6 | Viết code Python cho Lambda nhằm kích hoạt tính năng tự động thông báo khi có file mới vừa rơi vào S3 bucket hệ thống. | 19/06/2026 | 19/06/2026 | |
| 7 | Test tích hợp chuỗi liên kết: API Gateway -> Lambda -> SQS & Step Functions. Tắt các hàm kiểm thử để tiết kiệm tài nguyên hệ thống. | 20/06/2026 | 20/06/2026 | |

### Kết quả đạt được tuần 9:
* Định nghĩa xong các endpoint của API Gateway trên môi trường staging.
* Hàm Lambda xử lý logic cơ bản chạy mượt mà trên môi trường thử nghiệm.
* Hàng đợi SQS chịu tải tốt, phân luồng dữ liệu không bị nghẽn.
* Xây dựng xong sơ đồ trạng thái (State Machine) điều phối luồng Serverless tự động.
* Hệ thống tự động phát hiện và gửi tín hiệu xử lý ngay khi có file mới tải lên.
* Luồng Serverless Backend hoạt động đồng bộ.
