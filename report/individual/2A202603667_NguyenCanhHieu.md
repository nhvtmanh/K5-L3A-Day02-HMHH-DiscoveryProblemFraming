# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Nguyễn Cảnh Hiếu
- MSSV: 2A202603667
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: HMHH
- Link repo nhóm: https://github.com/nhvtmanh/K5-L3A-Day02-HMHH-DiscoveryProblemFraming.git

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại | Mỗi sáng cần tổng hợp thông tin, việc cần làm, thông báo từ nhiều kênh khác nhau dễ bị bỏ qua thông tin | Dev frontend, lead/PM giao việc | Tự bấm giờ 3 đến 5 buổi sáng, từ lúc mở máy đến lúc biết chắc hôm nay phải làm gì |
| 2 | Lặp lại | khi sửa code hoặc code một tính năng mới, tôi muốn biết mình có bị vi phạm các quy ước của dự án không(file quá dài, màu cứng, thứ tự import), để không bị đẩy lại | Dev frontend, lead/PM giao việc | mỗi tuần bị đẩy về 3 5 lỗi vi phạm về độ dài và thứ tự import|
| 3 | Cần đọc, tổng hợp nhiều thông tin | khi kết thúc buổi học, buổi họp cần tổng hợp kiến thức, thông tin để có thể theo sát tiến độ | Học viên, lead/PM | sau mỗi buổi học, buổi họp |
| 4 | tốn thời gian | cần tóm tắt nhanh thông tin, ý chính từ các file báo cáo 20 đến 30 trang để đưa ra nhận xét, quyết định | PM reviewer, design lead | 30-45p trên một bản, 4-5 bản trên tuần |
| 5 | Pain từ người khác | khi làm trưởng nhóm dự án, cần tổng hợp báo cáo những việc thành viên trong nhóm đã hoàn thành và chưa hoàn thành gửi lên CEO | CEO, PM | 2/8 tuần gần nhất báo cáo gửi trễ |
| 6 | Pain từ người khác | Khi backend hoặc BA đổi API hoặc nghiệp vụ, tôi muốn biết ngay phần giao diện nào bị ảnh hưởng, để không phát hiện muộn ở giai đoạn test| Backend, dev frontend | 5 lần trên chức năng dự án |
| 7 | Cần đọc, tổng hợp nhiều thông tin | ở mỗi bài lab từng ngày học khi bắt đầu cần phải đọc rất nhiều file, tổng hợp những checkpoints, lưu ý để có thể hoàn thành tốt | Học viên | mất khoảng 50 đến 60 phút để đọc hiểu những yêu cầu, thông tin, lưu í của bài |
| 8 | Pain từ người khác | khi thành viên trong nhóm chưa hoàn thành việc của họ, tôi muốn biết phần việc đấy có liên quan ảnh hưởng như thế nào đến phần việc của mình | Thành viên nhóm, trưởng nhóm | 1 đến 2 lần chờ thành viên hoàn thiện để trình bày báo cáo trên tháng|
| 9 | Lặp lại | Cuối ngày khi kết thúc công việc cần có danh sách những việc đã làm được trong ngày, những việc chưa hoàn thành, chuẩn bị những việc cho ngày mai | Bản thân | 30p đến 45p để rà soát, kiểm tra lại |
| 10 | Cần đọc, tổng hợp nhiều thông tin | Khi cần sửa một đoạn code hoặc logic cũ, tôi muốn biết vì sao nó được viết như vậy, để không sửa phá nghiệp vụ đang chạy | Dev frontend, đồng đội | 40 đến 60p đọc lại nghiệp vụ, 2 lần sửa lại sai logic ban đầu|
| 11 | Tốn thời gian | Khi nhận một bug mô tả mơ hồ (ví dụ "bản đồ bị lỗi"), tôi muốn tái hiện được đúng điều kiện xảy ra, để sửa đúng chỗ mà không phải mò | Dev frontend, tester | 5 bug gần nhất có 2 bug cần phải hỏi, trao đổi lại với tester |

