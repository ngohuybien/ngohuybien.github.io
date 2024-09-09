---
layout: post
title: "Các sản phẩm cần nộp của đồ án môn học quản lý dự án phần mềm"
categories: [Software Project Management]
author:
- Ngô Huy Biên
meta: "Software Project Management Artifacts"
---
_Tài liệu mô tả các sản phẩm cần nộp cho đồ án của môn học Software Project Management._

## 1. Quy định chung
* Điểm đồ án giữa kỳ được tự động **chia đều** cho các thành viên trong nhóm.
* Điểm đồ án cuối kỳ được tự động **chia đều** cho các thành viên trong nhóm.
* Nếu nhóm có mong muốn **tự chia điểm đồ án cuối kỳ** theo **tỷ lệ riêng**, thì cần ghi rõ thông tin từng thành viên và tỷ lệ điểm từng thành viên sẽ được nhận, ví dụ 50%, 120%, 150%, trong trang bìa **từng sản phẩm**. Tỷ lệ điểm từng thành viên sẽ được nhận cần giống hệt nhau ở tất cả các sản phẩm. Tổng số % của nhóm = Số thành viên x 100%. Nếu thành viên nào có % x Tổng điểm lớn hơn 10, thì điểm của thành viên cũng chỉ được tính là 10. Đồng thời trưởng nhóm cần thông báo cho giảng viên mong muốn tự chia điểm **trước** khi nộp kết quả đồ án cuối kỳ.
* Kết quả đồ án được đánh giá theo số thành viên thực sự hoạt động của nhóm. Do vậy, nếu nhóm có thành viên bỏ nhóm, hoặc không thực hiện đồ án, trưởng nhóm cần **thông báo trực tiếp cho giảng viên vào buổi vấn đáp đồ án giữa kỳ**, để các nhóm được đánh giá công bằng với nhau.

## 2. Quy định tổ chức và đặt tên thư mục
* Mỗi nhóm cần đặt tên thư mục gốc là Nhom_X, không dấu, X là số thứ tự nhóm, ghi dưới dạng 2 chữ số, ví dụ: 01, 02, 03, 04.
* Trong thư mục gốc bao gồm 3 thư mục chính.
    * **01_Documents**: chứa các tài liệu của dự án,
    * **02_Source**: chứa mã nguồn lấy từ source control về, dữ liệu hệ thống, và các tài liệu liên quan đến biên dịch.
    * **03_Packages**: chứa file cài đặt và các tài liệu liên quan việc triển khai và cài đặt.
      
<div align="center">
<img src ="https://ngohuybien.github.io/assets/images/project-folder-structure.png" alt = "Cây thư mục và tên sản phẩm" width="1024">
</div>
<div align="center">
<br>
<i>Hình minh họa tổ chức cây thư mục và tên sản phẩm.</i>
</div>

## 3. Định dạng các sản phẩm
* Các sản phẩm thường ở dạng **DOCX**, **XLSX**, hoặc **ZIP** (nếu sản phẩm gồm nhiều tập tin).
* Các sản phẩm không phải dạng ZIP cần được export ra bản **PDF** tương ứng nhằm đảm bảo việc kiểm tra sản phẩm không gặp vấn đề về font chữ hay layout.
* Các hệ thống trực tuyến của nhóm cần để **chế độ công khai** (Public) trừ trường hợp nhà cung cấp không cho phép.
* Các tài liệu của môn học cần **đơn giản**, diễn giải **đủ các khía cạnh**, dễ hiểu, hỗ trợ tốt cho việc liên lạc, tương tự như những gì đã được minh họa trên lớp.

