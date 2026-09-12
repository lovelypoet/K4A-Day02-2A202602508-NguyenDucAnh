02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1   | Nguyễn Tuấn Thành | 2A202602640 | Facilitator; tổng hợp Problem Card và workflow nghiên cứu |
| 2   | Nguyễn Đức Anh | 2A202602508 | Research về người dùng, accessibility và giải pháp có sẵn |
| 3   | Lò Văn Long | 2A202602541 | Workflow; mô tả pain trong phát triển sản phẩm HTML5 |
| 4   | Hoàng Quốc Việt | 2A202602563 | Research/validation; tổng hợp candidate trong bối cảnh giáo dục |

**Candidate problem nhóm chọn (1 câu):**

Người Điếc dùng ngôn ngữ ký hiệu gặp khó khi tiếp cận video tiếng Việt trên YouTube vì phụ đề không luôn phù hợp và video hiếm khi có phiên dịch ngôn ngữ ký hiệu.

---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Nguyễn Tuấn Thành | Lọc paper liên quan khi nhận business problem mới | AI researcher, tech lead và business team chờ hướng giải pháp | Skim 10-20 paper để đánh giá relevance khi thuật ngữ học thuật khác ngôn ngữ business; mất 3-5 giờ/topic | Workflow và metric thời gian rõ; cần human review để tránh bỏ sót paper quan trọng |
| 2 | Nguyễn Tuấn Thành | So sánh nhiều paper cùng topic | AI researcher và tech lead | Chuẩn hóa dataset, metric, baseline và limitation giữa 5-8 paper; mất 1-2 giờ | Có cấu trúc rõ, nhưng chất lượng so sánh cần researcher kiểm số liệu gốc |
| 3 | Nguyễn Tuấn Thành | Handoff research recommendation cho engineer | ML engineer và AI researcher | Note thiếu dataset, baseline, metric nên phát sinh 1-2 vòng hỏi lại | Pain ở handoff rõ; template/checklist có thể đã giải phần lớn |
| 4 | Lò Văn Long | Giải quyết bất đồng UI/UX giữa chuyên viên Hóa học và giám đốc dự án trước khi dev code bài thí nghiệm HTML | Dev HTML5, chuyên viên môn Hóa, giám đốc dự án | UI/UX bị bác sau khoảng 20 giờ code, phải làm lại 16-24 giờ và trễ release 5-7 ngày | Pain sản phẩm thật, workflow trước/sau rõ; cần xác định AI có hơn prototype review sớm hay không |
| 5 | Lò Văn Long | Sinh CSS/Canvas animation mô phỏng phản ứng Hóa học từ mô tả hiện tượng | Frontend/HTML5 developer | Viết hiệu ứng hạt Canvas và CSS keyframes thủ công mất 3-4 giờ/bài | Tăng năng suất code, nhưng phạm vi thiên về kỹ thuật cá nhân |
| 6 | Lò Văn Long | Đóng gói asset ảnh và minify HTML5 dưới 5 MB | Frontend developer, người dùng web trường học | Nén ảnh và minify thủ công mất 45-60 phút/bài, dễ sót file nặng | Bài toán rõ nhưng build tool/rule là lời giải phù hợp hơn AI |
| 7 | Hoàng Quốc Việt | Lập kế hoạch giảng dạy lặp cho 35 tuần | Giáo viên bộ môn | Ghép bài và xếp thứ tự cho từng tuần, lặp 35 lần | Đầu vào/đầu ra có cấu trúc; cần xác minh baseline trước khi khẳng định mức tiết kiệm |
| 8 | Hoàng Quốc Việt | Lọc công văn của quận gửi đến trường | Hiệu trưởng | Đọc toàn văn để tự suy ra phần liên quan tới trường | Đúng thế mạnh trích xuất của LLM, nhưng bỏ sót hạn hành chính là rủi ro cao |
| 9 | Hoàng Quốc Việt | Bật hotspot khi lên xe | Bố của Việt | Tìm mục điểm phát sóng trong Cài đặt | Một điều kiện-một hành động; nên dùng shortcut/rule, không cần AI |
| 10 | Nguyễn Đức Anh | Hỗ trợ người Điếc tiếp cận video YouTube/tin tức bằng ngôn ngữ ký hiệu | Người Điếc dùng ngôn ngữ ký hiệu | Video thường chỉ có phụ đề hoặc phụ đề tự động; phụ đề không luôn là kênh tiếp cận phù hợp | Impact xã hội lớn, nhưng phải hỏi trực tiếp người Điếc Việt Nam trước khi chốt workflow |
| 11 | Nguyễn Đức Anh | Phát hiện sự cố sức khỏe của người cao tuổi sống một mình | Người cao tuổi và người thân | Người thân không thể túc trực 24/7; chưa rõ cảm biến nào khả thi | Rủi ro an toàn cao, đòi hỏi thiết bị và quy trình y tế vượt scope lab |
| 12 | Nguyễn Đức Anh | Hỗ trợ ban đầu cho sinh viên/người trẻ chịu áp lực tâm lý | Sinh viên/người trẻ | Ngại tìm tư vấn vì chi phí, kỳ thị hoặc không biết bắt đầu | Gần người dùng nhưng ranh giới an toàn và escalation tới chuyên gia rất nhạy cảm |

### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A — Nghiên cứu và xử lý tri thức | #1, #2, #3, #8 | Tìm, đọc, trích xuất, chuẩn hóa và chuyển giao thông tin để ra quyết định | Cần người kiểm nội dung; #3 và #8 có thể cải thiện đáng kể bằng template/checklist trước |
| B — Sản xuất nội dung EdTech | #4, #5, #7 | Chuyển yêu cầu chuyên môn thành kế hoạch, UI/UX hoặc nội dung số | #4 có pain do rework lớn; #5 là tăng năng suất code; #7 có dữ liệu đầu vào khá cấu trúc |
| C — Tự động hóa rõ luật | #6, #9 | Input/điều kiện rõ, đầu ra xác định | Đây là các ví dụ nên chọn Rule/process fix thay vì AI |
| D — Tiếp cận và chăm sóc nhóm dễ bị tổn thương | #10, #11, #12 | Người dùng bị cản trở tiếp cận thông tin, chăm sóc hoặc hỗ trợ | #10 phù hợp để nghiên cứu tiếp; #11 và #12 có rủi ro an toàn cao hơn scope lab |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| #10 — Tiếp cận video YouTube bằng ngôn ngữ ký hiệu | Actor và impact xã hội rõ; đã có research về VSL, thiếu phiên dịch, giới hạn phụ đề và các mô hình human-in-the-loop; so sánh Rule/Workflow/Agent được rõ | Chưa phỏng vấn 5-10 người Điếc Việt Nam; chưa chốt phương ngữ và chưa biết người dùng muốn PiP người thật hay avatar |
| #4 — Chốt UI/UX trước khi dev HTML5 | Handoff giữa ba actor rõ; có thời gian rework, ảnh hưởng tiến độ và workflow dễ vẽ | Cần kiểm chứng nguyên nhân gốc: thiếu prototype/quy trình review hay thiếu công cụ AI; domain khá hẹp theo một dự án |
| #1 — Lọc paper cho business problem | Workflow 6 bước và pain 3-5 giờ/topic rõ; metric thời gian và human boundary cụ thể | Tiêu chí relevance còn chủ quan; cần benchmark/nhãn review để đo không bỏ sót paper quan trọng |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| #10 — Ngôn ngữ ký hiệu / YouTube | 5 | 4 | 4 | 5 | 3 | 5 | 3 | **29** |
| #4 — Chốt UI/UX trước khi code | 5 | 5 | 3 | 4 | 4 | 4 | 3 | **28** |
| #1 — Lọc paper cho business problem | 5 | 5 | 3 | 4 | 4 | 4 | 4 | **29** |

**Candidate nhóm chọn (1 bài duy nhất):**

```text
Người Điếc dùng ngôn ngữ ký hiệu gặp khó khi tiếp cận video tiếng Việt trên YouTube vì phụ đề không luôn phù hợp và video hiếm khi có phiên dịch ngôn ngữ ký hiệu.
```

