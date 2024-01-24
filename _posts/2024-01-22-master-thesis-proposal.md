---
layout: post
title: "Hướng dẫn viết đề cương cao học, lĩnh vực khoa học máy tính, hệ thống thông tin, công nghệ phần mềm"
categories: [Luận văn cao học]
author:
- Ngô Huy Biên
meta: "Master Thesis Proposal"
---
_Tài liệu hướng dẫn viết đề cương cao học, lĩnh vực khoa học máy tính, hệ thống thông tin, công nghệ phần mềm, do giảng viên Ngô Huy Biên hướng dẫn._

## 1. Xác định vấn đề
* Học viên chọn **một bài báo** yêu thích và tìm hiểu **vấn đề** bài báo đề cập và **giải pháp** đề xuất.
* Nếu học viên chưa có bài báo yêu thích thì có thể tìm theo chủ đề mình quan tâm trên <a target = "blank" href = "https://scholar.google.com/">Google Scholar</a> hoặc <a target = "blank" href = "https://paperswithcode.com/">Paper with Code</a>.
* **Hướng 1.1**: Nếu bài báo **không công bố mã nguồn/thư viện/hệ thống** thì học viên có thể xem xét việc xây dựng lại mã nguồn/thư viện/hệ thống theo đề xuất để đánh giá xem có thực là giải pháp khả thi hay không. Nếu theo hướng này học viên cần tạo trước được học viên cần **tạo trước** được mã nguồn Proof of Concept từ bài báo để đảm bảo giải pháp là khả thi. Khi đó bài báo có thể dùng cho phần phân tích tiếp theo.
* **Hướng 1.2**: Nếu bài báo **đã có sẵn mã nguồn/thư viện/hệ thống** (do đó không cần tạo mã nguồn Proof of Concept nữa) thì học viên **cần có hệ thống riêng của mình** hoặc **một hệ thống mã nguồn mở** để áp dụng giải pháp vào, và để đánh giá xem vấn đề có thực sự được giải quyết hay không. Mã nguồn của hệ thống riêng sẽ phải công bố sau này. Nếu học viên có hệ thống riêng hoặc tìm được hệ thống mã nguồn mở phù hợp thì bài báo có thể dùng cho phần phân tích tiếp theo.
* **Hướng 1.3**: Nếu bài báo **đã có sẵn mã nguồn/thư viện/hệ thống** (do đó không cần tạo mã nguồn Proof of Concept nữa) và học viên có các ý tưởng để **mở rộng mã nguồn** thì bài báo có thể dùng cho phần phân tích tiếp theo.
* Học viên chọn cụ thể một hướng đi trong 3 hướng ở trên để phân tích tiếp theo.
* Học viên phân tích bài báo theo các định hướng dưới đây:
    * #### Hướng 1.1
        * Tại sao lại cần xây dựng mã nguồn cho giải pháp đề xuất? Nhu cầu thực sự là gì?
        * Mã nguồn sẽ được đánh giá như thế nào?
    * #### Hướng 1.2
        * Học viên dự định áp dụng giải pháp để **giải quyết bài toán cụ thể** nào? Bài toán đó được mô hình cụ thể như thế nào? Học viên có thể mô hình bằng, nhưng không giới hạn: các business use case, các giao diện, các lược đồ, các mô hình toán học. Phần **Introduction** của bài báo có thể hỗ trợ thông tin trả lời cho câu hỏi này.
        * Giải pháp thủ công (trivial solution) để giải quyết vấn đề/bài toán là gì?
        * Đã có những giải pháp nào khác đã được đề xuất để giải quyết vấn đề này? Thông thường, phần **Related Work** của bài báo sẽ hỗ trợ trả lời cho câu hỏi này.
        * Dựa trên các **tiêu chí hay độ đo** nào, ví dụ: feasibility, performance, scalability, security, cost, time, mean opinion score, BLEU score, ROUGE score, để so sánh các giải pháp trên với nhau (**quan trọng**)? Phần **Evaluation**, hoặc **Performance**, hoặc **Experience** của bài báo có thể hỗ trợ thông tin trả lời cho câu hỏi này. Học viên có thẻ chỉ cần chọn một hoặc hai tiêu chí là đủ. Học viên cần lưu ý nếu chọn tiêu chí feasibility thì phải chưa có nghiên cứu có hoàn cảnh tương tự nào được thực hiện.
        * Học viên dự định thu thập các **dữ liệu** nào để đánh giá các tiêu chí hay độ đo ở trên (**quan trọng**)?
        * Giải pháp đề xuất đã được ứng dụng ở hệ thống phần mềm thực tế nào hay chưa?
        * Học viên dự định sẽ chọn hệ thống nào để so sánh với hệ thống của mình.
    * #### Hướng 1.3
        * Giải pháp có vấn đề gì, thiếu sót gì mà cần mở rộng? Ý tưởng mở rộng là gì? Ai là người có nhu cầu, sẽ quan tâm?
        * Dự kiến mã nguồn/thư viện/hệ thống có thể mở rộng ở đâu. Phần **Conclusion** hoặc **Future Work** của bài báo có thể hỗ trợ hỗ trợ thông tin cho phần phân tích này.
        * Học viên có thể xem xét mở rộng bằng cách hiệu chỉnh mã nguồn có sẵn cho một **bộ dữ liệu khác**, trong một **môi trường khác**, trong một **lĩnh vực khác**. Phần **Experiments** hoặc **Case Study** của bài báo có thể hỗ trợ thông tin cho việc phân tích này.
