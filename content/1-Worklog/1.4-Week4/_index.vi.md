---
title: "Worklog Tuần 4"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.4. </b> "
---

{{% notice warning %}}
⚠️ **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả warning này.
{{% /notice %}}

### Mục tiêu tuần 4:

- Tìm hiểu về các dịch vụ lưu trữ khối Elastic Block Store (EBS), Snapshot và Elastic IP.
- Nghiên cứu cơ sở dữ liệu quan hệ Amazon RDS và phương pháp sao lưu dữ liệu tự động với AWS Backup.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                                                                            | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------ | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tìm hiểu về Amazon EBS (Elastic Block Store), các loại ổ cứng (gp2, gp3, io1, io2) và cách gắn vào EC2.                            | 11/05/2026   | 11/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Tìm hiểu cách tạo EBS Snapshot để sao lưu dữ liệu ổ cứng và khái niệm Elastic IP (IP tĩnh) gắn cho máy chủ.                        | 12/05/2026   | 12/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Tìm hiểu tổng quan về Amazon RDS (Relational Database Service), các engine phổ biến (PostgreSQL, MySQL) và cách thiết lập kết nối. | 13/05/2026   | 13/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Nghiên cứu về AWS Backup: Thiết lập lịch trình (Backup Plan) và chính sách lưu trữ tự động cho dữ liệu hệ thống.                   | 14/05/2026   | 14/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - **Thực hành Lab:** Tạo EBS volume, chụp Snapshot, gắn Elastic IP cho EC2 và cấu hình RDS kết hợp AWS Backup.                       | 15/05/2026   | 15/05/2026      | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 4:

- Nắm vững kiến thức về quản lý lưu trữ và mạng mở rộng:
  - Hiểu cách sử dụng **Amazon EBS** để cung cấp dung lượng lưu trữ bền bỉ cho EC2 Instance.
  - Biết cách tạo **Snapshot** để định kỳ sao lưu dữ liệu ổ cứng phòng ngừa rủi ro mất mát.
  - Sử dụng thành thạo **Elastic IP** để đảm bảo địa chỉ IP của máy chủ không bị thay đổi khi khởi động lại.
- Làm quen với việc vận hành cơ sở dữ liệu trên Cloud:
  - Hiểu cách triển khai và quản lý cơ sở dữ liệu quan hệ với **Amazon RDS**, giúp tách biệt tầng dữ liệu ra khỏi máy chủ ứng dụng.
  - Cấu hình thành công lịch trình sao lưu tự động bằng **AWS Backup**, đảm bảo an toàn dữ liệu cho hệ thống trước khi bước sang giai đoạn phát triển dự án thực tế.
