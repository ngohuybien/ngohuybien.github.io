---
layout: post
title: "Hướng dẫn viết báo cáo luận văn cao học, lĩnh vực khoa học máy tính, hệ thống thông tin, công nghệ phần mềm"
categories: [Luận văn cao học]
author:
- Ngô Huy Biên
meta: "Master Thesis Report"
---
_Tài liệu hướng dẫn viết báo cáo luận văn cao học, lĩnh vực khoa học máy tính, hệ thống thông tin, công nghệ phần mềm, do giảng viên Ngô Huy Biên hướng dẫn._

## 1. Thông tin chung
* Học viên tuyệt đối **KHÔNG chép lại từ các nguồn tiếng Việt (hoặc chép và sửa vài từ), KHÔNG dịch lại từ các nguồn tiếng Anh**.
*	Học viên cần ghi đầy đủ các tài liệu tham khảo, và chỉ dùng **sách**, **bài báo** và các liên kết đến các tài liệu của **trường học**, **viện nghiên cứu**.
*	Với mỗi tài liệu được liệt kê trong danh mục tham khảo, học viên phải có trích dẫn trong báo cáo.
* Học viên cần thể hiện các tài liệu tham khảo theo chuẩn <a href = "https://www.mybib.com/tools/ieee-citation-generator" target ="_blank">IEEE</a> hoặc ACM.
*	Học viên **KHÔNG** dùng liên kết đến Wikipedia hay bất cứ trang tin tức nào.
*	Các liên kết đến mã nguồn, phần mềm nếu có trong luận văn học viên để trong Footnote tại trang đề cập, **KHÔNG** để trong danh mục tài liệu tham khảo.
*	Trong báo cáo học viên hạn chế tối đa mã nguồn và các ảnh chụp màn hình.
* Học viên chỉ sử dụng LaTeX để viết báo cáo. Học viên viết báo cáo trực tiếp trong trang web của Overleaf mà giảng viên đã tạo.

## 2. Cấu trúc của báo cáo
Báo cáo thường có cấu trúc sau:
* Trang bìa
* Lời cảm ơn
* Lời cam đoan
* Bảng thuật ngữ, từ viết tắt và ký hiệu
* Mục lục
* Danh sách hình
* Danh sách bảng
* Tóm tắt
* Chương 1 - Mở đầu
* Chương 2 - Cơ sở lý thuyết
* Chương 3 - Giải pháp đề xuất
* Chương 4 - Cài đặt giải pháp
* Chương 5 - Đánh giá giải pháp
* Chương 6 – Kết luận
* Phụ lục

## 3. Nội dung báo cáo
### 3.1. Chương 1 – Mở đầu (khoảng 10 trang)
* Tại sao thực hiện đề tài (WHY)? Học viên cần làm rõ ít nhất các ý sau:
    * Bối cảnh của đề tài.
    * Các vai trò quan tâm (roles, business cases), các vấn đề (problems) mà các vai trò gặp phải.
    * Giải thích tại sao phải giải quyết những vấn đề đó. Có nhu cầu thực tế không? Mang lại lợi ích thực tế gì? (nên có số liệu tin cậy, cụ thể minh chứng hoặc các trường hợp nghiên cứu của một tổ chức cụ thể)
    * Khảo sát hiện trạng quy trình thủ công trong thực tế nếu có.
    * Khảo sát, tổng hợp, phân tích, đánh giá **bản mẫu** của **bài báo** đã lựa chọn hoặc **một hệ thống thương mại tương tự** liên quan trực tiếp đến bài báo đang nghiên cứu. Bản mẫu hay hệ thống thương mại đã làm ra những sản phẩm nào, quy trình nào, tính năng nào để giải quyết vấn đề đang đề cập. Lập bảng so sánh các sản phẩm một cách chi tiết dựa trên từng quy trình thực tế. Phân tích điểm mạnh, điểm yếu, điểm chưa hoàn chỉnh.
* Phát biểu bài toán
    * Đề tài giải quyết vấn đề cụ thể nào (WHAT)? Của ai (WHO)?
    * Mô tả **luồng quy trình nghiệp vụ** dự kiến đề tài sẽ thực hiện để giải quyết vấn đề cho từng vai trò (end-to-end business workflows), các chức năng cần có để thực thi luồng quy trình nghiệp vụ đề ra. Học viên chỉ trình bày 1 hoặc 2 luồng nghiệp vụ chính ở chương này, những luồng khác, nếu có, cần để trong Phụ lục.
    * Bài toán cụ thể là gì? Đầu vào là gì? Đầu ra mong muốn là gì?