**Vì sao chọn (4-5 câu):**

```text
Nhóm chọn candidate này vì actor bị ảnh hưởng và rào cản tiếp cận được nêu rõ, đồng thời impact không chỉ nằm ở năng suất nội bộ mà ở khả năng tiếp cận thông tin. Research Phase 4 cho thấy phụ đề không thể mặc định thay thế ngôn ngữ ký hiệu và nguồn phiên dịch viên rất hạn chế. Các giải pháp đang có như Signapse và SiMAX đều để AI tạo nháp, sau đó có người dùng/người bản ngữ duyệt, nên human boundary có cơ sở. Candidate #10 và #1 cùng 29 điểm; nhóm ưu tiên #10 vì research đã chỉ ra một khoảng trống tiếp cận có ý nghĩa và những ràng buộc cần thu hẹp bài toán. Đây là lựa chọn tạm thời: trước Phase 5, nhóm phải xác nhận pain trực tiếp với người Điếc Việt Nam.
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
Không chọn #4 vì rework UI/UX đáng kể nhưng nguyên nhân có thể được xử lý trước bằng prototype, acceptance criteria và review sớm, không nhất thiết cần AI. Không chọn #1 vì pain và workflow tốt nhưng tiêu chí “paper liên quan” còn phụ thuộc đánh giá chuyên môn; nhóm chưa có bộ dữ liệu/nhãn để kiểm thử trong lab.

Các candidate #2, #3, #5, #7 và #8 đều có ích nhưng thiên về chuẩn hóa template hoặc hỗ trợ năng suất trong một workflow nội bộ. #6 và #9 phù hợp hơn với Rule/process fix. #11 và #12 có hệ quả sức khỏe và an toàn cao, đòi hỏi thiết bị, chuyên gia và quy trình escalation vượt phạm vi của bài lab hiện tại.
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
Nhóm có lo ngại hợp lý rằng chưa ai có bằng chứng trực tiếp từ cộng đồng Điếc, cũng chưa chắc người dùng muốn avatar thay cho người phiên dịch thật. Nhóm không giải quyết bằng cách giả định thay người dùng: vẫn chọn #10 để đi tiếp research, nhưng chốt Phase 4 là phải phỏng vấn/survey 5-10 người Điếc bằng phương thức tiếp cận phù hợp và chỉ thiết kế workflow sau khi có phản hồi.
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Interview | Chưa có | Chưa có quote trực tiếp; research desk không thay thế được phỏng vấn người dùng | Đây là khoảng trống lớn nhất: chưa biết hành vi xem YouTube, loại nội dung và điểm bỏ cuộc của người Điếc Việt Nam | Trước Phase 5, phỏng vấn 5-10 người Điếc bằng video ký hiệu hoặc qua người hỗ trợ giao tiếp |
| Survey / poll | Chưa có | Chưa thực hiện | Chưa biết người dùng ưu tiên phụ đề, PiP người thật hay avatar 3D | Dùng 2 mẫu video để hỏi mức hiểu và lựa chọn phương án |
| Log / ticket / review (nếu có) | 0 | Không có log hành vi người dùng | Không thể suy ra pain cụ thể trên YouTube từ thống kê khuyết tật nói chung | Không dùng số liệu hiện tại để khẳng định nhu cầu sử dụng sản phẩm |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Research xác nhận rào cản tiếp cận ngôn ngữ ký hiệu là có thật, nhưng chưa xác nhận trực tiếp pain khi xem YouTube của đúng nhóm người dùng mục tiêu. Vì vậy, problem chưa được validate hoàn toàn; đau ở đâu, phương ngữ nào và hình thức thể hiện nào phải do người Điếc trả lời.
```

