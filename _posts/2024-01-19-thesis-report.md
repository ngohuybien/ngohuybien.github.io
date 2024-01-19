---
layout: post
title: "Hướng dẫn viết báo cáo khóa luận hoặc thực tập dự án tốt nghiệp"
categories: thesis
author:
- Ngô Huy Biên
meta: "Thesis Report"
---
_Tài liệu hướng dẫn viết báo cáo khóa luận hoặc thực tập dự án tốt nghiệp do giảng viên Ngô Huy Biên hướng dẫn._

## 1. Thông tin chung
* Sinh viên tuyệt đối không chép lại từ các nguồn tiếng Việt (hoặc chép và sửa vài từ).
*	Sinh viên cần ghi đầy đủ các tài liệu tham khảo, và chỉ dùng sách, bài báo và các liên kết đến các trường học, viện nghiên cứu.
*	Sinh viên không dùng liên kết đến Wikipedia hay bất cứ trang tin nào.
*	Với mỗi tài liệu tham khảo, sinh viên phải có trích dẫn trong báo cáo.
*	Các liên kết nếu có sinh viên để trong Footnote tại trang đề cập.
*	Sinh viên cần thể hiện các tài liệu tham khảo theo đúng chuẩn thông dụng. Sinh viên nên sử dụng tính năng Cite (thể hiện bằng dấu nháy) của Google Scholar  để biết cách trình bày tài liệu tham khảo đúng chuẩn.
*	Trong báo cáo sinh viên hạn chế tối đa mã nguồn và việc sử dụng các liên kết.
* Sinh viên chỉ sử dụng LaTeX để viết báo cáo. Sinh viên viết báo cáo trực tiếp trong trang web của Overleaf mà giảng viên đã tạo.

## 2. Quy trình viết báo cáo
*	Khởi tạo: Tạo  bộ khung (mục lục). Những chương nào chưa có nội dung các em để là "Sẽ bổ sung". Bộ khung báo cáo sẽ gồm 6 chương:
  *	Chương 1 – Giới thiệu đề tài (trình bày các hệ thống có sẵn, roles, problems, business cases, user stories).
  *	Chương 2 – Lý thuyết nền tảng (trình bày các mẫu kiến trúc, các mô hình, các thuật toán đã được chứng minh là hiệu quả, sẽ được dùng trong đề tài).
  *	Chương 3 – Thiết kế giải pháp (so sánh phân tích các giải pháp cho các bài toán cụ thể của đề tài, giải thích kiến trúc, thuật toán đề xuất).
  *	Chương 4 – Cài đặt giải pháp (trình bày các nền tảng, công cụ, ngôn ngữ lập trình được sử dụng, kinh nghiệm xử lý các vấn đề gặp phải khi cài đặt).
  *	Chương 5 – Đánh giá giải pháp (mô tả cách tính toán các độ đo và thảo luận về các kết quả tính toán, trình bày việc kiểm thử, so sánh với các hệ thống tương tự).
  *	Chương 6 – Kết luận.
* Viết Chương 1.
* Liệt kê một số khái niệm của Chương 2.
* Tạo một số sơ đồ của Chương 3.
* Phát triển phần mềm hoặc thực hiện thí nghiệm, dựa vào các sản phẩm tạo ra để viết chương 4.
* Kiểm thử phần mềm, so sánh một hệ thống tương tự, dựa vào các sản phẩm tạo ra để viết Chương 5.
* Viết Chương 6.
* Cập nhật Chương 3.
* Cập nhật chi tiết Chương 2.
* Chỉnh sửa tất cả các chương theo mạch logic của từng chương như hướng dẫn ở mục 3 trong tài liệu này.
* Báo cáo được phép có một số nội dung trùng lắp với nội dung của Đề cương.
* Sinh viên có thể viết dài không giới hạn, giảng viên hướng dẫn sẽ cắt bỏ nhiều, thông thường bản cuối của báo cáo sẽ thiếu nội dung hơn là thừa.
* Sinh viên luôn viết bản nháp cho từng chương càng sớm càng tốt. Sau khi có bản nháp, sinh viên vẽ một bản đồ tư duy (mindmap) về những nội dung báo cáo dự định trình bày. Bắt đầu với điểm giữa là tên chủ đề của chương và lan dần ra những vấn đề, kiến thức liên quan. Sinh viên luôn luôn tự hỏi tại sao báo cáo lại trình bày nội dung này, liên quan gì đến điểm giữa của bản đồ tư duy, xa hay gần điểm giữa của bản đồ tư duy. Các điểm càng xa điểm giữa của bản đồ tư duy thì trình bày càng ít và sơ lược.

## 3. Nội dung báo cáo