## 4. Danh sách các sản phẩm cần nộp, và quy định đặt tên tập tin
* Các sản phẩm dưới đây là **bắt buộc**, nhưng không giới hạn. Các nhóm có thể nộp thêm các sản phẩm tự đề xuất trong quá trình thực hiện đồ án.
* Danh sách các sản phẩm này có thể được giảng viên hiệu chỉnh lại trong quá trình học, tùy theo tình hình lớp học.
* Thư mục **01_Documents** chứa các sản phẩm với các **tên in đậm** sau:
    * **01_Executive Summary.docx**: Tài liệu Tóm tắt dự án (Tổng quan về dự án, Business Requirements),
    *	**01_Executive Summary.pdf**,
    * **02_Project Vision and Scope.docx**: Tài liệu Viễn cảnh và phạm vi dự án (Tầm nhìn và phạm vi dự án, User Requirements),
    * **02_Project Vision and Scope.pdf**,
    * **03_Software Requirements.docx**: Tài liệu Yêu cầu phần mềm, tùy theo mô hình nhóm lựa chọn mà có nội dung tương ứng.
    * **03_Software Requirements.pdf**,
    * **04_Project Charter.docx**: Tài liệu Ủy nhiệm dự án,
    * **04_Project Charter.pdf**,
    * **05_Prototype.psd hoặc 05_Prototype_HTMLs.zip**: Trình bày giao diện từng bước của ít nhất một luồng quy trình nghiệp vụ,
    * **05_Prototype.pdf**,
    * **06_Proof of Concept.docx**: Trình bày quá trình nhóm đã thử nghiệm việc hiện thực hóa một tính năng khó về mặt kỹ thuật, và kết quả cụ thể thu được,
    * **06_Proof of Concept.pdf**,
    * **07_Architecture.docx**: Trình bày kiến trúc hệ thống theo các góc nhìn khác nhau, các công nghệ, công cụ được lựa chọn để xây dựng hệ thống,
    * **07_Architecture.pdf**,
    * **08_Feasibility Study Report.docx**: Tài liệu Phân tích tính khả thi của dự án.
    * **08_Feasibility Study Report.pdf**,
    * **09_Software Process Definition.docx**: Tài liệu Định nghĩa quy trình nhóm đề xuất dùng để phát triển phần mềm.
    * **09_Software Process Definition.pdf**,
    * **10_Project Estimate.docx**: Tài liệu Ước lượng ước lượng thời gian, chi phí, nhân lực cho dự án.
    * **10_Project Estimate.pdf**,
    * **11_Project Plan.docx**: Tài liệu Kế hoạch thực hiện dự án.
    * **11_Project Plan.pdf**,
    * **12_Statement of Work.docx**: Tài liệu Phát biểu công việc của dự án.
    * **12_Statement of Work.pdf**,
    * **13_Software Configuration Management Plan.docx**: Tài liệu Kế hoạch quản lý cấu hình của dự án. Ngoài ra trong tài liệu này còn có các thông tin sau:
        * Trang 2 chứa liên kết và tài khoản truy cập hệ thống tương tác, liên lạc của nhóm (ví dụ Slack, Discord).
        * Trang 3 chứa liên kết và tài khoản truy cập hệ thống quản lý yêu cầu của nhóm (ví dụ Confluence).
        * Trang 4 chứa liên kết và tài khoản truy cập hệ thống quản lý công việc của nhóm (ví dụ Trello, Jira Software, Asana).
        * Trang 5 chứa liên kết và tài khoản truy cập hệ thống quản lý mã nguồn của nhóm (ví dụ GitHub, GitLab).
        * Trang 6 chứa liên kết và tài khoản truy cập hệ thống quản lý việc tích hợp và chuyển giao liên tục (CI/CD/DevOps) phần mềm của nhóm (ví dụ CircleCI, GitLab, Azure DevOps, Render, Vercel).
        * Trang 7 chứa liên kết và tài khoản truy cập hệ thống quản lý lỗi của nhóm (ví dụ GitHub issues, GitLab issues, Bitbucket issue trackers, Jira).
    * **13_Software Configuration Management Plan.pdf**, 
    * **14_Project Status Report_Week 06.docx**: Tài liệu Báo cáo tình trạng của dự án tính đến tuần 6.
    * **14_Project Status Report_Week 06.pdf**,
    * **15_Meeting Minutes_Week 06.docx**: Biên bản buổi họp trong tuần 6 của nhóm.
    * **15_Meeting Minutes_Week 06.pdf**,
    * **16_Team Building.mp4**: Video team building của nhóm.
    * **17_Software Risk Management Plan.docx**: Tài liệu Kế hoạch quản lý rủi ro của dự án.
    * **17_Software Risk Management Plan.pdf**,
    * **18_Software Quality Management Plan.docx**: Tài liệu Kế hoạch quản lý chất lượng của dự án.
    * **18_Software Quality Management Plan Plan.pdf**,
    * **19_Lessons Learned.docx**: Tài liệu Báo cáo kinh nghiệm rút ra sau khi thực hiện dự án của nhóm.
    * **19_Lessons Learned.pdf**,
      
* Thư mục **02_Source** chứa các sản phẩm với các tên in đậm sau:
    * **01_Source Code**: Thư mục chứa mã nguồn hệ thống (bao gồm cả các thông tin của source control, các unit tests),
    * **02_Raw Data**: Thư mục chứa các dữ liệu gốc (raw) của hệ thống (nếu có). Ví dụ: các file dữ liệu ảnh (Photoshop), video, audio gốc,
    * **03_Build Scripts**: Thư mục chứa các tập tin cấu hình, kịch bản (scripts) build và tích hợp tự động,
    * **04_Compilation Guide.docx**: Tài liệu hướng dẫn **một nhà phát triển** cách cài đặt môi trường và biên dịch mã nguồn cho máy tính vừa cài đặt xong hệ điều hành và cách thực thi các tập tin cấu hình, kịch bản. Ngoài ra trong tài liệu này còn có các thông tin sau:
        * Trang 2 chứa liên kết đến video trên YouTube biểu diễn quá trình cài đặt môi trường, biên dịch, cấu hình và chạy mã nguồn thành công trên máy một nhà phát triển.
    * **04_Compilation Guide.pdf**,
    * **05_Coding Standards.docx**: thể hiện chuẩn mã nguồn (Coding Standards) hoặc quy ước mã nguồn (Coding Convention) nhóm phát triển cần tuân thủ,
    * **05_Coding Standards.pdf**.
    * Các giảng viên sẽ **KHÔNG** giải quyết các thắc mắc về điểm số nếu mã nguồn không biên dịch được theo tài liệu "04_Compilation Guide.docx" (minh chứng bằng các ảnh chụp màn hình).
    * Các giảng viên sẽ **KHÔNG** giải quyết các thắc mắc về điểm số nếu các liên kết hoặc tài khoản không hoạt động được (minh chứng bằng các ảnh chụp màn hình).

