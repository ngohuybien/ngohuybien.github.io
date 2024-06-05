---
layout: post
title: "Các sản phẩm cần nộp của khóa luận hoặc thực tập dự án tốt nghiệp"
categories: [Khóa luận đại học]
author:
- Ngô Huy Biên
meta: "Graduation Thesis Artifacts"
---
_Tài liệu mô tả các sản phẩm cần nộp của khóa luận hoặc thực tập dự án tốt nghiệp do giảng viên Ngô Huy Biên hướng dẫn._

## 1. Thông tin chung
* Đây là các sản phẩm do giảng viên hướng dẫn yêu cầu. Các sản phẩm này khác đôi chút so với với yêu cầu nộp sản phẩm của Khoa/Bộ môn (là thư mục **KANBAN** chứa các sản phẩm trung gian trong quá trình thực hiện đề tài).
* Sinh viên **không** dùng tiếng Việt có dấu khi đặt tên các thư mục hay tập tin.

## 2. Các sản phẩm cần nộp

### 2.1. Thư mục gốc tên là KL_TênĐềTàiKhôngDấu hoặc TTDATN_TênĐềTàiKhôngDấu
Thư mục gốc chứa
* Tập tin **ReadMe.txt** chứa thông tin liên lạc với nhóm tác giả (họ và tên, email cá nhân, số điện thoại cá nhân), và 
* Tập tin **CheckList.xlsx** liệt kê **tất cả** các thư mục con và sản phẩm được mô tả ở bên dưới, bao gồm cả những thư mục con hay sản phẩm được mô tả bên dưới nhưng không nộp do không liên quan đến đề tài, dạng hình cây, và đánh dấu chọn ( ☑ ) vào những **sản phẩm được nộp**.
* Tập tin **Software_Evaluation.xlsx** liệt kê **tất cả** các tiêu chí đánh giá phần mềm đã xây dựng, được giảng viên gợi ý, dạng danh sách, và đánh dấu chọn ( ☑ ) vào những **kết quả tự đánh giá** là đạt được.
* Tập tin **Report_Evaluation.xlsx** liệt kê **tất cả** các tiêu chí đánh giá báo cáo của đề tài, được giảng viên gợi ý, dạng danh sách, và đánh dấu chọn ( ☑ ) vào những **kết quả tự đánh giá** là đạt được.

### 2.2. Thư mục THESIS chứa
* Thư mục tên **DeCuong_LaTeX**: chứa đề cương đề tài.
* Thư mục tên **BaoCao_LaTeX**: chứa quyển báo cáo đề tài.
* Thư mục tên **PDF**: chứa file **DeCuong.pdf** kèm mục lục dạng Bookmarks bên trái, và file **BaoCao.pdf** kèm mục lục dạng Bookmarks bên trái.
* Thư mục tên **Slides**: chứa file **Slides.pptx** (đối với khóa luận), hoặc **Poster.psd/Poster.xml** và **Poster.pdf**  (đối với thực tập dự án tốt nghiệp) dùng để bảo vệ.
* Thư mục tên **Videos**: chứa file file **DryRun.mp4** quay thuyết trình bảo vệ thử, file **Demo.mp4** quay demo sẽ dùng để demo trong buổi bảo vệ.

### 2.3. Thư mục SOURCE chứa
* File **SourceCode.zip** chứa toàn bộ mã nguồn và dữ liệu của chương trình (desktop, mobile, web, API, unit tests, trang Release, các công cụ xử lý dữ liệu, tùy theo nội dung từng khóa luận).
* Thư mục **Testing** chứa các dữ liệu, kịch bản dùng để kiểm thử và kết quả kiểm thử của: performance testing, pen testing, và horizontal scalability testing.
* Thư mục **CompilationGuide_LaTeX**: chứa tài liệu “Hướng dẫn cài đặt công cụ, cấu hình và biên dịch mã nguồn” của Source Code cho OS sạch, kèm ảnh minh họa. OS sạch là máy tính vừa cài đặt xong hệ điều hành, chưa có bất cứ thư viện lập trình ứng dụng nào. Sinh viên được khuyến khích sử dụng các kịch bản viết cho các công cụ triển khai tự động, ví dụ như Docker, Kubernetes hay Circle CI, để thu gọn tài liệu “Hướng dẫn cài đặt công cụ, cấu hình và biên dịch mã nguồn”.
* File **CompilationGuide.pdf**: là bản PDF của thư mục CompilationGuide_LaTeX.
* Nếu khóa luận liên quan đến học máy hoặc học sâu, thì cần có thêm thư mục **Model_Training** chứa
  * Thư mục **Data** chứa toàn bộ dữ liệu training/validation/test để huấn luyện mô hình,
  * Thư mục **Model** chứa mã nguồn để huấn luyện các mô hình,
  * Thư mục **ModelTraningGuide_LaTeX** chứa tài liệu "Hướng dẫn huấn luyện các mô hình" cho OS sạch, kèm ảnh minh họa, dạng DOCX và PDF. Sinh viên được khuyến khích sử dụng các kịch bản viết cho các công cụ triển khai tự động, ví dụ như Docker, Kubernetes hay Circle CI, để thu gọn tài liệu “Hướng dẫn huấn luyện các mô hình”,  và
  * File **ModelTraningGuide.pdf**: là bản PDF của thư mục **ModelTraningGuide_LaTeX**.

