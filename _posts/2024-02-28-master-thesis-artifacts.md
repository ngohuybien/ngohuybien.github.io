---
layout: post
title: "Các sản phẩm cần nộp của luận văn cao học"
categories: [Luận văn cao học]
author:
- Ngô Huy Biên
meta: "Master Thesis Artifacts"
---
_Tài liệu mô tả các sản phẩm cần nộp và một số thông tin liên quan của luận văn cao học do giảng viên Ngô Huy Biên hướng dẫn._

## 1. Thông tin chung
* Các sản phẩm cần được nén lại thành **1 file .ZIP duy nhất**, sau đó tải lên một trang lưu trữ, tạo liên kết để tải về và gửi liên kết cho giảng viên hướng dẫn qua email **TRƯỚC** ngày đăng ký thông tin bảo vệ với Khoa tối thiểu **1 tháng**.
* Đối với những bộ dữ liệu lớn học viên có thể đưa lên nhiều tài khoản Google Drive (mỗi tài khoản được 15Gb).
* Học viên không dùng tiếng Việt có dấu khi đặt tên các thư mục hay tập tin.

## 2. Các sản phẩm cần nộp
### 2.1. Thư mục gốc tên là THESIS_TênĐềTàiBằngTiếngAnh
Thư mục gốc chứa
* Tập tin **ReadMe.txt** chứa thông tin liên lạc của học viên (họ và tên, email cá nhân, số điện thoại cá nhân), và 
* Tập tin **CheckList.xlsx** liệt kê **tất cả** các thư mục con và sản phẩm được mô tả ở bên dưới, bao gồm cả những thư mục con hay sản phẩm được mô tả bên dưới nhưng không nộp do không liên quan đến đề tài, dạng hình cây, và đánh dấu chọn ( ☑ ) vào những **sản phẩm được nộp**.

### 2.2. Thư mục THESIS chứa
* Thư mục tên **Proposal_LaTeX**: chứa đề cương của đề tài.
* Thư mục tên **Abstract_LaTeX**: chứa tóm tắt của đề tài.
* Thư mục tên **Report_LaTeX**: chứa quyển báo cáo của đề tài.
* Thư mục tên **PDF**: chứa file **Proposal.pdf** kèm mục lục dạng Bookmarks bên trái, file **Abstract.pdf** kèm mục lục dạng Bookmarks bên trái, và file **BaoCao.pdf** kèm mục lục dạng Bookmarks bên trái.
* Thư mục tên **Slides**: chứa file **Slides.pptx** dùng để thuyết trình khi bảo vệ.
* Thư mục tên **Videos**: chứa file **Demo.mp4** quay demo hệ thống, file **DryRun.mp4** quay bảo vệ thử.

### 2.3. Thư mục SOURCE chứa
* File **SourceCode.zip** chứa toàn bộ mã nguồn và dữ liệu của chương trình (bản mẫu desktop, mobile, web, API, unit tests, các công cụ xử lý dữ liệu, tùy theo nội dung từng luận văn).
* Thư mục **Testing** chứa các dữ liệu, kịch bản dùng để kiểm thử và kết quả kiểm thử của: performance testing, pen testing, và/hoặc horizontal scalability testing, nếu có.
* Thư mục **Evaluation** chứa các dữ liệu khảo sát, tính toán khảo sát, kết quả khảo sát liên quan đến việc đánh giá các kết quả của đề tài, nếu có.
* Thư mục **CompilationGuide_LaTeX**: chứa tài liệu “Hướng dẫn cài đặt công cụ, cấu hình, biên dịch và chạy mã nguồn” của Source Code cho OS sạch, kèm ảnh minh họa. OS sạch là máy tính vừa cài đặt xong hệ điều hành, chưa có bất cứ thư viện lập trình ứng dụng nào. Học viên được khuyến khích sử dụng các kịch bản viết cho các công cụ triển khai tự động, ví dụ như Docker, Kubernetes hay Circle CI, để thu gọn tài liệu “Hướng dẫn cài đặt công cụ, cấu hình, biên dịch và chạy mã nguồn”.
* File **CompilationGuide.pdf**: là bản PDF của thư mục CompilationGuide_LaTeX.
* Nếu luận văn liên quan đến học máy hoặc học sâu, thì cần có thêm thư mục **Model_Training** chứa
  * Thư mục **Data** chứa toàn bộ dữ liệu training/validation/test để huấn luyện mô hình,
  * Thư mục **Model** chứa mã nguồn để huấn luyện các mô hình,
  * Thư mục **ModelTraningGuide_LaTeX** chứa tài liệu "Hướng dẫn huấn luyện các mô hình" cho OS sạch, kèm ảnh minh họa, dạng DOCX và PDF. Học viên được khuyến khích sử dụng các kịch bản viết cho các công cụ triển khai tự động, ví dụ như Docker, Kubernetes hay Circle CI, để thu gọn tài liệu “Hướng dẫn huấn luyện các mô hình”,  và
  * File **ModelTraningGuide.pdf**: là bản PDF của thư mục **ModelTraningGuide_LaTeX**.
* Thư mục **CloudServiceGuide_LaTeX** chứa tài liệu “Hướng dẫn đăng ký các dịch vụ đám mây và cấu hình hệ thống để kết nối với các dịch vụ đám mây” nếu đề tài có sử dụng các Cloud API của một nhà cung cấp dịch vụ đám mây.
* File **CloudServiceGuide.pdf**: là bản PDF của thư mục CloudServiceGuide _LaTeX.
* File **CloudServiceGuide.mp4**: là file video minh họa việc thực hiện các bước của tài liệu “Hướng dẫn đăng ký các dịch vụ đám mây và cấu hình hệ thống để kết nối với các dịch vụ đám mây”.

### 2.4. Thư mục TOOLS
* Thư mục TOOLS chứa các phần mềm liên quan trong quá trình thực hiện đề tài (ví dụ, phần mềm chỉnh sửa ảnh, audio), các phần mềm dùng để hỗ trợ biên dịch mã nguồn.
* Trong trường hợp vì lý do chính đáng, không thể lưu tất cả các thành phần cần thiết để có thể cài đặt, học viên cần tạo file Links.txt ghi rõ tên phần mềm, phiên bản được sử dụng, và liên kết để tải về.

### 2.5. Thư mục REFERENCES
Thư mục REFERENCES chứa các tài liệu tham khảo. Tên các tập tin tài liệu tham khảo cần đặt theo chuẩn APA.    
  
## 3. Khi nào cần cập nhật tiến độ?
Mỗi tháng một lần học viên cần 
* Duplicate Timeline ra bản mới (**đừng xóa bản cũ**), 
* Cập nhật lại các công việc và tiến độ trong Preceden cho phù hợp với kế hoạch dự kiến của các bạn, và
* Gửi cho giảng viên liên kết đến Timeline mới trong trang Confluence _Tiến độ_.
* Học viên **tự chọn** thời điểm mình dự kiến bảo vệ dựa vào mục tiêu, kế hoạch cá nhân và quy định của Trường/Khoa, nhưng luôn cần cập nhật vào Preceden để giảng viên biết.

## 4. Dùng công cụ nào để viết đề cương, luận văn và tóm tắt luận văn?
* Học viên **phải** sử dụng LaTeX để viết đề cương, luận văn, và tóm tắt luận văn.
* Học viên viết trực tiếp trên trang Overleaf mà giảng viên đã tạo.
* Các phần khác (như Trang thông tin) học viên có thể dùng template của Trường.

### &copy; 2024 Ngô Huy Biên
