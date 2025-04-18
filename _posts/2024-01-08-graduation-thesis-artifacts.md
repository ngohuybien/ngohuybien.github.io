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
* Đây là các sản phẩm do giảng viên hướng dẫn yêu cầu. Các sản phẩm này khác đôi chút so với yêu cầu nộp sản phẩm của Khoa/Bộ môn (là thư mục **KANBAN** chứa các sản phẩm trung gian trong quá trình thực hiện đề tài).
* Bản quyền toàn bộ các sản phẩm thuộc về Trường Đại học Khoa học tự nhiên. Sinh viên cam kết sẽ **không** sử dụng chúng ở những nơi khác, với bất kỳ mục đích nào khác.
* Sinh viên **không** dùng tiếng Việt có dấu khi đặt tên các thư mục hay tập tin.

## 2. Các sản phẩm cần nộp

### 2.1. Thư mục gốc tên là KL_TênĐềTàiKhôngDấu hoặc TTDATN_TênĐềTàiKhôngDấu
Thư mục gốc chứa
* Tập tin **ReadMe.txt** chứa thông tin liên lạc với nhóm tác giả (họ và tên, email cá nhân, số điện thoại cá nhân), và 
* Tập tin **CheckList.xlsx** liệt kê **tất cả** các thư mục con và sản phẩm được mô tả ở bên dưới, bao gồm cả những thư mục con hay sản phẩm được mô tả bên dưới nhưng không nộp do không liên quan đến đề tài, dạng hình cây, và đánh dấu chọn ( ☑ ) vào những **sản phẩm được nộp**.
* Tập tin **Software_Evaluation.xlsx** liệt kê **tất cả** các tiêu chí đánh giá phần mềm đã xây dựng, được giảng viên gợi ý, dạng danh sách, và đánh dấu chọn ( ☑ ) vào những **kết quả tự đánh giá** là đạt được.
* Tập tin **Report_Evaluation.xlsx** liệt kê **tất cả** các tiêu chí đánh giá báo cáo của đề tài, được giảng viên gợi ý, dạng danh sách, và đánh dấu chọn ( ☑ ) vào những **kết quả tự đánh giá** là đạt được.

### 2.2. Thư mục THESIS chứa
* Tập tin tên **Proposal_LaTeX.zip**: chứa đề cương đề tài, định dạng LaTeX, bao gồm cả các ảnh và tài nguyên liên quan.
* Tập tin tên **Report_LaTeX.zip**: chứa quyển báo cáo đề tài, định dạng LaTeX, bao gồm cả các ảnh và tài nguyên liên quan.
* Thư mục tên **PDF**: chứa file **Proposal.pdf** là bản PDF của đề cương đề tài, kèm mục lục dạng Bookmarks bên trái, và file **Report.pdf** là bản PDF của quyển báo cáo đề tài, kèm mục lục dạng Bookmarks bên trái.
* Thư mục tên **Slides**: chứa file **Slides.pptx** (đối với khóa luận), hoặc **Poster.psd/Poster.xml** và **Poster.pdf**  (đối với thực tập dự án tốt nghiệp) dùng để bảo vệ.
* Thư mục tên **Videos**: chứa file file **DryRun.mp4** quay thuyết trình bảo vệ thử, file **Demo.mp4** quay demo sẽ dùng để demo trong buổi bảo vệ.

### 2.3. Thư mục SOURCE chứa
* Thư mục **SourceCode**: chứa toàn bộ mã nguồn và dữ liệu của chương trình (SQL scripts, desktop, mobile, web, API, unit tests source code, các công cụ xử lý dữ liệu, tùy theo nội dung từng khóa luận).
* File **CloudServiceGuide_LaTeX.zip**: là tài liệu "Hướng dẫn đăng ký các dịch vụ đám mây và cấu hình hệ thống để kết nối với các dịch vụ đám mây" nếu đề tài có sử dụng các Cloud API của một nhà cung cấp dịch vụ đám mây.
* File **CloudServiceGuide.pdf**: là bản PDF của tài liệu CloudServiceGuide.
* File **CloudServiceGuide.mp4**: là file video minh họa việc thực hiện các bước trong tài liệu CloudServiceGuide.
* Thư mục **Testing**: chứa các dữ liệu, kịch bản dùng để kiểm thử và kết quả kiểm thử của: manual testing (bắt buộc), performance testing (bắt buộc), pen testing (bắt buộc), horizontal scalability testing (nếu có), các dữ liệu khảo sát và kết quả tính toán (nếu có).
* File **CompilationGuide_LaTeX.zip**: là tài liệu "Hướng dẫn cài đặt công cụ, cấu hình, biên dịch và chạy mã nguồn" trên máy tính cục bộ của một lập trình viên, với OS sạch, kèm ảnh minh họa, định dạng LaTeX. OS sạch là máy tính vừa cài đặt xong hệ điều hành, chưa có bất cứ thư viện lập trình ứng dụng nào. Sinh viên được khuyến khích sử dụng các kịch bản viết cho các công cụ triển khai tự động, ví dụ như Docker, Kubernetes hay Circle CI, để thu gọn tài liệu Compilation Guide.
* File **CompilationGuide.pdf**: là bản PDF của tài liệu "Hướng dẫn cài đặt công cụ, cấu hình, biên dịch và chạy mã nguồn".
* Nếu khóa luận liên quan đến học máy, học sâu hay mô hình ngôn ngữ lớn, thì cần có thêm thư mục **Model_Training**: chứa
  * **Mã nguồn** để huấn luyện mô hình (ví dụ file .ipynb),
  * Thư mục **Data**: chứa toàn bộ các dữ liệu để huấn luyện mô hình (training/validation/test data),
  * Thư mục **Model**: chứa mô hình đã được huấn luyện,
  * File **ModelTraningGuide_LaTeX.zip**: là tài liệu "Hướng dẫn huấn luyện mô hình" cho OS sạch, kèm ảnh minh họa, định dạng LaTeX. Sinh viên được khuyến khích sử dụng các kịch bản viết cho các công cụ triển khai tự động, ví dụ như Docker, Kubernetes hay Circle CI, để thu gọn tài liệu "Hướng dẫn huấn luyện mô hình", và
  * File **ModelTraningGuide.pdf**: là bản PDF của tài liệu "Hướng dẫn huấn luyện mô hình".

