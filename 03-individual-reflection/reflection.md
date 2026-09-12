# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Nguyễn Đức Anh
- Mã học viên: 2A202602508
- Nhóm: Nhóm của Nguyễn Tuấn Thành, Lò Văn Long, Hoàng Quốc Việt
- Candidate problem nhóm chọn: Người Điếc dùng ngôn ngữ ký hiệu gặp khó khi tiếp cận video tiếng Việt trên YouTube vì phụ đề không luôn phù hợp và video hiếm khi có phiên dịch ngôn ngữ ký hiệu.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Mình lập 6 candidate problems từ các bối cảnh xã hội khác nhau, trong đó có tiếp cận thông tin, người cao tuổi, môi trường, sức khỏe tâm lý, y tế và an toàn thực phẩm. | Nhóm có thêm các lựa chọn đa dạng thay vì chỉ tập trung vào workflow nội bộ hoặc một giải pháp AI cụ thể. |
| Pitch Problem Card | Mình pitch Card #1 về việc người Điếc khó tiếp cận video YouTube/tin tức khi thiếu phụ đề chính xác hoặc phiên dịch ngôn ngữ ký hiệu. | Nhóm hiểu được actor, bottleneck, impact và hướng đo bằng mức độ hiểu đúng nội dung. |
| Challenge bài của bạn khác | Mình đặt câu hỏi về human boundary của ba candidate và ngưỡng độ chính xác tối thiểu để bot 3D đáng tin hơn phụ đề sai. | Nhóm phải xem xét rủi ro AI dịch sai thay vì chỉ nhìn vào tính hấp dẫn của ý tưởng. |
| Gom trùng / cluster | Mình đưa candidate của mình vào cluster D: tiếp cận và chăm sóc nhóm dễ bị tổn thương, cùng các bài toán người cao tuổi và sức khỏe tâm lý. | Nhóm nhìn thấy pattern chung và phân biệt được bài có impact xã hội với bài thiên về tự động hóa nội bộ. |
| Chọn candidate problem | Mình bảo vệ candidate #10, so sánh với #1 và #4, đồng thời chấp nhận rằng bài còn thiếu validation trực tiếp. | Nhóm chọn bài tiếp cận video bằng ngôn ngữ ký hiệu với 29 điểm và ghi rõ đây là lựa chọn tạm thời. |
| Validation / research | Mình phụ trách research về người dùng, accessibility và các giải pháp có sẵn; mình tổng hợp nguồn về VSL, Signapse, SiMAX và cảnh báo avatar không thay thế người thật. | Group report có cơ sở cho human-in-the-loop, nhưng cũng ghi rõ chưa phỏng vấn người Điếc Việt Nam. |
| Workflow nhóm | Mình góp ý về bước người Điếc duyệt bản nháp và fallback sang PiP người thật khi bản nháp không đạt. | Workflow tương lai giữ được human boundary và không cho AI tự xuất bản. |
| Problem Statement | Mình góp ý làm rõ actor là người Điếc dùng NNKH làm ngôn ngữ thứ nhất và giới hạn phạm vi theo nội dung, phương ngữ và người duyệt. | Problem Statement có boundary cụ thể hơn, đồng thời giữ các ô metric chưa đo ở trạng thái `[CẦN ĐO]`. |
| Rule / Workflow / Agent | Mình tham gia lập luận rằng bài toán có độ phức tạp và độ mơ hồ cao, nhưng quy trình vẫn cố định nên phù hợp với Workflow hơn Agent. | Nhóm chọn Workflow: AI tạo nháp, người Điếc duyệt bắt buộc; Rule chỉ làm lớp nền. |
| Decision | Mình ủng hộ quyết định `Not Yet` vì chưa có baseline, metric và bằng chứng hành vi trực tiếp từ người dùng mục tiêu. | Nhóm không quyết định Go chỉ vì muốn làm AI và đã liệt kê các bước validation cần làm trước. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Mình đóng góp phần research về idea của nhóm, accessibility và human-in-the-loop, giúp nhóm chọn Workflow thay vì Agent. Mình cũng giúp ghi rõ người Điếc phải duyệt bản nháp, AI không tự xuất bản, và quyết định cuối cùng là Not Yet vì chưa có validation trực tiếp.

