---
title: "Worklog Tuần 10"
date: 2024-01-01
weight: 2
chapter: false
pre: " <b> 1.10. </b> "
---

### Mục tiêu tuần 10:
* Dựng bảng DynamoDB, khởi tạo máy ảo t3.medium chạy AI, cài đặt CloudWatch giám sát.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | Tạo cơ sở dữ liệu NoSQL Amazon DynamoDB tốc độ cao. Thiết kế cấu trúc bảng dữ liệu để lưu trữ thông tin lịch sử quét và phân tích của người dùng. | 22/06/2026 | 22/06/2026 | |
| 3 | Cấu hình máy ảo Amazon EC2 (hoặc ECS) sử dụng dòng chip `t3.medium` đặt bên trong môi trường mạng Sandbox cô lập hoàn toàn (không có cổng Internet) để chạy mô hình AI. | 23/06/2026 | 23/06/2026 | |
| 4 | Thiết lập kết nối nội bộ từ Backend sang máy chủ EC2 AI thông qua VPC Endpoints để đảm bảo dữ liệu truyền tải nội bộ an toàn. | 24/06/2026 | 24/06/2026 | |
| 5 | Cấu hình Amazon CloudWatch để xem log tiến trình chạy của mô hình AI và đo đạc lưu lượng mạng phân tích hệ thống. | 25/06/2026 | 25/06/2026 | |
| 6 | Kết nối kho lưu trữ Git chứa mã nguồn Hugo của nhóm với dịch vụ AWS Amplify để tự động host trang web báo cáo an ninh mạng. Thay thế các biểu tượng mặc định của trang web. | 26/06/2026 | 26/06/2026 | |
| 7 | Thực hiện chính sách tối ưu chi phí: Tắt máy ảo EC2 `t3.medium` và giảm tải VPC Endpoints ngay sau khi phiên test kết thúc để hạ chi phí từ mức $33.00/tháng xuống còn $2.50. | 27/06/2026 | 27/06/2026 | |

### Kết quả đạt được tuần 10:
* Khởi tạo xong bảng lưu trữ dữ liệu trên DynamoDB sẵn sàng nhận ghi log dữ liệu.
* Máy chủ AI được khởi tạo thành công bên trong vùng mạng an toàn.
* Đường truyền nội bộ giữa các dịch vụ thông suốt, không đi qua internet công cộng.
* Các chỉ số hiệu năng và log ứng dụng AI hiển thị trực quan trên CloudWatch.
* Trang web Web Admin chạy trực tuyến ổn định trên môi trường AWS Amplify.
* Chi phí vận hành máy chủ AI được tối ưu triệt để đúng kế hoạch đề ra.
