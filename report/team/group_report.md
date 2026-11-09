# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: HMHH
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu):
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 |Hưng |Khi bắt đầu làm một bài lab tôi phải đọc rất nhiều file và phải mở đi mở lại trong quá trình làm |Sinh viên làm bài lab. Trợ giảng, người hướng dẫn bài lab. |Đối chiếu thông tin giữa nhiều nguồn (15 phút). |Có cần thiết không nếu chỉ cần ném hết file cho 1 AI khác để tổng hợp (Hoàng)|
| 2 | Hưng|Khi sử dụng một codebase hoặc framework mới, tôi muốn nhanh chóng hiểu được workflow| Sinh viên IT. Lập trình viên mới. Thành viên mới tham gia dự án|Tìm hiểu liên kết giữa các module (35 phút) |“Hiểu workflow và liên kết giữa các module” chưa gắn với công việc cụ thể vẫn hơi mơ hồ (Hiếu)|
| 3 | Hưng|Muốn biết tiến độ và vấn đế gặp phải nếu có trong làm việc nhóm  |Trưởng nhóm. Các thành viên |Chờ phản hồi từ các thành viên.(15 phút) | Vấn đề có thể tự cải thiện từ việc cải thiện ý thức của các thành viên không?(Mạnh)|
| 4 |Hoàng |Khi cuối tuần tôi cần tổng hợp lại quá trình làm việc của nhóm của các thành viên trong nhóm để báo cáo cho mentor |Trưởng nhóm, các thành viên, mentor |Bước đọc và tổng hợp mất nhiều thời gian khoảng 1 tiếng. Bước tự đánh giá mất khoảng 30p | Có thể cho các thành viên báo cáo vào 1 file doc chung được không(Mạnh)|
| 5 |Hoàng |Trước khi đi siêu thị tôi phải lập thực đơn và danh sách thực phẩm cho cả tuần | Tôi, những người nội trợ|Lên thực đơn và list thực phẩm phải mua mất khoảng 1 tiếng | Có thể có 3-5 thực đơn rồi xoay vòng được không(Hưng)|
| 6 | Hoàng|Phải check nhiều vấn đề như TKB, các lịch phát sinh và các kênh tin tức trên nhiều nền tảng |Học viên AI thực chiến | Bước check thông tin trên các nền tảng khác nhau (30p)| Làm thế nào để biết đâu là thông tin quan trọng?(Hiếu)|
| 7 |Mạnh |Khi bắt đầu làm bài Lab, tôi muốn biết rõ cần phải làm những bài nào, để có thể làm và nộp bài đầy đủ |Học viên | Đọc các file khoảng 1 tiếng| Nếu không có AI thì có thể giảm thời gian đọc file này bằng cách nào(Hoàng) |
| 8 |Mạnh | Khi AI Coding Agent generate code, tôi muốn biết AI đã làm những gì, để đảm bảo những thứ AI làm là đúng theo plan| Lập trình viên|Kiểm tra và đối chiếu với plan khoảng 15 - 30 phút|Làm thế nào để biết chính xác được xem là code gen ra đã chuẩn rồi (Hưng) |
| 9 | Mạnh| Khi vào đầu buổi sáng, tôi cần biết trong kho còn thiếu nguyên liệu gì, để có thể chuẩn bị đầy đủ nguyên liệu trước khi làm món|Người pha chế đồ uống |Kiểm tra số lượng và so sánh tồn kho khoảng 20 - 30 phút |Có những đồ khó có thể đo được như là chất lỏng mà không phải là hộp hay cái thì kiểm soát như thế nào(Hiếu) |
| 10 | Hiếu|Khi backend hoặc BA đổi API hoặc nghiệp vụ, tôi muốn biết ngay phần giao diện nào bị ảnh hưởng, để không phát hiện muộn ở giai đoạn test | dev frontend, backend, BA|Dò code khoảng 30 Phút|Lỗi này có thể được hạn chế mà không cần AI không?(Mạnh)  |
| 11 | Hiếu|Khi code xong hoặc sửa code một tính năng, tôi muốn biết ngay mình có vi phạm quy ước dự án không|Dev frontend,reviewer, lead/PM |Review mất 30 phút/lần| Bottleneck là bước này hay là do chưa kiểm tra code trước khi đẩy lên(Hoàng)|
| 12 | Hiếu|Khi đến kỳ báo cáo, tôi (trưởng nhóm) muốn có sẵn việc mỗi thành viên đã hoàn thành và chưa hoàn thành |Trưởng nhóm dự án,thành viên,CEO, PM  | Thu thập tiến độ khoảng 30 phút vì phải hỏi|Có thể dùng 1 cái file chung để mọi người điền báo cáo không?(Hưng)|

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A-Tổng hợp tài liệu| Đọc và đối chiếu nhiều file khi làm lab. Tìm hiểu workflow và liên kết giữa các module trong codebase/framework mới. Đọc tài liệu để biết đầy đủ các bài lab cần làm và nộp. |Thông tin cần thiết nằm ở nhiều phần; người dùng mất thời gian đọc, liên kết và xác định những gì cần hiểu trước khi bắt đầu làm.|
| B - Báo cáo/tổng hợp|Nắm tiến độ và khó khăn của thành viên. Tổng hợp quá trình làm việc của nhóm để báo cáo mentor. Thu thập số việc đã hoàn thành và chưa hoàn thành của từng thành viên.  | Thông tin công việc phân tán ở từng người; phải hỏi, chờ phản hồi và tổng hợp thủ công để có bức tranh chung.|
| C-Review code |Kiểm tra code do AI tạo có đúng kế hoạch không. Xác định phần giao diện bị ảnh hưởng khi API hoặc nghiệp vụ thay đổi. Kiểm tra code có vi phạm quy ước dự án không. | Phải đọc và đối chiếu code với kế hoạch, các phần liên quan hoặc quy ước để phát hiện sai lệch trước khi chuyển sang bước tiếp theo.|
|D – Cập nhật và lọc thông tin đa kênh|Kiểm tra thời khóa biểu, lịch phát sinh và tin tức trên nhiều nền tảng.|Phải chuyển qua nhiều kênh và tự lọc thông tin để biết điều gì quan trọng, điều gì cần hành động.|
|E – Kiểm kê và lập kế hoạch nguyên liệu, thực phẩm|Lên thực đơn và danh sách thực phẩm cần mua cho cả tuần. Kiểm tra nguyên liệu tồn kho để chuẩn bị trước khi làm món.|Cần đối chiếu lượng đang có với nhu cầu sử dụng để xác định những gì cần chuẩn bị hoặc mua thêm.|

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME:
Giảm thời gian xác định đầy đủ yêu cầu Lab
từ 60 phút xuống dưới 30 phút,
không làm tăng tỷ lệ bỏ sót yêu cầu.

