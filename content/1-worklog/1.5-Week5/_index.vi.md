---
title: "Worklog Tuần 5"
date: 2026-05-18
weight: 1
chapter: false
pre: " <b> 1.5. </b> "
---
### Mục tiêu tuần 5:
* Nghiên cứu kiến trúc phi máy chủ  và cách triển khai các hàm xử lý mã nguồn độc lập bằng Lambda cùng hệ thống kích hoạt .
* Tìm hiểu và cấu hình cổng kết nối API Gateway để tiếp nhận, điều hướng các yêu cầu HTTP/HTTPS.
* Nghiên cứu cơ sở dữ liệu NoSQL DynamoDB và các thao tác quản lý dữ liệu tối ưu.
* **Hands-on:** Xây dựng hoàn chỉnh hệ thống quản lý dữ liệu thông qua ứng dụng REST API backend phi máy chủ.
### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tìm hiểu khái niệm Serverless và mô hình kiến trúc Event-driven.<br> - Nghiên cứu dịch vụ AWS Lambda: vòng đời của hàm, cấu hình bộ nhớ và cách liên kết các Triggers tự động. | 18/05/2026   | 18/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Nghiên cứu Amazon API Gateway: thiết kế các HTTP/REST endpoints, phương thức định tuyến (GET, POST, PUT, DELETE) và tích hợp trực tiếp với AWS Lambda. | 19/05/2026   | 19/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Tìm hiểu Amazon DynamoDB: mô hình dữ liệu NoSQL, cách chọn Partition Key (PK) và Sort Key (SK).<br> - Nghiên cứu các phương thức thao tác dữ liệu: Query, Scan, PutItem, UpdateItem. | 20/05/2026   | 20/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Thiết kế sơ đồ luồng dữ liệu cho ứng dụng Backend xử lý các tác vụ CRUD (Create, Read, Update, Delete).<br> - Chuẩn bị môi trường viết mã nguồn xử lý cho các hàm Lambda bằng JavaScript/Node.js. | 21/05/2026   | 21/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - **Thực hành (Hands-on):** Triển khai ứng dụng REST API backend hoàn chỉnh kết hợp API Gateway, AWS Lambda và cơ sở dữ liệu DynamoDB.<br> - Kiểm thử các API bằng Postman thành công. | 22/05/2026   | 22/05/2026      | <https://cloudjourney.awsstudygroup.com/> |


### Kết quả đạt được tuần 5:
* Làm chủ tư duy phát triển Serverless:
  * Hiểu rõ ưu điểm của mô hình Serverless: tự động mở rộng theo lượng truy cập, tối ưu chi phí (chỉ trả tiền khi mã nguồn chạy) và giảm bớt gánh nặng quản lý máy chủ.
  * Thành thạo cách cấu hình biến môi trường, phân quyền IAM Role an toàn cho phép hàm Lambda có quyền đọc/ghi dữ liệu vào DynamoDB.
* Xây dựng và tích hợp API chuẩn công nghiệp:
  * Nắm vững cách thiết lập API Gateway để tiếp nhận dữ liệu từ Client, xử lý CORS (Cross-Origin Resource Sharing) và chuyển tiếp payload một cách chính xác đến backend.
  * Hiểu sự khác biệt về hiệu năng và chi phí giữa hai phương thức đọc dữ liệu Query (tối ưu) và Scan (tốn tài nguyên) trong DynamoDB.
* Kết quả thực hành Hands-on:
  * Xây dựng độc lập hệ thống REST API backend phi máy chủ hoàn chỉnh đạt độ ổn định cao.
  * Ứng dụng thực hiện mượt mà chuỗi tác vụ: Client gửi yêu cầu thông qua API Gateway. Kích hoạt AWS Lambda xử lý logic Truy vấn hoặc lưu trữ dữ liệu trực tiếp vào các bảng Amazon DynamoDB một cách an toàn. 


