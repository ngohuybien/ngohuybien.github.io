---
layout: post
title: "Các sản phẩm cần nộp của đồ án theo hướng hệ thống doanh nghiệp"
categories: [Software Engineering Capstone]
author:
- Ngô Huy Biên
meta: "Enterprise Project Artifacts"
---
_Tài liệu mô tả các sản phẩm cần nộp cho đồ án theo hướng hệ thống doanh nghiệp của môn học Software Engineering Capstone._

## 1. Quy định chung
* Điểm đồ án giữa kỳ được tự động **chia đều** cho các thành viên trong nhóm.
* Điểm đồ án cuối kỳ được tự động **chia đều** cho các thành viên trong nhóm.
* Nếu nhóm có mong muốn **tự chia điểm đồ án cuối kỳ** theo **tỷ lệ riêng**, thì cần ghi rõ mong muốn tự chia điểm, thông tin từng thành viên và tỷ lệ điểm từng thành viên sẽ được nhận, ví dụ 50%, 120%, 150%, trong trang bìa **từng sản phẩm**. Tổng số % của nhóm = Số thành viên x 100%. Nếu thành viên nào có % x Tổng điểm lớn hơn 10, thì điểm của thành viên cũng chỉ được tính là 10.
* Kết quả đồ án được đánh giá theo số thành viên thực sự hoạt động của nhóm. Do vậy, nếu nhóm có thành viên bỏ nhóm, hoặc không thực hiện đồ án, trưởng nhóm cần **thông báo trực tiếp cho giảng viên vào buổi vấn đáp đồ án giữa kỳ**, để các nhóm được đánh giá công bằng với nhau.

## 2. Quy định tổ chức và đặt tên thư mục
* Mỗi nhóm cần đặt tên thư mục gốc là Nhom_X, không dấu, X là số thứ tự nhóm, ghi dưới dạng 2 chữ số, ví dụ: 01, 02, 03, 04.
* Trong thư mục gốc bao gồm 3 thư mục chính.
    * **01_Documents**: chứa các tài liệu của dự án,
    * **02_Source**: chứa mã nguồn lấy từ source control về, dữ liệu hệ thống, và các tài liệu liên quan đến biên dịch.
    * **03_Packages**: chứa file cài đặt và các tài liệu liên quan việc triển khai và cài đặt.
      
<div align="center">
<img src ="https://ngohuybien.github.io/assets/images/folder-structure.png" alt = "Cây thư mục và tên sản phẩm" width="1024">
</div>
<div align="center">
<br>
<i>Hình minh họa tổ chức cây thư mục và tên sản phẩm.</i>
</div>

## 3. Định dạng các sản phẩm
* Các sản phẩm thường ở dạng **DOCX**, **PPTX**, **XLSX**, hoặc **ZIP** (nếu sản phẩm gồm nhiều tập tin).
* Các sản phẩm không phải dạng ZIP cần được export ra bản **PDF** tương ứng nhằm đảm bảo việc kiểm tra sản phẩm không gặp vấn đề về font chữ hay layout.
* Nếu nhóm có các sản phẩm là ảnh chụp rõ nét bản viết hoặc vẽ bằng tay hoặc ghi chú (sticky notes) dạng PNG hoặc JPG, thì nhóm chỉ cần dán vào các Slide.
* Các hệ thống trực tuyến của nhóm cần để **chế độ công khai** (Public) trừ trường hợp hệ thống không cho phép.
* Các tài liệu của môn học cần **đơn giản**, diễn giải đủ các khía cạnh, dễ hiểu, hỗ trợ tốt cho việc liên lạc, tương tự như những gì đã được minh họa trên lớp.

