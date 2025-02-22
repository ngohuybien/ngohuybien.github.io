---
layout: post
title: "Hướng dẫn thực hiện luận văn cao học lĩnh vực kiến trúc phần mềm"
categories: [Luận văn cao học]
author:
- Ngô Huy Biên
meta: "Software Architecture Research Process"
---
_Tài liệu hướng dẫn thực hiện đề tài luận văn cao học, trong lĩnh vực kiến trúc phần mềm, do giảng viên Ngô Huy Biên hướng dẫn._

## 1. Đề cương
* Thông thường đối với các đề tài về Reference Architecture, đề cương hoàn chỉnh chỉ là xác định rõ ràng bài toán (inputs, outputs, evaluation) và giải pháp dự kiến (solution) (định tính, khoảng 5% đề tài).
* Quá trình thực hiện sẽ cần nhiều công sức để hoàn thiện chi tiết các outputs/evaluation, và bài toán có thể thu hẹp lại nếu tình cờ phát hiện được một bài toán cụ thể hơn.

## 2. Các bước khuyến nghị
Các bước thực hiện thường như sau:
* Từ một Architecture có sẵn (trong Books hoặc Papers), học viên cần mở rộng mã nguồn bản mẫu hệ thống hoặc mã nguồn hệ thống thực tế (ví dụ hệ thống CRM, Hotel Management).
* Trong quá trình cài đặt học viên có thể bổ sung một số khía cạnh chưa được hỗ trợ (ví dụ multi-tenancy, serverless).
* Dựa trên mã nguồn đã cài đặt, học viên trích xuất ra Reference Architecture.
* Học viên gửi kiến trúc tham khảo đề xuất (Reference Architecture) đến các nhà nghiên cứu, kiến trúc sư, nhà phát triển để khảo sát các ý kiến một cách định tính. Ví dụ:
    * Người được khảo sát có mối quan tâm đến kiến trúc tham khảo (Reference Architecture) này hay không? Tại sao có? Tại sao không?
    * Kiến trúc (Architecture) tương tự như kiến trúc tham khảo này đã được người khảo sát dùng bao giờ hay chưa? Trong lĩnh vực nào? Tại sao kiến trúc được lựa chọn?
    * Người được khảo sát có đề xuất bổ sung thêm thành phần nào vào Reference Architecture này không? Lý do là gì?
    * Người được khảo sát có đề xuất loại bỏ thành phần nào của Reference Architecture này không? Lý do là gì?
    * Người được khảo sát có gặp vấn đề gì chưa được giải quyết không, khi sử dụng một kiến trúc tương tự như kiến trúc tham khảo này không?
* Dựa trên kết quả khảo sát, học viên chọn các ý kiến phù hợp (một cách định tính) để tinh chỉnh lại kiến trúc tham khảo.
* Dựa trên kiến trúc tham khảo đã tinh chỉnh, học viên hiệu chỉnh lại mã nguồn.
* Dựa trên mã nguồn học viên thực hiện việc đánh giá performance, scalability (định lượng).

## 3. Thu hẹp phạm vi (cơ hội)
* Trường hợp học viên tình cờ phát hiện được một bài toán cụ thể hơn trong khi viết mã nguồn cho bản mẫu, hoặc hệ thống thực tế, thì học viên có thể chỉ cần giải quyết bài toán cụ thể, đánh giá giải pháp cho bài toán cụ thể, và bỏ qua các bước còn lại.
* Thông thường đối với các hệ thống thực tế đủ lớn thì các bài toán này cụ thể này rất dễ tìm và rõ ràng. Tuy nhiên học viên cần lưu ý vấn đề bản quyền, đảm bảo phải được chủ sở hữu mã nguồn cho phép trước khi thực hiện nghiên cứu.

### &copy; 2025 Ngô Huy Biên