├── Opportunity A:
│   Học viên khó tìm đầy đủ nhiệm vụ vì
│   thông tin phân tán trong nhiều file.
│
├── Opportunity B:
│   Học viên khó phân biệt nhiệm vụ bắt buộc,
│   nhiệm vụ tùy chọn và tiêu chí chấm điểm.
│
└── Opportunity C:
    Học viên phải đọc lại nhiều tài liệu
    để kiểm tra bài làm có đúng yêu cầu.
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

-

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
|Tổng hợp tài liệu lab |5 |5 |3 |5 |5 |5 | 5|33 |
|Báo cáo tiến độ | 5|4 |3 |4 |5 |4 |5 |30 |
|Kiểm kê lập kế hoạch thực phẩm |4 |5 |3 |4 |4 | 4|3 |27 |

**Candidate được chọn:**

Tổng hợp tài liệu lab.

**Vì sao chọn:**

Vấn đề gần với trải nghiệm của nhóm: phải đọc nhiều file, đối chiếu yêu cầu và mở lại tài liệu trong quá trình làm bài. Dễ tiếp cận tài liệu và người dùng để thử nghiệm; phạm vi phù hợp với bài lab. Có thể đo hiệu quả bằng thời gian tìm yêu cầu, số yêu cầu bị bỏ sót và độ chính xác của bản tổng hợp. Dù điểm sơ bộ thấp hơn báo cáo tiến độ nhóm, hướng này có thể thử nghiệm ngay trên một bộ tài liệu có sẵn, ít phụ thuộc vào việc nhiều người cập nhật thông tin.

