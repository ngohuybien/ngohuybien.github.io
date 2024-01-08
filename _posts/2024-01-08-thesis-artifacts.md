---
layout: post
title: "Các sản phẩm cần nộp khóa luận hoặc thực tập dự án tốt nghiệp"
categories: thesis
author:
- Ngô Huy Biên
meta: "Thesis Artifacts"
---
_Tài liệu mô tả các sản phẩm cần nộp của khóa luận hoặc thực tập dự án tốt nghiệp do giảng viên Ngô Huy Biên hướng dẫn._

## 1. Thông tin chung
* Đây là các sản phẩm do giảng viên hướng dẫn yêu cầu. Các sản phẩm này có thể khác đôi chút so với với yêu cầu nộp sản phẩm của Khoa/Bộ môn (thư mục **Kanban** chứa thông tin quá trình thực hiện đề tài).
* Các sản phẩm cần được nén lại thành 1 file .ZIP duy nhất, sau đó tải lên một trang lưu trữ, tạo liên kết để tải về và gửi liên kết cho giảng viên hướng dẫn qua email.
* Đối với những bộ dữ liệu lớn sinh viên có thể đưa lên nhiều tài khoản Google Drive (mỗi tài khoản được 15Gb).
* Sinh viên không dùng tiếng Việt có dấu khi đặt tên các thư mục hay tập tin.

## 2. Các sản phẩm cần nộp

### 2.1. Thư mục THESIS chứa
* Thư mục tên DeCuong_LaTeX: chứa đề cương đề tài.
* Thư mục tên BaoCao_LaTeX: chứa quyển báo cáo đề tài.
* Thư mục tên PDF: chứa file DeCuong.pdf kèm mục lục dạng Bookmarks bên trái, và file BaoCao.pdf kèm mục lục dạng Bookmarks bên trái.
* Thư mục tên Slides: chứa file Slides.pptx (đối với khóa luận) hoặc Poster.png (thực tập dự án tốt nghiệp) dùng để bảo vệ.
* Thư mục tên Videos: chứa file Demo.mp4 quay demo hệ thống, file DryRun.mp4 quay bảo vệ thử.

### 2.2. Thư mục SOURCE chứa
* File SourceCode.zip chứa toàn bộ mã nguồn và dữ liệu của chương trình (desktop, mobile, web, API, unit tests, trang Release, các công cụ xử lý dữ liệu, tùy theo nội dung từng khóa luận).
* Thư mục Testing chứa các dữ liệu, kịch bản dùng để kiểm thử và kết quả kiểm thử của: performance testing, pen testing, và horizontal scalability testing.
* Thư mục CompilationGuide_LaTeX: chứa tài liệu “Hướng dẫn cài đặt công cụ, cấu hình và biên dịch mã nguồn” cho OS sạch, kèm ảnh minh họa, dạng DOCX và PDF. OS sạch là máy tính vừa cài đặt xong hệ điều hành, chưa có bất cứ thư viện lập trình ứng dụng nào. Sinh viên được khuyến khích sử dụng các kịch bản viết cho các công cụ triển khai tự động, ví dụ như Docker, Kubernetes hay Circle CI, để thu gọn tài liệu “Hướng dẫn cài đặt công cụ, cấu hình và biên dịch mã nguồn”.
* File CompilationGuide.pdf: là bản PDF của thư mục CompilationGuide_LaTeX.
* Thư mục ReleaseGuide_LaTeX: chứa tài liệu hướng dẫn tạo và triển khai trang Release.
File ReleaseGuide.pdf: là bản PDF của thư mục ReleaseGuide_LaTeX.
* Nếu khóa luận liên quan đến học máy hoặc học sâu, thì cần có thêm thư mục Model_Training chứa 
** Thư mục Data chứa toàn bộ dữ liệu training/validation/test để huấn luyện mô hình, 
** Thư mục Model chứa mã nguồn để huấn luyện các mô hình, và
** Thư mục ModelTraningGuide_LaTeX chứa tài liệu "Hướng dẫn huấn luyện các mô hình" cho OS sạch, kèm ảnh minh họa, dạng DOCX và PDF. Sinh viên được khuyến khích sử dụng các kịch bản viết cho các công cụ triển khai tự động, ví dụ như Docker, Kubernetes hay Circle CI, để thu gọn tài liệu “Hướng dẫn huấn luyện các mô hình”.
** File ModelTraningGuide.pdf: là bản PDF của thư mục ModelTraningGuide_LaTeX.

