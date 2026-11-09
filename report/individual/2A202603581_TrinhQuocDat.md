
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