* Mục tiêu và yêu cầu chi tiết của đề tài:
    * Đề tài giải quyết vấn đề mới hay khắc phục điểm yếu của hệ thống đã có? Mục tiêu khi làm đề tài này là gì? Các tính năng cần đạt được là gì? Các sản phẩm cần đạt được là gì?
    * Phần mục tiêu cần **bao gồm tối thiểu** các mục tiêu mà giảng viên đã trao đổi với học viên trong các buổi trao đổi trực tiếp.
    * Phần mục tiêu cần ghi rõ, ngắn gọn, gạch đầu dòng: Các sản phẩm cần đạt được, các tính năng cần đạt được, các cải tiến cần đạt được. Cần loại bỏ các mục tiêu mơ hồ, không thể hiện được bằng sản phẩm.
* Phạm vi đề tài: Các nội dung có liên quan nhưng đề tài sẽ không quan tâm, các tính năng có liên quan nhưng đề tài sẽ không thực hiện?
* Mạch logich của Chương 1 thường như sau:
    * Vì vấn đề P (dẫn chứng bằng số liệu) nên người ta đề xuất các giải pháp thủ công S1, S2. Các giải pháp S1, S2 có các hạn chế L1, L2 (dẫn chứng). Chúng tôi đề xuất giải pháp NEW_S1 để giải quyết hạn chế L1. Chúng tôi đề xuất giải pháp NEW_S2 để giải quyết hạn chế L2. Giải pháp NEW_S1 khác với giải pháp S1 ở chỗ... Giải pháp NEW_S2 khác với giải pháp S2 ở chỗ ...
    * và/hoặc
    * Vì vấn đề P (dẫn chứng bằng số liệu) nên người ta đã xây dựng hệ thống S3. Hệ thống S3 thiếu các tính năng F1, F2 hoặc có các hạn chế L3, L4 (dẫn chứng bằng khảo sát). Chúng tôi đề xuất xây dựng hệ thống S4 tương tự hệ thống S3 và bổ sung tính năng F1, tính năng F2, hoặc nhằm khắc phục hạn chế L3, L4.

### 3.2. Chương 2 – Cơ sở lý thuyết (khoảng 10 trang)
* Trình bày các kiến thức nền tảng liên quan đến từng vấn đề cần giải quyết của đề tài, dựa vào **bài báo** đã lựa chọn và **các sách hay bài báo** có liên quan. Các kiến thức trong chương 2 là các kiến thức **đã được chứng minh là đúng hoặc hiệu quả**. Học viên chỉ cần liệt kê các thuật ngữ thật ngắn gọn, không cần đi chi tiết vào diễn giải hay trình bày chi tiết các thuật ngữ này.
* Nội dung chương này có thể trình bày các mẫu kiến trúc, các mô hình, các thuật toán, **các độ đo đã được chứng minh là hiệu quả**, sẽ được **dùng trong đề tài**.
* So sánh phân tích các giải pháp hiện có, kiến trúc, thuật toán đề xuất.
* Mạch logich của Chương 2 thường như sau:
    * Ở chương 1 đề tài đã đề xuất giải pháp NEW_S1. Giải pháp NEW_S1 được xây dựng trên nền tảng lý thuyết T1. T1 là ... Chúng ta quan tâm đến T1 vì ... T1 hoạt động như sau ...
    * Ở chương 1 đề tài đã đề xuất xây dựng hệ thống S2. Hệ thống S2 được xây dựng trên nền tảng lý thuyết T2. T2 là ... Chúng ta quan tâm đến T2 vì ... T2 hoạt động như sau ...
    * Ở chương 1 đề tài đã đề xuất giải pháp NEW_S1. Giải pháp NEW_S1 có thể được đánh giá, so sánh với giải pháp S1 bằng độ đo M1. M1 được đề xuất bởi ... Chúng ta quan tâm đến M1 vì ... M1 hoạt động như sau ...