### 2.3. Thư mục Guides chứa các thư mục theo mô tả bên dưới.
* Thư mục CloudServiceGuide_LaTeX chứa tài liệu “Hướng dẫn đăng ký các dịch vụ đám mây và cấu hình hệ thống” nếu khóa luận có sử dụng các Cloud API của một nhà cung cấp dịch vụ đám mây.
* File CloudServiceGuide.pdf: là bản PDF của thư mục CloudServiceGuide _LaTeX.
* File CloudServiceGuide.mp4: là file video minh họa việc thực hiện các bước của tài liệu “Hướng dẫn đăng ký các dịch vụ đám mây và cấu hình hệ thống”.
* Thư mục DeploymentGuide_LaTeX chứa tài liệu “Hướng dẫn triển khai và cấu hình hệ thống” trên máy chủ EC2, hoặc Google Could, hoặc MS Azure, hoặc Heroku, hoặc một nhà cung cấp dịch vụ Hosting nếu khóa luận có phát triển phần web/api server. Sinh viên được khuyến khích sử dụng các kịch bản viết cho các công cụ triển khai tự động, ví dụ như Docker, Kubernetes hay Circle CI, để thu gọn tài liệu “Hướng dẫn triển khai và cấu hình”.
* File DeploymentGuide.pdf: là bản PDF của thư mục DeploymentGuide_LaTeX.
* File DeploymentGuide.mp4: là file video minh họa việc thực hiện các bước của tài liệu “Hướng dẫn triển khai và cấu hình hệ thống”.
* Thư mục StoreDeploymentGuide_LaTeX chứa tài liệu “Hướng dẫn triển khai mobile client” trên Google Play hoặc App Store, hoặc trên điện thoại cá nhân nếu khóa luận có phát triển phần mobile client.
* File StoreDeploymentGuide.pdf: là bản PDF của thư mục StoreDeploymentGuide_LaTeX.
* File StoreDeploymentGuide.mp4: là file video minh họa việc thực hiện các bước của tài liệu “Hướng dẫn triển khai mobile client”.
* Thư mục UserGuide_LaTeX chứa tài liệu “Hướng dẫn cài đặt và sử dụng phần mềm” cho người dùng cuối.
* File UserGuide.pdf: là bản PDF của thư mục UserGuide_LaTeX.
* File UserGuide.mp4: là file video minh họa việc thực hiện các bước của tài liệu “Hướng dẫn cài đặt và sử dụng phần mềm”.
* Các tài liệu kỹ thuật giảng viên yêu cầu thường nhiều hơn các tài liệu kỹ thuật Khoa yêu cầu. Sinh viên gửi cho giảng viên các sản phẩm theo hướng dẫn ở tài liệu này. Sinh viên gửi cho Khoa các sản phẩm theo yêu cầu cụ thể hằng năm của Khoa.

### 2.4. Thư mục Tools
Thư mục Tools chứa các phần mềm liên quan trong quá trình thực hiện đề tài (ví dụ, phần mềm chỉnh sửa ảnh, audio), các phần mềm dùng để hỗ trợ biên dịch mã nguồn. Trong trường hợp vì lý do chính đáng, không thể lưu tất cả các thành phần cần thiết để có thể cài đặt, sinh viên cần tạo file Links.txt chứa liên kết để tải về.

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

### &copy; 2023 Ngô Huy Biên
