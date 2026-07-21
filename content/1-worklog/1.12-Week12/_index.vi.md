---
title: "Worklog Tuần 12"
date: 2026-07-06
weight: 12
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

