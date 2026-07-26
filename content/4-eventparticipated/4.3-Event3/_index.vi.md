---
title: "Event 3"
date: 2026-07-25
weight: 1
chapter: false
pre: " <b> 4.3. </b> "
---


# Bài thu hoạch “FCAJ - AGENTIC AI BUILD WEEK”

###  Mở Đầu Sự Kiện
- Giới thiệu: Sự kiện Agentic AI Buildweek (AAQ/AIBW) phối hợp tổ chức tại TP.HCM. Chương trình được thiết kế dưới dạng Hackathon nhằm tạo sân chơi thực chiến, kết nối các lập trình viên cùng xây dựng sản phẩm AI agents và ứng dụng thực tế.
- Thông điệp mở màn:
    + Sự thay đổi thế hệ công nghệ: Thế hệ trước mất nhiều năm để đổi mới (từ thả 1 release/quý lên 2 tuần/lần), nhưng thời đại AI agents ngày nay có thể triển khai release liên tục từng phút.
    + Tư duy đổi mới: Khuyến khích các nhà phát triển liên tục thử thách các tư duy cũ và không bị ràng buộc bởi định kiến hay công nghệ của những thập kỷ trước.
    + Con người là trung tâm (Human in the Loop): Dù công nghệ hay AI vận hành lớn đến đâu, công nghệ vẫn chỉ là công cụ. Con người mới là yếu tố đưa ra quyết định và định hình chu kỳ đổi mới.
    + Học tập suốt đời (Lifelong Learning): Thành công bền vững đến từ việc duy trì tinh thần học hỏi liên tục mỗi ngày

###  Khảo sát chi tiết nội dung các phiên chuyên đề

####  Team 1: AI Powered Conversational Ordering
- Bài toán & Giải pháp
    + Bài toán (Problem): Các thử nghiệm AI đặt hàng tự động trước đây dễ bị nhầm lẫn ngữ cảnh (hallucination), dẫn đến sai sót đơn hàng. Ngoài ra, trải nghiệm đặt hàng online hiện tại bị đứt gãy do người dùng buộc phải chuyển ứng dụng, tạo tài khoản và thao tác menu phức tạp.  
    + Giải pháp (Solution): Xây dựng Chatbot Agent đa kênh (tập trung vào nền tảng nhắn tin phổ biến như Zalo, WhatsApp) giúp đặt hàng trực tiếp trong khung chat. Không chuyển app, không tạo tài khoản mới, giữ nguyên luồng trò chuyện tự nhiên.

- Bài học & Trải nghiệm: Xây dựng luồng xác nhận đơn hàng chặt chẽ là chìa khóa để xử lý bài toán hallucination của LLM khi thao tác dữ liệu giao dịch.

####  Team 2: Multi-Agent Corporate Intelligence & Strategy Analytics
- Bài toán & Giải pháp:
    + Bài toán (Problem): Dữ liệu phân tích chiến lược, báo cáo tài chính và cấu trúc vận hành của đối thủ cạnh tranh ngoài thị trường thường bị phân tán, mất nhiều thời gian thu thập và tổng hợp thủ công.
    + Giải pháp: Thu thập các chỉ số và dữ liệu rời rạc từ nhiều nguồn, tự động tổng hợp và trực quan hóa cấu trúc chiến lược. AI hỗ trợ phân tích tác động và tính toán hiệu quả đầu tư (ROI)

- Bài học & Trải nghiệm: Execution Over Idea: Ý tưởng lý thuyết cần phải được chứng minh bằng bản Demo/POC chạy thực tế. Lựa chọn dịch vụ đúng trọng tâm giúp giải quyết chính xác điểm đau (pain point) của bài toán.