* Tên đề tài học viên đề xuất là gì? Thường có thể là "Giải pháp XYZ cho bài toán ABC", hoặc "Hệ thống ABC dựa trên giải pháp XYZ".
* Học viên gửi kết quả tìm hiểu ở mục 1. dưới dạng một file PDF cho giảng viên để thảo luận và thống nhất **tên đề tài**, **bài toán** và **phạm vi**, sau đó nhận xác nhận của giảng viên để bắt đầu viết đề cương.
* Học viên cần **hoàn thành mục 1. trước** thời hạn nộp đơn đăng ký thực hiện luận văn của Trường **ít nhất là 1 tháng**.
  
## 2. Nội dung đề cương

### 2.1. Giới thiệu tổng quan
* Học viên cần trình bày ít nhất **một hệ thống thực tế** đã giải quyết vấn đề/bài toán tương tự.
* Phát biểu vấn đề/bài toán sẽ giải quyết.
* Tóm tắt ngắn gọn lịch sử một số hướng tiếp cận nổi bật, bao gồm cả giải pháp thủ công (trivial solution), cho bài toán.

### 2.2. Mục đích nghiên cứu
Học viên cần trình bày lý do thực hiện đề tài. Một số lý do thường gặp là 
* Muốn áp dụng mã nguồn giải pháp XYZ cho bài toán ABC trong một môi trường cụ thể (thường là trong một dự án của một công ty cụ thể).
* Muốn hiệu chỉnh mã nguồn giải pháp XYZ cho bài toán ABC trong một lĩnh vực mới (thường kết quả sẽ là một dự án open source).
* Muốn thử nghiệm mã nguồn giải pháp XYZ cho bài toán ABC trên một bộ dữ liệu mới (thường bộ dữ liệu mới là tiếng Việt).
* Muốn thử nghiệm mã nguồn giải pháp XYZ cho bài toán ABC nhằm hỗ trợ giải quyết một bài toán khác (thường kết quả sẽ hỗ trợ cải tiến tính nằng của một hệ thống đang vận hành).

### 2.3. Phần Đối tượng nghiên cứu
Học viên cần liệt kê các sản phẩm đã có sẵn, mô tả nội dung các sản phẩm, có thể bao gồm nhưng không giới hạn các sản phẩm sau:
* Giải pháp dự kiến áp dụng, học viên cần mô tả chi tiết **quy trình**, **kiến trúc**, **thuật toán**, **ngôn ngữ lập trình**, và **các công cụ** của giải pháp XYZ đề xuất bởi bài báo đã tìm hiểu. Học viên cần cung cấp liên kết đến các mã nguồn đã công bố có thể tải về được, dạng footnote, nếu bài báo đã có mã nguồn.
* Các nguồn **dữ liệu và mã nguồn có sẵn** dự kiến sẽ được dùng để nghiên cứu, học viên cần mô tả chi tiết cấu trúc của nguồn dữ liệu và mã nguồn này. Học viên cần cung cấp liên kết đến các bộ dữ liệu có thể tải về được, dạng footnote.
* Ảnh chụp kết quả chạy thử nghiệm mã nguồn và dữ liệu có sẵn nếu mã nguồn và dữ liệu đã có.
* Các **độ đo** sẽ dùng để so sánh, đánh giá các kết quả thu được.
* Kết quả hay hệ thống sẽ dùng để so sánh với các kết quả sẽ thu được. Học viên cần cung cấp liên kết đến các kết quả hay hệ thống này, dạng footnote.
* Danh sách những người dự kiến sẽ khảo sát (nếu có).
* Danh sách các công nghệ, công cụ, tài nguyên dự định sẽ sử dụng.