## 4. Danh sách các sản phẩm cần nộp, và quy định đặt tên tập tin
* Các sản phẩm dưới đây là **bắt buộc**, nhưng không giới hạn. Các nhóm có thể nộp thêm các sản phẩm tự đề xuất trong quá trình thực hiện đồ án.
* Danh sách các sản phẩm này có thể được giảng viên hiệu chỉnh lại trong quá trình học, tùy theo tình hình lớp học.
* Thư mục **01_Documents** chứa các sản phẩm với các **tên in đậm** sau:
    * **01_Project Proposal.pptx**: trình bày đề xuất dự án (những phần nào trong file trình chiếu liên quan đến một sản phẩm khác thì sinh viên chỉ trình bày một, hai hoặc tối đa là ba ví dụ, và ghi chú là xem chi tiết ở tài liệu "XYZ", ví dụ, phần Bản mẫu sinh viên chỉ trình bày 3 giao diện, và ghi chú là xem chi tiết bản mẫu ở tài liệu "05_Prototype.docx"),
    *	**01_Project Proposal.pdf**,
    * **02_Business Cases.docx**: trình bày các vai trò, các vấn đề, các mục tiêu một vai trò mong muốn đạt được, các luồng quy trình nghiệp vụ nhóm sẽ xây dựng để đạt được mục tiêu trong đời sống thực,
    * **02_Business Cases.pdf**,
    * **03_Domain Model.docx**: trình bày các thực thể nghiệp vụ trong đời sống thực (có thể có liên quan đến phần mềm) và mối liên hệ giữa các thực thể này với nhau,
    * **03_Domain Model.pdf**,
    * **04_Product Backlog.xlsx**: trình bày toàn bộ các sản phẩm và tính năng cần có để đạt được các mục tiêu đề ra.
    * **05_Prototype.docx**: trình bày giao diện từng bước của ít nhất một luồng quy trình nghiệp vụ,
    * **05_Prototype.pdf**,
    * **06_Architecture.docx**: trình bày kiến trúc hệ thống theo các góc nhìn khác nhau, các công nghệ, công cụ được lựa chọn để xây dựng hệ thống,
    * **06_Architecture.pdf**,
    * **07_Proof of Concept.docx**: trình bày quá trình nhóm đã thử nghiệm việc hiện thực hóa một tính năng khó về mặt kỹ thuật, và kết quả cụ thể thu được,
    * **07_Proof of Concept.pdf**,
    * **08_Project Management.docx**: trình bày các kết quả ước lượng kích cỡ, thời gian và chi phí cần có để hoàn thành đồ án, các cột mốc quan trọng được nhóm đề xuất. Ngoài ra trong tài liệu này còn có các thông tin sau:
        * Trang 2 chứa thông tin về các thành viên của nhóm, vai trò của thành viên trong nhóm.
        * Trang 3 chứa liên kết đến video trên YouTube quay một buổi team building của nhóm.
        * Trang 4 chứa liên kết và tài khoản truy cập hệ thống tương tác, liên lạc của nhóm (ví dụ Slack, Discord).
        * Trang 5 chứa liên kết và tài khoản truy cập hệ thống quản lý dự án của nhóm (ví dụ Trello, Jira, Asana).
        * Trang 6 chứa liên kết và tài khoản truy cập hệ thống quản lý lỗi của nhóm (ví dụ GitHub issues, GitLab issues, Bitbucket issue trackers).
    * **08_Project Management.pdf**,
    * **09_System Evaluation and Validation.docx**: trình bày cách đăng ký và/hoặc cài đặt các công cụ để kiểm thử hệ thống, phương pháp thực thi việc kiểm thử, các kết quả kiểm thử thu được, các kết quả khảo sát, bảng so sánh hệ thống với các hệ thống tương tự. Ngoài ra, trong tài liệu này còn có các thông tin sau:
        * Trang 2 chứa liên kết đến video trên YouTube biểu diễn quá trình đăng ký hoặc cài đặt các công cụ để kiểm thử hệ thống, phương pháp thực thi việc kiểm thử, và các kết quả kiểm thử thu được.
    * **09_System Evaluation and Validation.pdf**,

* Thư mục **02_Source** chứa các sản phẩm với các tên in đậm sau:
    * **01_Source Code**: Thư mục chứa mã nguồn hệ thống (bao gồm cả các thông tin của source control, các unit tests),
    * **02_Raw Data**: Thư mục chứa các dữ liệu gốc (raw) của hệ thống (nếu có). Ví dụ: các file dữ liệu ảnh (Photoshop), video, audio gốc,
    * **03_Build Scripts**: Thư mục chứa các tập tin cấu hình, kịch bản (scripts) build và tích hợp tự động,
    * **04_Compilation Guide.docx**: Tài liệu hướng dẫn **một nhà phát triển** cách cài đặt môi trường và biên dịch mã nguồn cho máy tính vừa cài đặt xong hệ điều hành và cách thực thi các tập tin cấu hình, kịch bản. Ngoài ra trong tài liệu này còn có các thông tin sau:
        * Trang 2 chứa liên kết và tài khoản để truy cập hệ thống source control của nhóm (ví dụ GitHub).
        * Trang 3 chứa liên kết và tài khoản để truy cập hệ thống build và tích hợp tự động của nhóm (ví dụ GitLab).
        * Trang 4 chứa liên kết đến video trên YouTube biểu diễn quá trình cài đặt môi trường, biên dịch, cấu hình và chạy mã nguồn trên máy một nhà phát triển.
    * **04_Compilation Guide.pdf**,
    * **05_Coding Standards.docx**: thể hiện chuẩn mã nguồn (Coding Standards) hoặc quy ước mã nguồn (Coding Convention) nhóm phát triển cần tuân thủ,
    * **05_Coding Standards.pdf**.
    * Các giảng viên sẽ **KHÔNG** giải quyết các thắc mắc về điểm số nếu mã nguồn không biên dịch được theo tài liệu "04_Compilation Guide.docx" (minh chứng bằng các ảnh chụp màn hình).
    * Các giảng viên sẽ **KHÔNG** giải quyết các thắc mắc về điểm số nếu các liên kết hoặc tài khoản không hoạt động được (minh chứng bằng các ảnh chụp màn hình).

