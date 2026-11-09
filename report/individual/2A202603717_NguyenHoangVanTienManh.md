# Báo cáo cá nhân — 2A202603717_NguyenHoangVanTienManh

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Nguyễn Hoàng Văn Tiến Mạnh
- MSSV: 2A202603717
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: HMHH
- Link repo nhóm: https://github.com/nhvtmanh/K5-L3A-Day02-HMHH-DiscoveryProblemFraming.git

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

|   # | Lăng kính                         | Job Story: Khi… tôi muốn… để…                                                                                                   | Ai chịu ảnh hưởng?    | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng)                 |
| --: | --------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- | --------------------- | ------------------------------------------------------------------------- |
|   1 | Lặp lại                           | Khi mỗi tối trước khi đi ngủ, tôi muốn biết ngày hôm nay đã làm được những gì, để chuẩn bị những việc cần làm vào sáng mai      | Tôi                   | 15 phút mỗi tối                                                           |
|   2 | Tốn thời gian                     | Khi AI Coding Agent generate code, tôi muốn biết AI đã làm những gì, để đảm bảo những thứ AI làm là đúng theo plan              | Lập trình viên        | Mất 15 - 30 phút tùy độ khó task                                          |
|   3 | Cần đọc, tổng hợp nhiều thông tin | Khi bắt đầu làm bài Lab, tôi muốn biết rõ cần phải làm những bài nào, để có thể làm và nộp bài đầy đủ                           | Học viên AI20K        | Mất trung bình 1 tiếng để tự tổng hợp thông tin                           |
|   4 | Pain từ người khác                | Khi vào đầu buổi sáng, tôi cần biết trong kho còn thiếu nguyên liệu gì, để có thể chuẩn bị đầy đủ nguyên liệu trước khi làm món | Người pha chế đồ uống | Mất khoảng 20 - 30 phút để lên danh sách nguyên vật liệu cần nhập         |
|   5 | Pain từ người khác                | Khi vào cuối tháng, tôi cần biết mỗi nhân sự đã làm việc bao nhiêu tiếng, để có thể tính lương cho họ                           | Bộ phận nhân sự       | Mất 1 - 2 tiếng để lên danh sách, tổng hợp và kiểm tra lại nếu có sai sót |

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem                       | Vì sao chọn                                                    | Điều còn chưa chắc                                                              |
| ---: | ----------------------------- | -------------------------------------------------------------- | ------------------------------------------------------------------------------- |
|    1 | Tổng hợp thông tin từ bài Lab | Mất thời gian để đọc nhiều file khác nhau                      | AI có thể tổng hợp thiếu thông tin quan trọng                                   |
|    2 | Review code AI                | Cần đảm bảo AI làm đúng yêu cầu                                | Chưa có cách đo chất lượng code phù hợp                                         |
|    3 | Kiểm tra nguyên liệu          | Để biết thiếu hiện tại đang thiếu nguyên liệu nào cần chuẩn bị | Làm thế nào để xác định chính xác nguyên liệu hiện có và nguyên liệu còn thiếu? |

### Problem Card #1

| Trường                                    | Nội dung                                                                                                                                |
| ----------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story                                 | Khi bắt đầu làm bài Lab, tôi muốn biết rõ cần phải làm những bài nào, để có thể làm và nộp bài đầy đủ                                   |
| Actor                                     | Học viên AI20K                                                                                                                          |
| Thời điểm / bối cảnh                      | Vào đầu buổi Lab                                                                                                                        |
| Quy trình hiện tại (3–7 bước)             | 1. Clone repository về máy 2. Đọc README.md 3. Đọc RULES.md 4. Đọc CHECKPOINTS.md 5. Đọc RUBRIC.md 6. Đọc SUBMISSION.md                 |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2 - 6: khoảng 1 tiếng, có thể mất nhiều hơn khi bắt đầu làm vì phải đọc lại file cần thiết để check có làm đúng yêu cầu không      |
| Impact (nếu không giải thì sao)           | Mất thời gian xác định nhiệm vụ, có thể bỏ sót checkpoint, yêu cầu chấm điểm hoặc file cần nộp, dẫn đến nộp bài thiếu hoặc sai quy định |
| Success metric (baseline → target)        | Tổng thời gian đọc hiểu từ 1 tiếng xuống dưới 30 phút                                                                                   |
| Phương án không dùng AI                   | Có một file tổng hợp bao gồm hướng dẫn, checklist, tiêu chí hoàn thành và yêu cầu nộp bài                                               |
| Giả thuyết về AI (nếu có)                 | AI đọc các file Lab và tự động trích xuất nhiệm vụ, checkpoint, rubric và yêu cầu nộp bài                                               |
| Cảm nhận nhanh                            | Workflow                                                                                                                                |

