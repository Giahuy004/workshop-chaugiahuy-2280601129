---
title: "Worklog Tuần 4"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.4. </b> "
---

### Mục tiêu tuần 4:
* Tự tay thiết kế một kiến trúc mạng an toàn độc lập trên đám mây.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | Nghiên cứu Amazon VPC (Virtual Private Cloud). Tìm hiểu về IP Subnetting (CIDR), Public Subnet, Private Subnet. | 11/05/2026 | 11/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | Thực hành cấu hình Internet Gateway (IGW), NAT Gateway, và các Bảng định tuyến (Route Tables) cho VPC vừa tạo. | 12/05/2026 | 12/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | Tìm hiểu bộ cân bằng tải Application Load Balancer (ALB). Tạo Target Group gồm 2 máy chủ EC2 nằm ở 2 AZs khác nhau và gắn vào ALB. | 13/05/2026 | 13/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | Nghiên cứu dịch vụ phân giải tên miền Amazon Route 53 và mạng lưới phân phối nội dung Amazon CloudFront (CDN). | 14/05/2026 | 14/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 6 | Bài Lab thực tế lớn: Triển khai mô hình 2 lớp (2-Tier Architecture). Đưa toàn bộ mã nguồn Frontend lên S3/CloudFront, đưa phần mã nguồn Backend và Database RDS vào vùng Private Subnet an toàn bên trong VPC. | 15/05/2026 | 15/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | Tìm hiểu và phân biệt cách hoạt động kiểm soát traffic của Security Groups (Stateful) và Network ACLs (Stateless). Khắc phục một số lỗi mất kết nối mạng thường gặp trong bài Lab. | 16/05/2026 | 16/05/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 4:
* Vẽ sơ đồ phác thảo một hệ thống mạng gồm 1 VPC, 2 Public Subnets và 2 Private Subnets nằm trên 2 Availability Zones khác nhau nhằm đảm bảo tính sẵn sàng cao (High Availability).
* Cấu hình giúp cho máy chủ nằm trong Private Subnet không thể truy cập từ internet nhưng vẫn có thể đi ra ngoài internet để tải bản cập nhật qua NAT Gateway.
* Khi truy cập vào DNS của ALB, lưu lượng truy cập được phân phối đều (Round-robin) sang cả 2 máy chủ thành công.
* Hiểu cách CloudFront cache các file tĩnh từ S3 về các Edge Locations gần người dùng nhất để tăng tốc độ tải trang web Frontend.
* Hệ thống chạy liên thông mượt mà; bảo mật được lớp cơ sở dữ liệu cô lập hoàn toàn khỏi internet công cộng.
* Thành thạo kỹ năng debug lỗi liên quan đến Network và Firewall trên AWS.