* Thư mục **03_Packages** chứa các sản phẩm với các tên in đậm sau:
    * **01_Deployment_Package**: Thư mục chứa các sản phẩm để cài đặt và triển khai, bao gồm cả các tập tin cấu hình, kịch bản (scripts) để triển khai.
    * **02_Deployment Guide.docx**: Tài liệu hướng dẫn **người quản trị hệ thống** cách đăng ký hoặc cài đặt môi trường triển khai, cách cấu hình hệ thống triển khai/chuyển giao liên tục, mô tả các kịch bản cung cấp và quản lý tài nguyên để vận hành hệ thống (IaaC), mô tả các kết quả thu được khi thực thi các kịch bản triển khai hệ thống lên môi trường Internet và thiết bị thực sự. Ngoài ra trong tài liệu này còn có các thông tin sau:
        * Trang 2 chứa liên kết đến video trên YouTube biểu diễn cách triển khai hệ thống của nhóm.
    * **02_Deployment Guide.pdf**, 
    * **03_User Guide.docx**: Tài liệu hướng dẫn **người dùng cuối** cách cài đặt và sử dụng sản phẩm. Ngoài ra trong tài liệu này còn có các thông tin sau:
        * Trang 2 chứa liên kết đến video trên YouTube giới thiệu cách sử dụng hệ thống của nhóm.
    * **03_User Guide.pdf**.

## 3. Hình thức và thời hạn nộp
Các sản phẩm của đồ án được nộp làm **2 lần**:
* Lần 1:
    * Các nhóm in ra tất cả các sản phẩm trong thư mục **01_Documents**,
    * Demo trực tiếp sản phẩm đã triển khai, **trong 15 phút**, và 
    * Trả lời các câu hỏi liên quan, vào **tuần thứ 6** của môn học đối với lớp CLC, hoặc **tuần thứ 8** của môn học đối với lớp CQ, **tại lớp học lý thuyết**.
* Lần 2:
    * Nhóm trưởng các nhóm nộp bản mềm điện tử tất cả các sản phẩm ở mục 2. trong tài liệu này, không nén, cho lớp trưởng.
    * Đối với các tài liệu, các nhóm **có thể cập nhật** lại nếu cần.
    * Lớp trưởng nén thư mục của toàn lớp lại thành 1 tập tin .zip hoặc .rar, chỉ **một tập tin .zip hoặc .rar duy nhất** cho toàn lớp.
    * Lớp trưởng liên hệ và nộp cho giảng viên **qua email** vào thứ 6, **tuần thứ 11** của môn học đối với lớp CLC, hoặc **tuần thứ 15** của môn học đối với lớp CQ.

## 4. Các tiêu chí đánh giá
* Kết quả **lần 1** được đánh giá dựa trên **các câu hỏi thường gặp** dưới đây:
    * Demo **một vấn đề** được giải quyết bằng hệ thống đã xây dựng (một business case).
    * Demo quy trình nhóm đã áp dụng để xây dựng hệ thống tính đến thời điểm hiện tại thông qua các dữ liệu của bảng Kanban.
    * Demo việc build và tích hợp mã nguồn giữa các thành viên.
    * Tại sao Product Backlog của nhóm lại gồm những stories như đề xuất?
    * Bao giờ thì toàn bộ Product Backlog của nhóm có thể hoàn thành? Tại sao?
    * Giải thích Development View của kiến trúc thông qua hệ thống thư mục và việc build toàn bộ các thành phần hệ thống.
    * Giải thích Logical View, Process View của kiến trúc thông qua mã nguồn của một story đã được hoàn thành.
    * Giải thích Deployment View của kiến trúc thông qua hệ thống đã triển khai.

* Kết quả **lần 2** của đồ án được đánh giá dựa trên 4 yếu tố:
    * Việc hoàn thành toàn bộ và chất lượng nội dung của các sản phẩm ở mục 2. trong tài liệu này.
    * Việc hoàn thành toàn bộ Product Backlog và việc thể hiện được các business cases thông qua hệ thống đã xây dựng.
    * Việc so sánh kết quả của đồ án với 1 hệ thống tương tự.
    * Việc hoàn thành **các yêu cầu kỹ thuật** dưới đây của môn học. Các yêu cầu này có thể được giảng viên hiệu chỉnh lại trong quá trình học, tùy theo tình hình lớp học.
        * Đồ án phải áp dụng microservices.
        * Đồ án phải áp dụng các thư viện hỗ trợ giao diện có sẵn (ví dụ React, Bootstrap).
        * Đồ án phải có áp dụng RESTful API, gRPC API, và GraphQL API.
        * Đồ án **KHÔNG** tự thực hiện phần identity and access (authentication/authorization) management, mà **phải** sử dụng công cụ có sẵn (ví dụ Keycloak, Okta).
        * Đồ án phải có áp dụng domain-driven design.
        * Đồ án phải có áp dụng test automation.
        * Đồ án phải có áp dụng continuous deployment.
        * Đồ án phải có áp dụng load balancing.
        * Đồ án phải có áp dụng database replication and sharding.
        * Đồ án phải có áp dụng event sourcing.
        * Đồ án được _khuyến khích_ áp dụng event-driven architecture.

### &copy; 2024 Ngô Huy Biên