Bằng chứng đính kèm (nếu có): `02-group-problem-statement-survey.png`, `...-interview-notes.md`

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| VDS 2023 và Thông tư 17/2020/TT-BGDĐT | https://www.nso.gov.vn/tin-tuc-thong-ke/2024/11/thong-cao-bao-chi-ve-ket-qua-dieu-tra-nguoi-khuyet-tat-nam-2023/ ; https://luatvietnam.vn/giao-duc/thong-tu-17-2020-tt-bgddt-ngon-ngu-ky-hieu-cho-nguoi-khuyet-tat-185588-d1.html | Xác định bối cảnh tiếp cận và giới hạn chuẩn VSL hiện có | Nguồn Việt Nam chính thức; chuẩn chỉ có 408 từ/ngữ ký hiệu | Tỷ lệ khuyết tật nghe không đồng nghĩa số người Điếc dùng ký hiệu; chưa nói trực tiếp về YouTube | Không suy rộng quy mô người dùng; phải thu hẹp theo nhóm, phương ngữ và loại video |
| Signapse | https://www.signapse.ai/post/ai-sign-language-interpreter-fluency | Sinh bản dịch ký hiệu từ nội dung, sau đó đánh giá mức dễ hiểu | Có nhiều người bản ngữ duyệt đầu ra | Là tiếng Anh/BSL; không thể áp thẳng sang VSL | Đặt người Điếc/người bản ngữ ở bước duyệt, không để AI tự phát hành |
| SiMAX / Signtime và WFD/WASLI | https://theventury.com/case-studies/signtime/ ; https://wfdeaf.org/wfd-wasli-issue-statement-signing-avatars/ | Tạo gợi ý ký hiệu/animation bán tự động | Người Điếc tinh chỉnh trước phát hành | Avatar không nên thay phiên dịch viên người thật; VSL có khác biệt phương ngữ | Pilot chỉ nên làm một tập video ngắn, một phương ngữ, AI tạo nháp và người thật duyệt |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
Không nên build “avatar dịch mọi video YouTube sang VSL” hoặc để AI tự xuất bản. Hướng đáng thử là workflow human-in-the-loop cho một nhóm video ngắn, một phương ngữ được cộng đồng xác nhận: AI hỗ trợ tạo nháp/chú giải, người Điếc hoặc người ký hiệu có năng lực duyệt và chỉnh trước khi công bố. Trước mọi quyết định build, nhóm phải hoàn thành quick validation được liệt kê trong Phase 4.1.
```

> Lưu ý: không dùng số liệu AI đưa nếu không verify được link chính thức. Ghi rõ giả định chưa chắc.

---

# Phase 5 — Workflow + Problem Statement

> Bám candidate đã chốt: **ngôn ngữ ký hiệu cho người Điếc khi xem video
> tiếng Việt trên YouTube.** Số liệu lấy từ `02-group-problem-statement-research-notes.md`.
> Ô còn `[CẦN ĐO]` là chỗ nhóm phải phỏng vấn người Điếc thật mới điền được —
> không bịa.

## 5.1 — Current workflow (cách một creator thêm ký hiệu hôm nay, khi họ CÓ cố làm)

```text
[1 Video xong, có phụ đề: đã có]
→ [2 Tìm phiên dịch NNKH: __ ngày, thường KHÔNG tìm được]  <-- bottleneck
→ [3 Phiên dịch dịch + quay riêng: __ ]
→ [4 Ghép video phiên dịch vào góc màn hình (PiP), thủ công: __ ]
→ [5 Xuất bản: đã có]

