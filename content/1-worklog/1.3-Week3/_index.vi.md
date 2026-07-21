---
title: "Worklog Tuần 3"
date: 2026-05-04
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---


### Mục tiêu tuần 3:
* Nghiên cứu và nắm vững kiến trúc nền tảng mạng ảo độc lập hạ tầng đám mây (**Amazon VPC**).
* Hiểu sâu sắc phân hệ bảo mật đa tầng, thiết lập định tuyến và kiểm soát các luồng traffic qua mạng.
* **Thực hành (Hands-on):** Xây dựng thành công mô hình kiến trúc hạ tầng mạng đa tầng bảo mật (**Multi-tier network architecture**) để làm nền tảng triển khai hệ thống Web & Database an toàn.
### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Nghiên cứu sâu lý thuyết tổng quan về Amazon VPC. <br> - Học cách quy hoạch IP và phân tách phân vùng mạng: Public Subnet, Private Subnet, Internet gateway và Route Tables.                                                                                             | 04/05/2026   | 04/05/2026     |
| 3   | - Phân tích, so sánh cơ chế hoạt động của tường lửa bảo mật tầng mạng                | 05/05/2026   | 05/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Nghiên cứu hệ thống quản lý danh tính Quản lý Users, Groups, Policies nâng cao dựa trên nguyên tắc cấp quyền tối thiểu.<br> - Cấu hình IAM Roles đặc thù cho phép tài nguyên kết nối chéo dữ liệu bảo mật. | 06/05/2026   | 06/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Tìm hiểu cơ chế chuyển đổi địa chỉ mạng để cấp quyền truy cập Internet một chiều ra ngoài cho các tài nguyên nằm trong vùng bảo mật Private Subnet.<br> - Tối ưu luồng dữ liệu an toàn mạng nội bộ.                  | 07/05/2026   | 07/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - **Thực hành (Hands-on):** Triển khai cấu trúc mô hình hạ tầng mạng đa tầng thực tế trên hệ sinh thái VPC.<br> - Cấu hình định tuyến giữa Web Server và Database Server                                                                                    | 08/05/2026   | 08/05/2026      | <https://cloudjourney.awsstudygroup.com/> |


### Kết quả đạt được tuần 3:
* Làm chủ kiến thức thiết kế hệ thống mạng (Networking):
  * Hiểu bản chất thiết lập dải CIDR block, cách phân bổ và chia nhỏ các Subnet  tương ứng với yêu cầu kiến trúc hạ tầng an toàn thông tin.
  * Nắm rõ nguyên lý chuyển hướng định tuyến gói tin thông qua Route Table và vai trò của Internet Gateway đối với tài nguyên public công khai.

* Hoàn thiện tư duy phòng thủ bảo mật đa tầng mạng:
  * Phân biệt rõ ràng và biết cách phối hợp linh hoạt giữa Security Group kiểm soát inbound/outbound cho máy chủ với Network ACLs chặn lọc ở cửa ngõ phân vùng Subnet.
  * Triển khai cấu hình NAT Gateway hoạt động chính xác, đảm bảo hệ thống DB Backend có thể cập nhật các gói phần mềm, thư viện cần thiết nhưng chặn đứng tuyệt đối mọi nguy cơ quét và xâm nhập từ môi trường Internet bên ngoài.

* Kỹ năng phân quyền truy cập hệ thống (Identity & Access):
  * Viết và tùy chỉnh cấu trúc IAM Policies thành thạo, gán IAM Role an toàn cho các tác vụ điện toán trực tiếp thay vì lưu trữ cứng thông tin cấu hình Access Key nguy hiểm.

* Kết quả thực hành Hands-on:
  * Xây dựng độc lập hệ thống mạng VPC phân tầng chức năng tối ưu. Cấu hình kiểm thử luồng kết nối phân tầng thành công: client truy cập trực tiếp vào tầng Web xử lý, nhưng chỉ có tầng Web mới được phép gửi truy vấn dữ liệu sâu xuống tầng Database Server.