####  Team 3: SA Professional AI-Native App
- Bài toán & Giải pháp:
    + Bài toán (Problem): Việc thiết kế sơ đồ kiến trúc Cloud, tính toán chi phí và viết mã nguồn triển khai (IAC) thủ công dưới áp lực thời gian ngắn tốn nhiều công sức và dễ xảy ra sai sót.
    + Giải pháp (Solution): Phân tích yêu cầu từ ngôn ngữ tự nhiên -> Tự động tạo sơ đồ kiến trúc trực quan -> Hỗ trợ tùy chỉnh -> Xuất bảng dự toán chi phí và sinh mã nguồn Infrastructure as Code (Terraform) -> Hỗ trợ triển khai tự động lên AWS.

- Bài học & Trải nghiệm: Yếu tố kỹ thuật cốt lõi của ứng dụng AI nằm ở kỹ năng Prompt & Context Engineering, giúp hiện thực hóa ý tưởng thành trợ lý công việc hiệu quả. 

####  Team 4: Computer Vision & AI Crowd Management System
- Bài toán & Giải pháp:
    + Bài toán (Problem): Tình trạng ùn tắc tại các khu vực công cộng (sân bay, sự kiện, điểm kiểm soát) gây ảnh hưởng đến luồng vận hành và trải nghiệm.
    + Giải pháp (Solution): Kết nối hệ thống camera giám sát để tự động phát hiện mật độ, phân tích vùng ùn tắc và đề xuất phương án điều phối nhân sự kịp thời.

- Bài học & Trải nghiệm:
    + Tối ưu tài nguyên: Tối ưu hóa mô hình AI nhẹ hơn giúp tiết kiệm đáng kể chi phí hạ tầng cloud.
    + Quản lý phạm vi (Scope Control): Giới hạn quy mô tính năng vừa đủ (MVP) để đảm bảo tiến độ triển khai.

####  Team 5: Adaptive Workflow Engine for AML
- Bài toán & Giải pháp:
    + Bài toán (Problem): Tỷ lệ báo động giả (False Positive) trong giám sát giao dịch tài chính rất cao (90% - 95%). Việc kiểm tra thủ công tốn nhiều chi phí và thời gian của chuyên viên.
    + Giải pháp (Solution): Xây dựng hệ thống Multi-Agent tự động hóa quá trình điều tra thông tin, phân tích dòng tiền và tổng hợp chứng cứ, giúp giảm thời gian xử lý hồ sơ xuống còn vài phút.


- Bài học & Trải nghiệm: Trong các lĩnh vực nhạy cảm, AI đóng vai trò là trợ lý (Co-pilot) tăng cường khả năng xử lý của con người, kết hợp cơ chế kiểm tra tính minh bạch và nguồn gốc dữ liệu (Traceability).

### Tri thức thu hoạch & Góc nhìn kỹ thuật

#### Sự chuyển dịch từ Single-Prompt sang Multi-Agent Architecture
- Hạn chế của mô hình đơn (Single LLM): Nếu chỉ dùng một prompt duy nhất để xử lý toàn bộ quy trình công việc phức tạp (như phân tích tài chính hay tự động hóa hạ tầng), LLM rất dễ rơi vào trạng thái quá tải ngữ cảnh (context overload) và sinh ra phản hồi sai lệch (hallucination).
- Mô hình Multi-Agent: Chia nhỏ bài toán lớn thành các Agent chuyên biệt đảm nhận từng tác vụ riêng lẻ (thu thập dữ liệu, phân tích, tổng hợp, kiểm tra lỗi). Cách tiếp cận này giúp cô lập phạm vi ngữ cảnh, tăng độ chính xác và dễ dàng kiểm thử từng công đoạn.

#### Prompt & Context Engineering là xương sống của AI-Native App
- Dữ liệu đầu vào (Context) quyết định 80% chất lượng đầu ra của AI. Việc thiết kế hệ thống không chỉ dừng lại ở việc chọn mô hình (Model Selection) mà là cách quản lý bộ nhớ (Memory management), kỹ thuật RAG (Retrieval-Augmented Generation) và định hình cấu trúc đầu ra (Structured Output) như JSON/YAML để kết nối mượt mà với các hệ thống backend truyền thống.