Thực tế: bước 2 chặn hầu hết các video lại. Đa số creator bỏ qua toàn bộ
4 bước sau và xuất bản chỉ với phụ đề — không phải vì làm tệ, mà vì bước
ký hiệu KHÔNG NẰM trong quy trình sản xuất mặc định.
```

| Bước | Actor | Input | Output | Thời gian/tần suất | Ghi chú |
|---|---|---|---|---|---|
| 1 | Creator | Video đã dựng | Video + phụ đề tự động | Mỗi video | Bước duy nhất luôn xảy ra |
| 2 | Creator | Nhu cầu thêm ký hiệu | Phiên dịch (nếu tìm được) | [CẦN ĐO] | Cả nước chỉ hơn 10 phiên dịch chuyên nghiệp (2019) |
| 3 | Phiên dịch NNKH | Nội dung video | Video phiên dịch dịch riêng | [CẦN ĐO] | Phụ thuộc lịch của rất ít người |
| 4 | Editor | 2 video (gốc + phiên dịch) | Video ghép PiP | [CẦN ĐO] | Thủ công, không có công cụ chuẩn |
| 5 | Creator | Video đã ghép | Video xuất bản | Mỗi video | |

Bottleneck chính:

```text
Bước 2. Không phải "làm chậm" — mà là hầu như KHÔNG CÓ ai để làm bước này.
Hệ quả: bước 2-4 gần như không xảy ra trong thực tế, và người Điếc mặc định
chỉ có phụ đề.
```

## 5.2 — Future workflow

```text
[1 Máy tách câu từ phụ đề có sẵn: vài giây]                     — Rule
→ [2 AI đề xuất chuỗi ký hiệu (gloss), đánh dấu chỗ không chắc: vài phút]  — AI hỗ trợ
→ [3 AI dựng bản nháp hình ảnh/animation: vài phút]              — AI hỗ trợ
→ [4 Người Điếc duyệt, sửa hoặc bác bỏ nháp: __ ]  <-- human boundary, BẮT BUỘC
→ [5 Xuất bản kèm track ký hiệu: đã có]

