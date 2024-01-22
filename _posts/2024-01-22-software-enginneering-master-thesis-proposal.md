---
layout: post
title: "Hướng dẫn viết đề cương cao học, lĩnh vực công nghệ phần mềm"
categories: master-thesis
author:
- Ngô Huy Biên
meta: "Software Engineering Master Thesis Proposal"
---
_Tài liệu hướng dẫn viết đề cương đề cương cao học, lĩnh vực công nghệ phần mềm, do giảng viên Ngô Huy Biên hướng dẫn._

## 1. Xác định vấn đề
* Học viên chọn một bài báo yêu thích và tìm hiểu vấn đề bài báo đề cập và giải pháp đề xuất.
* Nếu học viên chưa có bài báo yêu thích thì có thể tìm theo chủ đề mình quan tâm trên Google Scholar Paper with Code.
* Nếu bài báo **không công bố mã nguồn/thư viện/hệ thống** thì học viên có thể xem xét việc xây dựng lại mã nguồn/thư viện/hệ thống theo đề xuất để đánh giá xem có thực là giải pháp khả thi hay không. Nếu học viên tạo được bản mẫu từ bài báo thì bài toán khả thi và bài báo có thể dùng cho phần phân tích tiếp theo.
* Nếu giải pháp này **đã có sẵn mã nguồn/thư viện/hệ thống** (do đó không cần tạo bản mẫu nữa) thì học viên **cần có hệ thống riêng của mình (hoặc một hệ thống mã nguồn mở)** để áp dụng giải pháp vào, và đánh giá xem vấn đề có thực sự được giải quyết hay không (mã nguồn của hệ thống riêng của mình sẽ phải công bố). Khi đó bài báo có thể dùng cho phần phân tích tiếp theo.
* Học viên phân tích bài báo theo các định hướng dưới đây:
    * Học viên dự định áp dụng giải pháp để giải quyết vấn đề/bài toán cụ thể nào? Bài toán đó được mô hình cụ thể như thế nào? Học viên có thể mô hình bằng, nhưng không giới hạn: các business use case, các giao diện, các lược đồ, các mô hình toán học. Thông thường, phần **Introduction** của bài báo sẽ hỗ trợ trả lời cho câu hỏi này.
    * Giải pháp thủ công (trivial solution) để giải quyết vấn đề này là gì?
    * Đã có những giải pháp nào khác đã được đề xuất để giải quyết vấn đề này? Thông thường, phần **Related Work** của bài báo sẽ hỗ trợ trả lời cho câu hỏi này.
    * Dựa trên các **tiêu chí hay độ đo** nào, ví dụ: feasibility, performance, scalability, security, cost, time, để so sánh các giải pháp trên với nhau (quan trọng)? Thông thường, phần Evaluation, hoặc Performance, hoặc Experience của bài báo sẽ hỗ trợ trả lời cho câu hỏi này. Học viên cần lưu ý nếu chọn tiêu chí feasibility thì phải chưa có nghiên cứu có hoàn cảnh tương tự nào được thực hiện.
    * Học viên dự định thu thập các **dữ liệu** nào để đánh giá các tiêu chí hay độ đo ở trên (quan trọng)?
    * Tên đề tài học viên đề xuất là gì? Thường có thể là "Giải pháp XYZ cho bài toán ABC", hoặc "Hệ thống ABC dựa trên giải pháp XYZ".
* Học viên gửi kết quả tìm hiểu ở mục 1. dưới dạng một file PDF cho giảng viên để thảo luận và thống nhất tên đề tài, bài toán và phạm vi, sau đó nhận xác nhận của giảng viên để bắt đầu viết đề cương.
  
## 2. Nội dung đề cương

### 2.1. Phần Giới thiệu tổng quan
* Học viên cần thể hiện ít nhất một hệ thống thực tế đã giải quyết vấn đề/bài toán tương tự.
* Tóm tắt vấn đề/bài toán ABC luận văn sẽ giải quyết.
* Tóm tắt thật ngắn gọn lịch sử một số hướng tiếp cận nổi bật, bao gồm cả giải pháp thủ công (trivial solution), cho bài toán ABC.

