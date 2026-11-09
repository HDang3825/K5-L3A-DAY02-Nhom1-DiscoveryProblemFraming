
---

## Thông tin học viên
Họ tên: Trịnh Quốc Đạt
MSSV: 2A202603581

---

## CP1 — Scan 5+ problems (25') · *Discover*


### 6 lăng kính

|#| Lăng kính | Job Story | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---|---|---|---|---
| **1** | Lặp lại| Khi tới chiều thứ Sáu, tôi muốn có sẵn tuần này mình đã làm gì và còn kẹt ở đâu, để gửi update cho mentor trước 17h | Thực tập sinh, mentor | ~40 phút/tuần, phải lục lại Jira và Slack để nhớ; 2/6 tuần gửi trễ |
| **2** | Tốn thời gian | Khi được giao một task mới, tôi muốn gom yêu cầu đang rải ở Slack, Jira và Notion về một chỗ, để hiểu đúng việc cần làm trước khi bắt tay | Thực tập sinh, mentor | ~45 phút/task, ~3 task/tuần; phải hỏi lại mentor 2–3 lần/task |
| **3** | Tốn thời gian | Khi gặp câu hỏi về quy trình hoặc hệ thống cũ, tôi muốn biết nên hỏi ai hoặc xem tài liệu nào, để không làm phiền sai người | Thực tập sinh, các thành viên team | ~15 phút/lần tìm người đúng, ~4 lần/tuần; từng hỏi nhầm người 2 lần |
| **4** | Cần đọc, tổng hợp nhiều thông tin | Khi mới vào dự án, tôi muốn nắm các quyết định chính và lý do từ tài liệu, ghi chú họp cũ, để không đề xuất lại điều team đã loại | Thực tập sinh mới, mentor | Khoảng 20+ trang ghi chú và spec; ~2 tiếng đọc trong tuần đầu mà vẫn chưa nắm hết |
| **5** | Cần đọc, tổng hợp nhiều thông tin | Khi vừa xong buổi họp sprint, tôi muốn có danh sách việc của riêng mình kèm hạn, để không sót việc được giao miệng | Thực tập sinh, mentor | ~20 phút/buổi lọc từ ghi chú, 2 buổi/tuần; tuần trước sót 1 việc
| **6** | Pain từ người khác | Khi gửi bản nháp cho mentor review, tôi muốn biết trước những lỗi hay bị nhắc, để sửa trước khi gửi | Mentor, thực tập sinh | Mentor nhắc cùng loại lỗi (thiếu link nguồn, sai format, thiếu bước kiểm) ~3 lần/tuần, đếm từ comment review |

---

## CP2 — Top 3 Problem Cards + quy trình nháp (35') · *Discover*

### Chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---
|**1**| Gom yêu cầu cho task mới (#2) | Quy trình rõ, tốn thời gian nhất tuần, đếm được số lần hỏi lại | Mentor có chịu dùng template không? “Hiểu đúng yêu cầu” đo thế nào? |
|**2**| Update cuối tuần cho mentor (#1) | Lặp lại đều, có baseline bấm giờ được, 2/6 tuần gửi trễ | Mentor có thật sự đọc update không? |
| **3** | Lỗi lặp lại khi mentor review (#6) | Bằng chứng từ người khác (comment review), pain rõ | Các lỗi có đủ giống nhau để đếm không? |

### Problem Card #1: Gom yêu cầu cho task mới

| Trường | Nội dung|
|---|---
| Job Story | Khi được giao một task mới, tôi muốn gom yêu cầu đang rải ở Slack, Jira và Notion về một chỗ, để hiểu đúng việc cần làm trước khi bắt tay |
| Actor | Thực tập sinh làm dự án thật, nhận task từ mentor| 
| Thời điểm / bối cảnh | Ngay sau khi mentor giao task (đầu tuần hoặc sau họp sprint), trước khi bắt đầu làm |
| Quy trình hiện tại | 1. Đọc mô tả task trên Jira · 2. Tìm và đọc các thread Slack liên quan · 3. Tìm spec/ghi chú liên quan trên Notion · 4. Tự tổng hợp yêu cầu ra ghi chú riêng · 5. Nhắn mentor hỏi lại phần còn mơ hồ |
| Bottleneck | Bước 2, tìm và đọc lại thread Slack: khoảng 15 phút/task, vì yêu cầu nằm rải rác và không có từ khóa chung |
| Impact | ~45 phút/task × ~3 task/tuần = ~135 phút/tuần cho 1 thực tập sinh; mentor bị hỏi lại 2–3 lần/task |
| Success metric | Thời gian từ 45 xuống dưới 20 phút/task; số lần hỏi lại mentor từ 2–3 xuống tối đa 1 lần/task; task không bị trả lại vì hiểu sai yêu cầu |
| Phương án không dùng AI | Mentor điền một template “task brief” 1 trang khi giao việc (mục tiêu, link tài liệu, quyết định liên quan, câu hỏi còn mở) |
| Giả thuyết về AI | AI soạn bản brief nháp từ thread và tài liệu liên quan, kèm danh sách câu hỏi còn mở; Linh kiểm lại và xác nhận với mentor |
| Cảm nhận nhanh | No AI hoặc Workflow (cần kiểm chứng) |

HIỆN TẠI — 45 phút/task

[1 Đọc task Jira: 5'] → [2 Tìm thread Slack: 15'] ← BOTTLENECK
→ [3 Tìm spec Notion: 10'] → [4 Tự tổng hợp: 10']
→ [5 Hỏi lại mentor: 5']

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---
| Baseline 45 phút và "bước 2 mất 15 phút" là ước lượng từ trí nhớ, chưa bấm giờ. Có thể là quy trình tưởng tượng. | Đồng ý | Bấm giờ 3 task thật trong tuần, ghi từng bước, thay số nháp bằng số đo |
| Mất 15 phút tìm Slack có thể do mới vào, chưa quen kênh nào chứa gì; sau 1 tháng có thể tự giảm. | Đồng ý một phần | Thêm câu hỏi vào CP4: hỏi thực tập sinh làm lâu hơn xem họ còn mất bao lâu |
| Template mentor điền là giải pháp No AI rất rẻ; card chưa chứng minh vì sao template chưa đủ. | Đồng ý | Giữ No AI làm phương án đối chứng; ghi rõ cần kiểm: mentor có sẵn lòng điền không |
| Metric "không bị trả lại vì hiểu sai yêu cầu" chưa đo được. | Đồng ý | Đổi thành "số lần mentor sửa hướng làm sau khi bắt đầu", đếm qua comment Jira |

### Problem Card #2: Update cuối tuần cho mentor

| Trường | Nội dung |
|---|---
| Job Story | Khi tới chiều thứ Sáu, tôi muốn có sẵn tuần này mình đã làm gì và còn kẹt ở đâu, để gửi update cho mentor trước 17h |
| Actor | Thực tập sinh gửi update hằng tuần cho mentor (anh Quân) |
| Thời điểm / bối cảnh | Chiều thứ Sáu, hạn gửi 17h, thường trùng lúc đang chạy nốt task cuối |
| Quy trình hiện tại | 1. Mở Jira xem task đã chuyển trạng thái · 2. Lướt lại Slack cả tuần để nhớ các việc ngoài Jira (hỏi đáp, họp, hỗ trợ đồng nghiệp) · 3. Xem lại update tuần trước để giữ cấu trúc · 4. Viết update (đã làm, đang kẹt, kế hoạch tuần sau) · 5. Đọc lại, chỉnh câu chữ · 6. Gửi Slack/email cho mentor |
| Bottleneck | Bước 2, nhớ lại và gom việc từ Slack: khoảng 15 phút/tuần, hay sót việc không có ticket |
| Impact | ~40 phút/tuần cho 1 thực tập sinh; 2/6 tuần gửi trễ; mentor thiếu thông tin để gỡ vướng kịp |
| Success metric | Thời gian từ 40 xuống dưới 15 phút/tuần; 0 tuần gửi trễ trong 4 tuần; mentor không phải hỏi bổ sung về nội dung update |
| Phương án không dùng AI | Ghi nhanh vào một file “nhật ký làm việc” 2 phút cuối mỗi ngày, cuối tuần chỉ việc sắp xếp lại theo template 3 mục |
| Giả thuyết về AI | AI soạn nháp update từ danh sách task Jira đã đổi trạng thái và các ghi chú ngắn của Linh; Linh bổ sung phần kẹt và kế hoạch, rồi tự gửi |
| Cảm nhận nhanh | Rule hoặc Workflow

HIỆN TẠI — 40 phút/tuần

[1 Xem Jira: 5'] → [2 Lướt lại Slack: 15'] ← BOTTLENECK
→ [3 Xem update tuần trước: 3'] → [4 Viết update: 10']
→ [5 Đọc lại, chỉnh: 5'] → [6 Gửi: 2']

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì|
|---|---|---
| Chỉ có 1 actor và 6 tuần dữ liệu; chưa rõ thực tập sinh khác có mất 40 phút không. | Đồng ý | Hỏi 2 thực tập sinh khác ở CP4, ghi cả trường hợp họ mất ít hơn |
| Chưa có bằng chứng mentor đọc update. Nếu chỉ liếc qua, nên giảm độ dài update thay vì làm nhanh hơn. | Đồng ý | Đưa vào danh sách giả định cần kiểm chứng: hỏi mentor phần nào thật sự đọc |
| Nhật ký 2 phút/ngày + template đã gần đủ; để mức Rule/Workflow là nhảy sang tự động hóa hơi sớm. | Đồng ý một phần | Đổi "cảm nhận nhanh" thành "No AI, cần kiểm chứng"; AI chỉ là giả thuyết phụ |
| Phần "đang kẹt", phần giá trị nhất, phải tự nghĩ; AI chỉ làm được phần liệt kê việc. | Đồng ý | Giới hạn giả thuyết AI ở "liệt kê việc đã làm"; boundary: AI không tự viết phần kẹt và kế hoạch |

### Problem Card #3: Lỗi lặp lại khi mentor review

| Trường | Nội dung |
|---|---
| Job Story | Khi gửi bản nháp cho mentor review, tôi muốn biết trước những lỗi hay bị nhắc, để sửa trước khi gửi |
| Actor | Thực tập sinh gửi bản nháp (tài liệu, spec, báo cáo ngắn) cho mentor; mentor là người review |
| Thời điểm / bối cảnh | Trước khi gửi mỗi bản nháp, khoảng 2–3 bản/tuần |
| Quy trình hiện tại | 1. Viết bản nháp · 2. Tự đọc lại một lượt · 3. Gửi mentor · 4. Mentor comment · 5. Sửa theo comment · 6. Gửi lại, có thể lặp vòng 2 |
| Bottleneck | Bước 2, tự đọc lại: Linh không biết cần kiểm gì nên bỏ sót lỗi lặp (thiếu link nguồn, sai format, thiếu bước kiểm), dẫn đến vòng sửa thứ hai: khoảng 20 phút/bản |
| Impact | ~3 comment lặp/tuần; ~20 phút sửa lại/bản × 2–3 bản/tuần = 40–60 phút/tuần; mentor mất thời gian nhắc lại cùng một loại lỗi |
| Success metric | Số comment lặp từ ~3 xuống tối đa 1/tuần; số bản phải gửi lại vòng 2 giảm một nửa (đếm trong 4 tuần) |
| Phương án không dùng AI| Checklist 5–7 mục rút ra từ các comment cũ của mentor, Linh tự tick trước khi gửi |
| Giả thuyết về AI | AI đối chiếu bản nháp với checklist và chỉ ra mục còn thiếu; chưa chắc cần, checklist có thể đã đủ |
| Cảm nhận nhanh | No AI

HIỆN TẠI — khoảng 20 phút sửa lại/bản (khi bị nhắc lỗi lặp)

[1 Viết nháp] → [2 Tự đọc lại: 5'] ← BOTTLENECK (không biết kiểm gì)
→ [3 Gửi mentor] → [4 Mentor comment: chờ]
→ [5 Sửa theo comment: 15'] → [6 Gửi lại vòng 2]

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---
| "~3 comment lặp/tuần" chưa có nguồn đếm; chưa rõ có thật cùng loại lỗi. | Đồng ý | Lấy comment review của 3–4 bài gần nhất, gom theo loại lỗi, ghi số thật |
| Bottleneck là thiếu tiêu chuẩn, không phải thiếu AI; card gần như chắc chắn là No AI. | Đồng ý | Ghi rõ kết luận dự kiến là No AI, không ép tìm giả thuyết AI |
| Nếu mentor không xác nhận, checklist chỉ là ý kiến cá nhân. | Đồng ý | Đưa checklist cho mentor xem 5 phút để xác nhận |
| Impact chỉ tính thời gian của thực tập sinh, chưa tính thời gian mentor nhắc lại. | Không đồng ý hoàn toàn | Giữ impact tập trung vào actor của card; ghi thời gian mentor như tín hiệu phụ, chưa đo |

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
| CP2 Problem Card |  | | |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5-6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1-6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5-8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