**Vì sao loại các candidate còn lại:**

Báo cáo tiến độ nhóm: Hiệu quả phụ thuộc vào việc thành viên cập nhật đầy đủ, đúng hạn. Cần kiểm chứng thêm liệu biểu mẫu báo cáo chung đã đủ giải quyết vấn đề hay chưa.

Kiểm kê, lên kế hoạch thực phẩm: Phạm vi còn rộng, đang gộp nhu cầu gia đình và pha chế. Cần thêm dữ liệu về tồn kho, định lượng, khẩu phần và ngân sách; nhóm chưa hiểu rõ domain bằng tài liệu lab.

**Xử lý bất đồng (nếu có):**

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

Với vấn đề tổng hợp thông tin để làm bài lab, tôi đưa ra các giả định sau:

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Sinh viên cũng gặp khó khăn khi phải đọc nhiều file và quy định để làm bài lab | Value | 5 | 1 | Có |
| 2 | Việc đọc và đối chiếu thông tin từ nhiều nguồn làm mất nhiều thời gian | Value | 5 | 1 | Có |
| 3 | Việc đối chiếu yêu cầu giữa README, CHECKPOINTS và RUBRIC là bước gây khó khăn | Value | 4 | 1 | Có |
| 4 | AI có thể đọc nhiều tài liệu và tổng hợp yêu cầu kèm nguồn tham khảo | Feasibility | 4 | 3 | Có |
| 5 | Sinh viên được phép sử dụng AI với tài liệu của bài lab | Viability | 4 | 2 | Có |
| 6 | Người dùng có thể dễ dàng đưa tài liệu vào và nhận được nội dung tổng hợp phù hợp | Usability | 3 | 2 | Không |

Giả định nhóm kiểm chứng trong buổi này:

Các giả định cần kiểm tra trước là vấn đề có thực sự xảy ra với sinh viên khác hay không, thời gian bị mất nằm ở bước nào và các hướng dẫn có sẵn trong đề lab đã giải quyết được vấn đề chưa.

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn theo phương pháp Mom Test (dự kiến). Các câu hỏi tập trung vào trải nghiệm thực tế thay vì hỏi người được phỏng vấn có thích ý tưởng hay không.

Một số câu hỏi dự kiến:

- Lần gần nhất bạn làm bài lab có nhiều file hướng dẫn là khi nào?
- Bạn đã đọc những file nào và đọc theo thứ tự nào?
- Có lúc nào bạn phải quay lại README, CHECKPOINTS hoặc RUBRIC để kiểm tra thông tin không?
- Phần nào khiến bạn mất nhiều thời gian nhất?
- Bạn thường làm gì để tổng hợp các yêu cầu trước khi bắt đầu?
- Bạn đã từng bỏ sót yêu cầu nào do có quá nhiều thông tin chưa?

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Chưa phỏng vấn |
| Câu nói đáng nhớ nhất (nguyên văn) | Chưa có |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Chưa có dữ liệu |
| Hiện đang xử lý bằng cách nào (workaround)? | Chưa có dữ liệu |
| Mất bao lâu, bao lần? | Chưa có dữ liệu |
| Insight / opportunity rút ra | Cần kiểm chứng thêm |

Hiện tại tôi chưa có kết quả phỏng vấn thực tế nên chưa thể kết luận các giả định trên đúng hay sai.

Tổng hợp:

| Nguồn | Bằng chứng | Nhận xét |
|---|---|---|
| Trải nghiệm cá nhân | Ước tính khoảng 60 phút để đọc và tổng hợp tài liệu bài lab | Chưa phải số liệu đo thực tế |
| README | Có hướng dẫn thứ tự đọc | Cần kiểm tra mức độ hữu ích |
| CHECKPOINTS | Có phần tự kiểm tra cho từng CP | Cần kiểm tra xem đã đủ rõ chưa |
| SUBMISSION | Có checklist trước khi nộp | Có thể hỗ trợ giảm việc bỏ sót yêu cầu |
| Phỏng vấn | Chưa thực hiện | Chưa có dữ liệu từ người khác |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

