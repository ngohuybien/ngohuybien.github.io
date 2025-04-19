---
layout: post
title: "Hướng dẫn lựa chọn chủ đề cho luận văn cao học, lĩnh vực khoa học máy tính, hệ thống thông tin, công nghệ phần mềm"
categories: [Luận văn cao học]
author:
- Ngô Huy Biên
meta: "Master Thesis Topic Selection"
---
_Tài liệu hướng dẫn lựa chọn chủ đề cho luận văn cao học, lĩnh vực khoa học máy tính, hệ thống thông tin, công nghệ phần mềm, do giảng viên Ngô Huy Biên hướng dẫn._

## 1. Xác định vấn đề và giải pháp
* Học viên chọn **một bài báo** yêu thích và tìm hiểu **vấn đề** bài báo đề cập và **giải pháp** đề xuất của bài báo.
* Nếu học viên chưa có bài báo yêu thích thì có thể tìm theo từ khóa chủ đề mình quan tâm trên <a target = "blank" href = "https://scholar.google.com/">Google Scholar</a> hoặc <a target = "blank" href = "https://paperswithcode.com/">Paper with Code</a>.
* Học viên cần chọn bài báo **gần nhất**, hoặc bài báo **có hiệu quả thực sự** vẫn còn tính ứng dụng, liên quan đến chủ đề mình quan tâm, và chỉ cần một bài báo là đủ. Luận văn sẽ tập trung vào việc tạo ra kết quả, và so sánh kết quả đó với kết quả của bài báo được lựa chọn.
* Bài báo được chọn, nếu tốt, sẽ có sẵn cách so sánh, kết quả so sánh với giải pháp trước đó, và thường có cả mã nguồn/thư viện/hệ thống/dữ liệu. Cách tiến hành thực nghiệm và đánh giá của bài báo thường sẽ được dùng để định hướng quá trình thực hiện luận văn.

## 2. Lựa chọn hướng đi
* #### Hướng 1 - Xây dựng lại giải pháp
    * Nếu bài báo **không công bố mã nguồn/thư viện/hệ thống/dữ liệu** thì học viên có thể xem xét việc xây dựng lại mã nguồn/thư viện/hệ thống/dữ liệu theo đề xuất để đánh giá xem có thực là giải pháp khả thi hay không.
    * Học viên có thể tái sử dụng các mã nguồn/thư viện/hệ thống/dữ liệu mở có liên quan để xây dựng lại giải pháp.
    * Nếu theo hướng này học viên cần **tạo trước** được mã nguồn Proof of Concept từ nội dung bài báo. Nếu học viên tạo được mã nguồn Proof of Concept thì bài báo có thể dùng cho phần phân tích tiếp theo.
* #### Hướng 2 - Áp dụng giải pháp vào hệ thống khác
    * Nếu bài báo **đã có sẵn mã nguồn/thư viện/hệ thống/dữ liệu** (do đó không cần tạo mã nguồn Proof of Concept nữa) thì học viên **cần có hệ thống riêng của mình** hoặc **tìm được một hệ thống mã nguồn mở phù hợp** để áp dụng giải pháp vào.
    * Mục đích là để đánh giá xem **vấn đề trong hệ thống riêng này** có thực sự cần phải giải quyết như bài báo đề cập hay không, và giải pháp đề xuất trong bài báo có thực sự giải quyết được vấn đề trong hệ thống riêng này hay không.
    * Mã nguồn của hệ thống riêng của học viên sẽ phải công bố sau này.
    * Nếu học viên có hệ thống riêng hoặc tìm được hệ thống mã nguồn mở phù hợp thì bài báo có thể dùng cho phần phân tích tiếp theo.
* #### Hướng 3 - Cải tiến giải pháp
    * Nếu bài báo **đã có sẵn mã nguồn/thư viện/hệ thống/dữ liệu** (do đó không cần tạo mã nguồn Proof of Concept nữa), và từ nền tảng và kinh nghiệm của mình, học viên có các ý tưởng để **mở rộng mã nguồn hoặc dữ liệu** thì bài báo có thể dùng cho phần phân tích tiếp theo.
    * Học viên cũng có thể chọn **mở rộng mã nguồn hoặc dữ liệu** nếu trong quá trình tìm hiểu bài báo học viên phát hiện các vấn đề có thể xảy ra đối với giải pháp đề xuất, hoặc học viên có hứng thú và khả năng giải quyết một số vấn đề tồn đọng, chưa được giải quyết triệt để, được bài báo đề cập.
    * Ví dụ: Các mô hình nhận dạng âm thanh tiếng Việt (trừ các mô hình của Google hay Microsoft) còn các hạn chế sau:
        * Mô hình chưa có độ chính xác cao đối với đầu vào là các từ ngẫu nhiên do dữ liệu huấn luyện chưa đủ lớn.
        * Mô hình chưa nhận tốt được các dấu câu, các từ tiếng Anh lẫn vào, và các tên riêng.
        * Hệ thống áp dụng mô hình chưa có khả năng nhận dạng liên tục theo thời gian thực do tốc độ thực thi chưa đủ nhanh.
        * Hệ thống áp dụng mô hình có chi phí triển khai còn rất tốn kém.

