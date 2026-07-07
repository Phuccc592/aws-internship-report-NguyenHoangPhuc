---
title: "Worklog Tuần 8"
date: 2026-06-08
weight: 1
chapter: false
pre: " <b> 1.8. </b> "
---
### Mục tiêu tuần 8:
* Nghiên cứu dịch vụ giám sát tài nguyên, thu thập chỉ số và thiết lập cảnh báo tự động thông qua Amazon CloudWatch.
* Tìm hiểu giải pháp ghi nhật ký kiểm toán, theo dõi lịch sử hoạt động và bảo mật tài khoản với AWS CloudTrail.
* Nghiên cứu cơ chế truy vết phân tán để phân tích và tối ưu hóa hiệu năng ứng dụng bằng AWS X-Ray.
* **Hands-on:** Thực hiện thiết lập hệ thống giám sát và quản lý nhật ký tập trung toàn diện.
### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tìm hiểu kiến thức nền tảng về quan sát hệ thống: các khái niệm Metrics, Logs, và Alarms.<br> - Nghiên cứu Amazon CloudWatch để thu thập dữ liệu hiệu năng của EC2, Lambda. | 08/06/2026   | 08/06/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Học cách tạo CloudWatch Alarms để gửi thông báo tự động qua SNS khi tài nguyên vượt ngưỡng.<br> - Cấu hình CloudWatch Logs thu thập nhật ký từ ứng dụng. | 09/06/2026   | 09/06/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Nghiên cứu dịch vụ AWS CloudTrail: theo dõi và kiểm toán các hành động gọi API trong hệ thống, cấu hình lưu trữ log bảo mật vào S3 bucket. | 10/06/2026   | 10/06/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Tìm hiểu AWS X-Ray distributed tracing: tích hợp SDK vào mã nguồn ứng dụng để vẽ bản đồ dịch vụ và phát hiện các điểm nghẽn cổ chai. | 11/06/2026   | 11/06/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - **Thực hành (Hands-on):** Xây dựng hệ thống giám sát toàn diện liên kết CloudWatch, CloudTrail và X-Ray.<br> - Giả lập tải cao, kiểm tra luồng phát tín hiệu cảnh báo thành công. | 12/06/2026   | 12/06/2026      | <https://cloudjourney.awsstudygroup.com/> |


### Kết quả đạt được tuần 8:
* Làm chủ tư duy quan sát và tối ưu vận hành hệ thống:
  * Hiểu rõ tầm quan trọng của việc chủ động giám sát trạng thái sức khỏe tài nguyên trên cloud thay vì đợi hệ thống gặp sự cố mới xử lý.
  * Thành thạo kỹ năng phân tích lỗi ứng dụng thông qua việc đọc log tập trung và phân tích cấu trúc log kiểm toán bảo mật.
* Thành thạo các công cụ giám sát tiêu chuẩn đám mây:
  * Biết cách thiết lập hệ thống cảnh báo tự động thời gian thực bằng CloudWatch kết hợp SNS giúp người quản trị xử lý sự cố ngay lập tức.
  * Làm chủ cơ chế theo dõi luồng đi của request thông qua microservices bằng X-Ray, dễ dàng xác định chính xác hàm Lambda hay truy vấn DynamoDB nào đang chạy chậm.
* Kết quả thực hành Hands-on:
  * Triển khai độc lập thành công một hạ tầng giám sát toàn diện. Hệ thống đảm bảo tính minh bạch cao: mọi hành vi thay đổi cấu trúc đều bị CloudTrail ghi lại, mọi chỉ số tài nguyên được CloudWatch theo dõi, và các luồng xử lý ứng dụng được X-Ray truy vết trực quan.

