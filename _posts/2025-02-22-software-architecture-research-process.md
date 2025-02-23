---
layout: post
title: "Hướng dẫn thực hiện luận văn cao học lĩnh vực kiến trúc phần mềm"
categories: [Luận văn cao học]
author:
- Ngô Huy Biên
meta: "Software Architecture Research Process"
---
_Tài liệu hướng dẫn thực hiện đề tài luận văn cao học, trong lĩnh vực kiến trúc phần mềm, do giảng viên Ngô Huy Biên hướng dẫn._

## 1. Lưu ý chung
* Thông thường, đối với các đề tài tập trung vào kiến trúc tham khảo (Reference Architecture), đề cương hoàn chỉnh chỉ ở mức xác định rõ ràng bài toán (inputs, outputs, evaluation methods) và giải pháp dự kiến (solution) một cách định tính (chiếm khoảng 5% khối lượng công việc của đề tài).
* Quá trình thực hiện đề tài sẽ cần nhiều công sức để hoàn thiện chi tiết mã nguồn bản mẫu, các sơ đồ và diễn giải, các kết quả khảo sát và đánh giá, và bài toán có thể thu hẹp lại nếu tình cờ phát hiện được một bài toán cụ thể hơn.
* Một kiến trúc tham khảo đề xuất luôn phải được đánh giá bởi các chuyên gia bằng khảo sát, và bằng một số độ đo định lượng phù hợp (ví dụ performance, scalability).

## 2. Quy trình khuyến nghị
Các bước thực hiện thường như sau:
* Từ một kiến trúc mẫu (Architecture Pattern), hoặc một kiến trúc tham khảo (Reference Architecture) có sẵn trong sách, hoặc đề xuất bởi một bài báo khoa học, học viên mở rộng mã nguồn bản mẫu có sẵn, hoặc mã nguồn hệ thống thực tế có sẵn (ví dụ hệ thống CRM, Hotel Management), nhằm bổ sung một số khía cạnh chưa được hỗ trợ (ví dụ Multi-tenancy, Service Mesh, Serverless).
* Nếu chọn xây dựng **bản mẫu hệ thống từ đầu**, học viên nên tìm thử **mã nguồn mở** liên quan mới nhất, để tiết kiệm thời gian, đồng thời khối lượng và chất lượng của bản mẫu phù hợp với nhu cầu thực tế, không quá đơn giản. Chỉ trong trường hợp không thể tìm được mã nguồn có sẵn nào phù hợp, và thời gian và khả năng pho phép, thì học viên mới viết mã nguồn từ đầu cho bản mẫu.
* Dựa trên mã nguồn đã cài đặt, học viên trích xuất ra kiến trúc tham khảo (Reference Architecture). Kiến trúc tham khảo đề xuất luôn cần dựa trên một kiến trúc có sẵn (học viên không tự suy diễn), và có mã nguồn minh họa (học viên đề xuất thuần túy lý thuyết).
* Dựa trên mạng lưới quan hệ của cá nhân mình, và dựa trên giới thiệu của giảng viên, học viên gửi kiến trúc tham khảo đề xuất (Reference Architecture) đến các nhà nghiên cứu, kiến trúc sư, nhà phát triển để khảo sát các ý kiến một cách định tính. Ví dụ:
    * Người được khảo sát có mối quan tâm đến kiến trúc tham khảo (Reference Architecture) này hay không? Tại sao có? Tại sao không?
    * Kiến trúc (Architecture) tương tự như kiến trúc tham khảo này đã được người khảo sát dùng bao giờ hay chưa? Trong lĩnh vực nào? Tại sao kiến trúc được lựa chọn?
    * Người được khảo sát có đề xuất bổ sung thêm thành phần nào vào Reference Architecture này không? Lý do là gì?
    * Người được khảo sát có đề xuất loại bỏ thành phần nào của Reference Architecture này không? Lý do là gì?
    * Người được khảo sát có gặp vấn đề gì chưa được giải quyết không, khi sử dụng một kiến trúc tương tự như kiến trúc tham khảo này không?
* Dựa trên kết quả khảo sát, học viên chọn các ý kiến phù hợp (một cách định tính) để tinh chỉnh lại kiến trúc tham khảo.
* Dựa trên kiến trúc tham khảo đã tinh chỉnh, học viên hiệu chỉnh lại mã nguồn.
* Dựa trên mã nguồn học viên thực hiện việc đánh giá performance, scalability (định lượng).

## 3. Thu hẹp phạm vi (cơ hội)
* Trường hợp học viên tình cờ phát hiện được một bài toán cụ thể hơn trong khi viết mã nguồn cho bản mẫu, hoặc cho hệ thống thực tế, thì học viên có thể **chỉ cần giải quyết bài toán cụ thể**, đánh giá giải pháp cho bài toán cụ thể, và bỏ qua các bước còn lại của quy trình. Cơ hội này giúp học viên tiết kiệm được nhiều thời gian, và các kết quả của đề tài thường được đánh giá cao hơn so với các kết quả của quy trình thông thường.
* Thông thường, đối với các hệ thống thực tế đủ lớn thì các bài toán này cụ thể này có thể rất dễ tìm và rõ ràng. Tuy nhiên học viên cần lưu ý vấn đề bản quyền, đảm bảo phải được chủ sở hữu mã nguồn cho phép trước khi thực hiện và công bố các kết quả nghiên cứu.

### &copy; 2025 Ngô Huy Biên
