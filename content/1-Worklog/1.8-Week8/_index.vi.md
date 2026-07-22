---
title: "Worklog Tuần 8"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.8. </b> "
---

### Mục tiêu tuần 8:
* Cấu hình xác thực người dùng qua Amazon Cognito và thiết lập tích hợp lưu trữ client-side và server-side với Amazon S3.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | Khởi tạo và cấu hình Amazon Cognito User Pool để phục vụ tính năng đăng ký, đăng nhập hệ thống. | 08/06/2026 | 08/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | Lập trình giao diện Web Frontend tích hợp luồng xác thực Cognito, xử lý lưu trữ an toàn mã token session và cookie. | 09/06/2026 | 09/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | Xây dựng kho chứa Amazon S3 phía Client nhận tập tin trực tiếp và cấu hình CORS. | 10/06/2026 | 10/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | Thiết lập kho lưu trữ Amazon S3 phía Server; cấu hình S3 Lifecycle Policies để tự động hóa quy trình phân loại và dọn rác dữ liệu. | 11/06/2026 | 11/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 6 | Viết logic cho Frontend để gọi API lấy Presigned URL, giúp tối ưu hóa việc upload file trực tiếp lên S3 một cách bảo mật. | 12/06/2026 | 12/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | Kiểm tra an ninh các liên kết S3 công cộng. Thực hiện tối ưu chi phí lưu trữ tệp tin trên S3. Họp nhóm review tiến độ tích hợp Web - Storage. | 13/06/2026 | 13/06/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 8:
* Tạo và cấu hình thành công Amazon Cognito User Pool hoạt động ổn định.
* Web Frontend lưu trữ và quản lý an toàn mã token session và cookie.
* Cấu hình CORS thành công cho S3 Client và nhận tập tin trực tiếp.
* Kích hoạt thành công S3 Lifecycle Policies phía Server để phân loại dữ liệu tự động.
* Frontend lấy được Presigned URL và đẩy file lên kho chứa S3 an toàn.
* Hệ thống lưu trữ chạy ổn định.