Chưa có đủ dữ liệu để xác nhận Problem Statement ban đầu. Tạm thời giữ vấn đề ở mức giả định:

> Khi làm bài lab có nhiều file hướng dẫn, tôi muốn tổng hợp và đối chiếu các yêu cầu từ README, CHECKPOINTS và RUBRIC để hiểu rõ những việc cần làm và tránh bỏ sót yêu cầu.

Cần kiểm tra thêm xem khó khăn chính nằm ở việc không biết thứ tự đọc, phải quay lại nhiều lần hay nội dung giữa các file chưa rõ ràng.

### 3.3. Research giải pháp đã có

Tôi tìm hiểu một số công cụ hiện có có thể hỗ trợ đọc và tổng hợp tài liệu.

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| NotebookLM | https://notebooklm.google.com/ | Thêm tài liệu và đặt câu hỏi dựa trên nguồn đã cung cấp | Có thể tổng hợp và trả lời dựa trên tài liệu | Cần kiểm tra lại câu trả lời với tài liệu gốc | <!-- TODO --> |
| ChatGPT | https://help.openai.com/en/articles/8555545-uploading-files-and-audio-to-chatgpt | Tải file lên và yêu cầu đọc, so sánh hoặc tổng hợp | Dễ sử dụng, có thể xử lý nhiều dạng yêu cầu | Có thể hiểu sai hoặc bỏ sót yêu cầu | <!-- TODO --> |
| Adobe Acrobat AI Assistant | https://helpx.adobe.com/acrobat/desktop/use-acrobat-ai/generative-ai-features/ai-get-answers.html | Đặt câu hỏi và tìm thông tin trong tài liệu PDF | Hữu ích khi đọc tài liệu PDF dài | Không tập trung riêng vào yêu cầu của bài lab | <!-- TODO --> |

**Kết luận**

Qua tìm hiểu, các công cụ hiện có đã hỗ trợ đọc và tổng hợp tài liệu. Vì vậy, việc chỉ tạo một công cụ tóm tắt nội dung có thể chưa tạo ra nhiều khác biệt.

Nếu tiếp tục phát triển ý tưởng, tôi nghĩ cần tập trung vào việc tổng hợp yêu cầu riêng cho bài lab, đối chiếu thông tin giữa README, CHECKPOINTS và RUBRIC, đồng thời chỉ rõ nguồn của từng yêu cầu. Tuy nhiên, trước khi chọn giải pháp AI, tôi vẫn cần kiểm tra xem các hướng dẫn và checklist có sẵn đã đủ giải quyết vấn đề hay chưa.

---

## 4. Quy trình trước/sau (CP5)
 
### 4.1. Quy trình hiện tại
 
Candidate được dùng để vẽ quy trình: **đọc và đối chiếu nhiều tài liệu khi bắt đầu một bài lab** (gộp pitch #1 của Hưng và pitch #7 của Mạnh, cùng cluster A; problem đã chỉnh ở mục 3.2).
 
Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):
 
```text
[1] Xác định có những file nào cần đọc            (cần đo)
        |
        v
[2] Đọc lần lượt từng file                        (~60 phút/bài lab)
        |
        v
[3] Đối chiếu đề bài / README / rubric            (~15 phút)  <== BOTTLENECK (giả thuyết)
        |
        v
[4] Ghi lại danh sách việc cần làm, rule, tiêu chí (cần đo)
        |
        v
[5] Làm bài, mở lại file gốc để kiểm tra khi cần  (nhiều lần, cần đo)
```
 
| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Sinh viên | Repo / thư mục bài lab | Danh sách file cần đọc (đề bài, README, rule, rubric) | Cần đo | Chưa ai trong nhóm báo số phút cho bước này |
| 2 | Sinh viên | Từng file riêng lẻ | Hiểu rời rạc về yêu cầu của từng file | ~60 phút mỗi bài lab | Nguồn: pitch #7 (Mạnh), 1 người tự báo |
| 3 | Sinh viên | Hiểu biết từ nhiều file | Biết yêu cầu nào trùng, lệch hoặc thiếu giữa các nguồn | ~15 phút | Nguồn: pitch #1 (Hưng), 1 người tự báo. Chưa rõ có nằm trong 60 phút ở bước 2 hay không |
| 4 | Sinh viên | Kết quả bước 3 | Danh sách việc cần làm, rule, tiêu chí chấm | Cần đo | Thường ghi tay hoặc nhớ trong đầu |
| 5 | Sinh viên | Danh sách ở bước 4 + file gốc | Bài lab hoàn thành và nộp đủ | Mở lại file nhiều lần mỗi bài (pitch #1), chưa có số phút | Mở lại file gốc khi quên hoặc nghi ngờ yêu cầu |
 
 
**Bottleneck chính:** Bước 3, đối chiếu yêu cầu giữa đề bài, README và rubric (~15 phút mỗi bài). Đây là giả thuyết làm việc, khớp với problem đã chỉnh ở mục 3.2, nhưng số liệu hiện có cho thấy bước 2 (đọc, ~60 phút) tốn nhiều thời gian hơn. Cần đo riêng từng bước trước khi chốt.
 
### 4.2. Quy trình tương lai
 
Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.
 
```text
[1] RULE   Gom đủ file (đề bài, README, rubric), gắn nhãn nguồn theo tên file + mục
        |
        v
[2] AI     Trích việc cần làm, rule, tiêu chí rubric thành checklist
           - mỗi dòng kèm nguồn (file + mục)
           - gắn cờ dòng mâu thuẫn hoặc chưa rõ giữa các file
        |
        v
[3] NGƯỜI  (HITL) Đối chiếu checklist với file gốc:
           bắt buộc kiểm tra mọi dòng bị gắn cờ, mọi con số, hạn nộp, rule bắt buộc
        |
        +-- đạt ------------> [4] NGƯỜI  Làm bài theo checklist,
        |                               mở file gốc qua nguồn khi nghi ngờ
        |
        +-- sai / thiếu / dòng không có nguồn
                             -> [QUAY VỀ] Bỏ dòng đó, đọc trực tiếp file gốc
                                          (như quy trình hiện tại)
```
 
| Bước | Ai làm | Việc | Ghi chú |
|---:|---|---|---|
| 1 | Rule | Kiểm tra đủ các loại file, gắn nhãn nguồn | Không cần AI, chỉ là quy ước đặt tên và gom file |
| 2 | AI | Tạo checklist có nguồn, gắn cờ mâu thuẫn | AI chỉ trích và phân loại, không quyết định |
| 3 | Con người | Kiểm tra checklist với file gốc | Bước HITL bắt buộc, không được bỏ |
| 4 | Con người | Làm bài theo checklist | Tra nguồn gốc khi nghi ngờ |
 
**Boundary:** AI không được tự kết luận rule nào đúng khi các file mâu thuẫn (chỉ gắn cờ), không được thêm yêu cầu không có trong tài liệu, và không được đưa ra dòng nào thiếu nguồn. AI không làm bài thay sinh viên.
 
**Phương án quay về:** Nếu một dòng sai, thiếu hoặc không có nguồn, bỏ dòng đó và đọc trực tiếp file gốc. Nếu checklist sai nhiều dòng quan trọng, bỏ cả checklist và quay về quy trình hiện tại (mục 4.1).
 
**Điều kiện áp dụng:** Chỉ đưa tài liệu lab vào công cụ AI khi quy định môn học cho phép (giả định 6 ở mục 3.1 chưa kiểm chứng).
 
### 4.3. Before / after
 
| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | 5 | 4 | Bước 1 và 4 trước đây gộp lại thành checklist có sẵn |
| Tổng thời gian | ~60–75 phút mỗi bài lab (cần đo lại) | ≤ 30 phút (mục tiêu đề xuất, chưa đo) | Trước: ~60 phút đọc (pitch #7) + ~15 phút đối chiếu (pitch #1), chưa rõ chồng lấn. Sau: gồm cả bước kiểm tra của con người |
| Số bước thủ công | 5/5 | 2/4 | Còn lại bước kiểm tra checklist và làm bài |
| Bottleneck chính | Bước 3, đối chiếu giữa các file (giả thuyết) | Bước 3, kiểm tra checklist có nguồn thay vì tự đối chiếu từ đầu | Cần pilot để biết bottleneck mới nằm ở đâu |
| Rủi ro mới phát sinh | Không có | AI bỏ sót hoặc diễn giải sai rule; người dùng tin checklist mà không kiểm tra; đưa tài liệu lab lên công cụ AI có thể vi phạm quy định môn học | Giảm bằng bước HITL bắt buộc, nguồn trên từng dòng và điều kiện áp dụng |
 
---
 
## 5. Problem Statement v0 (CP5)
 
| Trường | Nội dung |
|---|---|
| **Actor** | Sinh viên làm bài lab (4 thành viên nhóm là người dùng đầu tiên). Người liên quan: trợ giảng, người hướng dẫn bài lab. |
| **Quy trình** | Bắt đầu một bài lab: xác định file cần đọc → đọc từng file → đối chiếu đề bài, README, rubric → ghi lại việc cần làm → làm bài và mở lại file gốc khi cần (5 bước, mục 4.1). |
| **Bottleneck** | Bước 3, đối chiếu yêu cầu giữa đề bài, README và rubric, vì thông tin nằm rải rác ở nhiều file và phải tự tìm chỗ trùng, lệch, thiếu (~15 phút mỗi bài). Giả thuyết, bước 2 (đọc, ~60 phút) có thể lớn hơn, cần đo riêng. |
| **Impact** | ~60–75 phút mỗi bài lab dành cho đọc và đối chiếu trước khi bắt đầu làm (tự báo của 2 thành viên). Nếu đối chiếu sai hoặc sót, sinh viên có thể bỏ sót yêu cầu, làm thiếu hoặc phải làm lại (chưa có số liệu). Số bài lab mỗi kỳ chưa đo. |
| **Success Metric** (baseline → target, cách đo) | **Thời gian:** baseline ~60–75 phút mỗi bài lab (cần đo lại trên ít nhất 3 lần làm lab thật) → target ≤ 30 phút, tính cả bước kiểm tra của con người (đề xuất, nhóm xác nhận). **Chất lượng:** số yêu cầu bắt buộc bị bỏ sót sau khi kiểm tra = 0. **Cách đo:** bấm giờ từ lúc mở file đến lúc có checklist đã kiểm tra, trên cùng một bài lab, làm tay so với quy trình mới. Đếm bỏ sót bằng cách so với danh sách yêu cầu do người đối chiếu tay lập. |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | AI **không được**: tự kết luận rule nào đúng khi các file mâu thuẫn (chỉ gắn cờ), thêm yêu cầu không có trong tài liệu, đưa dòng không kèm nguồn, hoặc làm bài thay sinh viên. **Con người bắt buộc kiểm tra** trước khi làm bài: mọi dòng bị gắn cờ, mọi con số, hạn nộp, rule bắt buộc. Chỉ dùng khi quy định môn học cho phép đưa tài liệu lên công cụ AI. |
 
Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:
 
Các lỗ hổng dưới đây do AI chỉ ra, chưa viết lại v0. Cột cuối để nhóm tự điền sau khi thảo luận.
 
| # | Lỗ hổng | Vì sao đáng lo | Nhóm đồng ý? |
|---:|---|---|---|
| 1 | Baseline chỉ là tự báo của 2 người, mỗi con số 1 nguồn, chưa có phỏng vấn CP4. | Đây là bằng chứng yếu, chưa phân biệt được "tôi thấy lâu" với "thực tế lâu". | Nhóm điền |
| 2 | 60 phút (đọc) và 15 phút (đối chiếu) có thể chồng lấn, tổng 75 phút chưa chắc đúng. | Baseline sai thì target ≤ 30 phút không có ý nghĩa. | Nhóm điền |
| 3 | Bottleneck chọn là đối chiếu (15 phút) nhưng bước đọc (60 phút) tốn nhiều hơn. | Nếu bước đọc mới là nghẽn thật, quy trình tương lai đang nhắm sai chỗ. | Nhóm điền |
| 4 | Mục 1 và 2.4 chưa ghi candidate được chọn. Bản này dựa vào pitch #1, #7 và mục 3.2. | Problem Statement phải nối được với candidate đã chốt ở CP3. | Nhóm điền |
| 5 | Target ≤ 30 phút là đề xuất, chưa có cơ sở. | Cần nhóm quyết định hoặc đo thử trước khi đưa vào v1. | Nhóm điền |
| 6 | Phản biện của Hoàng ở pitch #1 (đưa hết file cho một AI khác) và kết quả research 3.3 cho thấy công cụ đọc và tóm tắt đã có sẵn. | Phần khác biệt của nhóm chỉ còn là checklist có nguồn và gắn cờ mâu thuẫn, cần nói rõ vì sao công cụ có sẵn chưa đủ. | Nhóm điền |
| 7 | Giả định 6 (quy định môn học về việc đưa tài liệu lên AI) chưa kiểm chứng. | Nếu không được phép, toàn bộ bước 2 phải bỏ. | Nhóm điền |

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô:

Vì sao:

### 6.2. So sánh 4 mức

| Mức                       | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
| ------------------------- | -------------------------- | ---------- | ------ | ----- |
| **No AI** (sửa quy trình) |                            |            |        |       |
| **Rule**                  |                            |            |        |       |
| **Workflow**              |                            |            |        |       |
| **Agent**                 |                            |            |        |       |

**Mức chọn:**

**Vì sao không chọn mức đơn giản hơn:**

### 6.3. AI Canvas rút gọn

| Thành phần                                                        | Nội dung |
| ----------------------------------------------------------------- | -------- |
| **Prediction** — AI dự đoán / tạo ra gì?                          |          |
| **Judgment** — con người cân nhắc, quyết định gì?                 |          |
| **Action** — hành động cuối cùng là gì, ai làm?                   |          |
| **Outcome** — đo kết quả bằng gì?                                 |          |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? |          |
| **Feedback** — lấy phản hồi ở đâu để cải thiện?                   |          |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường                                          | Nội dung                        |
| ----------------------------------------------- | ------------------------------- |
| **Actor**                                       |                                 |
| **Quy trình**                                   |                                 |
| **Bottleneck**                                  |                                 |
| **Impact**                                      |                                 |
| **Success Metric** (baseline → target, cách đo) |                                 |
| **Boundary**                                    |                                 |
| **AI intervention point**                       |                                 |
| **Mức chọn**                                    | No AI / Rule / Workflow / Agent |
| **Rủi ro & người kiểm tra**                     |                                 |

**Thay đổi so với v0 và lý do:**

| Trường | v0  | v1  | Vì sao đổi |
| ------ | --- | --- | ---------- |
|        |     |     |            |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

|   # | Tiêu chí | Đạt khi | Không đạt khi |
| --: | -------- | ------- | ------------- |
|   1 |          |         |               |
|   2 |          |         |               |
|   3 |          |         |               |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro          | Câu hỏi                                                           | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
| --------------- | ----------------------------------------------------------------- | ----------------------------------------------------- | ------------------ |
| **Value**       | Người dùng có thật sự cần và sẽ dùng không?                       |                                                       |                    |
| **Usability**   | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? |                                                       |                    |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không?                     |                                                       |                    |
| **Viability**   | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành?     |                                                       |                    |

### 8.2. Kết luận

**Quyết định:** Go / Not Yet / No-Go

**Lý do:**

**Nếu Go — pilot nhỏ nhất:**

**Nếu Not Yet — cần kiểm chứng gì trước:**

**Nếu No-Go — nên làm gì thay AI:**

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

---

## 9. Hạn chế và hướng tiếp theo

-

## 10. Tài liệu tham khảo

-
