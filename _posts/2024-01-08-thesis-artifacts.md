---
layout: post
title: "Các sản phẩm cần nộp của khóa luận hoặc thực tập dự án tốt nghiệp"
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

### 2.3. Thư mục GUIDES chứa các thư mục theo mô tả bên dưới.
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

### 2.4. Thư mục TOOLS
Thư mục TOOLS chứa các phần mềm liên quan trong quá trình thực hiện đề tài (ví dụ, phần mềm chỉnh sửa ảnh, audio), các phần mềm dùng để hỗ trợ biên dịch mã nguồn. Trong trường hợp vì lý do chính đáng, không thể lưu tất cả các thành phần cần thiết để có thể cài đặt, sinh viên cần tạo file Links.txt chứa liên kết để tải về.

### 2.5. Thư mục REFERENCES
Thư mục REFERENCES chưa các tài liệu tham khảo. Tên các tập tin tài liệu tham khảo cần đặt theo chuẩn ghi tài liệu tham khảo trong báo cáo. Sinh viên cần thể hiện các tài liệu tham khảo theo đúng chuẩn thông dụng. Sinh viên nên sử dụng tính năng Cite (thể hiện bằng dấu nháy) của [Google Scholar](https://scholar.google.com.vn/scholar?hl=en&as_sdt=0%2C5&q=Efficient+backprop) để xem mẫu trình bày tài liệu tham khảo. Sinh viên nên chọn chuẩn APA.

### 2.6. Thư mục KANBAN
Thư mục KANBAN chứa các sản phẩm của mô hình Kanban, có thể bao gồm (nhưng không giới hạn)
* DomainModel.vsd của Visio (hoặc DomainModel.xml của Draw.io): Mô hình nghiệp vụ.
* Prototype.zip: Bản mẫu.
* ProductBacklog.xls: Các tính năng và sản phẩm cần hoàn thành.
* Architecture.vsd của Visio (hoặc Architecture.xml của Draw.io).
* ProofOfConcept.zip: Mã nguồn tính năng khó của hệ thống nhóm chưa thực hiện bao giờ.
* File ConfigurationManagement.txt chứa
** Liên kết và tài khoản truy cập hệ thống quản lý dự án (ví dụ Trello).
** Liên kết và tài khoản truy cập hệ thống build tự động (ví dụ CircleCI).
** Liên kết đến trang Release liệt kê các sản phẩm hoàn thành hằng tuần.
** Liên kết đến hệ thống triển khai cho người dùng và người quản trị sử dụng cập nhật hằng tuần (ví dụ liên kết của Render).

### &copy; 2024 Ngô Huy Biên
