---
title: "Worklog Tuần 7"
date: 2026-06-01
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---
### Mục tiêu tuần 7:
* Nghiên cứu các khái niệm cơ bản về nền tảng ảo hóa container Docker basics.
* Tìm hiểu và làm quen với kho lưu trữ hình ảnh container đám mây Amazon Elastic Container Registry.
* Nghiên cứu dịch vụ điều phối và quản lý cụm container nâng cao Amazon Elastic Container Service.
* **Hands-on:** Thực hiện đóng gói và triển khai một ứng dụng web hoàn chỉnh chạy trên môi trường container.
### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tìm hiểu kiến thức nền tảng về Docker: cấu trúc tệp Dockerfile, Docker Image, và Docker Container. | 01/06/2026   | 01/06/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 3   |- Thực hành viết Dockerfile đóng gói ứng dụng và build image ở máy cục bộ. | 02/06/2026   | 02/06/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Nghiên cứu Amazon ECR, thực hành cấu hình AWS CLI, đăng nhập mật khẩu bảo mật và đẩy image từ local lên kho ECR. | 03/06/2026   | 03/06/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Tìm hiểu kiến trúc điều phối Amazon ECS (clusters, services) và phân biệt cơ chế vận hành giữa AWS Fargate với EC2. | 04/06/2026   | 04/06/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - Học cách định nghĩa cấu trúc Task Definitions trong ECS (CPU, RAM, Image URL, Port mapping) và thiết lập cấu hình mạng kết nối. | 05/06/2026   | 06/06/2026      | <https://cloudjourney.awsstudygroup.com/> |


### Kết quả đạt được tuần 7:
* Làm chủ tư duy ảo hóa và quản lý Container:
  * Hiểu rõ lợi ích vượt trội của Container hóa: giúp tối ưu hóa dung lượng phần cứng, đảm bảo môi trường chạy mã nguồn đồng nhất giữa máy local của lập trình viên và môi trường triển khai thực tế trên đám mây.
  * Viết thành thạo cấu trúc tệp Dockerfile chuẩn hóa, tối ưu dung lượng layer của các image ứng dụng web.
* Thành thạo quy trình điều phối container trên đám mây:
  * Nắm vững quy trình quản lý vòng đời Image thông qua Amazon ECR registry độc lập.
  * Làm chủ cơ chế vận hành cụm dịch vụ của Amazon ECS: biết cách cấu hình Task Definition để làm bản thiết kế chạy máy chủ và quản lý trạng thái hoạt động tự động thông qua ECS Service.
* Kết quả thực hành Hands-on:
  * Triển khai thành công ứng dụng Containerized web app chạy ổn định trên AWS Fargate mà không cần tự tay quản lý, vá lỗi hệ điều hành hay vận hành các máy chủ ảo EC2 nền tảng.
  * Hệ thống tự động kéo image từ ECR, khởi chạy luồng xử lý và phân phối lưu lượng mạng truy cập một cách mượt mà.

