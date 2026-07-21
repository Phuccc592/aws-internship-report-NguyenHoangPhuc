---
title: "Worklog Tuần 11"
date: 2026-06-29
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---
### Mục tiêu tuần 11:
* Hoàn thiện và tối ưu hóa các thao tác tương tác dữ liệu nâng cao (Thêm, Sửa, Xóa) trên giao diện quản trị.
* Triển khai mô-đun quản lý tin tức truyền thông và tiếp nhận xử lý ý kiến phản hồi từ khách hàng.
* Đồng bộ hóa cấu trúc định danh mã hồ sơ bệnh án theo căn cước công dân.
* Đồng nhất toàn bộ cấu trúc dữ liệu đặt tên trường thông tin giữa đội ngũ Frontend và Backend.
### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Sửa và hoàn thiện các thao tác CRUD. Tập trung xử lý triệt để lỗi bất đồng bộ giao diện: khắc phục lỗi xóa bác sĩ/nhân sự báo thành công nhưng giao diện không tự động cập nhật lại danh sách. | 29/06/2026   | 29/06/2026      | Nhật ký kiểm thử phần mềm                 |
| 3   | - Xây dựng và hoàn thiện trang quản lý tin tức hiển thị ngoài trang chủ và màn hình duyệt phản hồi ý kiến khách hàng gửi về hệ thống. | 30/06/2026   | 30/06/2026      | Yêu cầu tính năng truyền thông            |
| 4   | - Điều chỉnh giao diện màn hình danh sách hồ sơ bệnh án phía Admin: đơn giản hóa giao diện, hiển thị tổng quan thông tin mã hồ sơ, ngày tạo, trạng thái xử lý hành chính. | 01/07/2026   | 01/07/2026      | Biểu mẫu thiết kế quản lý hồ sơ           |
| 5   | - Cấu hình logic đồng bộ, sử dụng số Căn cước công dân (CCCD) làm mã định danh duy nhất cho hồ sơ bệnh án, loại bỏ hoàn toàn việc hiển thị lẫn lộn với mã định danh cũ (HSBA-BN001). | 02/07/2026   | 02/07/2026      | Quy chuẩn định danh cơ sở dữ liệu mới     |
| 6   | - **Thực hành (Hands-on):** Tiến hành reset toàn bộ dataset hệ thống để kiểm thử khả năng tương thích và chịu lỗi của giao diện Admin.<br> - Phối hợp họp bàn với đội ngũ Backend để chuẩn hóa thống nhất đặt tên các trường khóa chính (patientId, recordId, citizenId, entityType), loại bỏ lỗi không đọc được thuộc tính. | 03/07/2026   | 03/07/2026      |


### Kết quả đạt được tuần 11:
* Nâng cao tính chính xác và nhất quán dữ liệu ứng dụng:
  * Giải quyết hoàn toàn lỗi bất đồng bộ dữ liệu cục bộ (UI State out of sync), đảm bảo danh sách tự động làm mới tức thời (Auto-refresh loop) sau khi thực hiện lệnh xóa hoặc cập nhật thành công.
  * Định hình thành công giải pháp định danh hồ sơ y tế số hóa dựa trên mã định danh công dân (CCCD), tối giản hóa quy trình tra cứu hành chính.
* Đồng bộ hóa tiêu chuẩn tích hợp hệ thống:
  * Loại bỏ hoàn toàn các lỗi xung đột đặt tên trường dữ liệu (Naming convention mismatches) giữa Frontend và Backend, giúp luồng truyền tải thông tin qua API mượt mà và không sinh lỗi Runtime.

