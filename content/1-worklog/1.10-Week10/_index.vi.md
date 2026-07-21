---
title: "Worklog Tuần 10"
date: 2026-06-22
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---
### Mục tiêu tuần 10:
* Xây dựng và hoàn thiện các trang chức năng quản lý cốt lõi của giao diện Admin.
* Tích hợp các cổng API để kết nối trực tiếp với dữ liệu thực tế lưu trữ trên Amazon DynamoDB.
* Tối ưu hóa luồng nghiệp vụ tạo tài khoản người dùng trực tiếp từ trang quản trị.
* Triển khai, cấu hình và kiểm thử hệ thống giao diện sau khi phân phối qua mạng lưới Amazon CloudFront.
### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Xây dựng chi tiết các trang quản lý chính: Bệnh nhân, Bác sĩ, Nhân sự y tế, Khoa/Chuyên khoa, Dịch vụ, Thuốc và Tài khoản người dùng. | 22/06/2026   | 22/06/2026      |               |
| 3   | - Tích hợp kết nối API backend cho các màn hình quản lý, thực hiện gọi và hiển thị dữ liệu thật được truy vấn từ cơ sở dữ liệu Amazon DynamoDB. | 23/06/2026   | 23/06/2026      |         |
| 4   | - Hoàn thiện mã nguồn chức năng tạo tài khoản từ Admin: cấu hình tài khoản được tạo tự động kích hoạt trạng thái "Confirmed" ngay lập tức, loại bỏ bước chờ mã OTP hoặc xét duyệt. | 24/06/2026   | 24/06/2026      |    |
| 5   | - Bổ sung logic xử lý phân trang nâng cao và thanh tìm kiếm thời gian thực cho các bảng dữ liệu.<br> - Điều chỉnh Dashboard Admin tập trung vào số liệu bệnh viện (lịch hẹn, hóa đơn, phản hồi), loại bỏ các chỉ số hạ tầng AWS không cần thiết cho Admin. | 25/06/2026   | 25/06/2026      |            |
| 6   | - **Thực hành (Hands-on):** Kết nối thành công dữ liệu động từ DynamoDB ra trang chủ công cộng (Public Homepage) cho các mục chuyên khoa, bác sĩ nổi bật.<br> - Deploy ứng dụng lên CloudFront, tiến hành kiểm thử và xử lý các lỗi cache hệ thống, lỗi định tuyến (Route) và lỗi Token khi refresh trang. | 26/06/2026   | 26/06/2026      |                     |

### Kết quả đạt được tuần 10:
* Chuyển đổi thành công dữ liệu số từ Hệ thống Đám mây:
  * Thay thế toàn bộ dữ liệu mẫu (Mock data) bằng dữ liệu động thực tế, giúp các màn hình quản trị hiển thị chính xác trạng thái từ DynamoDB.
  * Tối ưu hóa trải nghiệm vận hành hành chính nhờ cơ chế tạo tài khoản trực tiếp (Direct Confirmed Account Creation Setup), tăng hiệu suất làm việc của nhân viên bệnh viện.
* Ổn định hạ tầng mạng phân phối Frontend:
  * Cấu hình Dashboard tập trung hoàn toàn vào chỉ số kinh doanh y tế (Lịch hẹn, Hóa đơn, Phản hồi) giúp thông tin mạch lạc, rõ ràng.
  * Khắc phục triệt để lỗi mất dữ liệu khi tải lại trang (Hard Refresh) và xử lý bất đồng bộ định tuyến trên môi trường CDN Amazon CloudFront.

