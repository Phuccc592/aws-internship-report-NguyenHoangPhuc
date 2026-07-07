---
title: "Worklog Tuần 9"
date: 2026-06-15
weight: 1
chapter: false
pre: " <b> 1.9. </b> "
---
### Mục tiêu tuần 9:
* Phân tích các yêu cầu chức năng nghiệp vụ thuộc vai trò Admin trong hệ thống bệnh viện.
* Thiết kế cấu trúc bố cục tổng thể và giải pháp UI/UX đồng nhất cho giao diện quản trị web.
* Xác định danh sách các API tổng quan cần tích hợp với hệ thống backend.
* Xây dựng kiến trúc các thành phần linh kiện giao diện Reusable UI Components dùng chung cho các màn hình quản lý.
### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Phân tích các chức năng thuộc vai trò Admin: quản lý tài khoản, bệnh nhân, bác sĩ, nhân sự y tế, khoa/chuyên khoa, dịch vụ y tế, thuốc, tin tức và phản hồi người dùng. | 15/06/2026   | 15/06/2026      |      |
| 3   | - Thiết kế bố cục tổng thể (Layout) cho giao diện Admin web: hệ thống sidebar, topbar, dashboard, bảng hiển thị dữ liệu và form nhập liệu để đảm bảo tính nhất quán. | 16/06/2026   | 16/06/2026      |                       |
| 4   | - Xác định danh sách hệ thống các API mà Admin cần gọi từ backend (danh sách tài khoản, thông tin dữ liệu bác sĩ, bệnh nhân, nhân sự, danh mục khoa, dịch vụ, hồ sơ bệnh án tổng quan). | 17/06/2026   | 17/06/2026      |                |
| 5   | - Lên phương án giải pháp phân trang (Pagination), thanh công cụ tìm kiếm (Search) và các bộ lọc dữ liệu (Filter) cho các bảng quản trị để tối ưu hiệu năng hiển thị dataset lớn. | 18/06/2026   | 18/06/2026      |                 |
| 6   | - **Thực hành (Hands-on):** Thiết lập cấu trúc mã nguồn, chuẩn bị các UI components dùng chung (Table, Search bar, Action buttons, trạng thái loading/empty/error và toast thông báo).<br> - Định nghĩa nguyên tắc bảo mật: Admin chỉ xem thông tin quản lý tổng quan, không đi sâu vào chi tiết y tế nhạy cảm của hồ sơ bệnh án. | 19/06/2026   | 19/06/2026      |


### Kết quả đạt được tuần 9:
* Hoàn thiện tư duy thiết kế hệ thống quản trị bệnh viện:
  * Định hình rõ ràng phạm vi phân quyền và luồng nghiệp vụ lưu trữ dữ liệu của tài khoản Admin đối với tất cả các thực thể (Bệnh nhân, Bác sĩ, Thuốc, Khoa).
  * Thống nhất được bộ quy tắc bảo mật dữ liệu y tế (HIPAA/Medical Privacy): Giới hạn hiển thị thông tin lâm sàng chi tiết đối với cấp quản trị hành chính.
* Tối ưu hóa cấu trúc mã nguồn Frontend:
  * Thiết kế thành công kiến trúc giao diện chuẩn hóa với Sidebar điều hướng linh hoạt và Dashboard trực quan.
  * Đóng gói hoàn chỉnh các thành phần linh kiện giao diện (UI Components) tái sử dụng cao, giúp giảm thiểu trùng lặp mã nguồn và tăng tốc độ phát triển cho các tuần kế tiếp.