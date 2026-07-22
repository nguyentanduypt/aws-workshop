---
title: "Worklog Tuần 3"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.3. </b> "
---

{{% notice warning %}}
⚠️ **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả warning này.
{{% /notice %}}

### Mục tiêu tuần 3:

- Khám phá và sử dụng dịch vụ lưu trữ đối tượng Amazon S3.
- Thực hành nâng cao với Amazon EC2 và quản lý vòng đời tài nguyên trên hệ thống.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                                                                            | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------ | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tìm hiểu tổng quan về Amazon S3, khái niệm Bucket, Object và cơ chế phân quyền truy cập (Bucket Policy, ACL).                      | 04/05/2026   | 04/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Tìm hiểu về các tính năng quản lý nâng cao của S3: Versioning (quản lý phiên bản) và Lifecycle Rules (vòng đời dữ liệu).           | 05/05/2026   | 05/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Thực hành tạo S3 Bucket và ứng dụng lưu trữ file tĩnh (hình ảnh sản phẩm, tài liệu) phục vụ cho dự án E-commerce.                  | 06/05/2026   | 06/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Thực hành EC2 nâng cao: Cấu hình User Data để tự động chạy script khi khởi động instance, tìm hiểu về AMI tùy chỉnh.               | 07/05/2026   | 07/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - Thực hành quản lý tài nguyên EC2: Kiểm tra trạng thái, thực hiện stop/start, resize instance type và theo dõi log hệ thống cơ bản. | 08/05/2026   | 08/05/2026      | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 3:

- Nắm vững kiến thức và cách vận hành dịch vụ **Amazon S3**:
  - Biết cách tạo lập, quản lý S3 Bucket và cấu hình quyền truy cập an toàn cho file.
  - Hiểu cách ứng dụng S3 để lưu trữ các tài nguyên tĩnh (hình ảnh, media) cho ứng dụng Web.
- Thành thạo các thao tác nâng cao với **Amazon EC2**:
  - Biết cách sử dụng **User Data** để tự động hóa quá trình cài đặt phần mềm khi khởi tạo máy chủ.
  - Quản lý hiệu quả vòng đời tài nguyên máy chủ ảo (tối ưu chi phí bằng cách tắt khi không sử dụng).
- Tích lũy thêm kỹ năng cấu hình lưu trữ và tính toán, chuẩn bị dữ liệu nền tảng cho việc phát triển các module tiếp theo của hệ thống.
