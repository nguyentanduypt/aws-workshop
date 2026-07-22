---
title: "Worklog Tuần 2"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.2. </b> "
---

### Mục tiêu tuần 2:

- Hiểu rõ về kiến trúc mạng ảo (VPC) và cách bảo mật hệ thống bằng Security Groups.
- Làm quen với dịch vụ máy chủ ảo Amazon EC2 và các khái niệm cơ bản.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                                                  | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ---------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tìm hiểu về Amazon VPC, Subnet (Public/Private), Internet Gateway và Route Table.                        | 27/04/2026   | 27/04/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Tìm hiểu cơ chế bảo mật mạng cơ bản: Security Groups và Network ACLs.                                    | 28/04/2026   | 28/04/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Học lý thuyết tổng quan về Amazon EC2: Instance Types, AMI (Amazon Machine Image) và mô hình định giá.   | 29/04/2026   | 29/04/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Tìm hiểu về cách quản lý khóa bảo mật (Key Pairs) và các phương thức kết nối SSH/RDP vào EC2.            | 30/04/2026   | 30/04/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - **Thực hành:** Tạo VPC cơ bản, cấu hình Security Group và khởi tạo một EC2 Instance để kiểm tra kết nối. | 01/05/2026   | 01/05/2026      | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 2:

- Nắm vững kiến thức nền tảng về mạng ảo trên Cloud:
  - Hiểu cách hoạt động của **VPC** (Virtual Private Cloud) và cách phân chia **Subnet** để cô lập tài nguyên.
  - Phân biệt và cấu hình được **Security Groups** (tường lửa ảo ở mức instance) để kiểm soát lưu lượng ra/vào.
- Hiểu rõ cấu trúc và thông số của một máy chủ ảo **Amazon EC2**:
  - Biết cách lựa chọn **Instance Types** phù hợp với nhu cầu tính toán (CPU, RAM).
  - Hiểu về **AMI** và cách sử dụng các hệ điều hành khác nhau trên cloud.
- Hoàn thành bài thực hành cơ bản:
  - Tạo thành công một EC2 Instance trên môi trường AWS.
  - Sử dụng Key Pair để cấu hình và kết nối SSH thành công vào máy chủ ảo từ máy cá nhân.
