---
title: "Worklog Tuần 6"
date: 2026-05-25
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---
### Mục tiêu tuần 6:
* Nghiên cứu các dịch vụ tích hợp và truyền thông điệp ứng dụng  bao gồm dịch vụ hàng đợi Amazon SQS và dịch vụ thông báo Amazon SNS.
* Tìm hiểu giải pháp định tuyến và quản lý sự kiện thời gian thực thông qua Amazon EventBridge.
* Nghiên cứu công cụ thiết kế luồng công việc tự động hóa nâng cao Step Functions.
* **Hands-on:** Triển khai hoàn chỉnh hệ thống kiến trúc hướng sự kiện phi tập trung.
### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tìm hiểu lý thuyết về tích hợp ứng dụng và truyền tin nhắn.<br> - Nghiên cứu dịch vụ gửi nhận tin dạng hàng đợi Amazon SQS và mô hình Pub/Sub của Amazon SNS. | 25/05/2026   | 25/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Nghiên cứu Amazon EventBridge: cách thiết lập các Event Buses, viết quy tắc định tuyến để tự động hóa phát hiện thay đổi trạng thái tài nguyên hệ thống. | 26/05/2026       | 26/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Tìm hiểu AWS Step Functions: học cách thiết kế luồng công việc dưới dạng máy trạng thái trực quan, xử lý logic phân nhánh phức tạp. | 27/05/2026   | 27/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Thiết kế kịch bản liên kết lỏng: Tạo liên kết SNS Topic đẩy dữ liệu tự động về SQS Queue, cấu hình quyền hạn cho các dịch vụ giao tiếp an toàn. | 28/05/2026   | 28/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - **Thực hành (Hands-on):** Xây dựng kiến trúc hướng sự kiện hoàn chỉnh.<br> - Chạy mô hình giả lập, kiểm tra luồng dữ liệu tự động kích hoạt Step Functions và SNS gửi email thông báo thành công. | 29/05/2026   | 31/05/2026      | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 6:
* Làm chủ tư duy kiến trúc hướng sự kiện (Event-driven):
  * Hiểu rõ ưu điểm của việc thiết kế hệ thống liên kết lỏng (Loose Coupling), giúp các dịch vụ hoạt động độc lập, tăng khả năng chịu lỗi và không làm nghẽn hệ thống khi quá tải.
  * Phân biệt và phối hợp thành thạo mô hình quạt ra (Fan-out pattern) bằng cách kết hợp giữa SNS và SQS để phân phối một thông điệp đến nhiều nơi xử lý khác nhau cùng lúc.
* Tự động hóa luồng công việc phức tạp:
  * Thành thạo cách sử dụng EventBridge để lắng nghe sự kiện từ các dịch vụ AWS và chuyển hướng chính xác đến các mục tiêu xử lý backend thích hợp.
  * Sử dụng thành thạo cấu trúc Amazon States Language (ASL) trong Step Functions để quản lý trạng thái, bắt lỗi (Error handling) và điều phối các tác vụ tự động hóa một cách trực quan.
* Kết quả thực hành Hands-on:
  * Triển khai thành công hạ tầng Event-driven hoàn chỉnh. Luồng dữ liệu chạy mượt mà: Sự kiện được kích hoạt EventBridge định tuyến Step Functions vận hành chuỗi logic phân nhánh  SNS gửi email thông báo trạng thái tức thời cho người quản trị.