Học viên chọn cụ thể 1 trong 3 hướng đi ở trên để phân tích tiếp theo.

## 3. Phân tích giải pháp
Học viên phân tích giải pháp theo **một hướng đi cụ thể** đã lựa chọn. Mục đích chính của việc phân tích này là xác định được **bài toán cụ thể**, thực sự cần giải quyết?

   * #### Hướng 1 - Xây dựng lại giải pháp
       * Giải pháp đề xuất đã được ứng dụng ở hệ thống phần mềm thực tế nào hay chưa?
       * Tại sao lại cần xây dựng mã nguồn hay dữ liệu cho giải pháp đề xuất? Ai là người có nhu cầu? Nhu cầu thực sự là gì?
       * Mã nguồn hay dữ liệu sẽ được đánh giá như thế nào?
       * Các bảng dữ liệu khảo sát, nếu có, sẽ có cấu trúc như thế nào? Lý do thu thập dữ liệu khảo sát là gì?
         
   * #### Hướng 2 - Áp dụng giải pháp vào hệ thống khác
       * Mã nguồn/thư viện/hệ thống/dữ liệu có sẵn có thể tải về từ đâu, hoặc sử dụng trực tiếp ở đâu?
       * Kết quả sau khi chạy mã nguồn/thư viện/hệ thống/dữ liệu có sẵn là gì?
       * Kết quả đánh giá từ mã nguồn/thư viện/hệ thống/dữ liệu có sẵn như thế nào?
       * Giải pháp đề xuất đã được ứng dụng ở hệ thống phần mềm thực tế nào hay chưa?
       * Học viên dự định áp dụng giải pháp để giải quyết **bài toán cụ thể** nào, trong **hệ thống cụ thể** nào? Bài toán đó được mô hình cụ thể như thế nào? Học viên có thể mô hình bằng, nhưng không giới hạn: các nghiệp vụ thực tế (business use cases), các giao diện, các lược đồ, các mô hình toán học. Phần **Introduction** của bài báo có thể hỗ trợ thêm thông tin cho phần phân tích này.
       * Điểm quan trọng cần lưu ý ở đây là **bài toán cụ thể** đề tài dự định giải quyết cần nhất quán với bài toán mà bài báo đề cập. Nghĩa là bài toán cụ thể có thể có phạm vi trùng khớp, hoặc nhỏ hơn, hoặc lớn hơn phạm vi bài toán bài báo đề xuất, nhưng cả hai đều phải có chung vấn đề quan tâm, và cùng hướng đến các tiêu chí đánh giá giống nhau. Phần **Related Work**, **Evaluation**,  **Performance**, hoặc **Experience** của bài báo có thể hỗ trợ thêm thông tin cho phần phân tích này.
       * Kết quả **thực sự** của đề tài sẽ là gì? Ai là người sẽ quan tâm? Trong công nghệ phần mềm, người quan tâm thực sự đến kết quả đề tài thường là các lập trình viên. Tại sao các lập trình viên lại cần quan tâm đến kết quả đề tài? (thường là do họ gặp vấn đề gì đó và không thể làm tốt theo cách thông thường), và kết quả của mình sẽ mang lại lợi ích thực tế gì cho họ (thường là sẽ giải quyết vấn đề họ gặp phải).
       * Giải pháp thủ công (trivial solution) hoặc giải pháp hiện tại hệ thống đang sử dụng để giải quyết **bài toán cụ thể** này, nếu có, là gì? Giải pháp đề xuất của bài báo có thực sự cần thiết phải áp dụng trong **hệ thống cụ thể** này hay không?
       * Đã có những giải pháp nào khác đã được đề xuất để giải quyết **bài toán cụ thể** này? Thông thường, phần **Related Work** của bài báo sẽ hỗ trợ thông tin cho phần phân tích này.
       * Dựa trên các **tiêu chí** hay **độ đo** nào, ví dụ: feasibility, performance, scalability, security, cost, time, mean opinion score, BLEU score, ROUGE score, để so sánh các giải pháp trên với nhau (**quan trọng**)? Phần **Evaluation**,  **Performance**, hoặc **Experience** của bài báo có thể hỗ trợ thông tin cho phần phân tích này.
       * Học viên có thể chỉ cần chọn **một** hoặc **hai tiêu chí** là đủ.
       * Học viên lưu ý nếu chọn tiêu chí **feasibility** thì cần đảm bảo rằng chưa có **hệ thống cụ thể** nào đã áp dụng giải pháp đề xuất bởi bài báo, và lý giải được động cơ thực sự để đánh giá tính khả thi của giải pháp.
       * Học viên dự định thu thập các **dữ liệu** nào để đánh giá tiêu chí hay độ đo được lựa chọn ở trên (**quan trọng**)?
       * Học viên dự định sẽ chọn hệ thống thực tế nào để so sánh với hệ thống của mình. Thông thường, hệ thống cũ khi chưa áp dụng giải pháp, có thể được chọn.
       * Các bảng dữ liệu khảo sát, nếu có, sẽ có cấu trúc như thế nào? Lý do thu thập dữ liệu khảo sát là gì?
         
  * #### Hướng 3 - Cải tiến giải pháp
       * Mã nguồn/thư viện/hệ thống/dữ liệu có sẵn có thể tải về từ đâu, hoặc sử dụng trực tiếp ở đâu?
       * Kết quả sau khi chạy mã nguồn/thư viện/hệ thống/dữ liệu có sẵn là gì?
       * Kết quả đánh giá từ mã nguồn/thư viện/hệ thống/dữ liệu có sẵn như thế nào?
       * Giải pháp đề xuất đã được ứng dụng ở hệ thống phần mềm thực tế nào hay chưa?
       * Giải pháp có vấn đề gì, thiếu sót gì mà cần mở rộng? Ý tưởng mở rộng là gì? Ai là người có nhu cầu, hoặc sẽ quan tâm?
       * Dự kiến mã nguồn/thư viện/hệ thống/dữ liệu có thể mở rộng ở đâu. Phần **Conclusion** hoặc **Future Work** của bài báo có thể hỗ trợ hỗ trợ thông tin cho phần phân tích này.
       * Học viên có thể xem xét mở rộng bằng cách hiệu chỉnh mã nguồn có sẵn nhằm **cải thiện tốc độ**, **cải thiện độ chính xác** của giải pháp. Phần **Experiments** hoặc **Performance** của bài báo có thể hỗ trợ thông tin cho việc phân tích này.
       * Học viên có thể xem xét mở rộng bằng cách hiệu chỉnh mã nguồn có sẵn cho một **bộ dữ liệu khác**, trong một **môi trường khác**, trong một **lĩnh vực khác**. Phần **Experiments** hoặc **Case Study** của bài báo có thể hỗ trợ thông tin cho phần phân tích này.
       * Học viên có thể xem xét mở rộng bằng cách tạo một **công cụ mới** hỗ trợ tự động hóa một tác vụ liên quan đến giải pháp, hoặc giúp triển khai, sử dụng giải pháp dễ dàng hơn.
       * Học viên có thể xem xét mở rộng bằng cách thêm **dữ liệu mới** vào giải pháp để giải pháp có độ chính xác cao hơn.
       * Các bảng dữ liệu khảo sát, nếu có, sẽ có cấu trúc như thế nào? Lý do thu thập dữ liệu khảo sát là gì?

