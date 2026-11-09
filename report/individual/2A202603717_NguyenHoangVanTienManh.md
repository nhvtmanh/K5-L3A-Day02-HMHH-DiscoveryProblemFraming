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

|   # | Lăng kính                         | Job Story: Khi… tôi muốn… để…                                                                                                   | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
| --: | --------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- | ------------------ | --------------------------------------------------------- |
|   1 | Lặp lại                           | Khi mỗi tối trước khi đi ngủ, tôi muốn biết ngày hôm nay đã làm được những gì, để chuẩn bị những việc cần làm vào sáng mai      |                    |                                                           |
|   2 | Tốn thời gian                     | Khi AI Coding Agent gen code, tôi muốn biết AI đã làm những gì, để đảm bảo những thứ AI làm là đúng theo plan                   |                    |                                                           |
|   3 | Cần đọc, tổng hợp nhiều thông tin | Khi bắt đầu làm bài Lab, tôi muốn biết rõ cần phải làm những bài nào, để có thể làm và nộp bài đầy đủ                           |                    |                                                           |
|   4 | Pain từ người khác                | Khi vào đầu buổi sáng, tôi cần biết trong kho còn thiếu nguyên liệu gì, để có thể chuẩn bị đầy đủ nguyên liệu trước khi làm món |                    |                                                           |
|   5 | Pain từ người khác                |                                                                                                                                 |                    |                                                           |
|   6 |                                   |                                                                                                                                 |                    |                                                           |
|   7 |                                   |                                                                                                                                 |                    |                                                           |
|   8 |                                   |                                                                                                                                 |                    |                                                           |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- ***

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem                       | Vì sao chọn                                                    | Điều còn chưa chắc                                                              |
| ---: | ----------------------------- | -------------------------------------------------------------- | ------------------------------------------------------------------------------- |
|    1 | Tổng hợp thông tin từ bài Lab | Mất thời gian để đọc nhiều file khác nhau                      | AI có thể tổng hợp thiếu thông tin quan trọng                                   |
|    2 | Review code AI                | Cần đảm bảo AI làm đúng yêu cầu                                | Chưa có cách đo chất lượng code phù hợp                                         |
|    3 | Kiểm tra nguyên liệu          | Để biết thiếu hiện tại đang thiếu nguyên liệu nào cần chuẩn bị | Làm thế nào để xác định chính xác nguyên liệu hiện có và nguyên liệu còn thiếu? |

### Problem Card #1

| Trường                                    | Nội dung                                                                                                                                 |
| ----------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story                                 | Khi bắt đầu làm bài Lab, tôi muốn biết rõ cần phải làm những bài nào, để có thể làm và nộp bài đầy đủ                                    |
| Actor                                     | Học viên                                                                                                                                 |
| Thời điểm / bối cảnh                      | Vào đầu buổi Lab                                                                                                                         |
| Quy trình hiện tại (3–7 bước)             | 1. Clone repository về máy 2. Đọc README.md 3. Đọc RULES.md 4. Đọc CHECKPOINTS.md 5. Đọc RUBRIC.md 6. Đọc SUBMISSION.md                  |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2 - 6: khoảng 1 tiếng, có thể mất nhiều hơn khi bắt đầu làm vì phải đọc lại file cần thiết để check có làm đúng yêu cầu không       |
| Impact (nếu không giải thì sao)           | Mất thời gian xác định nhiệm vụ, có thể bỏ sót checkpoint, yêu cầu chấm điểm hoặc file cần nộp, dẫn đến nộp bài thiếu hoặc sai quy định. |
| Success metric (baseline → target)        | Tổng thời gian đọc hiểu từ 1 tiếng xuống dưới 30 phút                                                                                    |
| Phương án không dùng AI                   | Có một file tổng hợp bao gồm hướng dẫn, checklist, tiêu chí hoàn thành và yêu cầu nộp bài                                                |
| Giả thuyết về AI (nếu có)                 | AI đọc các file Lab và tự động trích xuất nhiệm vụ, checkpoint, rubric và yêu cầu nộp bài                                                |
| Cảm nhận nhanh                            | Workflow                                                                                                                                 |

Quy trình nháp hiện tại:

```text

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

```

### Card muốn pitch nhất

- Card số:
- Vì sao:
- Câu hỏi muốn nhóm phản biện:

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
| ------------------ | ------- | --------- |
|                    |         |           |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động                  | Tôi đã làm gì?         | Kết quả / ảnh hưởng tới bài nhóm |
| -------------------------- | ---------------------- | -------------------------------- |
| Pitch Problem Card         |                        |                                  |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt:    |                                  |
| Nhận phản biện             | Câu hỏi tôi nhận được: | Tôi đã sửa gì:                   |
| Gom cluster / cây OST      |                        |                                  |
| Chọn candidate problem     |                        |                                  |
| Kiểm chứng / research      |                        |                                  |
| Quy trình nhóm             |                        |                                  |
| Problem Statement          |                        |                                  |
| Mức can thiệp AI           |                        |                                  |
| Quyết định                 |                        |                                  |

---

## 5. Dùng AI

| Checkpoint                     | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
| ------------------------------ | ---------------------- | ----------------- | -------------------------- | ----------------------------------- |
| CP1 Scan                       |                        |                   |                            |                                     |
| CP2 Problem Card               |                        |                   |                            |                                     |
| CP4 Research                   |                        |                   |                            |                                     |
| CP5 Quy trình                  |                        |                   |                            |                                     |
| CP5–6 Problem Statement        |                        |                   |                            |                                     |
| CP6 Mức can thiệp / quyết định |                        |                   |                            |                                     |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi _problem → quy trình → metric → boundary → mức can thiệp AI → quyết định_ của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