### 2.4. Các phương pháp nghiên cứu
Học viên cần liệt kê các công việc dự kiến sẽ tiến hành, _có thể_ bao gồm nhưng không giới hạn các công việc sau:
* Viết mã nguồn giải pháp XYZ để chứng minh giải pháp đề xuất là khả thi.
* Viết mã nguồn giải pháp XYZ cho hoàn cảnh MNK.
* Chỉnh sửa mã nguồn giải pháp XYZ cho phù hợp với hoàn cảnh MNK.
* Viết mã nguồn các công cụ hỗ trợ giải quyết bài toán ABC.
* Thu thập, phân tích dữ liệu để so sánh kết quả **sau khi** áp dụng XYZ với **trước khi** áp dụng dựa trên các độ đo.
* Khảo sát ý kiến, xây dựng bảng đánh giá kết quả của việc áp dụng XYZ vào bài toán ABC.
* Xác định, giải quyết và tài liệu hóa các vấn đề tiềm ẩn.
* Viết các các tài liệu kỹ thuật hướng dẫn chi tiết phương pháp tái tạo các sản phẩm.
* Viết luận văn tổng kết lại toàn bộ quá trình thực hiện luận văn và mô tả, giải thích, thảo luận các kết quả.
Các đề tài liên quan đến học máy, _có thể_ bao gồm thêm nhưng không giới hạn các công việc sau:
* Chuẩn bị dữ liệu.
* Tạo dữ liệu mới.
* Chỉnh sửa mã nguồn mô hình.
* Viết mã nguồn mới cho mô hình hay công cụ hỗ trợ.
* Huấn luyện mô hình.
* Đánh giá mô hình dựa trên dữ liệu thực nghiệm và độ đo.
* Khảo sát ý kiến, xây dựng bảng đánh giá mô hình.
* Viết mã nguồn hệ thống triển khai và biểu diễn mô hình.
* Khảo sát ý kiến, xây dựng bảng đánh giá kết quả của hệ thống với các hệ thống tương tự trong việc giải quyết vấn đề đặt ra.

### 2.5. Nội dung và phạm vi của vấn đề sẽ đi sâu nghiên cứu
Học viên cần liệt kê các sản phẩm **KHÁC** với những gì đã có sẵn, dự kiến thu được, _có thể_ bao gồm nhưng không giới hạn các sản phẩm sau:
* Mã nguồn hệ thống phần mềm (ứng dụng di động, ứng dụng web, dịch vụ web, công cụ hỗ trợ) được chỉnh sửa/tạo thêm/tạo mới.
* Dữ liệu hệ thống phần mềm được chỉnh sửa/tạo thêm/tạo mới.
* Hệ thống phần mềm sẽ được triển khai.
* Dữ liệu kiểm thử hệ thống phần mềm.
* Báo cáo so sánh với các hệ thống tương tự,
* Các bảng dữ liệu khảo sát, 
* Dữ liệu lịch sử thể hiện việc áp dụng quy trình, thực hiện thí nghiệm,
* Các tài liệu kỹ thuật hướng dẫn chi tiết phương pháp tái tạo các sản phẩm.
* Bản luận văn hoàn chỉnh mô tả chi tiết cơ sở lý thuyết và các kết quả thu được, 
* Bài báo 4 trang tóm tắt lại luận văn (không bắt buộc).

Các đề tài liên quan đến học máy, _có thể_ bao gồm thêm nhưng không giới hạn các sản phẩm sau:
* Mã nguồn huấn luyện mô hình học máy, mã nguồn dịch vụ triển khai mô hình, mã nguồn công cụ hỗ trợ được chỉnh sửa/tạo thêm/tạo mới.
* Dữ liệu huấn luyện mô hình học máy được chỉnh sửa/tạo thêm/tạo mới.
* Mã nguồn ứng dụng biểu diễn việc sử dụng mô hình học máy đã được triển khai.

### 2.6. Nơi thực hiện đề tài nghiên cứu của luận văn
Học viên cần thể hiện các nơi làm việc thực sự trong quá trình thực hiện luận văn.

### 2.7. Thời gian thực hiện
Học viên cần tạo bảng kế hoạch với những cột mốc phù hợp để hoàn thành luận văn, dựa vào _những sản phẩm có sẵn_ trong phần 2.3, _những công việc dự kiến_ sẽ thực hiện trong phần 2.4, _các sản phẩm dự kiến_ sẽ tạo ra trong phần 2.5, các cột mốc thời gian của nhà Trường, và nguồn nhân lực và tài nguyên hiện có.

### 2.8. Tài liệu tham khảo
* Học viên liệt kê các sách và bài báo, bao gồm bài báo ở phần 1. và ít nhất thêm 4 tài liệu là các sách, bài báo liên quan.
* Học viên **KHÔNG** sử dụng các liên kết trong phần này. Các liên kết trong đề cương nếu có, , ví dụ liên kết đến mã nguồn hoặc dữ liệu trên GitHub, học viên viên để trong Footnote tại trang đề cập.
* Học viên cần thể hiện các tài liệu tham khảo theo đúng chuẩn thông dụng. Học viên nên sử dụng tính năng Cite (thể hiện bằng dấu nháy) của <a href target = "blank" href = "https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Efficient+backprop">Google Scholar</a> để xem mẫu trình bày tài liệu tham khảo. Học viên nên chọn chuẩn APA.

## 3. Công cụ viết đề cương
* Học viên **phải** sử dụng LaTeX để viết đề cương.
* Học viên có thể đăng ký tài khoản trang web của <a target = "blank" href = "https://www.overleaf.com/">Overleaf</a> để viết đề cương.
* Học viên có thể hiệu chỉnh lại <a target = "blank" href = "https://www.overleaf.com/read/qxbpwhmkcfbh#94c634">biểu mẫu khóa luận (đại học) của Khoa</a> để viết đề cương.

### &copy; 2024 Ngô Huy Biên