## 4. Chuẩn bị kết quả để thảo luận
* Tên đề tài học viên đề xuất là gì? Thường có thể là "Giải pháp XYZ cho bài toán ABC", hoặc "Hệ thống ABC dựa trên giải pháp XYZ".
* Học viên **in ra** các kết quả đã tìm hiểu, bao gồm:
  * Tên đề tài,
  * Bài báo lựa chọn,
  * Hướng đi lựa chọn,
  * Liên kết đến mã nguồn/thư viện/hệ thống/dữ liệu có sẵn, nếu học viên chọn hướng 2 hoặc 3.
  * Các câu lệnh, và ảnh chụp kết quả chạy mã nguồn/thư viện/hệ thống/dữ liệu có sẵn, nếu học viên chọn hướng 2 hoặc 3.
  * Các câu lệnh, và ảnh chụp kết quả đánh giá từ mã nguồn/thư viện/hệ thống/dữ liệu có sẵn, nếu học viên chọn hướng 2 hoặc 3.
  * Nếu luận văn chọn mở rộng dữ liệu thì cần có liên kết đến **dữ liệu của riêng mình**, và có một mô hình lựa chọn để so sánh, kèm ảnh chụp kết quả chạy mô hình này, và chỉ cần một mô hình phù hợp nhất để so sánh là đủ. Học viên chỉ được phép sử dụng các dataset của công ty trong trường hợp có giấy chấp nhận đồng ý của công ty.
  * Nếu luận văn chọn tạo một plug-in thì phải có một plug-in tương tự, hoặc một tool tương tự (tốt nhất là commercial), để so sánh.
  * Mô tả **bài toán cụ thể**,
  * Diễn giải **các tiêu chí đánh giá**, và
  * Các nội dung khác nếu có,
  * sau đó **gặp và thảo luận trực tiếp với giảng viên** để thống nhất nội dung đề tài.
* Học viên cần có các kết quả đã tìm hiểu, và thảo luận trực tiếp với giảng viên **trước** thời hạn nộp đơn đăng ký thực hiện luận văn của Trường **ít nhất là 2 tháng**.
* Sau khi thảo luận với giảng viên và xác định được đề tài, học viên nhận xác nhận của giảng viên, và bắt đầu viết đề cương chi tiết.

### &copy; 2024 Ngô Huy Biên
