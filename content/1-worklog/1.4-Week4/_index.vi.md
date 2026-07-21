---
title: "Worklog Tuần 4"
date: 2026-05-12
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---
### Mục tiêu tuần 4:
* Nghiên cứu chuyên sâu dịch vụ quản lý truy cập và định danh AWS IAM.
* Hiểu cấu trúc viết chính sách phân quyền IAM Policies và cách cấp quyền tối thiểu an toàn.
* Tìm hiểu và cấu hình cơ chế xác thực đa yếu tố MFA setup bảo mật tài khoản.
* **Hands-on:** Triển khai môi trường làm việc phân quyền an toàn cho nhiều người dùng.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Nghiên cứu lý thuyết nền tảng về AWS IAM.<br> - Phân biệt các khái niệm chính: IAM Users (Người dùng), IAM Groups (Nhóm người dùng), và IAM Roles (Vai trò hệ thống). | 11/05/2026   | 11/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Học cấu trúc cú pháp của tệp IAM Policy (JSON bao gồm Effect, Action, Resource, Condition).<br> - Nghiên cứu nguyên tắc cấp quyền tối thiểu (Principle of Least Privilege). | 12/05/2026   | 12/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Tìm hiểu tầm quan trọng của bảo mật tài khoản root và tài khoản quản trị.<br> - Nghiên cứu quy trình thiết lập xác thực hai lớp (MFA setup). | 13/05/2026   | 13/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Chuẩn bị kịch bản phân quyền cho một dự án thực tế: Phân tách quyền truy cập tài nguyên EC2 và S3 Bucket cho các phòng ban kỹ thuật khác nhau. | 14/05/2026   | 14/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - **Thực hành (Hands-on):** Tạo cấu trúc nhóm làm việc bảo mật .<br> -cấu hình Policy giới hạn quyền và kích hoạt MFA thành công. | 15/05/2026   | 15/05/2026      | <https://cloudjourney.awsstudygroup.com/> |


### Kết quả đạt được tuần 4:
* Nắm vững kiến thức cốt lõi về AWS Identity & Security:
  * Phân biệt rõ ràng khi nào nên sử dụng IAM User (cho người dùng thật) và khi nào dùng IAM Role (ủy quyền tạm thời cho các dịch vụ hoặc ứng dụng kết nối với nhau).
  * Hiểu cách đọc và tự viết mã JSON để định nghĩa các IAM Policies tùy chỉnh thay vì chỉ dùng các chính sách mặc định của AWS.
* Nâng cao tư duy bảo mật hạ tầng đám mây:
  * Nhận thức rõ ràng tầm quan trọng của việc không sử dụng tài khoản Root cho các tác vụ hàng ngày.
  * Đã kích hoạt cấu hình bảo mật nâng cao MFA thành công cho tài khoản quản trị để ngăn chặn rủi ro rò rỉ mật khẩu.
* Kết quả thực hành thực tế:
  * Giả lập và cấu hình thành công môi trường làm việc đa người dùng thực tế: tạo nhóm Dev (chỉ có quyền thao tác EC2) và nhóm Tester (chỉ được đọc dữ liệu S3).
  * Kiểm thử phân quyền chính xác: Hệ thống chặn đứng hoàn toàn mọi hành vi truy cập vượt quyền hoặc can thiệp trái phép vào tài nguyên của nhóm khác.

