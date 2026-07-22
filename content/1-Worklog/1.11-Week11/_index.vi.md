---
title: "Worklog Tuần 11"
date: 2024-01-01
weight: 2
chapter: false
pre: " <b> 1.11. </b> "
---

### Mục tiêu tuần 11:
* Xây dựng Pipeline tự động, viết luật WAF chống spam, cài đặt Auto-Remediation.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | Xây dựng luồng tự động hóa CI/CD bằng AWS CodePipeline và AWS CodeBuild. Cấu hình cơ chế: Cứ ai trong nhóm push code Backend mới lên GitHub, hệ thống tự lấy về và cập nhật lên mây. | 29/06/2026 | 29/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | Triển khai AWS WAF (Web Application Firewall) để bảo vệ ứng dụng web và các cổng kết nối API Gateway. | 30/06/2026 | 30/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | Viết các luật tùy chỉnh (Custom Rules) và cơ chế chặn spam (Rate Limiting) trên AWS WAF để bảo vệ tối đa cho các cổng API. | 01/07/2026 | 01/07/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | Xây dựng bẫy tự động bằng AWS Config kết hợp EventBridge. Viết lệnh tự động khắc phục sự cố (Auto-Remediation): Ví dụ tự động khóa kín lại thư mục S3 trong 1 giây nếu có người lỡ tay mở Public. | 02/07/2026 | 02/07/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 6 | Cấu hình tính năng dọn rác nâng cao trên bộ lưu trữ S3 Server: Lập lịch tự động xóa toàn bộ file mã độc trên lưu trữ sau 7 ngày lưu trữ. | 03/07/2026 | 03/07/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | Chạy thử luồng CI/CD và bật WAF để kiểm tra khả năng phòng thủ của hệ thống. Sau khi test xong, cấu hình lại WAF về chế độ tối ưu chi phí ($0.50 thay vì $7.00 nếu bật 24/7). | 04/07/2026 | 04/07/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 11:
* Kích hoạt thành công luồng deployment tự động cho nhóm phát triển.
* Tường lửa ứng dụng được thiết lập chặn các mối nguy cơ bảo mật cơ bản.
* Chặn đứng các đợt request spam dồn dập thử nghiệm vào cổng <code>/upload</code>.
* Cơ chế tự động vá lỗ hổng cấu hình sai hoạt động chính xác theo thời gian thực.
* Đảm bảo kho lưu trữ luôn sạch và tối ưu dung lượng định kỳ.
* Hệ thống tự động hóa an toàn.
