---
title: "Workshop"
date: 2024-01-01
weight: 5
chapter: false
pre: " <b> 5. </b> "
---

# Xây dựng Hạ tầng Mạng và CI/CD Tối ưu Chi phí cho Nền tảng E-commerce Thời trang

#### Tổng quan

**AWS VPC Endpoints và PrivateLink** cung cấp kết nối riêng tư, bảo mật trực tiếp từ các tài nguyên trong VPC (như máy chủ ứng dụng Spring Boot ở Private Subnet) đến các dịch vụ AWS mà không cần thông qua Internet công cộng, giúp loại bỏ hoàn toàn chi phí NAT Gateway đắt đỏ.

Trong phần Workshop này, bạn sẽ học cách thiết lập và cấu hình hạ tầng mạng Multi-AZ, tối ưu hóa đường truyền dữ liệu cho hệ thống thương mại điện tử thời trang (_Fashion E-commerce Platform_):

- **Gateway Endpoint** - Được sử dụng để định tuyến lưu lượng truy cập từ VPC đến **Amazon S3** (lưu trữ hình ảnh sản phẩm) bằng địa chỉ IP nội bộ thông qua bảng định tuyến (Route Tables).
- **Interface Endpoint** - Được sử dụng cho các dịch vụ CI/CD (như AWS CodeDeploy) để tự động hóa quy trình phát hành mã nguồn vào các máy chủ backend trong Private Subnet một cách bảo mật tuyệt đối.

#### Nội dung

1. [Giới thiệu](5.1-Workshop-overview)
2. [Các bước chuẩn bị](5.2-Prerequiste/)
3. [Tối ưu hạ tầng mạng](5.3-S3-vpc/)
4. [Thiết lập Backend & Data Layer](5.4-S3-onprem/)
5. [CI/CD Tự động hóa](5.5-Policy/)
6. [Tối ưu hóa chi phí & Giám sát](5.6-Cleanup/)
