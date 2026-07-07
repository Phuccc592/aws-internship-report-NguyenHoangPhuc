---
title: "Worklog Tuần 1"
date: 2026-04-17
weight: 1
chapter: false
pre: " <b> 1.1. </b> "
---


### Mục tiêu tuần 1:

* Kết nối, làm quen với các thành viên trong First Cloud Journey.
* Hiểu dịch vụ AWS cơ bản, cách dùng console & CLI.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 6   | - Làm quen với các thành viên FCJ <br> - Đọc và lưu ý các nội quy, quy định tại đơn vị thực tập                                                                                             | 17/04/2026   | 17/04/2026      |
| 2   | - Tìm hiểu AWS và các loại dịch vụ <br>&emsp; + Compute <br>&emsp; + Storage <br>&emsp; + Networking <br>&emsp; + Database <br>&emsp; + ... <br>                                            | 20/04/2026   | 20/04/2026      | <https://cloudjourney.awsstudygroup.com/> |                                         | 20/04/2026   | 20/04/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Tạo AWS Free Tier account <br> - Tìm hiểu AWS Console & AWS CLI <br> - **Thực hành:** <br>&emsp; + Tạo AWS account <br>&emsp; + Cài AWS CLI & cấu hình <br> &emsp; + Cách sử dụng AWS CLI | 21/04/2026   | 21/04/2026     | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Tìm hiểu EC2 cơ bản: <br>&emsp; + Instance types <br>&emsp; + AMI <br>&emsp; + EBS <br>&emsp; + ... <br> - Các cách remote SSH vào EC2 <br> - Tìm hiểu Elastic IP   <br>                  | 22/04/2026   | 23/04/2026     | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - **Thực hành:** <br>&emsp; + Tạo EC2 instance <br>&emsp; + Kết nối SSH <br>&emsp; + Gắn EBS volume                                                                                         | 24/04/2026   | 24/04/2026      | <https://cloudjourney.awsstudygroup.com/> |


### Kết quả đạt được tuần 1:
* Kiến thức và Công cụ:
  * Nắm vững các nhóm dịch vụ chính của AWS: Compute, Storage, Networking, Database.
  * Thiết lập thành công tài khoản AWS Free Tier và làm quen với giao diện Management Console.
  * Cài đặt, cấu hình thành công AWS CLI trên máy cá nhân (Access Key, Secret Key).
Thực hành AWS EC2:
  * Khởi tạo Instance WebServer chạy Amazon Linux 2023 thành công.
  * Cấu hình Security Group mở cổng 80 (HTTP) và 22 (SSH) để cho phép truy cập từ internet.
  * Sử dụng Key Pair Phuc-Key để kết nối an toàn vào hệ thống.
Triển khai Web Server:
  * Cài đặt và kích hoạt Apache Web Server (httpd) trên EC2.
  * Cá nhân hóa trang web hiển thị nội dung: "Nguyen Hoang Phuc - AWS Web Server Live!" tại IP 100.53.10.33.
![Web Server Success](/images/WebServer.png)