Quy trình nháp hiện tại:

```text

HIỆN TẠI — ≥ 60 phút

[1 Clone repository: 1']
    ↓
[2 Đọc README.md: 15']
    ↓
[3 Đọc RULES.md: 10']
    ↓
[4 Đọc CHECKPOINTS.md: 15']
    ↓
[5 Đọc RUBRIC.md: 10']
    ↓
[6 Đọc SUBMISSION.md: 10']
    ↑
    └── BOTTLENECK: Bước 2–6 (~60 phút)
        Đọc, đối chiếu nhiều file để hiểu yêu cầu
        và xác định đầy đủ nhiệm vụ cần làm.

Trong lúc làm Lab:
[Tra cứu lại file] → [Kiểm tra yêu cầu] → [Tiếp tục làm]
         ↑
         └── Có thể lặp lại nhiều lần

```

### Problem Card #2

| Trường                                    | Nội dung                                                                                                                                                                                                                                           |
| ----------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story                                 | Khi AI Coding Agent generate code, tôi muốn biết AI đã làm những gì, để đảm bảo những thứ AI làm là đúng theo plan                                                                                                                                 |
| Actor                                     | Lập trình viên                                                                                                                                                                                                                                     |
| Thời điểm / bối cảnh                      | Sau khi AI Coding Agent generate code                                                                                                                                                                                                              |
| Quy trình hiện tại (3–7 bước)             | 1. Developer đưa yêu cầu và plan cho AI 2. AI tạo hoặc chỉnh sửa code 3. Developer đọc phần tóm tắt của AI 4. Kiểm tra các file thay đổi bằng Git diff 5. Đối chiếu code với plan 6. Chạy build/test 7. Chấp nhận thay đổi hoặc yêu cầu AI sửa lại |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 4 - 5: khoảng 15 - 30 phút tùy độ phức tạp của task                                                                                                                                                                                           |
| Impact (nếu không giải thì sao)           | Có thể bỏ sót yêu cầu hoặc sai logic, không làm đúng plan                                                                                                                                                                                          |
| Success metric (baseline → target)        | Thời gian review giảm xuống thành 5 - 10 phút                                                                                                                                                                                                      |
| Phương án không dùng AI                   | Dùng Git diff và review code theo plan                                                                                                                                                                                                             |
| Giả thuyết về AI (nếu có)                 | AI review code độc lập                                                                                                                                                                                                                             |
| Cảm nhận nhanh                            | Agent                                                                                                                                                                                                                                              |

Quy trình nháp hiện tại:

```text

HIỆN TẠI — >= 60 phút

[1 Developer đưa yêu cầu + plan: 15']
    ↓
[2 AI generate/chỉnh sửa code: 5']
    ↓
[3 Đọc tóm tắt của AI: 5']
    ↓
[4 Kiểm tra Git diff:  10']
    ↓
[5 Đối chiếu code với plan: 20']
    ↓
[6 Chạy build/test: 5']
    ↓
[7 Chấp nhận hoặc yêu cầu AI sửa: 5']
    │
    └── Nếu chưa đạt → Quay lại bước 2

BOTTLENECK: Bước 4–5 (15–30 phút)
Phải đọc các thay đổi và tự xác minh
AI có thực hiện đúng yêu cầu trong plan không

```

### Problem Card #3