Fallback: nháp sai quá nhiều hoặc người duyệt bác → quay về bước 2 (PiP
người thật) cho đúng video đó. Không tệ hơn hiện tại, vì hiện tại vốn không
có gì.
```

Before/after impact:

| Metric | Trước | Sau kỳ vọng | Ghi chú |
|---|---:|---:|---|
| Số bước | 5 (nhưng hiếm khi xảy ra hết) | 5 | Không đổi số bước — đổi ai làm bước nào |
| Tổng thời gian | [CẦN ĐO], thực tế ~không xảy ra | Mục tiêu vài giờ/video | Máy làm bước 1-3 trong vài phút |
| Số bước thủ công | 4/5 (tìm, dịch, quay, ghép) | 2/5 (duyệt, xuất bản) | |
| Bottleneck chính | Thiếu người phiên dịch (nguồn lực) | Người Điếc duyệt (cổng chất lượng, cố ý giữ lại) | Bottleneck đổi loại, không biến mất |
| Risk mới | Gần như không áp dụng (hiện tại ~không xảy ra) | AI dịch sai văn hóa/ngữ pháp mà người duyệt bỏ sót | Rủi ro đổi từ "không có gì" sang "có nhưng có thể sai" |

## 5.3 — Problem Statement v0

| Field | Nội dung |
|---|---|
| **Actor** | Người Điếc dùng ngôn ngữ ký hiệu (NNKH) làm ngôn ngữ thứ nhất, xem nội dung video tiếng Việt trên YouTube |
| **Workflow** | Video được sản xuất và xuất bản kèm phụ đề tự động; bước thêm ký hiệu không tồn tại trong quy trình mặc định vì cả nước chỉ có hơn 10 phiên dịch NNKH chuyên nghiệp (2019) |
| **Bottleneck** | Bước "thêm ký hiệu" bị bỏ qua hoàn toàn ở hầu hết video — không phải làm tệ, mà là không làm |
| **Impact** | [CẦN ĐO] — nhóm chưa phỏng vấn người Điếc thật nên chưa có số về tỉ lệ hiểu nội dung hiện tại hay hành vi bỏ xem giữa chừng |
| **Success Metric** | Tỉ lệ trả lời đúng câu hỏi nội dung của nhóm xem có ký hiệu so với nhóm chỉ có phụ đề. Baseline: [CẦN ĐO] |
| **Boundary** | Một loại nội dung có kịch bản sẵn, một phương ngữ NNKH, người Điếc duyệt bắt buộc mọi video. Không làm live, không để máy tự xuất bản |

---

# Phase 6 — Rule / Workflow / Agent + Decision

## 6.0 — Ma trận độ phù hợp với AI

| Câu hỏi | Trả lời của nhóm |
|---|---|
| Output có thể khác nhau mỗi lần mà vẫn chấp nhận được không? | **Có** — nhiều cách diễn đạt ký hiệu vẫn đúng, miễn truyền đúng ý → độ mơ hồ **cao** |
| Cần phối hợp 3+ bước hoặc 3+ nguồn dữ liệu không? | **Có** — phụ đề, danh mục 408 từ chuẩn, ngữ pháp không gian NNKH, video gốc → độ phức tạp **cao** |
| AI có cần tự quyết định bước tiếp theo không? | **Không** — trình tự luôn cố định: tách câu → gloss → dựng hình → duyệt → xuất bản. AI không tự chọn bước kế tiếp |

```text
Bài toán nằm ở ô: độ phức tạp cao × độ mơ hồ cao (ô "Agent có thể phù hợp").
```

```text
Vì sao vẫn chọn Workflow chứ không Agent:
Hai câu hỏi đầu đẩy bài toán vào ô gợi ý Agent. Nhưng câu hỏi thứ ba —
AI có tự quyết định bước tiếp theo không — trả lời KHÔNG, và đây là câu hỏi
quyết định, không phải hai câu kia. Trình tự 5 bước không đổi giữa các video;
AI chỉ cần chạy đúng chuỗi đó, không cần tự lập kế hoạch. Độ mơ hồ cao nằm ở
NỘI DUNG đầu ra, không nằm ở QUY TRÌNH — nên vẫn là Workflow, chỉ là Workflow
có một bước AI khó hơn bình thường.
```

## 6.1 — So sánh Rule / Workflow / Agent

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? |
|---|---|---|---|---|
| **Rule** | Từ điển tra 1-1: chữ tiếng Việt → ký hiệu trong danh mục 408 từ | Chỉ đủ cho thuật ngữ cố định (chữ cái, số, tên riêng) | NNKH có ngữ pháp không gian riêng — ghép rule từng-từ ra câu vô nghĩa | Không, nhưng dùng làm lớp nền bên trong Workflow |
| **Workflow** | Máy tách câu → sinh gloss → dựng nháp → **người Điếc duyệt bắt buộc** → xuất bản | Nội dung có kịch bản cố định, trình tự các bước luôn giống nhau | Bản nháp sai mà người duyệt bỏ sót nếu mệt hoặc số lượng lớn | **Có — mức chọn** |
| **Agent** | Máy tự quyết định khi nào cần thêm ngữ cảnh, tự tìm nguồn bổ sung, tự xuất bản không cần duyệt | Chỉ khi cần xử lý số lượng cực lớn hoàn toàn không có người | Đúng rủi ro WFD/WASLI (2018) đã cảnh báo: avatar thay thế người hoàn toàn, sai văn hóa không ai bắt được | Không |

Mức chọn:

```text
Workflow
```

Vì sao chọn:

```text
Pipeline cố định, AI không cần tự quyết định bước tiếp theo (xem 6.0). Hai
sản phẩm thương mại đang chạy thật — Signapse, SiMAX — đều vận hành đúng
mức Workflow, không phải Agent: máy sinh nháp, người Điếc luôn là bước cuối.
Đây là bằng chứng mức này đã đủ ở quy mô thương mại thật, không phải suy
đoán của nhóm.
```

Vì sao không chọn mức đơn giản hơn (Rule):

```text
Danh mục chuẩn quốc gia (Thông tư 17/2020) chỉ có 408 từ — không đủ phủ nội
dung tự do của một video bất kỳ. Và dịch từng-từ-sang-từng-ký-hiệu không tôn
trọng ngữ pháp không gian của NNKH, tạo ra chuỗi ký hiệu người Điếc không
hiểu được — đúng lỗi mà chuẩn quốc gia không giải quyết được vì nó chỉ là
từ vựng, không phải ngữ pháp.
```

## 6.2 — Problem Statement v1

| Field | Nội dung |
|---|---|
| **Actor** | Người Điếc dùng NNKH làm ngôn ngữ thứ nhất, xem video tiếng Việt trên YouTube |
| **Workflow** | Xem 5.1/5.2 — hiện tại bước ký hiệu không tồn tại; tương lai máy dựng nháp, người duyệt, rồi xuất bản |
| **Bottleneck** | Thiếu phiên dịch (hơn 10 người cả nước) khiến bước ký hiệu bị bỏ qua mặc định |
| **Impact** | [CẦN ĐO qua phỏng vấn] |
| **Success Metric** | Tỉ lệ hiểu đúng nội dung, có ký hiệu so với chỉ phụ đề. Baseline [CẦN ĐO] |
| **Boundary** | 1 loại nội dung có kịch bản sẵn, 1 phương ngữ, người Điếc duyệt bắt buộc, không live, không AI tự xuất bản |
| **AI intervention point** | Bước 1-3: tách câu, sinh gloss, dựng bản nháp animation |
| **Mức chọn** | Workflow |
| **Rủi ro & người thật kiểm tra** | Rủi ro chính: nháp sai văn hóa/ngữ pháp mà người duyệt (bước 4, người Điếc, bắt buộc) bỏ sót nếu mệt hoặc số lượng lớn. Kiểm soát: ngưỡng lỗi nghiêm trọng = 0, dừng ngay khi phát hiện một lỗi loại này lọt qua |

## 6.3 — Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú |
|---|---|---|
| Actor và workflow đã rõ chưa? | Not Yet | Actor rõ; workflow phía người xem vẫn là suy luận, chưa phỏng vấn ai |
| Baseline và success metric đã đo được chưa? | Not Yet | Toàn bộ metric ở 5.3/6.2 còn `[CẦN ĐO]` |
| Có data/input đủ dùng chưa? | Not Yet | Chưa chốt phương ngữ (5.1 phạm vi); chưa đếm tỉ lệ phủ 408 từ trên video mẫu |
| Nếu AI sai, hậu quả có chấp nhận được không? | Yes | Có bước duyệt bắt buộc + ngưỡng lỗi = 0. Hậu quả tệ nhất là nháp bị bác, không phải xuất bản sai |
| Có người review/owner vận hành không? | Yes | Người Điếc duyệt là bắt buộc trong thiết kế, không phải tùy chọn |
| Có cách non-AI đơn giản hơn không? | Yes | PiP người thật — đúng nhưng không scale (hơn 10 phiên dịch cả nước) |

Decision:

```text
Not Yet
```

Lý do:

```text
Khung so sánh Rule/Workflow/Agent và ranh giới người/máy đã rõ và có bằng
chứng (WFD/WASLI, Signapse, SiMAX, Thông tư 17/2020). Nhưng metric baseline
và bằng chứng trực tiếp về hành vi xem YouTube của người Điếc Việt Nam thì
chưa có — mọi evidence hiện tại chỉ chứng minh "thiếu tiếp cận nói chung".
Quyết định Go trước khi có dữ liệu đó là go vì muốn làm AI, không phải vì
bằng chứng.
```

Nếu Go (sau khi validate), pilot nhỏ nhất là:

```text
1 video dưới 3 phút, 1 phương ngữ đã chốt, nội dung có kịch bản sẵn. Cho 5
người Điếc duyệt bản nháp AI, đo: tỉ lệ câu phải sửa, và tỉ lệ trả lời đúng
câu hỏi nội dung so với nhóm chỉ xem phụ đề.
```

Nếu Not Yet, cần validate gì trước:

```text
1. Phỏng vấn 5-10 người Điếc thật, hỏi bằng video ký hiệu — không hỏi bằng
   bảng hỏi chữ.
2. Cho cùng nhóm đó xem 2 mẫu (người thật PiP vs avatar 3D), hỏi thích cái nào.
3. Đếm tỉ lệ phủ: lấy phụ đề 5 video mẫu, đối chiếu 408 từ chuẩn quốc gia.
4. Chốt 1 phương ngữ theo nơi nhóm tiếp cận được người Điếc để duyệt.
5. Đọc nghiên cứu JASigning/SiGML tiếng Việt đã có trước khi tự dựng lại.
```

Nếu No-Go, nên làm gì thay AI:

```text
Vận động creator lớn thêm PiP người thật cho video quan trọng nhất trước;
hoặc hợp tác trực tiếp với 1 trong hơn 10 phiên dịch hiện có, ưu tiên nội
dung giáo dục/y tế công cộng trước khi mở rộng.
```