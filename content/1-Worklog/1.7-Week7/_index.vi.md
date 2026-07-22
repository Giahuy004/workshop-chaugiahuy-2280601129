---
title: "Worklog Tuần 7"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.7. </b> "
---

### Mục tiêu tuần 7:
* Dựng VPC Sandbox, thiết lập quyền IAM OIDC, tạo repo chung và cấu hình cảnh báo ngân sách.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | Họp nhóm thống nhất kiến trúc hệ thống tổng thể. Thiết lập Tổ chức chung trên GitHub để quản lý mã nguồn. Cấu hình AWS Budgets để theo dõi các dịch vụ có phí như EC2 t3.medium, WAF, và VPC Endpoints. | 01/06/2026 | 01/06/2026 | |
| 3 | Thiết lập phân quyền tài khoản qua AWS IAM (OIDC) để chuẩn bị cấp token tạm thời cho luồng CI/CD sau này. Khởi tạo mạng cô lập Amazon VPC bao gồm các Subnets và VPC Endpoints nội bộ. | 02/06/2026 | 02/06/2026 | |
| 4 | Tạo mã khóa mã hóa trên AWS KMS để bảo vệ toàn bộ dữ liệu lưu trữ. Kích hoạt AWS CloudTrail và GuardDuty trên toàn hệ thống để ghi log audit và giám sát an ninh. | 03/06/2026 | 03/06/2026 | |
| 5 | Khởi tạo dự án Web Frontend (React) local. Cấu hình môi trường Web Admin bằng framework Hugo với giao diện theme `aafu`, tùy chỉnh mã nguồn giao diện để gắn link mã nguồn nhóm. | 04/06/2026 | 04/06/2026 | |
| 6 | Thiết lập AWS Secrets Manager để làm két sắt lưu trữ tập trung các thông tin mật mã và API Keys của dự án. Cấu hình AWS Config để theo dõi các thay đổi tài nguyên. | 05/06/2026 | 05/06/2026 | |
| 7 | Kiểm tra lại chi phí phát sinh của tuần đầu tiên dựa trên bảng giá. Đảm bảo các tài nguyên chạy thử được tối ưu và đóng đúng cấu hình. Tổng kết tài liệu tuần 1. | 06/06/2026 | 06/06/2026 | |

### Kết quả đạt được tuần 7:
* Tạo thành công GitHub Organization; kích hoạt cảnh báo chi phí ban đầu trên AWS.
* Môi trường VPC mạng lõi sẵn sàng; kết nối OIDC được cấu hình sơ bộ.
* Kích hoạt thành công dịch vụ giám sát an ninh và cấu hình xong khóa mã hóa dữ liệu KMS.
* Bộ khung Frontend và trang blog Hugo chạy thành công ở local.
* Toàn bộ Key bảo mật được lưu trữ an toàn, không bị lộ trong mã nguồn.