**AI gợi ý thêm:** sau khi tự scan 9 ý, mình hỏi AI theo 4 lăng kính và giữ lại ý #10 và #11, vì cả hai đều có quy trình thật và đếm được (số phút tái hiện bug, số lần tìm lại lý do trong code). Bỏ ý "trợ lý AI hỗ trợ toàn bộ công việc của dev" vì quá rộng và không có quy trình cụ thể.

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

-

---


## 3. Top 3 Problem Cards (CP2)
 
| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | API/nghiệp vụ đổi, biết muộn giao diện nào bị ảnh hưởng (#6) | Nhiều người liên quan (backend, BA, dev frontend); đã đếm được 5 lần/chức năng; quy trình vẽ được | Nút thắt thật là biết muộn hay mất công tìm phạm vi ảnh hưởng trong code? |
| 2 | Vi phạm quy ước code của dự án (#2) | Đo được rõ (3–5 lỗi/tuần); actor rõ; so sánh được No AI / Rule / Workflow | Mỗi lần sửa mất bao lâu, mấy vòng review? Rule (linter, hook) có đủ không? |
| 3 | Tổng hợp tiến độ thành viên để báo cáo CEO (#5) | Có hậu quả đo được (2/8 tuần gửi trễ); cần gom thông tin từ nhiều người | Gửi trễ do khâu thu thập hay khâu viết? Người khác có gặp không? |
 
---
 
### Problem Card #1 — API/nghiệp vụ đổi, biết muộn giao diện nào bị ảnh hưởng
 
| Trường | Nội dung |
|---|---|
| Job Story | Khi backend hoặc BA đổi API hoặc nghiệp vụ, tôi muốn biết ngay phần giao diện nào bị ảnh hưởng, để không phát hiện muộn ở giai đoạn test |
| Actor | **Actor chính: dev frontend** (người chịu mất thời gian dò và sửa giao diện). Actor phụ: backend, BA (người đổi API/nghiệp vụ, không phải người chịu pain) |
| Thời điểm / bối cảnh | Khi có thay đổi API hoặc nghiệp vụ giữa sprint hoặc sau khi tích hợp |
| Quy trình hiện tại | 1. Nhận tin thay đổi (chat/họp) · 2. Đọc thay đổi, so với bản cũ · 3. Dò code tìm chỗ bị ảnh hưởng · 4. Sửa type và xử lý · 5. Test tay các màn liên quan · 6. Phát hiện sót ở giai đoạn test, quay lại sửa |
| Bottleneck | Bước 3, dò code tìm chỗ bị ảnh hưởng: khoảng 30'* mỗi lần, vì không có danh sách sẵn màn nào dùng trường/endpoint đã đổi |
| Impact | 5 lần trên chức năng dự án (**trong __ sprint/tháng** — cần ghi rõ khoảng thời gian); khoảng 105'* mỗi lần xử lý; phần phát hiện muộn ở giai đoạn test gây quay lại sửa (~20'* mỗi lần); **độ trễ từ lúc backend đổi đến lúc frontend biết: ~__ giờ*** (chưa tính vào 105') |
| Success metric | **Metric 1:** baseline ~105'*/lần, target dưới 45'*/lần, đo bằng tự ghi thời gian mỗi lần có thay đổi trong 4 tuần. **Metric 2 (kết quả cuối):** số lần phát hiện muộn ở giai đoạn test từ 5 xuống 0–1 trong cùng khoảng thời gian, đếm từ lịch sử bug/ticket |
| Phương án không dùng AI | Thống nhất kênh và định dạng thông báo đổi API giữa backend và frontend (changelog ngắn nêu endpoint/trường đổi); để TypeScript báo lỗi biên dịch khi type đổi (cần kiểm tra backend có tài liệu API/schema chuẩn để sinh type không) |
| Giả thuyết về AI | **Chỉ xét nếu phương án không dùng AI ở trên không đủ.** Khi đó: công cụ đối chiếu thay đổi với code để liệt kê màn bị ảnh hưởng; người xác nhận danh sách trước khi sửa. *Chỉ là giả thuyết, cần kiểm chứng ở CP4* |
| Cảm nhận nhanh | □ No AI ☑ Rule/Workflow (giả thuyết) □ Agent □ Chưa biết |
 
```text
HIỆN TẠI — khoảng 105 phút/lần*
 
[1 Nhận tin: 5'*] → [2 Đọc, so sánh bản cũ: 10'*] → [3 Dò code tìm chỗ ảnh hưởng: 30'*] ← BOTTLENECK
→ [4 Sửa type + xử lý: 25'*] → [5 Test tay các màn liên quan: 15'*]
→ [6 Phát hiện sót ở giai đoạn test, sửa lại: 20'*]
```
 
---
 
### Problem Card #2 — Vi phạm quy ước code của dự án
 
| Trường | Nội dung |
|---|---|
| Job Story | Khi code xong hoặc sửa code một tính năng, tôi muốn biết ngay mình có vi phạm quy ước dự án không (file quá dài, màu cứng, thứ tự import), để không bị đẩy PR lại |
| Actor | Dev frontend (người viết); reviewer, lead/PM giao việc (người phải xem và đẩy lại) |
| Thời điểm / bối cảnh | Sau khi code xong, trước và sau khi tạo PR |
| Quy trình hiện tại | 1. Code xong tính năng · 2. Tạo PR · 3. Reviewer phát hiện vi phạm quy ước · 4. Sửa theo feedback · 5. Push lại, chờ review lại |
| Bottleneck | Bước 3, vi phạm chỉ bị phát hiện sau khi đã tạo PR: chờ khoảng 30'* mỗi lần, làm mất lượt review |
| Impact | 3–5 lỗi vi phạm mỗi tuần bị đẩy về (độ dài file, thứ tự import); khoảng 70'* mỗi lần tính cả chờ; làm chậm việc merge |
| Success metric | Baseline: 3–5 lỗi/tuần, ~70'*/lần (đo bằng đếm comment review về quy ước trong 2 tuần). Target: 0–1 lỗi/tuần, dưới 20'*/lần. Cách đo: đếm comment review về quy ước mỗi tuần trong 4 tuần |
| Phương án không dùng AI | Quy tắc kiểm tra tự động (độ dài file, thứ tự import, màu cứng) chạy khi commit hoặc trên CI; checklist ngắn trước khi tạo PR |
| Giả thuyết về AI | Có thể không cần. Rule (linter/hook) giải được phần lớn vì đúng/sai rõ ràng. AI chỉ cân nhắc nếu có quy ước mềm khó viết thành rule |
| Cảm nhận nhanh | □ No AI ☑ Rule (giả thuyết) □ Workflow □ Agent □ Chưa biết |
 
```text
HIỆN TẠI — khoảng 70 phút/lần*
 
[1 Code xong: 0'] → [2 Tạo PR: 5'*] → [3 Reviewer phát hiện vi phạm: chờ 30'*] ← BOTTLENECK
→ [4 Sửa theo feedback: 15'*] → [5 Push lại, chờ review lại: 20'*]
```
 
---
 
### Problem Card #3 — Tổng hợp tiến độ thành viên để báo cáo CEO
 
| Trường | Nội dung |
|---|---|
| Job Story | Khi đến kỳ báo cáo, tôi (trưởng nhóm) muốn có sẵn việc mỗi thành viên đã hoàn thành và chưa hoàn thành, để gửi CEO đúng hạn |
| Actor | Trưởng nhóm dự án (người tổng hợp); thành viên (người cung cấp tiến độ); CEO, PM (người nhận) |
| Thời điểm / bối cảnh | Cuối tuần hoặc trước buổi họp, khi cần gửi báo cáo cho CEO |
| Quy trình hiện tại | 1. Thu thập tiến độ từng thành viên (nhắn/hỏi) · 2. Đối chiếu việc xong/chưa xong · 3. Viết báo cáo · 4. Review lại · 5. Gửi CEO |
| Bottleneck | Bước 1, thu thập tiến độ: khoảng 30'* mỗi kỳ vì phải chờ và nhắc từng người trả lời |
| Impact | 2/8 tuần gần nhất báo cáo gửi trễ; khoảng 72'* mỗi kỳ cho người tổng hợp |
| Success metric | Baseline: ~72'*/kỳ, trễ 2/8 tuần (đo bằng bấm giờ + đếm số tuần trễ). Target: dưới 30'*/kỳ, trễ 0/8 tuần. Cách đo: tự ghi thời gian và hạn gửi mỗi kỳ trong 4 tuần |
| Phương án không dùng AI | Template báo cáo cố định; thành viên tự cập nhật vào một bảng chung hằng ngày; nhắc hạn tự động |
| Giả thuyết về AI | AI soạn nháp báo cáo từ bảng tiến độ đã gom; trưởng nhóm review và sửa trước khi gửi. *Chỉ là giả thuyết, cần kiểm chứng ở CP4* |
| Cảm nhận nhanh | □ No AI □ Rule ☑ Workflow (giả thuyết) □ Agent □ Chưa biết |
 
```text
HIỆN TẠI — khoảng 72 phút/kỳ*
 
[1 Thu thập tiến độ từng người: 30'*] ← BOTTLENECK → [2 Đối chiếu xong/chưa xong: 15'*]
→ [3 Viết báo cáo: 20'*] → [4 Review: 5'*] → [5 Gửi CEO: 2'*]
```
 
---
 
### Card pitch với nhóm
 
**Card muốn pitch nhất:** Problem Card #1 (API/nghiệp vụ đổi).
 
**Câu hỏi muốn nhóm phản biện:**
 
> Nếu không dùng AI, cách đơn giản nhất để frontend biết sớm một thay đổi API sẽ ảnh hưởng màn hình nào là gì? Và theo các bạn, nút thắt thật là biết muộn hay tìm phạm vi ảnh hưởng?
 
---
 
### AI phản biện card #1
 
Prompt đã dùng (dán Problem Card #1 ở trên vào chỗ `[dán card]`):
 
```text
Đây là Problem Card của tôi:
[dán card]
 
Đóng vai một product manager hoài nghi và phản biện:
1. Actor có đủ cụ thể không?
2. Quy trình có thật không, hay là quy trình tôi tưởng tượng?
3. Bottleneck có phải một bước cụ thể không?
4. Metric có đo được không?
5. Sửa quy trình hoặc dùng rule đã đủ chưa?
6. Tôi có đang nhảy sang AI quá sớm không?
Trả lời ngắn, chỉ nói điểm yếu.
```
 
> Kết quả phản biện do AI đóng vai PM hoài nghi tạo ra cho card #1. Cột "Đồng ý?" là **đề xuất**: bạn đọc lại, đổi nếu không đồng ý, và ghi lý do bằng lời của bạn.
 
| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Actor chưa rõ: có ba bên (dev frontend, backend, BA) nhưng không nói ai là người chịu pain chính | Đồng ý | Ghi rõ actor chính là dev frontend, backend và BA là actor phụ (người gây ra thay đổi) |
| "5 lần trên chức năng dự án" không có khoảng thời gian, không biết nhiều hay ít | Đồng ý | Thêm "trong __ sprint/tháng" vào Impact; bạn cần điền khoảng thời gian thật |
| Quy trình chưa tính thời gian chờ từ lúc backend đổi đến lúc frontend biết, trong khi "biết muộn" mới là tên của vấn đề | Đồng ý | Thêm "độ trễ biết tin" vào Impact (chưa tính vào 105'), cần đo thật |
| Metric chỉ đo thời gian xử lý, không đo thứ bạn thực sự muốn giảm (phát hiện muộn ở giai đoạn test) | Đồng ý | Thêm Metric 2: số lần phát hiện muộn từ 5 xuống 0–1 |
| Chưa chứng minh phương án không dùng AI không đủ (TypeScript, tài liệu API chuẩn) mà đã có giả thuyết AI | Đồng ý | Ghi giả thuyết AI chỉ xét nếu phương án không dùng AI không đủ; thêm việc cần kiểm tra backend có schema API chuẩn để sinh type không |
| Con số 105 phút và bottleneck 30 phút chưa đo | Đồng ý (đã nêu ở ghi chú đầu file) | Giữ dấu `*`; bạn phải thay bằng số đo thật |


## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | | | | |
| CP2 Problem Card | | | | |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Nghe 12 candidate, tôi nhận ra một pattern chung: mọi người đều khổ sở ở khâu đọc và tổng hợp thông tin rải rác. Các bài toán của tôi (#10, #11) lại quá thiên về dev frontend (xử lý API), khiến các bạn khó đồng cảm và khó kiểm chứng. Do đó, tôi thấy việc chốt chọn vấn đề "đọc tài liệu lab" là hoàn toàn hợp lý, vì đó là nỗi đau thật mà cả bốn anh em đều đang nếm trải, dễ dàng phỏng vấn và validate hơn.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Có, rất rõ ở vòng phản biện. Mọi người liên tục hỏi nhau theo hướng giải pháp: "không cần AI được không", "ném hết file cho AI tổng hợp đi". Nhận ra nhóm đang đi quá nhanh, chúng tôi phải dừng lại để vẽ chi tiết quy trình 5 bước hiện tại (CP5). Khi research thấy các tool có sẵn như NotebookLM đã làm quá tốt việc tóm tắt, nhóm mới bẻ lái sang giải pháp tạo checklist có trích nguồn và gắn cờ mâu thuẫn để tạo sự khác biệt.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Tôi đã đổi ý. Ban đầu tôi bảo vệ bài toán làm API của mình, nhưng AI (vai PM) và các bạn trong nhóm đã phân tích sắc bén: những lỗi đó có thể chặn dứt điểm bằng rule cứng như linter hay type schema thay vì dùng "dao mổ trâu" AI. Khi thấy giải pháp của mình chưa đủ thuyết phục và bài toán của nhóm sát thực tế hơn, tôi vui vẻ gác lại candidate của mình.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Bất ngờ lớn nhất không đến từ người dùng (vì nhóm chưa phỏng vấn), mà từ chính số liệu nội bộ. Thứ nhất, ChatGPT và NotebookLM đã cover rất tốt khâu tóm tắt. Thứ hai, khi bóc tách quy trình, khâu "đọc" ngốn tới 60 phút, áp đảo khâu "đối chiếu" (15 phút) – khâu vốn được nhóm giả định là bottleneck. Điều này dội một gáo nước lạnh, chỉ ra giả thuyết của nhóm có thể đang sai và việc phỏng vấn thực tế (Mom Test) là bắt buộc.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Khó nhất là baseline thời gian (60–75 phút) chỉ dựa trên ước lượng cá nhân của hai thành viên nên rất yếu. Thứ hai là sự mâu thuẫn khi chọn bottleneck: bước đối chiếu khớp với định hướng giải pháp, nhưng bước đọc mới tốn thời gian nhất. Cuối cùng là làm sao diễn đạt được điểm khác biệt (checklist trích nguồn) mà không vô tình biến Problem Statement thành một bản mô tả tính năng sản phẩm.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Tôi sẽ ép nhóm đi phỏng vấn (Mom Test) và đo đạc thời gian trên bài lab thật ngay lập tức, thay vì dùng số liệu tự biên tự diễn. Về phản biện, tôi sẽ làm gắt hơn: yêu cầu nhóm làm rõ xem 60 phút đọc và 15 phút đối chiếu có bị tính trùng nhau không, và bắt chỉ đích danh những điểm yếu cụ thể của NotebookLM trước khi chốt hướng đi mới.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

Sinh viên mất 60-75 phút để đọc, đối chiếu đề bài, rule, rubric. Quy trình 5 bước hiện tại xác định khâu đối chiếu là bottleneck giả thuyết. Metric kỳ vọng: Giảm thời gian xuống ≤ 30 phút/lab, 0 bỏ sót yêu cầu. Boundary: AI chỉ gom file, tạo checklist có nguồn, báo mâu thuẫn; con người bắt buộc tự kiểm chứng và làm bài.
Mức can thiệp: Workflow (Rule gom file → AI lập checklist → Người duyệt).
Quyết định của nhóm: Not Yet. Baseline hiện tại quá mỏng, chưa phỏng vấn user thực tế và các giả định chưa được kiểm chứng, nên bắt buộc phải lùi lại thu thập data thật trước khi chốt Go.

---

## 7. Tài liệu tham khảo

-

