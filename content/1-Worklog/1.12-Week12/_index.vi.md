---
title: "Worklog Tuần 12"
date: 2026-07-06
weight: 2
chapter: false
pre: " <b> 1.12 </b> "
---
### Mục tiêu tuần 12:
* Thực hiện chuỗi kiểm thử tự động và thủ công toàn diện (End-to-End Testing) trên môi trường CloudFront thực tế.
* Tối ưu hóa, tinh chỉnh các lỗi thiết kế giao diện UI/UX cuối cùng trước khi đóng gói sản phẩm.
* Kiểm tra xác thực tính đúng đắn của dữ liệu thanh toán và tích hợp quản trị chuỗi khối Amazon Managed Blockchain (AMB).
* Tổng hợp tài liệu, hình ảnh bằng chứng và hoàn thiện phần nội dung báo cáo phân công công việc cá nhân.
### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Kiểm thử toàn bộ các kịch bản tương tác người dùng của vai trò Admin trực tiếp trên môi trường CDN CloudFront (đăng nhập, xem dashboard, phân trang, truy vấn lọc dữ liệu và CRUD). | 06/07/2026   | 06/07/2026      |           |
| 3   | - Rà soát và sửa đổi các lỗi UI/UX: xử lý bảng tràn màn hình (Responsive table), lệch nút hành động, form không tự reset dữ liệu sau khi lưu, tối ưu hóa các thông báo modal thông tin. | 07/07/2026   | 07/07/2026      |   |
| 4   | - Kiểm tra luồng dữ liệu quản trị tài chính và theo dõi sổ cái chuỗi khối: xác minh Admin xem được trạng thái hóa đơn thanh toán hành chính và mã băm trạng thái hồ sơ tổng quan trên AMB. | 08/07/2026   | 08/07/2026      |                  |
| 5   | - Ghi nhận chi tiết danh mục các giới hạn hệ thống của phân hệ Admin (Admin không xử lý chuyên môn y tế, không can thiệp thay đổi cấu trúc mã hóa giao dịch Blockchain của Bác sĩ/Bệnh nhân). | 09/07/2026   | 09/07/2026      |               |
| 6   | - **Thực hành (Hands-on):** Chụp ảnh minh chứng tất cả các màn hình chức năng Admin làm tài liệu đính kèm báo cáo.<br> - Tổng hợp, biên soạn phần nội dung mô tả công việc của thành viên **Hoàng Phúc** (vai trò phát triển Web Admin, đồng bộ API, thiết kế UI, xử lý dữ liệu và kiểm thử hệ thống). | 10/07/2026   | 10/07/2026      |  |


### Kết quả đạt được tuần 12:
* Đảm bảo chất lượng sản phẩm đầu ra ở mức cao nhất:
  * Hệ thống web quản trị Admin đạt độ ổn định tuyệt đối sau chuỗi kiểm thử nghiêm ngặt trên môi trường CloudFront, không phát sinh lỗi hiển thị hay tràn khung giao diện trên nhiều độ phân giải màn hình.
  * Tích hợp thành công giải pháp theo dõi giao dịch thanh toán và giám sát mã băm bảo mật (Blockchain hashes) từ hạ tầng Amazon Managed Blockchain một cách an toàn và minh bạch.
* Hoàn thiện hồ sơ nghiệm thu kỹ thuật:
  * Thu thập đầy đủ kho dữ liệu hình ảnh minh chứng thực tế cho báo cáo đồ án.
  * Hoàn thành xuất sắc phần báo cáo đóng góp cá nhân của Hoàng Phúc, làm nổi bật vai trò cốt lõi trong việc xây dựng kiến trúc web quản trị hệ thống y tế thông minh phi máy chủ.
---
**Trong trang này** bạn sẽ cần giới thiệu worklog của bạn **như thế nào**? Bạn hoàn thành chương trình trong vòng **bao nhiêu tuần**? Bạn **đã làm gì** trong các tuần đó?

Nhật ký công việc (Worklog) này ghi lại toàn bộ quá trình học tập, nghiên cứu kiến trúc đám mây và phát triển ứng dụng của tôi trong suốt giai đoạn vừa qua. Chương trình được triển khai và hoàn thành liên tục trong vòng **12 tuần**. 

Trong suốt thời gian này, lộ trình làm việc của tôi được chia làm hai giai đoạn chính: **4 tuần đầu** tập trung làm quen với hạ tầng mạng và máy chủ ảo cơ bản của AWS; **4 tuần giữa** đi sâu vào các giải pháp nâng cao như Serverless, kiến trúc hướng sự kiện (Event-driven), Container và hệ thống giám sát; **4 tuần cuối** tập trung hoàn toàn vào việc phân tích, thiết kế, tối ưu UI/UX và tích hợp API cho phân hệ Admin quản trị hệ thống bệnh viện thông minh.

Dưới đây là sơ đồ tóm tắt nội dung công việc chi tiết theo từng tuần:

**Tuần 1:** [Làm quen với AWS, IAM, EC2 và các dịch vụ cơ bản trong AWS](1.1-week1/)

**Tuần 2:** [Nghiên cứu kiến trúc VPC mạng mở rộng và hệ thống lưu trữ Amazon S3 / EBS](1.2-week2/)

**Tuần 3:** [Thiết lập hạ tầng mạng có tính sẵn sàng cao với ALB và Auto Scaling Group](1.3-week3/)

**Tuần 4:** [Tìm hiểu và cấu hình hệ thống cơ sở dữ liệu Amazon RDS và dịch vụ lưu trữ EFS](1.4-week4/)

**Tuần 5:** [Phát triển ứng dụng phi máy chủ Serverless Computing với Lambda, API Gateway và DynamoDB](1.5-week5/)

**Tuần 6:** [Xây dựng mô hình tích hợp ứng dụng và kiến trúc hướng sự kiện SQS, SNS và EventBridge](1.6-week6/)

**Tuần 7:** [Ảo hóa ứng dụng với Docker và điều phối cụm Container trên Amazon ECS / ECR / Fargate](1.7-week7/)

**Tuần 8:** [Thiết lập hệ thống giám sát, quản lý nhật ký và truy vết toàn diện với CloudWatch, CloudTrail và X-Ray](1.8-week8/)

**Tuần 9:** [Phân tích nghiệp vụ hệ thống bệnh viện và thiết kế giao diện Admin Web tổng quan](1.9-week9/)

**Tuần 10:** [Xây dựng các màn hình quản lý cốt lõi, xử lý phân trang và tích hợp dữ liệu DynamoDB](1.10-week10/)

**Tuần 11:** [Hoàn thiện các thao tác CRUD dữ liệu y tế, đồng bộ mã hồ sơ theo CCCD và chuẩn hóa cấu trúc API](1.11-week11/)

**Tuần 12:** [Kiểm thử End-to-End hệ thống trên CloudFront, kiểm tra dữ liệu Blockchain và hoàn thiện báo cáo](1.12-week12/)