```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Mình sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Mình dùng AI để gợi ý danh sách problem xã hội đa dạng, actor, bằng chứng cần tìm và giới hạn của AI. | AI giúp mình mở rộng góc nhìn sang nhiều lĩnh vực và tránh dồn cả scan vào một chủ đề. | Danh sách và bằng chứng ban đầu còn chung chung; AI không cung cấp validation trực tiếp hay số liệu đủ chắc. | Mình tự chọn 6 problem, kiểm tra lại theo bối cảnh của mình và bỏ các ý tưởng solution-first hoặc có rủi ro để AI quyết định thay người. |
| Problem Card | Không dùng AI để viết thay card; mình tự chọn và phát triển 3 card từ scan. | Việc tự viết giúp mình nắm rõ actor, bottleneck, metric và giới hạn của từng bài. | Các metric ban đầu vẫn là giả định, chưa có người dùng thật xác nhận. | Mình ghi rõ điều chưa chắc, human boundary và fallback thay vì biến giả định thành kết luận. |
| Workflow | Không dùng AI; mình tự mô tả current/future workflow và các điểm bàn giao. | Tự vẽ workflow làm rõ bước nào AI có thể hỗ trợ và bước nào phải do con người xác nhận. | Mình chưa có log thời gian thực tế từ creator hoặc người Điếc. | Mình giữ các số chưa biết là `[CẦN ĐO]` và thêm fallback khi bản nháp sai. |
| Research | Không dùng AI để thay thế việc kiểm nguồn; mình đọc và tổng hợp các nguồn/case được ghi trong group report. | Research giúp nhóm có căn cứ cho human-in-the-loop qua Signapse, SiMAX và WFD/WASLI. | Research desk không thay thế phỏng vấn người Điếc Việt Nam và không xác nhận được nhu cầu YouTube cụ thể. | Mình ghi rõ khoảng trống validation, không suy rộng số liệu khuyết tật nghe thành quy mô người dùng. |
| Problem Statement | Không dùng AI; nhóm tự viết dựa trên workflow và research đã kiểm tra. | Cấu trúc worksheet giúp tách actor, bottleneck, impact, metric và boundary. | Impact và baseline vẫn chưa đo được. | Mình ủng hộ để `[CẦN ĐO]` thay vì bịa số và thu hẹp phạm vi còn một loại nội dung, một phương ngữ. |
| Rule / Workflow / Agent | Không dùng AI để quyết định thay nhóm. | Ma trận của worksheet giúp nhóm phân biệt độ mơ hồ của nội dung với độ tự chủ của quy trình. | Ý tưởng avatar 3D dễ khiến nhóm nhầm bài toán thành Agent hoặc solution-first. | Mình đồng ý chọn Workflow vì chuỗi bước cố định, người Điếc duyệt bắt buộc và AI không tự xuất bản. |
| Decision | Không dùng AI để chốt Go/Not Yet/No-Go. | Nhóm có thể đối chiếu decision với các ô metric, baseline, input và owner. | Chưa có dữ liệu đủ để kết luận sản phẩm có hiệu quả thực tế. | Mình ủng hộ `Not Yet` và đề xuất phỏng vấn 5-10 người Điếc, so sánh PiP với avatar, kiểm tra coverage và chốt phương ngữ trước khi Go. |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của mình?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, mình sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text
Khi nghe top 3 problems của các bạn, mình học được rằng một problem có impact xã hội lớn chưa chắc đã là bài phù hợp nhất để làm trong lab. Mình pitch bài toán người Điếc tiếp cận video YouTube vì thấy phụ đề chữ không mặc nhiên thay thế được ngôn ngữ ký hiệu, nhưng mình cũng nhận ra mình ban đầu đang nói khá nhanh về bot 3D trước khi có đủ bằng chứng từ người dùng. Câu hỏi về human boundary và ngưỡng chính xác tối thiểu khiến mình phải nhìn lại rủi ro AI dịch sai thuật ngữ hoặc sắc thái văn hóa. Đóng góp rõ nhất của mình vào artifact cuối là research về accessibility, các giải pháp Signapse và SiMAX, cùng lập luận rằng người Điếc phải duyệt bản nháp trước khi xuất bản. Mình cũng góp phần giữ fallback sang PiP người thật và không để AI tự xuất bản khi bản nháp không đạt. Điều khó nhất khi viết Problem Statement là chấp nhận để impact và baseline ở trạng thái chưa đo thay vì điền một con số nghe có vẻ thuyết phục. Qua việc so sánh Rule, Workflow và Agent, mình hiểu rằng độ mơ hồ cao của nội dung không tự động có nghĩa là phải dùng Agent; nếu trình tự công việc cố định thì Workflow có thể phù hợp hơn. Mình thấy AI hữu ích nhất ở giai đoạn mở rộng góc nhìn và gợi ý hướng research, nhưng AI hời hợt khi tạo ra bằng chứng chung chung hoặc khiến một ý tưởng giải pháp trông như đã được validation. Vì vậy nhóm chọn Not Yet, vì chưa có phỏng vấn người Điếc Việt Nam, baseline và success metric đáng tin cậy, chứ không chọn Go chỉ vì muốn xây một avatar. Nếu làm lại, mình sẽ challenge nhóm mạnh hơn ngay từ đầu về việc phải phỏng vấn đúng cộng đồng mục tiêu, chốt phương ngữ và xác định người duyệt trước khi thảo luận sâu về công nghệ.

```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [X] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [X] [12đ] Mình đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [X] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [X] [15đ] Nhóm có workflow trước/sau
- [X] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [X] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [X] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [X] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [X] [6đ] Mình tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

