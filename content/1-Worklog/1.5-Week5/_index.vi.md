---
title: "Worklog Tuần 5"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu tuần 5:
* Đảm bảo hệ thống vận hành ổn định, tự động hóa và tuân thủ các tiêu chuẩn kỹ thuật.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | Học về dịch vụ giám sát Amazon CloudWatch. Cấu hình theo dõi các chỉ số (Metrics) của EC2 như CPU Utilization, Network In/Out. | 18/05/2026 | 18/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | Cấu hình CloudWatch Alarms. Thiết lập kịch bản: Nếu CPU của máy chủ vượt quá 80% trong vòng 5 phút, hệ thống sẽ tự động gửi email cảnh báo thông qua Amazon SNS. | 19/05/2026 | 19/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | Nghiên cứu về kiểm toán và bảo mật: AWS CloudTrail (ghi lại log API), AWS Config (quản lý cấu hình tài nguyên) và AWS Secrets Manager (lưu trữ mật khẩu database an toàn). | 20/05/2026 | 20/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | Tìm hiểu về Auto Scaling Groups (ASG). Thiết lập cấu hình tối thiểu (Minimum = 1), mong muốn (Desired = 2), và tối đa (Maximum = 4) máy chủ dựa trên tải thực tế của hệ thống. | 21/05/2026 | 21/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 6 | Nghiên cứu 6 Trụ cột của Khung kiến trúc chuẩn hóa AWS (AWS Well-Architected Framework): Operational Excellence, Security, Reliability, Performance Efficiency, Cost Optimization, Sustainability. | 22/05/2026 | 22/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | Tổng kết các dịch vụ hỗ trợ bảo mật vòng ngoài: AWS WAF (chống tấn công DDoS, SQL Injection tầng ứng dụng) và AWS Shield. Đọc tài liệu chuẩn bị cho tuần cuối. | 23/05/2026 | 23/05/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 5:
* Thiết kế được một Dashboard trực quan trên CloudWatch để theo dõi sức khỏe hệ thống theo thời gian thực.
* Nhận được email thông báo kiểm thử thành công khi dùng lệnh benchmark giả lập đẩy cao CPU của EC2.
* Ứng dụng Backend không còn lưu cứng (hardcode) mật khẩu DB trong code nữa mà gọi API qua Secrets Manager để lấy mật khẩu tự động.
* Hệ thống tự động khởi chạy thêm một máy chủ EC2 mới khi lượng traffic giả lập tăng đột biến và tự xóa đi khi tải giảm xuống.
* Đối chiếu toàn bộ kiến trúc bài Lab tuần trước với các tiêu chí này để tự chấm điểm và tìm ra các điểm cần tối ưu hóa.
* Hiểu cách bảo vệ ứng dụng web toàn diện trước các mối đe dọa phổ biến trên internet.
