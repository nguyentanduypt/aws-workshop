---
title: "Worklog Tuần 11"
date: 2024-01-01
weight: 2
chapter: false
pre: " <b> 1.11. </b> "
---

### Mục tiêu tuần 11:

- Triển khai hệ thống (Deploy) lên môi trường thực tế trên AWS.
- Cấu hình quy trình CI/CD cơ bản để tự động hóa việc build và deploy khi có mã nguồn mới đẩy lên GitHub.
- Vận hành hoàn chỉnh toàn bộ hệ thống (Frontend + Backend + Database + Cache) trên môi trường Cloud thật.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                                                                                      | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ---------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | -------------- |
| 2   | - Chuẩn bị cơ sở hạ tầng trên AWS (Cấu hình EC2 Instance, phân quyền Security Groups, kết nối Amazon RDS và ElastiCache).                      | 29/06/2026   | 29/06/2026      |                |
| 3   | - Đưa các Docker Image đã được "container hóa" từ tuần trước lên môi trường AWS và tiến hành cấu hình biến môi trường (Environment Variables). | 30/06/2026   | 30/06/2026      |                |
| 4   | - Nghiên cứu và cấu hình quy trình **CI/CD** để tự động hóa quá trình build và deploy khi có code mới cập nhật lên GitHub.                     | 01/07/2026   | 01/07/2026      |                |
| 5   | - Kiểm tra, tinh chỉnh kết nối mạng giữa các thành phần trên Cloud (đảm bảo Frontend gọi được Backend, Backend kết nối tốt với RDS và Redis).  | 02/07/2026   | 02/07/2026      |                |
| 6   | - Vận hành và kiểm thử toàn diện hệ thống ở trạng thái hoàn chỉnh (**Frontend + Backend + Database + Cache**) trên môi trường thật.            | 03/07/2026   | 03/07/2026      |                |

### Kết quả đạt được tuần 11:

- Triển khai thành công ứng dụng E-commerce lên môi trường Cloud AWS, hệ thống hoạt động ổn định và có khả năng truy cập công khai từ bên ngoài.
- Thiết lập thành công hệ thống tự động hóa **CI/CD** qua AWS CodePipeline, giúp tiết kiệm thời gian cập nhật mã nguồn lên server.
- Hoàn thiện việc kết nối đồng bộ toàn bộ 4 thành phần cốt lõi (**Frontend, Backend, Database, Cache**) trên nền tảng đám mây.