#### Nguyên tắc Human-in-the-Loop & Traceability trong các bài toán nhạy cảm
- Trong các nghiệp vụ có rủi ro cao (giao dịch tài chính, chống rửa tiền AML, thanh toán), AI không thay thế con người mà đóng vai trò là một Co-pilot (Trợ lý tăng cường).
- Hệ thống Agent bắt buộc phải có cơ chế Traceability (truy xuất nguồn gốc): mọi đề xuất hoặc quyết định do AI đưa ra đều phải kèm theo bằng chứng, log suy luận (reasoning path) và dữ liệu trích dẫn rõ ràng để chuyên viên con người duyệt trước khi thực thi.


### Ghi nhận góc nhìn cá nhân tại khán phòng

#### Các phiên trải nghiệm thực tế
- Trực tiếp quan sát các nhóm thi demo sản phẩm thực tế chỉ sau thời gian ngắn phát triển tại Hackathon mang lại trải nghiệm vô cùng trực quan:
    + Tập trung vào nỗi đau thực sự (Pain point): Những ý tưởng thành công nhất không nhất thiết phải dùng công nghệ phức tạp nhất, mà là những giải pháp giải quyết triệt me các điểm đứt gãy cụ thể (như xử lý giao dịch không cần chuyển app, hay giảm thời gian xác minh AML).
    + Execution Over Idea: Sự khác biệt nằm ở khả năng hiện thực hóa ý tưởng thành bản Demo/POC chạy ổn định, có luồng xử lý lỗi (error handling) rõ ràng thay vì chỉ trình bày slide lý thuyết.


#### Sự kết nối với lộ trình thực tập
- Trải nghiệm tại sự kiện giúp liên hệ trực tiếp và định hình rõ ràng hơn cho hành trình phát triển nghề nghiệp sắp tới:
    + Tối ưu hóa kỹ năng Full-stack & Cloud: Việc hiểu cách tích hợp các mô hình AI vào hệ thống Backend sẵn có và triển khai hạ tầng tự động (IaC/AWS) là lợi thế lớn cho các dự án thực tế.
    + Tư duy giải quyết bài toán: Nhận ra rằng giá trị cốt lõi của một kỹ sư không dừng lại ở việc viết code thuần túy, mà nằm ở khả năng sử dụng công cụ AI để tối ưu hóa quy trình làm việc và tạo ra giá trị cho người dùng cuối.

#### Giá trị cộng đồng và mạng lưới kết nối
- Sự kiện là cầu nối tuyệt vời để học hỏi kinh nghiệm thực chiến từ các anh chị Chuyên gia/Mentors và giao lưu cùng các bạn trẻ có chung niềm đam mê công nghệ.
- Bầu không khí trao đổi cởi mở, phản biện tích cực tại khán phòng tiếp thêm rất nhiều động lực và niềm tin vào sự phát triển mạnh mẽ của cộng đồng lập trình AI tại Việt Nam.

#### Tổng kết bài học quan trọng
- Con người là trung tâm (Human-in-the-Loop): Công nghệ hay AI dù tiến hóa nhanh đến đâu vẫn chỉ là công cụ hỗ trợ. Sự nhạy bén, tư duy phản biện và quyết định cuối cùng của con người mới là yếu tố định hình giá trị sản phẩm.
- Tư duy tinh gọn (MVP): Luôn bắt đầu từ phiên bản nhỏ nhất chạy được, liên tục nhận phản hồi và cải tiến thay vì cố gắng xây dựng một hệ thống cồng kềnh ngay từ đầu.
- Tinh thần học tập suốt đời (Lifelong Learning): Công nghệ thay đổi theo từng tuần, việc chủ động cập nhật tri thức mới và sẵn sàng rũ bỏ tư duy cũ là chìa khóa duy nhất để không bị tụt lại phía sau.