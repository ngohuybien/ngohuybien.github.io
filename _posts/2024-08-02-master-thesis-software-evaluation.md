---
layout: post
title: "Hướng dẫn đánh giá phần mềm hoặc bản mẫu của luận văn cao học"
categories: [Luận văn cao học]
author:
- Ngô Huy Biên
meta: "Master Thesis Software Evaluation"
---
_Tài liệu mô tả một số tiêu chí có thể dùng để tự đánh giá phần mềm hoặc bản mẫu của luận văn cao học do giảng viên Ngô Huy Biên hướng dẫn._

## 1.	Tại sao cần đánh giá phần mềm hoặc bản mẫu?
* Để đảm bảo phần mềm hoặc bản mẫu đạt chất lượng đủ để có thể đăng ký bảo vệ.
* Để nâng cao kỹ năng viết tài liệu kỹ thuật một cách logic, hợp lý.
* Để nâng cao tính tự chủ và tinh thần trách nhiệm trong công việc.
*	Để nâng cao tính cẩn thận, chi tiết đối với kết quả công việc.

## 2.	Một số tiêu chí đánh giá phần mềm hoặc bản mẫu

### 2.1. Giao diện
* Giao diện đã tương tự với giao diện của một phần mềm mẫu được chọn hay chưa? Nếu có, hãy cho biết tên phần mềm được dùng để so sánh.
* Paddings, font chữ, color, headers/titles trên giao diện đã phù hợp với các nguyên lý chưa? Học viên có thể kiểm tra tự động bằng <a href="https://accessibe.com/accessscan" target="_blank">Access Scan</a> và <a href="https://www.accessibilitychecker.org/" target="_blank">Accessibility Checker</a>.
* Phần mềm đã loại bỏ việc phải kéo (scroll) thanh ngang khi sử dụng chưa?
* Validation messages, error messages đã có chưa?
* Phần mềm đã loại bỏ các incomplete/unavailable features, broken links hay chưa?

### 2.2. Nghiệp vụ
* Nghiệp vụ có tương đương hoặc tốt hơn giải pháp thủ công (trivial solution) hay không?
* Nghiệp vụ đã giải quyết trọn vẹn một bài toán cụ thể hay chưa?
* Nghiệp vụ có tương đương hoặc tốt hơn giải pháp của một phần mềm sẵn có hay không? Nếu có, hãy cho biết tên phần mềm được dùng để so sánh.

### 2.3. Kiểm thử
* Các test cases thủ công đã được thực hiện hay chưa?
* Các test cases, test data, test reports của quá trình kiểm thử thủ công đã được đưa vào thư mục SOURCE/Testing hay chưa?
* Các dữ liệu khảo sát và kết quả tính toán, nếu có, đã được đưa vào thư mục SOURCE/Testing hay chưa?
* Tốc độ phần mềm đã được đánh giá bằng công cụ hay dịch vụ đám mây hay chưa?
* Các dữ liệu đánh giá tốc độ và kết quả thu được, nếu có, đã được đưa vào thư mục SOURCE/Testing hay chưa?
* Khả năng mở rộng của phần mềm đã được đánh giá hay chưa?
* Các dữ liệu đánh giá khả năng mở rộng và kết quả thu được, nếu có, đã được đưa vào thư mục SOURCE/Testing hay chưa?

### 2.4. Tài liệu kỹ thuật
* Học viên tham khảo một số tài liệu kỹ thuật ở <a href="https://bit.ly/3IMkWa4" target="_blank">đây</a>.
* Tài liệu kỹ thuật đã hỗ trợ phiên bản LTS gần nhất của các công cụ được sử dụng hay chưa?
* Tài liệu kỹ thuật đã mô tả phiên bản của các công cụ được sử dụng hay chưa?
* Các bước của tài liệu kỹ thuật đã được sắp xếp để có thể thực hiện tuần tự, có sự logic, liên kết giữa các bước hay chưa?
* Các bước và hình ảnh tương ứng cài đặt cơ sở dữ liệu, chạy script, import built-in data đã có hay chưa? (Nếu hard-code các script và data trong mã nguồn thì cần bổ sung mô tả vào trong tài liệu biên dịch và tài liệu triển khai.)
* Các bước và hình ảnh tương ứng run hệ thống thành công trên local cho từng service và cho toàn hệ thống đã có hay chưa?
* Các bước và hình ảnh tương ứng run hệ thống thành công trên production cho từng service và cho toàn hệ thống đã có hay chưa?
* Học viên đã chạy các bước của tài liệu biên dịch trên máy ảo vừa mới cài hệ điều hành chưa?
* Học viên đã chạy các bước của tài liệu triển khai trên máy ảo vừa mới cài hệ điều hành chưa?
* Học viên đã chạy các bước của tài liệu triển khai trên môi trường thực (ví dụ AWS, Azure, Google Cloud) hay chưa?

### 2.5. Cấu hình
* Tài liệu biên dịch và tài liệu triển khai đã bao gồm các bước để tạo và nhận các thông tin cấu hình (ví dụ như thông tin truy cập cơ sở dữ liệu, các API keys, các tài khoản online) hay chưa?
* Vị trí thông tin cấu hình cần thay đổi trong các file mã nguồn, để biên dịch hoặc triển khai, đã được tài liệu hóa trong tài liệu biên dịch và tài liệu triển khai hay chưa?

## 3.	Kết quả tự đánh giá
* Học viên tạo một file Excel với tên gọi **Software_Evaluation.xlsx**, và liệt kê tất cả các tiêu chí ở trên.
* Học viên có thể đề xuất thêm các tiêu chí khác vào cuối file, nếu có, để phần mềm của mình được đánh giá toàn diện hơn.
* Học viên đánh dấu chọn ( ☑ ) vào những tiêu chí nào phần mềm đạt được.

## 4.	Thông tin thêm
* Học viên tham khảo một số tiêu chí đánh giá hằng năm của Khoa ở <a href ="https://bit.ly/46FNblp" target="_blank">đây</a>.

### &copy; 2024 Ngô Huy Biên