### 2.4. Thư mục GUIDES chứa các thư mục theo mô tả bên dưới.
* Thư mục **CloudServiceGuide_LaTeX** chứa tài liệu “Hướng dẫn đăng ký các dịch vụ đám mây và cấu hình hệ thống để kết nối với các dịch vụ đám mây” nếu đề tài có sử dụng các Cloud API của một nhà cung cấp dịch vụ đám mây.
* File **CloudServiceGuide.pdf**: là bản PDF của thư mục CloudServiceGuide _LaTeX.
* File **CloudServiceGuide.mp4**: là file video minh họa việc thực hiện các bước của tài liệu “Hướng dẫn đăng ký các dịch vụ đám mây và cấu hình hệ thống để kết nối với các dịch vụ đám mây”.
* Thư mục **DeploymentGuide_LaTeX** chứa tài liệu “Hướng dẫn triển khai và cấu hình hệ thống” trên máy chủ EC2, hoặc Google Could, hoặc MS Azure, hoặc Heroku, hoặc một nhà cung cấp dịch vụ Hosting nếu đề tài có phát triển phần web/api server. Sinh viên được khuyến khích sử dụng các kịch bản viết cho các công cụ triển khai tự động, ví dụ như Docker, Kubernetes hay Circle CI, để thu gọn tài liệu “Hướng dẫn triển khai và cấu hình”.
* File **DeploymentGuide.pdf**: là bản PDF của thư mục DeploymentGuide_LaTeX.
* File **DeploymentGuide.mp4**: là file video minh họa việc thực hiện các bước của tài liệu “Hướng dẫn triển khai và cấu hình hệ thống”.
* Thư mục **StoreDeploymentGuide_LaTeX** chứa tài liệu “Hướng dẫn triển khai mobile client” trên Google Play hoặc App Store, hoặc trên điện thoại cá nhân nếu đề tài có phát triển phần mobile client.
* File **StoreDeploymentGuide.pdf**: là bản PDF của thư mục StoreDeploymentGuide_LaTeX.
* File **StoreDeploymentGuide.mp4**: là file video minh họa việc thực hiện các bước của tài liệu “Hướng dẫn triển khai mobile client”.
* Thư mục **UserGuide_LaTeX** chứa tài liệu “Hướng dẫn cài đặt và sử dụng phần mềm” cho người dùng cuối.
* File **UserGuide.pdf**: là bản PDF của thư mục UserGuide_LaTeX.
* File **UserGuide.mp4**: là file video minh họa việc thực hiện các bước của tài liệu “Hướng dẫn cài đặt và sử dụng phần mềm”.

### 2.5. Thư mục TOOLS
* Thư mục TOOLS chứa các phần mềm liên quan trong quá trình thực hiện đề tài (ví dụ, phần mềm chỉnh sửa ảnh, audio), các phần mềm dùng để hỗ trợ biên dịch mã nguồn.
* Trong trường hợp vì lý do chính đáng, không thể lưu tất cả các thành phần cần thiết để có thể cài đặt, sinh viên cần tạo file Links.txt ghi rõ tên phần mềm, phiên bản được sử dụng, và liên kết để tải về.

### 2.6. Thư mục REFERENCES
Thư mục REFERENCES chứa các tài liệu tham khảo. Tên các tập tin tài liệu tham khảo cần đặt theo chuẩn APA.

### 2.7. Thư mục KANBAN
Thư mục KANBAN chứa các sản phẩm của mô hình Kanban, có thể bao gồm, nhưng không giới hạn, các sản phẩm sau:
* **DomainModel.vsdx** của Visio (hoặc **DomainModel.xml** của Draw.io): Mô hình nghiệp vụ.
* **Prototype.zip**: Bản mẫu.
* **ProductBacklog.xlsx**: Các tính năng và sản phẩm cần hoàn thành.
* **Architecture.vsdx** của Visio (hoặc **Architecture.xml** của Draw.io).
* **ProofOfConcept.zip**: Mã nguồn tính năng khó của hệ thống nhóm chưa thực hiện bao giờ.
* **Timeline_v1_YYYY-MM-DD.pdf**, **Timeline_v2_YYYY-MM-DD.pdf**: Các timelines, trong đó YYYY-MM-DD ngày tạo, ví dụ 2023-12-18.
* File **ConfigurationManagement.txt** chứa
  * Liên kết và tài khoản truy cập hệ thống quản lý dự án (ví dụ Trello).
  * Liên kết và tài khoản truy cập hệ thống build tự động (ví dụ CircleCI).
  * Liên kết đến trang web tĩnh liệt kê các sản phẩm hoàn thành mỗi tuần.
  * Liên kết đến hệ thống triển khai cho người dùng và người quản trị sử dụng cập nhật hằng tuần (ví dụ liên kết của Render).
    
## 3. Hình thức và thời hạn nộp
* Các sản phẩm cần được nén lại thành **1 file .ZIP duy nhất**, sau đó tải lên một trang lưu trữ, ưu tiên Google Drive, tạo liên kết để tải về và gửi liên kết đến đến 1 file ZIP duy nhất (**không** gửi liên kết đến thư mục) vào trang "Nộp CD bản cuối" trong Confluence **trước ngày nộp đơn đăng ký bảo vệ theo dự kiến của Khoa 3 tuần**.
* Đối với những bộ dữ liệu lớn sinh viên có thể đưa lên nhiều tài khoản Google Drive (mỗi tài khoản được 15Gb).

### &copy; 2024 Ngô Huy Biên