| Trường                                    | Nội dung                                                                                                                                                                                                                                                         |
| ----------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story                                 | Khi vào đầu buổi sáng, tôi cần biết trong kho còn thiếu nguyên liệu gì, để có thể chuẩn bị đầy đủ nguyên liệu trước khi làm món                                                                                                                                  |
| Actor                                     | Người pha chế đồ uống                                                                                                                                                                                                                                            |
| Thời điểm / bối cảnh                      | Đầu buổi sáng trước khi mở quán                                                                                                                                                                                                                                  |
| Quy trình hiện tại (3–7 bước)             | 1. Kiểm tra danh sách món dự kiến chế biến 2. Xác định nguyên liệu cần dùng cho từng món 3. Kiểm tra số lượng nguyên liệu trong kho 4. So sánh lượng tồn kho với nhu cầu sử dụng thực tế 5. Ghi lại nguyên liệu thiếu và số lượng cần bổ sung 6. Báo lại cho chủ |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 - 4: khoảng 20 - 30 phút                                                                                                                                                                                                                                  |
| Impact (nếu không giải thì sao)           | Thiếu nguyên liệu pha chế, khách phải đợi món lâu                                                                                                                                                                                                                |
| Success metric (baseline → target)        | Thời gian kiểm tra nguyên liệu giảm xuống dưới 5 phút                                                                                                                                                                                                            |
| Phương án không dùng AI                   | Dùng giấy note lại toàn bộ nguyên liệu và số lượng cần nhập                                                                                                                                                                                                      |
| Giả thuyết về AI (nếu có)                 | AI phân tích và dự báo số lượng món, đề xuất nguyên liệu còn thiếu và số lượng cần nhập                                                                                                                                                                          |
| Cảm nhận nhanh                            | Rule                                                                                                                                                                                                                                                             |

Quy trình nháp hiện tại:

```text

HIỆN TẠI — ~ 60 phút

[1 Kiểm tra món dự kiến pha chế: 5']
    ↓
[2 Xác định nguyên liệu cần dùng: 5']
    ↓
[3 Kiểm tra tồn kho thực tế: 20']
    ↓
[4 So sánh tồn kho với nhu cầu: 10']
    ↓
[5 Ghi nguyên liệu thiếu + số lượng: 10']
    ↓
[6 Báo lại cho chủ quán: 5']

BOTTLENECK: Bước 3–4 (20–30 phút)
Phải kiểm tra từng nguyên liệu và tính toán
thủ công số lượng còn thiếu

```

### Card muốn pitch nhất

- Card số: 1
- Vì sao: nhiều học viên cũng đang gặp tình trạng tương tự
- Câu hỏi muốn nhóm phản biện: làm thế nào để giải quyết hiệu quả vấn đề mất thời gian trên?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra                                                                               | Đồng ý?         | Đã sửa gì                                       |
| ------------------------------------------------------------------------------------------------ | --------------- | ----------------------------------------------- |
| Actor "Học viên" quá chung chung, chưa xác định nhóm học viên cụ thể                             | Đồng ý          | Sửa thành Học viên AI20K                        |
| Quy trình có thể chỉ là giả định, chưa xác minh học viên có thực sự đọc đủ 5 file theo thứ tự đó | Đồng ý một phần | Theo dõi các học viên qua các bài Lab khác nhau |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động                  | Tôi đã làm gì?                                                                                                                               | Kết quả / ảnh hưởng tới bài nhóm                                                                                                                         |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Pitch Problem Card         | Pitch "Tổng hợp thông tin từ bài Lab", "Review code AI", "Kiểm tra nguyên liệu"                                                              | Trao đổi, góp ý và phản biện phần Pitch "Tổng hợp thông tin từ bài Lab"                                                                                  |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: dùng cách nào để xử lý tổng hợp thông tin từ nhiều file?                                                                 | Phân tích dùng Workflow để xử lí thông tin                                                                                                               |
| Problem Statement          | Tham gia xác định Actor, quy trình hiện tại, bottleneck, impact, success metric và boundary cho bài toán tổng hợp thông tin từ tài liệu Lab  | Giúp nhóm làm rõ vấn đề, xác định bước đối chiếu tài liệu là bottleneck giả thuyết và đề xuất mục tiêu giảm thời gian từ 60 - 75 phút xuống dưới 30 phút |
| Mức can thiệp AI           | Phân tích ma trận độ mơ hồ + độ phức tạp, so sánh No AI, Rule, Workflow và Agent, đề xuất Workflow có AI hỗ trợ và học viên kiểm tra kết quả | Giúp nhóm lựa chọn mức can thiệp phù hợp, tránh sử dụng Agent không cần thiết và xác định rõ trách nhiệm của AI và con người                             |
| Quyết định                 | Đánh giá 4 rủi ro Value, Usability, Feasibility, Viability, đề xuất quyết định Not Yet                                                       | Giúp nhóm nhận ra cần thử nghiệm và so sánh với giải pháp không AI trước khi quyết định triển khai                                                       |

