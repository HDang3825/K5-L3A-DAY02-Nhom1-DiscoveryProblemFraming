
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
| Pitch Problem Card | Trình bày Problem Card #1 (Gom yêu cầu cho task mới) trước cả nhóm | Mọi người có bàn luận và đánh giá tương dối về tính khả thi nhưng còn hạn chế về data |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt:"Về vấn đề data từ các bộ luật có nhiều không và mình có thể sử dụng những cơ sở hạ tầng lưu trữ nào và có mất phí không?" (cho bạn Đăng) | Giúp nhóm có thể hiểu hơn về data của Đăng là được lấy từ đâu và có sức chứa như nào và dùng cơ sở hạ tầng nào |
| Nhận phản biện | Câu hỏi tôi nhận được:"Bài toán này có thật sự cần thiết khi phải làm 1 dự án lớn hay công ty có chấp nhận chi trả cho 1 đội nhóm AI để làm hay không?"(bạn Đăng hỏi) | Tôi đã sửa gì:"Mình sẽ scope dự án lớn hơn không chỉ để phục vụ cho 1 mục đích hay 1 bộ phận thực tập sinh mà còn mở rộng lên cho cả công ty dùng và tra cứu thông tin" |
| Gom cluster / cây OST | Đề xuất gom các bài toán của nhóm theo vấn đề gốc chung (thông tin đầu vào của task thiếu hoặc mơ hồ, thông tin nội bộ nằm rải rác khó tra cứu); cùng nhóm vẽ cây OST từ outcome → opportunity → solution và gạch bỏ các solution chỉ thiên về công nghệ | Cây OST bám vào nhu cầu của người dùng thay vì tính năng; bài toán gom yêu cầu cho task mới nằm rõ trong một cụm opportunity |
| Chọn candidate problem | Trình bày lý do chọn Problem Card #1 theo 3 tiêu chí: tần suất xảy ra, mức ảnh hưởng tới người làm task, và khả năng tiếp cận data (trả lời lại mối lo về data mà bạn Đăng nêu) | Nhóm thống nhất chọn bài toán này làm candidate problem để đi tiếp |
| Kiểm chứng / research | Lập Assumption Map, chọn giả định rủi ro nhất (“[người dùng thật sự mất nhiều thời gian vì yêu cầu task không rõ]”) để kiểm chứng; phỏng vấn [số người] [thực tập sinh / mentor] theo nguyên tắc The Mom Test | Rút ra insight: [điều phát hiện chính, ví dụ vấn đề nằm ở bước hiểu yêu cầu chứ không phải bước làm]; giúp nhóm thu hẹp phạm vi bài toán |
| Quy trình nhóm | Phác thảo sơ đồ Before/After (Mermaid) cho quy trình nhận và làm rõ task; chỉ ra các bottleneck chính như hỏi đi hỏi lại nhiều lần, thông tin nằm ở nhiều nơi | Cả nhóm hình dung được chỗ mất thời gian nhất và mục tiêu giảm |
| Problem Statement | Soạn Problem Statement v0, sau đó nâng lên v1 bổ sung người dùng, bối cảnh, điểm can thiệp của AI, mức độ rủi ro, người kiểm tra và tiêu chí đo lường | Bài toán được định hình rõ ràng, có tiêu chí đo lường cụ thể để đánh giá sau này |
| Mức can thiệp AI | Phân tích vì sao không chọn Rule (yêu cầu task quá đa dạng, luật cứng không bao phủ hết) và vì sao không chọn Agent (tự quyết định trên dữ liệu nội bộ, rủi ro sai lệch cao); đề xuất Workflow có bước người duyệt | Nhóm thống nhất chọn Workflow làm mức can thiệp AI vừa đủ và an toàn |
| Quyết định | Đề xuất quyết định Go với phạm vi pilot nhỏ ([một nhóm / một bộ phận]), kèm ngưỡng dừng sau [số tuần] nếu chưa đạt chỉ số đo lường | Hoàn thiện quyết định cuối cùng có căn cứ và có điều kiện dừng rõ ràng |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Nhờ AI gợi ý thêm các góc nhìn về việc nhận và làm rõ task mới ở thực tập sinh, mentor và quản lý | Mở rộng được các khía cạnh tôi chưa nghĩ tới, như task thiếu tiêu chí hoàn thành, thông tin nằm rải rác ở nhiều nơi | AI đưa ra danh sách chung chung, nhiều ý không gắn với bối cảnh thực tế của công ty | Lọc bớt, chỉ giữ các ý tôi có thể kiểm chứng và viết lại theo form Job Story |
| CP2 Problem Card | Nhờ AI đóng vai phản biện để chất vấn Problem Card #1 (Gom yêu cầu cho task mới)  | Chỉ ra được các điểm yếu như thiếu bằng chứng về mức độ thường xuyên của vấn đề, và phạm vi quá rộng | AI có xu hướng đẩy bài toán thành một hệ thống lớn tự động hóa toàn bộ, vượt quá khả năng của nhóm |Tôi thu hẹp phạm vi, giữ con người ở vai trò quyết định và đặt câu hỏi: “bài toán này có đủ cần thiết để công ty đầu tư không?” |
| CP4 Research | Nhờ AI tìm các công cụ và giải pháp tương tự đã có để quản lý yêu cầu và tra cứu tài liệu nội bộ | Liệt kê nhanh được nhiều nhóm công cụ để tôi so sánh | Một số công cụ, tính năng hoặc nguồn AI nêu không chính xác hoặc đã lỗi thời, có link không mở được | Tôi tự kiểm tra từng nguồn trên trang chính thức của công cụ và chỉ giữ những gì xác minh được |
| CP5 Quy trình | Nhờ AI chuyển mô tả quy trình bằng lời thành sơ đồ Mermaid (Before/After) | Xuất mã Mermaid nhanh và đúng cú pháp, dễ chỉnh | AI tự gộp các bước, và không biết bước nào thực sự tốn thời gian nên đặt sai vị trí bottleneck | Tôi tách từng bước, gán số phút thực tế [số liệu đo được] và đánh dấu rõ nhãn BOTTLENECK |
| CP5-6 Problem Statement | Nhờ AI chỉ ra lỗ hổng trong Problem Statement v0 | Gợi ý các câu hỏi tôi chưa trả lời được, ví dụ bài toán áp dụng cho nhóm nào, đo thành công bằng gì | AI hay viết lại bằng các từ ngữ hoa mỹ nhưng làm mất tính định lượng | Tôi giữ nguyên các chỉ số baseline/target đo bằng thời gian và số lần hỏi lại, rồi bổ sung phạm vi người dùng |
| CP6 Mức can thiệp / quyết định | Nhờ AI phân tích các khía cạnh rủi ro theo Rule / Workflow / Agent | Gợi ý góc nhìn đa chiều về tính khả thi (data, hạ tầng lưu trữ, chi phí) và vận hành | AI khuyên nên làm Agent tự động đọc và trả lời toàn bộ, bỏ qua rủi ro trả lời sai khi dữ liệu nội bộ chưa đầy đủ | Tôi giữ mức Workflow có bước người duyệt, vì tôi thấy rõ rủi ro dữ liệu và trách nhiệm khi AI trả lời sai |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1-6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Em thấy mọi người có những quan điêm cũng như ý tưởng từ những khóa cạnh mới mà em chưa được tiếp xúc qua. Em đã được mở mang kiến thức từ các bạn

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Không có ạ

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Có. Lúc đầu em đánh giá dự án của em rất khả thi vì nó đơn giản và nhắm vào đối tượng cụ thể. Nhưng khi bạn Đăng có hỏi em về câu hỏi "Về vấn đề data từ các bộ luật có nhiều không và mình có thể sử dụng những cơ sở hạ tầng lưu trữ nào và có mất phí không?" Thì đã phải mở scope lên rộng hơn. Từ đó thì lại là một bài toán lớn và khó khăn với bọn em. Nên chúng em đã bỏ qua dự án này

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Không có ạ

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Điều em cảm thấy khó khăn nhất là làm sao cân bằng giữa việc đề xuất giải pháp và xác định một Success Metric thực sự cụ thể, có cơ sở đo lường rõ ràng. Ban đầu, em dễ bị cuốn vào việc mô tả những lợi ích mang tính chung chung như “giúp người dùng hoàn thành hồ sơ nhanh chóng và thuận tiện hơn”. Tuy nhiên, để xây dựng được các chỉ số có tính thực tiễn, chẳng hạn như rút ngắn thời gian xử lý từ 420 phút xuống dưới 60 phút và đạt tỷ lệ thành công 85%, em đã phải cùng nhóm phân tích chi tiết từng công đoạn trong quy trình Before/After, tính toán mức độ cải thiện và xác định phương pháp đo lường dựa trên dữ liệu từ tập mẫu thử nghiệm thực tế.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Em sẽ suy nghĩ kĩ hơn về đối tượng em muốn hướng đến trong dự án, sẽ cố gắng tìm scope vừa và cụ thể hơn. Phản biên nhóm mạnh nhất ở điểm thay vì cứ dùng AI hay AI Agent thì mình sẽ hướng đến những tối ưu từ thiết kế non AI, rule hay luồng automation

**6.7. Hiểu bài:** giải thích bằng 5-8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

Nhóm em xác định vấn đề chính là các chủ hộ kinh doanh mất trung bình 420 phút để tìm hiểu quy định pháp lý và chuẩn bị hồ sơ, dẫn đến tình trạng thiếu giấy tờ, hồ sơ bị trả lại nhiều lần. Vì vậy, nhóm đặt mục tiêu rút ngắn thời gian xuống dưới 60 phút và nâng tỷ lệ hồ sơ hợp lệ lần đầu từ 40% lên 85%. Về giải pháp, nhóm lựa chọn Workflow kết hợp Rule phân loại ngành và AI đọc hiểu thông tư, với nguyên tắc AI chỉ hỗ trợ tạo checklist, mọi kết quả đều phải được con người rà soát. Nhóm quyết định Go thử nghiệm trên 20 quán ăn trong 4 tuần; nếu tỷ lệ hồ sơ hợp lệ không đạt 75% thì sẽ dừng và quay lại sử dụng checklist in sẵn.

---

## 7. Tài liệu tham khảo

-