### 3.1. Chương 1 – Giới thiệu đề tài (khoảng 10 trang)
* Đề tài làm gì (WHAT)? Sinh viên cần làm rõ ít nhất các ý sau:
  * Xác định rõ các vai trò quan tâm, các vấn đề họ gặp phải.
  * Giải thích tại sao phải giải quyết những vấn đề đó. Có nhu cầu thực tế không? Mang lại lợi ích thực tế gì? (nên có số liệu tin cậy, cụ thể)
  * Khảo sát, tổng hợp, phân tích, đánh giá các hệ thống tương tự đã làm ra những sản phẩm nào, quy trình nào, tính năng nào để giải quyết vấn đề trên. So sánh các sản phẩm một cách chi tiết dựa trên từng quy trình thực tế. Phân tích điểm mạnh, điểm yếu, điểm chưa hoàn chỉnh.
  * Xác định luồng quy trình nghiệp vụ để giải quyết vấn đề cho từng vai trò, các chức năng cần có để giải quyết vấn đề dự kiến đề tài sẽ thực hiện.
  * Xác định mục tiêu và yêu cầu chi tiết của đề tài:
    * Khảo sát hiện trạng trong thực tế để xác định rõ các mục tiêu cần đạt được để giải quyết vấn đề hay khắc phục điểm yếu của các ứng dụng tương tự, các yêu cầu chức năng cần làm để đạt được các mục tiêu đề ra: Mục tiêu khi làm đề tài này là gì? Các tính năng cần đạt được là gì? Các sản phẩm cần đạt được là gì?
    * Phần mục tiêu cần ghi rõ, ngắn gọn, gạch đầu dòng: Các sản phẩm cần đạt được, các tính năng cần đạt được, các cải tiến cần đạt được. Cần loại bỏ các mục tiêu mơ hồ, không thể hiện được bằng sản phẩm.
    * Phần mục tiêu cần bao gồm tối thiểu các mục tiêu trong File “Tên và mục tiêu đề tài” mà giảng viên đã gửi cho sinh viên.
  * Phạm vi đề tài: Các nội dung sẽ không quan tâm, các tính năng sẽ không thực hiện?
* Mạch logich của Chương 1 thường như sau:
  * Vì vấn đề P (dẫn chứng bằng số liệu) nên người ta đề xuất các giải pháp thủ công S1, S2.
  * Các giải pháp S1, S2 có các hạn chế L1, L2 (dẫn chứng). Chúng tôi đề xuất giải pháp NEW_S1 để giải quyết hạn chế L1. Chúng tôi đề xuất giải pháp NEW_S2 để giải quyết hạn chế L2. Giải pháp NEW_S1 khác với giải pháp S1 ở chỗ... Giải pháp NEW_S2 khác với giải pháp S2 ở chỗ ...
  * Vì vấn đề P (dẫn chứng bằng số liệu) nên người ta đã xây dựng hệ thống S3.
  * Hệ thống S3 thiếu các tính năng F1, F2 hoặc có các hạn chế L3, L4 (dẫn chứng bằng khảo sát). Chúng tôi đề xuất xây dựng hệ thống S4 tương tự hệ thống S3 và bổ sung tính năng F1, tính năng F2, hoặc nhằm khắc phục hạn chế L3, L4.


### 2.2. Phần Phạm vi đề tài
Sinh viên liệt kê các tính năng của phần mềm có liên quan đến đề tài nhưng dự định sẽ KHÔNG làm.

### 2.3. Phần Cách tiếp cận dự kiến

#### Nếu sinh viên làm khóa luận theo hướng ứng dụng hoặc thực tập dự án tốt nghiệp thì cần trình bày
* Bản mẫu, 
* Kiến trúc,
* Mô hình dữ liệu, 
* Thuật toán, 
* Các mục tiêu kiểm thử dự định (load testing, stress testing, penetration testing) sẽ được thực hiện trên hệ thống,
* Phương pháp so sánh, đánh giá hệ thống với các hệ thống tương tự, và
* Danh sách các công nghệ, công cụ dự định sẽ sử dụng. Sinh viên cần mô tả, giải thích cụ thể các sơ đồ.

#### Nếu sinh viên làm khóa luận theo hướng nghiên cứu thì cần trình bày
* Các nghiên cứu liên quan trực tiếp đến đề tài,
* Các mô hình dự kiến áp dụng hoặc cải tiến,
* Các độ đo để so sánh, đánh giá các kết quả thu được,
* Các nguồn dữ liệu và mã nguồn có sẵn dự kiến sẽ được dùng để huấn luyện,
* Tài nguyên GPU dự định sẽ sử dụng, 
* Ảnh chụp kết quả chạy thử nghiệm huấn luyện và suy luận bằng mã nguồn và bộ dữ liệu có sẵn, và
* Bản mẫu

### 2.4. Phần Kết quả dự kiến của đề tài

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

### &copy; 2024 Ngô Huy Biên