### 3.3. Chương 3 – Giải pháp đề xuất (khoảng 15 trang)
* Nội dung chương 3 trình bày giải pháp cho **từng bài toán cụ thể** (end-to-end business workflows). Các nội dung cần trình bày **bằng ví dụ**, với các giá trị cụ thể, minh họa cho các khái niệm. Các ví dụ được lấy ra từ hệ thống phần mềm hoặc bản mẫu **đã** được viết.
* Giải pháp được trình bày **không phụ thuộc vào ngôn ngữ lập trình, công cụ sử dụng**.
* Học viên dựa vào các tài liệu tham khảo, các suy luận, các chuẩn có sẵn, các kết quả đạt được khi thực nghiệm để chứng minh, lý giải vì sao lại chọn giải pháp như vậy cho từng bài toán.
* Nội dung chương 3 có thể bao gồm, nhưng không giới hạn:
    * Giải pháp lưu trữ dữ liệu: Mô tả bằng các sơ đồ và diễn giải từng thành phần trong sơ đồ.
    * Thiết kế kiến trúc tổng quan của hệ thống: Mô tả bằng các sơ đồ và diễn giải từng thành phần trong sơ đồ.
    * Các thuật toán để hiện thực các tính năng cốt lõi của hệ thống: Mô tả bằng các sơ đồ và diễn giải từng thành phần trong sơ đồ.
* Mạch logich của Chương 3 thường như sau:
    * Ở chương 1 chúng tôi đề xuất xây dựng hệ thống S1.
    * Chúng tôi thiết kế hệ thống S1 như sau: S1 bao gồm các thành phần sau… S1 hoạt động như sau…. Chúng tôi thiết kế S1 như vậy vì…
    * Ở chương 1 chúng tôi đề xuất giải pháp NEW_S1. Chúng tôi thiết kế giải pháp NEW_S1 như sau: hình vẽ hoặc sơ đồ. Diễn giải: NEW_S1 bao gồm các thành phần sau… NEW_S1 hoạt động như sau…. Chúng tôi đề xuất thiết kế NEW_S1 như vậy vì ...

### 3.4. Chương 4 – Cài đặt giải pháp (khoảng 10 trang)
* Học viên tập trung chủ yếu vào việc **báo cáo kinh nghiệm thực tế**. Mô tả các kinh nghiệm xử lý các vấn đề gặp phải khi áp dụng nền tảng, công cụ, ngôn ngữ vào việc cài đặt hệ thống hoặc xây dựng bản mẫu. Phần lớn nội dung chi tiết của chương này nằm ở Phụ lục, chỉ các ý chính được trình bày trong báo cáo.
* Học viên cần làm rõ những kết quả nào **đã có sẵn** (nền tảng, khung ứng dụng, thư viện, mã nguồn có sẵn, dữ liệu có sẵn), những kết quả này đã cung cấp sẵn các tính năng nào trong việc giải quyết vấn đề đặt ra, những kết quả này tồn tại vấn đề gì chưa giải quyết.
* Đề tài đã tạo thêm các công cụ để xử lý tác vụ đặc thù nào, đã chỉnh/thêm dữ liệu nào, đã chỉnh/thêm các thành phần hệ thống có sẵn nào, đã chỉnh/thêm mã nguồn có sẵn nào. Những thay đổi này dùng để giải quyết vấn đề gì?
* Các công cụ nào đã được dùng để cài đặt, kiểm thử từng giải pháp hoặc từng thành phần ở Chương 3.
* Các kinh nghiệm thực tế về các vấn đề phát sinh khi cài đặt giải pháp. Nội dung này là **quan trọng nhất** và nên được lựa chọn theo từng vấn đề thực tế mà học viên gặp phải, nhằm trình bày các kinh nghiệm, phân tích và đánh giá giải pháp của công nghệ mới so với kỹ thuật truyền thống.
* Mạch logich của Chương 4 thường như sau:
   * Ở chương 3 chúng tôi đã trình bày thiết kế của giải pháp NEW_S1. Giải pháp NEW_S1 được chúng tôi cài đặt bằng công cụ, thành phần, thư viện sau ... Khi cài đặt giải pháp NEW_S1 bằng công cụ, thành phần, thư viện ... chúng tôi gặp các vấn đề sau… Chúng tôi đã giải quyết như sau ... Chúng tôi rút ra kinh nghiệm sau ...
   * Hệ thống S1 được chúng tôi cài đặt bằng công cụ, thành phần, thư viện ... Khi cài đặt hệ thống S1 bằng công cụ, thành phần, thư viện ... chúng tôi gặp các vấn đề sau ... Chúng tôi đã giải quyết như sau ... Chúng tôi rút ra kinh nghiệm sau ...
   * Học viên có thể lập bảng để trình bày ngắn gọn hơn.