### 2.4. Thư mục DEPLOYMENT chứa các thư mục theo mô tả bên dưới.
* File **Package.zip**: chứa các sản phẩm dùng để triển khai, ví dụ mã nguồn, SQL scripts. Sinh viên được khuyến khích đưa các sản phẩm này lên các dịch vụ đám mây hoặc hệ thống DevOps.
* Thư mục **DeploymentGuide_LaTeX**: chứa tài liệu “Hướng dẫn triển khai và cấu hình hệ thống” trên máy chủ EC2, hoặc Google Could, hoặc MS Azure, hoặc Heroku, hoặc một nhà cung cấp dịch vụ Hosting nếu đề tài có phát triển phần web/api server. Sinh viên được khuyến khích sử dụng các kịch bản viết cho các công cụ triển khai tự động, ví dụ như Docker, Kubernetes hay Circle CI, để thu gọn tài liệu “Hướng dẫn triển khai và cấu hình hệ thống”.
* File **DeploymentGuide.pdf**: là bản PDF của thư mục DeploymentGuide_LaTeX.
* File **DeploymentGuide.mp4**: là file video minh họa việc thực hiện các bước của tài liệu “Hướng dẫn triển khai và cấu hình hệ thống”.
* Thư mục **StoreDeploymentGuide_LaTeX**: chứa tài liệu “Hướng dẫn triển khai mobile client” trên Google Play hoặc App Store, hoặc trên điện thoại cá nhân nếu đề tài có phát triển phần mobile client.
* File **StoreDeploymentGuide.pdf**: là bản PDF của thư mục StoreDeploymentGuide_LaTeX.
* File **StoreDeploymentGuide.mp4**: là file video minh họa việc thực hiện các bước của tài liệu “Hướng dẫn triển khai mobile client”.
* Thư mục **UserGuide_LaTeX**: chứa tài liệu “Hướng dẫn cài đặt và sử dụng phần mềm” cho người dùng cuối.
* File **UserGuide.pdf**: là bản PDF của thư mục UserGuide_LaTeX.
* File **UserGuide.mp4**: là file video minh họa việc thực hiện các bước của tài liệu “Hướng dẫn cài đặt và sử dụng phần mềm”.

### 2.5. Thư mục TOOLS
* Thư mục TOOLS chứa các phần mềm liên quan, được sử dụng trong quá trình thực hiện đề tài. Ví dụ các phần mềm dùng để hỗ trợ biên dịch mã nguồn, phần mềm chỉnh sửa ảnh, audio.
* Trong trường hợp phần mềm liên quan lớn hơn 1Gb, hoặc bắt buộc phải cài đặt online, sinh viên cần tạo file Links.txt trong thư mục này, trong đó ghi rõ tên phần mềm, phiên bản được sử dụng, và liên kết để tải về file cài đặt.

### 2.6. Thư mục REFERENCES
Thư mục REFERENCES chứa các tài liệu tham khảo. Tên các tập tin tài liệu tham khảo cần đặt theo chuẩn APA. Các sách, nếu có, cần được xuất bản trong 5 năm gần nhất trở lại.

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
    
## 3. Kiểm tra đĩa CD
* Các sản phẩm đã được sắp vào đúng các thư mục theo hướng dẫn ở mục 2. hay chưa?
* Các thư mục LateX đã chứa mã nguồn LateX hay chưa? Các hình ảnh đã có trong các thư mục LateX hay chưa?
* Thư mục _KANBAN_ đã chứa các Timelines hay chưa?
* Thư mục _Slides_ đã có đủ các files quy định hay chưa? Tên của các files đã được đặt đúng hay chưa?
* Thư mục _SOURCE/Testing_ đã có dữ liệu và kết quả kiểm thử thủ công hay chưa?
* Thư mục _SOURCE/Testing_ đã có dữ liệu và kết quả kiểm thử performance, security bằng công cụ hay chưa?
* Thư mục _SOURCE/Testing_ đã có dữ liệu và kết quả khảo sát, nếu có, hay chưa?
* Thư mục _SOURCE/Model_Training_ đã có dữ liệu, mã nguồn, và hướng dẫn hay chưa? (Nếu đề tài có liên quan đến học máy.)
 
## 4. Hình thức và thời hạn nộp
* Các sản phẩm cần được nén lại thành **1 file .ZIP duy nhất**, sau đó tải lên một trang lưu trữ, ưu tiên Google Drive, tạo liên kết để tải về và gửi liên kết đến đến 1 file ZIP duy nhất (**không** gửi liên kết đến thư mục) vào trang **Nộp CD bản cuối** trong Confluence **trước ngày nộp đơn đăng ký bảo vệ theo dự kiến của Khoa 3 tuần**.
* Đối với những bộ dữ liệu lớn sinh viên có thể đưa lên nhiều tài khoản Google Drive (mỗi tài khoản được 15Gb).

### &copy; 2024 Ngô Huy Biên
