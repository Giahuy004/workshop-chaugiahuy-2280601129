---
title: "Worklog Tuần 12"
date: 2024-01-01
weight: 2
chapter: false
pre: " <b> 1.12 </b> "
---

### Mục tiêu tuần 12:
* Đánh giá end-to-end hệ thống, tối ưu hóa hóa đơn tài khoản, đóng gói sản phẩm.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | Tiến hành chạy kiểm thử tích hợp toàn bộ hệ thống từ Frontend (React/Cognito) -> API Gateway -> Lambda/SQS/Step Functions -> EC2 AI Sandbox -> DynamoDB. | 06/07/2026 | 06/07/2026 | |
| 3 | Thực hiện kiểm tra an ninh nâng cao, đọc lại log Audit từ CloudTrail và các cảnh báo từ GuardDuty để rà soát lỗ hổng. | 07/07/2026 | 07/07/2026 | |
| 4 | Cập nhật dữ liệu, biểu đồ vận hành và mã nguồn dự án lên trang tin tức hiển thị chạy bằng Hugo trên AWS Amplify để nghiệm thu công việc. | 08/07/2026 | 08/07/2026 | |
| 5 | Tiến hành buổi họp nghiệm thu nội bộ nhóm. Phân tích hóa đơn sử dụng dịch vụ AWS thực tế so với bảng tính toán chi phí ước tính ban đầu. | 09/07/2026 | 09/07/2026 | |
| 6 | Đóng gói mã nguồn dự án, xuất bản các file cấu hình kiến trúc mạng (VPC), IAM Policy, Lambda code và tài liệu hướng dẫn vận hành. | 10/07/2026 | 10/07/2026 | |
| 7 | Thực hiện xóa bỏ (Terminate) hoặc đóng băng an toàn các tài nguyên có phí cao như EC2, WAF, VPC Endpoints để tránh phát sinh chi phí ẩn sau khi kết thúc kỳ thực tập. Hoàn thiện slide báo cáo dự án nhóm gửi cho Mentor AWS. | 11/07/2026 | 11/07/2026 | |

### Kết quả đạt được tuần 12:
* Toàn bộ luồng nghiệp vụ của dự án nhóm chạy liên thông không có lỗi lớn xảy ra.
* Xác nhận hệ thống đạt các tiêu chuẩn bảo mật đám mây đề ra trong kế hoạch ban đầu.
* Trang kết quả dự án hiển thị đầy đủ, trực quan, chuyên nghiệp.
* Chi phí thực tế được tối ưu tiệt trùng về mức phí tối thiểu nhờ chính sách tắt bật hợp lý khi chạy thử.
* Bộ bàn giao dự án hoàn thiện 100%.
* Tài khoản AWS sạch sẽ an toàn.
