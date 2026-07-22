---
title: "Worklog Tuần 2"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.2. </b> "
---

### Mục tiêu tuần 2:
* Kết nối, làm quen với các thành viên trong First Cloud AI Journey.
* Hiểu dịch vụ AWS cơ bản, cách dùng console & CLI.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | Tìm hiểu về Amazon EC2 (Elastic Compute Cloud). Học về các loại Instance types, AMIs, Key Pairs và cách thức tính giá. | 27/04/2026 | 27/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | Cấu hình Security Groups (Inbound/Outbound rules) cho EC2. Viết mã script script user_data để tự động cài đặt Nginx khi khởi tạo máy chủ. | 28/04/2026 | 28/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | Nghiên cứu về mô hình Không máy chủ (Serverless) thông qua AWS Lambda. Viết một hàm Lambda đơn giản bằng Node.js/Java để xử lý chuỗi logic. | 29/04/2026 | 29/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | Tìm hiểu dịch vụ Amazon Elastic Beanstalk và các khái niệm cơ bản về Container (Docker, Amazon ECS/ECR) | 30/04/2026 | 30/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 6 | Tiến hành bài Lab: Sử dụng EC2 User Data để tự động clone một source code Frontend (React/Vite) từ GitHub về và chạy deploy trên môi trường máy chủ ảo. <br> Thực hiện tắt/xóa các tài nguyên EC2 dư thừa để tránh phát sinh chi phí. | 01/05/2026 | 01/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | Xem lại trong tuần đã học và làm được những gì rồi note lại | 02/05/2026 | 02/05/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 2:
* Khởi tạo thành công một EC2 Instance
* Truy cập được vào địa chỉ Public IP của EC2 từ trình duyệt và thấy trang chào mừng của Nginx
* Hiểu cách AWS đơn giản hóa việc deploy code mà không cần tự quản lý hạ tầng hệ điều hành
* Thực thi thử nghiệm hàm Lambda trên AWS Console thành công
* Tối ưu hóa chi phí tài khoản thực tập
