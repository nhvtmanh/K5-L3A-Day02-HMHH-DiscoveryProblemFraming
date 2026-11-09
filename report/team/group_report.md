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

|   # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
| --: | -------- | -------------------------------------------------- | ---------------: | ---------------------: | ----------------- |
|   1 |          |                                                    |                  |                        |                   |
|   2 |          |                                                    |                  |                        |                   |
|   3 |          |                                                    |                  |                        |                   |
|   4 |          |                                                    |                  |                        |                   |
|   5 |          |                                                    |                  |                        |                   |
|   6 |          |                                                    |                  |                        |                   |

_Điền 4–6 giả định; xóa dòng thừa._

Giả định nhóm kiểm chứng trong buổi này:

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey / Log, ticket, review

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường                                            | Nội dung |
| ------------------------------------------------- | -------- |
| Người được hỏi (vai trò, không ghi tên thật)      |          |
| Câu nói đáng nhớ nhất (nguyên văn)                |          |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? |          |
| Hiện đang xử lý bằng cách nào (workaround)?       |          |
| Mất bao lâu, bao lần?                             |          |
| Insight / opportunity rút ra                      |          |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
| ----- | ----------------: | ----------------- | ----------------- |
|       |                   |                   |                   |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
| ------------------------ | ---- | ------------------------------ | --------- | --------------------- | ---------------- |
|                          |      |                                |           |                       |                  |
|                          |      |                                |           |                       |                  |
|                          |      |                                |           |                       |                  |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
| ---: | ----- | ----- | ------ | -------------------- | ------- |
|    1 |       |       |        |                      |         |
|    2 |       |       |        |                      |         |
|    3 |       |       |        |                      |         |
|    4 |       |       |        |                      |         |
|    5 |       |       |        |                      |         |

**Bottleneck chính:**

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text

```

### 4.3. Before / after

| Chỉ số               | Trước | Sau (kỳ vọng) | Ghi chú |
| -------------------- | ----: | ------------: | ------- |
| Số bước              |       |               |         |
| Tổng thời gian       |       |               |         |
| Số bước thủ công     |       |               |         |
| Bottleneck chính     |       |               |         |
| Rủi ro mới phát sinh |       |               |         |

---

## 5. Problem Statement v0 (CP5)

| Trường                                                                     | Nội dung |
| -------------------------------------------------------------------------- | -------- |
| **Actor**                                                                  |          |
| **Quy trình**                                                              |          |
| **Bottleneck**                                                             |          |
| **Impact**                                                                 |          |
| **Success Metric** (baseline → target, cách đo)                            |          |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) |          |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

- ***

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