### 2.2. Phần Phạm vi đề tài
Sinh viên liệt kê các tính năng của phần mềm có liên quan đến đề tài nhưng dự định sẽ KHÔNG làm.

### 2.3. Phần Cách tiếp cận dự kiến

#### Nếu sinh viên làm khóa luận theo hướng ứng dụng hoặc thực tập dự án tốt nghiệp thì cần trình bày
* Bản mẫu, 
* Kiến trúc,
* Mô hình dữ liệu, 
* Thuật toán, 
* Các mục tiêu kiểm thử dự định (load testing, stress testing, penetration testing) sẽ được thực hiện trên hệ thống,
* Phương pháp so sánh, đánh giá hệ thống với các hệ thống tương tự, và
* Danh sách các công nghệ, công cụ dự định sẽ sử dụng. Sinh viên cần mô tả, giải thích cụ thể các sơ đồ.

#### Nếu sinh viên làm khóa luận theo hướng nghiên cứu thì cần trình bày
* Các nghiên cứu liên quan trực tiếp đến đề tài,
* Các mô hình dự kiến áp dụng hoặc cải tiến,
* Các độ đo để so sánh, đánh giá các kết quả thu được,
* Các nguồn dữ liệu và mã nguồn có sẵn dự kiến sẽ được dùng để huấn luyện,
* Tài nguyên GPU dự định sẽ sử dụng, 
* Ảnh chụp kết quả chạy thử nghiệm huấn luyện và suy luận bằng mã nguồn và bộ dữ liệu có sẵn, và
* Bản mẫu

### 2.4. Phần Kết quả dự kiến của đề tài

#### Nếu sinh viên làm khóa luận theo hướng ứng dụng hoặc thực tập dự án tốt nghiệp thì cần trình bày các sản phẩm liên quan đến phần mềm dự kiến sẽ thu được ở đây, ví dụ như
* Mã nguồn ứng dụng di động, 
* Mã nguồn ứng dụng web, 
* Mã nguồn dịch vụ web, 
* Dữ liệu mới tạo được,
* Báo cáo các kết quả kiểm thử,
* Báo cáo so sánh với các hệ thống tương tự,
* Các tài liệu kỹ thuật hướng dẫn chi tiết phương pháp tái tạo các sản phẩm của khóa luận.

#### Nếu sinh viên làm khóa luận theo hướng nghiên cứu thì cần trình bày các sản phẩm KHÁC với những gì đã có sẵn, dự kiến sẽ thu được ở đây, ví dụ như
* Mã nguồn huấn luyện mô hình được chỉnh sửa/tạo thêm/tạo mới,
* Dữ liệu chỉnh sửa/tạo thêm/tạo mới,
* Mô hình đã được huấn luyện,
* Mã nguồn công cụ xử lý dữ liệu,
* Dịch vụ triển khai mô hình,
* Ứng dụng biểu diễn việc sử dụng mô hình đã được triển khai,
* Các tài liệu kỹ thuật hướng dẫn chi tiết phương pháp tái tạo các sản phẩm của khóa luận.

### 2.5. Phần Kế hoạch thực hiện
* Sinh viên dựa vào phần Mục tiêu, phần Kết quả dự kiến của đề tài, các cột mốc thời gian của Khoa, và nguồn nhân lực của nhóm để đưa ra kế hoạch phù hợp.
* Sinh viên trình bày theo các cột mốc và sản phẩm tương ứng.

### 2.6. Phần Tài liệu tham khảo
* Sinh viên chỉ liệt kê các sách và bài báo, và cần có ít nhất 5 tài liệu tham khảo.
* Sinh viên KHÔNG sử dụng các liên kết trong phần này. Các liên kết trong đề cương nếu có sinh viên để trong Footnote tại trang đề cập.
* Sinh viên cần thể hiện các tài liệu tham khảo theo đúng chuẩn thông dụng. Sinh viên nên sử dụng tính năng Cite (thể hiện bằng dấu nháy) của [Google Scholar](https://scholar.google.com.vn/scholar?hl=en&as_sdt=0%2C5&q=Efficient+backprop) để xem mẫu trình bày tài liệu tham khảo. Sinh viên nên chọn chuẩn APA.

### &copy; 2024 Ngô Huy Biên
