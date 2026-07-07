---
title: "Worklog Tuần 2"
date: 2026-04-27
weight: 1
chapter: false
pre: " <b> 1.2. </b> "
---

### Mục tiêu tuần 2:

* Tìm hiểu lý thuyết và cách thức hoạt động của các dịch vụ lưu trữ (Storage) và cơ sở dữ liệu (Databases) cốt lõi trên AWS.
* Thực hành cấu hình vòng đời lưu trữ, quản lý ổ đĩa, thiết lập hệ quản trị cơ sở dữ liệu quan hệ và xây dựng ứng dụng hoàn chỉnh.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Nghiên cứu về Amazon S3 buckets <br> Tìm hiểu cấu hình và thiết lập chính sách vòng đời dữ liệu (Lifecycle policies) trên S3 | 27/04/2026 | 27/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Tìm hiểu dịch vụ lưu trữ khối Amazon EBS <br> - Phân tích cách thức quản lý EBS volumes và cơ chế sao lưu dữ liệu bằng Snapshot | 28/04/2026 | 28/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Tìm hiểu dịch vụ cơ sở dữ liệu quan hệ Amazon RDS <br> - Nghiên cứu quy trình khởi tạo, thiết lập cấu hình và quản trị cơ sở dữ liệu (RDS setup and management) | 29/04/2026 | 29/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - **Thực hành (Hands-on):** Khởi tạo cấu phần lưu trữ S3 và kết nối phân quyền <br> - Thiết kế hệ thống tải tập tin lên đám mây (Build file upload system) | 30/04/2026 | 01/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - **Thực hành (Hands-on):** Khởi tạo và liên kết instance cơ sở dữ liệu RDS <br> - Hoàn thiện mã nguồn ứng dụng, kết nối đồng bộ giữa lớp lưu trữ file và lớp dữ liệu | 01/04/2026 | 02/04/2026 | <https://cloudjourney.awsstudygroup.com/> |


### Kết quả đạt được tuần 2:

* Nắm vững kiến thức nền tảng và cơ chế vận hành của các nhóm dịch vụ:
  * **Amazon S3:** Lưu trữ đối tượng (Object Storage), cách phân chia quyền truy cập và tối ưu chi phí lưu trữ dài hạn bằng quy tắc vòng đời (Lifecycle policies).
  * **Amazon EBS:** Lưu trữ khối (Block Storage) gắn liền với máy chủ ảo EC2, cách tăng dung lượng ổ đĩa trực tiếp và tạo bản sao lưu an toàn (Snapshot).
  * **Amazon RDS:** Cách vận hành một hệ quản trị cơ sở dữ liệu đám mây tự động hóa hoàn toàn các tác vụ vá lỗi, backup và mở rộng quy mô.

* Đã thực hành khởi tạo thành công các S3 Buckets bảo mật và thiết lập các chính sách tự động chuyển đổi lớp lưu trữ (Standard sang Glacier) hoặc tự động xóa tệp tin cũ theo chu kỳ.

* Làm chủ các thao tác quản trị ổ đĩa cứng đám mây bao gồm: Tạo mới EBS volume, gắn (attach) trực tiếp vào máy chủ Linux/Windows và thực thi các lệnh mount phân vùng trên hệ điều hành.

* Triển khai thiết lập thành công Instance cơ sở dữ liệu Amazon RDS (MySQL/SQL Server), làm chủ quy trình cấu hình Security Group để cho phép phân quyền truy cập từ các dải IP mạng nội bộ.

* **Hoàn thành bài thực hành Hands-on:** Xây dựng và triển khai thành công mã nguồn ứng dụng quản lý tải tập tin (File upload system), lưu giữ toàn bộ dữ liệu metadata trong cơ sở dữ liệu quan hệ RDS và đẩy toàn bộ tệp tin đa phương tiện lưu trữ an toàn trên Amazon S3.
* ...