* Thư mục **03_Packages** chứa các sản phẩm với các tên in đậm sau:
    * **01_Deployment_Package**: Thư mục chứa các sản phẩm để cài đặt và triển khai, bao gồm cả các tập tin cấu hình, kịch bản (scripts) để triển khai.
    * **02_Deployment Guide.docx**: Tài liệu hướng dẫn **người quản trị hệ thống** cách đăng ký hoặc cài đặt môi trường triển khai, cách cấu hình hệ thống triển khai/chuyển giao liên tục, mô tả các kịch bản cung cấp và quản lý tài nguyên để vận hành hệ thống (IaaC), mô tả các kết quả thu được khi thực thi các kịch bản triển khai hệ thống lên môi trường Internet và thiết bị thực sự. Ngoài ra trong tài liệu này còn có các thông tin sau:
        * Trang 2 chứa liên kết đến video trên YouTube biểu diễn cách triển khai và chạy thành công hệ thống của nhóm trên môi trường thực.
    * **02_Deployment Guide.pdf**, 
    * **03_User Guide.docx**: Tài liệu hướng dẫn **người dùng cuối** cách cài đặt và sử dụng sản phẩm. Ngoài ra trong tài liệu này còn có các thông tin sau:
        * Trang 2 chứa liên kết đến video trên YouTube giới thiệu cách sử dụng hệ thống của nhóm để giải quyết từng vấn đề của người dùng.
    * **03_User Guide.pdf**.

## 5. Hình thức và thời hạn nộp
Các sản phẩm của đồ án được nộp làm **2 lần**:
* Lần 1 (giữa kỳ):
    * Các nhóm in ra tất cả các sản phẩm đã được dạy trong thư mục **01_Documents**,
    * Demo trực tiếp sản phẩm đã triển khai, **trong 15 phút**, và 
    * Trả lời các câu hỏi của giảng viên, vào **tuần thứ 6** của môn học đối với lớp CLC, hoặc **tuần thứ 8** của môn học đối với lớp CQ, **tại lớp học lý thuyết**.
    * Chỉ những bạn sinh viên có mặt ở buổi kiểm tra mới có điểm đồ án giữa kỳ.
* Lần 2 (cuối kỳ):
    * Nhóm trưởng các nhóm nộp bản mềm điện tử tất cả các sản phẩm ở mục 2. trong tài liệu này, không nén, cho lớp trưởng.
    * Đối với các tài liệu, các nhóm **có thể cập nhật** lại nếu cần.
    * Lớp trưởng nén thư mục của toàn lớp lại thành 1 tập tin .zip hoặc .rar, chỉ **một tập tin .zip hoặc .rar duy nhất** cho toàn lớp.
    * Lớp trưởng liên hệ và nộp cho giảng viên **qua email** vào thứ 6, **tuần thứ 11** của môn học đối với lớp CLC, hoặc **tuần thứ 15** của môn học đối với lớp CQ.

## 6. Các tiêu chí đánh giá
* Kết quả **lần 1 (giữa kỳ)** được đánh giá dựa trên **các câu hỏi thường gặp** dưới đây:
    * Demo **một vấn đề** được giải quyết bằng hệ thống đã xây dựng (một business case).
    * Demo **quy trình** nhóm đã áp dụng để quản lý dự án tính đến thời điểm hiện tại thông qua **các dữ liệu đã được thu thập** trên các hệ thống quản lý.
    * Lý giải tại sao Yêu cầu phần mềm của nhóm lại có nội dung như đề xuất?
    * Khi nào thì dự án của nhóm có thể hoàn thành? Tại sao?
    * Demo việc build, tích hợp, và triển khai tự động mã nguồn của nhóm.

* Kết quả **lần 2 (cuối kỳ)** của đồ án được đánh giá dựa trên 4 yếu tố:
    * Việc hoàn thành **toàn bộ** và **chất lượng** nội dung của các sản phẩm ở mục 4. trong tài liệu này.
    * **Các dữ liệu** thu thập được trên các hệ thống quản lý thể hiện nhóm đã thực hiện dự án theo quy trình đề ra.
    * Việc hoàn thành toàn bộ Yêu cầu phần mềm nhóm đã đề xuất thông qua hệ thống đã xây dựng.
    * Việc so sánh kết quả của đồ án với 1 hệ thống tương tự.

### &copy; 2024 Ngô Huy Biên