---

## 5. Dùng AI

| Checkpoint                     | Tôi dùng AI để làm gì?                       | AI hữu ích ở đâu?                                                | AI sai hoặc hời hợt ở đâu?                                       | Tôi sửa gì bằng nhận định của mình?                                           |
| ------------------------------ | -------------------------------------------- | ---------------------------------------------------------------- | ---------------------------------------------------------------- | ----------------------------------------------------------------------------- |
| CP1 Scan                       | Gợi ý và phân tích các vấn đề thực tế        | Giúp mở rộng ý tưởng, xác định pain và actor                     | Một số vấn đề còn chung chung, thiếu bằng chứng                  | Chọn 3 vấn đề gần với trải nghiệm cá nhân                                     |
| CP2 Problem Card               | Phản biện Problem Card theo góc nhìn PM      | Phát hiện actor chưa rõ, bottleneck và metric chưa cụ thể        | Một số nhận định dựa trên giả định, chưa có dữ liệu thực tế      | Điều chỉnh cách mô tả và xác định những giả định cần kiểm chứng               |
| CP5–6 Problem Statement        | Phân tích và hoàn thiện Problem Statement v1 | Làm rõ bottleneck, success metric, boundary và tiêu chí đánh giá | AI có xu hướng đề xuất giải pháp khi vấn đề chưa được kiểm chứng | Giữ các số liệu chưa xác minh ở mức giả thuyết, bổ sung cách đo và kiểm chứng |
| CP6 Mức can thiệp / quyết định | So sánh 4 mức AI và đánh giá 4 rủi ro        | Giúp lựa chọn Workflow và phân tích lý do Not Yet                | Chưa chứng minh Workflow tốt hơn giải pháp không AI              | Đề xuất thử checklist thủ công và phỏng vấn người dùng trước khi triển khai   |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Nhận ra vấn đề nào thực sự cần để giải quyết thay vì cần AI để giải quyết mọi vấn đề

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Khi thảo luận bài toán đọc nhiều tài liệu Lab, nhóm đã nghĩ đến dùng AI tổng hợp. Có thành viên phản biện rằng chỉ cần đưa các file vào công cụ AI có sẵn hoặc làm checklist thủ công.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Khi phân tích sâu hơn, nhóm nhận ra bước đối chiếu tài liệu khoảng 15 phút cũng là bottleneck giả thuyết.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Research cho thấy NotebookLM và ChatGPT đã hỗ trợ đọc và tổng hợp tài liệu. Điều đáng suy nghĩ là nhóm chưa chứng minh được cần xây công cụ riêng.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Phân biệt vấn đề với giải pháp, xác định đúng bottleneck và xây dựng metric đo được. Ví dụ, baseline 60 – 75 phút chưa chắc chính xác vì thời gian đọc và đối chiếu có thể chồng lấn.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Cân nhắc việc đo thời gian từng bước sớm hơn, phỏng vấn học viên ngoài nhóm, thử checklist thủ công trước.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi _problem → quy trình → metric → boundary → mức can thiệp AI → quyết định_ của bài nhóm mình.

1. Problem: chọn vấn đề học viên mất nhiều thời gian đọc và đối chiếu các tài liệu Lab để xác định đầy đủ yêu cầu cần thực hiện.
2. Quy trình: học viên phải tìm các file, đọc từng tài liệu, đối chiếu yêu cầu, tổng hợp nhiệm vụ và tra cứu lại khi làm bài.
3. Metric: đặt mục tiêu giảm thời gian đọc và tổng hợp từ khoảng 60–75 phút xuống dưới 30 phút, đồng thời không bỏ sót yêu cầu bắt buộc.
4. Boundary và mức can thiệp AI: đề xuất Workflow sử dụng AI để trích xuất và tổng hợp checklist có dẫn nguồn, nhưng học viên vẫn phải kiểm tra kết quả và quyết định cuối cùng.
5. Quyết định: chọn Not Yet vì chưa đủ bằng chứng từ người dùng thực tế và cần kiểm chứng xem AI có hiệu quả hơn checklist thủ công hoặc công cụ có sẵn hay không.