### 3.5. Chương 5 – Đánh giá giải pháp (khoảng 15 trang)
* Đề tài đã xây dựng được hệ thống phần mềm hay bản mẫu với bao nhiêu dòng mã nguồn, bao nhiêu hàm/lớp, bao nhiêu mối liên hệ giữa các hàm/lớp, bao nhiêu bảng dữ liệu, bao nhiêu mối liên hệ giữa các bảng, bao nhiêu màn hình giao diện?
* Giải pháp đã được kiểm thử như thế nào? Các kết quả kiểm thử thể hiện điều gì? Chúng tôi đã thực hiện kiểm thử NEW_S1 bằng công cụ, thành phần, thư viện sau ... Kết quả kiểm thử có số liệu như sau ... Kết quả này thể hiện rằng ...
* Đề tài đã xây dựng đã xây dựng được hệ thống phần mềm với những tính năng nổi bật nào, đã giải quyết được những vấn đề gì trong thực tế.
* Bảng so sánh các nghiệp vụ chính của phần mềm so với một hệ thống tương tự.
* Đánh giá định lượng dựa trên **các độ đo tiêu chẩn**: độ đo nào được sử dụng, quá trình đo lường diễn ra như thế nào, dữ liệu đo lường là gì, các dữ liệu được tính toán ra sao, kết quả thể hiện điều gì.
* Đánh giá định tính dựa trên **các tiêu chí** mà ngành công nghiệp hoặc cộng đồng nghiên cứu thường dùng để đánh giá sản phẩm: các nội dung khảo sát là gì, các dữ liệu khảo sát được tính toán như thế nào, kết quả thể hiện điều gì.
* Đánh giá định tính hoặc định lượng **lợi ích của sản phẩm** khi áp dụng vào môi trường thực: tiết kiệm bao nhiêu thời gian, chi phí so với giải pháp thủ công, dữ liệu khảo sát hay dữ liệu đo lường nào thể hiện điều này.
* Đề tài luôn bắt buộc phải có đánh giá định lượng hoặc định tính, hoặc cả hai.
* Mạch logich của Chương 4 thường như sau:
    * Giải pháp đã được đánh giá định lượng, so sánh với ... dựa trên độ đo ... Các kết quả đánh giá thể hiện có số liệu như sau ... Kết quả này thể hiện rằng ... Chi tiết dữ liệu tính toán có thể truy cập ở ...
    * Giải pháp đã được đánh giá định tính bằng ... (khảo sát) ... Số lượng khảo sát là ... Nội dung khảo sát là ... Kết quả thể hiện ...  Chi tiết dữ liệu khảo sát có thể truy cập ở ...

### 3.6. Chương 6 – Kết luận (khoảng 5 trang)
* Các sản phẩm nổi bật thu được là gì (thiết kế, hệ thống phần mềm, công cụ hỗ trợ, tài liệu nghiên cứu về sản phẩm, dữ liệu tạo ra được, mô hình huấn luyện được, công cụ tạo ra được để xử lý một tác vụ đặc thù nào đó). Có cải tiến, mở rộng mã nguồn có sẵn không?
* Bảng so sánh các kết quả thu được với các mục tiêu đề ra ban đầu.
* Phương hướng phát triển và nghiên cứu trong tương lai: Liệt kê một số vấn đề còn tồn tại và đề ra phương hướng giải quyết (một cách rất tổng quát) trong tương lai.
* Tập trung vào ưu điểm của ứng dụng. Không tập trung vào các hạn chế, không nêu các lý do biện minh (nhân lực, thời gian), chỉ nói là chúng tôi dự định trong tương lai sẽ khắc phục một số hạn chế sau.

### 3.7. Phụ lục
* Lịch sử các hệ thống, công cụ, nếu có những thay đổi đột phá.
* Giao diện hệ thống. Các giao diện nếu có nên được trình bày ngắn gọn, thể hiện giải pháp ở góc độ trực giác trong việc giải quyết bài toán. Học viên hạn chế liệt kê toàn bộ các giao diện.
* Bản mô tả chi tiết thiết kế hệ thống.

### &copy; 2024 Ngô Huy Biên
