# Báo cáo cá nhân — 2A202603598_NguyenHuuTien

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Nguyễn Hữu Tiến
- MSSV: 2A202603598
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: 1
- Link repo nhóm: https://github.com/HDang3825/K5-L3A-DAY02-Nhom1-DiscoveryProblemFraming.git

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| #   | Lăng kính                         | Job Story: Khi… tôi muốn… để…                                                                                             | Ai chịu ảnh hưởng?         | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng)                                   |
| --: | --------------------------------- | ------------------------------------------------------------------------------------------------------------------------- | -------------------------- | ------------------------------------------------------------------------------------------- |
| 1   | Cần đọc, tổng hợp nhiều thông tin | Khi bắt đầu task mới, tôi muốn gom requirement đang nằm rải ở nhiều chỗ vào một nơi, để khỏi sót case lạ rồi phải sửa lại | BE trong nhóm              | ~25-40 phút/lần đọc-đối chiếu; ~2-3 lần/tuần; tuần trước sót requirement phải sửa lại 1 lần |
| 2   | Lặp lại                           | Khi tôi đổi response API, tôi muốn người làm FE dùng đúng format mới, để họ không map nhầm data cũ rồi hỏi lại trên chat  | BE và FE trong nhóm        | FE hỏi lại API ~1-2 lần/tuần; mỗi lần giải thích ~10-15 phút                                |
| 3   | Tốn thời gian                     | Khi webhook lỗi, tôi muốn tìm nhanh đoạn log/request sai, để khỏi cuộn tất cả log tìm tay                                 | BE làm SePay/PayOS         | ~45-60 phút/lần debug; ~1-2 lần/tuần                                                        |
| 4   | Pain từ người khác                | Khi nhánh main build lỗi, tôi muốn cả nhóm biết trước khi pull, để không mất công chạy local trên code hỏng               | FE/BE trong nhóm           | 1 bạn than tuần trước; mất ~20-30 phút pull + chạy lại rồi mới biết lỗi ở main              |
| 5   | Cần đọc, tổng hợp nhiều thông tin | Khi review PR, tôi muốn thấy nhanh chỗ đổi logic thật, để không đọc hết file chỉ sửa format                               | Người review PR trong nhóm | ~15-25 phút/PR chỉ để lọc file; ~3-5 PR/tuần trên GitLab                                    |
| 6   | Lặp lại                           | Khi vừa đổi endpoint, tôi muốn Postman/Swagger khớp với code, để lần test sau không gọi nhầm path/field cũ                | BE, FE                     | Sửa docs tay ~15-20 phút/lần; lệch docs-code ~2 lần/tuần; test nhầm mất thêm ~10 phút       |
| 7   | Tốn thời gian                     | Khi webhook SePay/PayOS trả JSON lạ hoặc thiếu field, tôi muốn biết chỗ khác mẫu ở đâu, để khỏi so từng dòng              | BE thanh toán              | So JSON ~20-35 phút/lần; ~1 lần/tuần (sandbox đổi field / lỗi chữ ký)                       |
| 8   | Pain từ người khác                | Khi người làm FE cần làm UI, họ muốn biết field nào bắt buộc và có ví dụ response, để không đoán bừa rồi làm lại          | FE , BE                    | FE hỏi/chờ ~2-3 lần/tuần; mỗi lần ~30-60 phút mới rõ để code tiếp                           |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- Tự viết #1-#5 trước, rồi hỏi AI thêm. **Giữ** #6, #7, #8 vì đúng việc nhóm đã làm và có số đo. **Bỏ** ý tìm lại quyết định trong thread, checklist trước demo, và lỗi chỉ có trên server deploy — vì trùng #1/#3/#4 hoặc chưa gặp. Có sửa #2 và #4 cho không viết kiểu giải pháp (“tự động…”).

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem                                  | Vì sao chọn                                           | Điều còn chưa chắc                                                        |
| ---: | ---------------------------------------- | ----------------------------------------------------- | ------------------------------------------------------------------------- |
| 1    | Debug webhook / rà log (scan #3, #7)     | Mất nhiều phút, vẽ được từng bước, đúng việc nhóm làm | Nhanh hơn nhờ “tìm log dễ hơn” hay nhờ “log ghi đủ id từ đầu”?            |
| 2    | API đổi mà FE/docs lệch (scan #2, #6)    | Hay gặp trong nhóm, cả BE và FE đều gặp                     | Lỗi vì quên báo FE, hay vì quên cập nhật Swagger/Postman?                 |
| 3    | Gom requirement trước khi code (scan #1) | Mỗi task mới đều gặp;  | Requirement đang nằm ở issue, chat, hay docs? Số 25-40 phút mới ước lượng |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi webhook lỗi, tôi muốn tìm nhanh đoạn log/request sai, để khỏi cuộn tất cả log |
| Actor | BE trong nhóm, đang làm phần thanh toán SePay/PayOS |
| Thời điểm / bối cảnh | Webhook lỗi chữ ký, thiếu field, hoặc callback không khớp đơn - khoảng 1-2 lần/tuần |
| Quy trình hiện tại (3-7 bước) | 1. Nghe FE/test báo lỗi hoặc xem PayOS · 2. Mở log · 3. Cuộn tìm request theo giờ · 4. So JSON nhận được với mẫu · 5. Sửa code/config · 6. Test lại webhook · 7. Kiểm tra đơn đã cập nhật chưa |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3-4: tìm log + so JSON — khoảng 25-35 phút (trong tổng ~45-60 phút/lần) |
| Impact (nếu không giải thì sao) | Mỗi lần mất gần 1 tiếng; cả nhóm chờ test thanh toán; dễ sửa tạm rồi quên |
| Success metric (baseline → target) | Từ lúc biết lỗi → tìm ra request/JSON sai: ~30 phút xuống dưới 10 phút/lần |
| Phương án không dùng AI | Log thêm mã đơn/request id; lọc log theo mã đó; checklist field bắt buộc trước khi xử lý |
| Giả thuyết về AI (nếu có) | AI giúp so JSON thật với mẫu và chỉ chỗ lệch; mình vẫn quyết định sửa gì |
| Cảm nhận nhanh | Rule hoặc Workflow — chưa chắc cần Agent |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — ~45-60 phút/lần

[1 Nhận báo lỗi: 5'] → [2 Mở log: 5']
→ [3 Cuộn tìm request: 15-20'] ← BOTTLENECK
→ [4 So JSON với mẫu: 10-15'] ← BOTTLENECK phụ
→ [5 Sửa code/config: 10'] → [6 Test lại: 5-10'] → [7 Kiểm tra OK: 5']
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi tôi đổi response API, tôi muốn dev FE dùng đúng format mới, để họ không map nhầm rồi hỏi lại trên chat |
| Actor | BE đổi API; dev FE dùng API |
| Thời điểm / bối cảnh | Sau khi merge đổi field/path; FE đang code hoặc test Postman — hỏi lại ~1-2 lần/tuần |
| Quy trình hiện tại (3-7 bước) | 1. BE sửa API · 2. Merge · 3. Hay quên cập nhật Swagger/Postman · 4. FE gọi theo bản cũ · 5. Lỗi / hỏi chat · 6. BE giải thích hoặc gửi JSON mẫu · 7. FE sửa lại |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 5-6: hỏi-đáp trên chat ~10-15 phút/lần; FE còn mất thêm thời gian sửa UI |
| Impact (nếu không giải thì sao) | FE làm lại; BE bị ngắt giữa chừng; hay nghe câu: API đổi rồi à |
| Success metric (baseline → target) | Số lần FE hỏi lại API: 1-2 lần/tuần → 0-1 lần/tuần |
| Phương án không dùng AI | Trước khi merge: cập nhật Postman/Swagger + dán ví dụ response vào MR |
| Giả thuyết về AI (nếu có) | AI so code API với Swagger/Postman và liệt kê chỗ lệch trước khi merge |
| Cảm nhận nhanh | Rule trước; nếu cần hỗ trợ so docs thì Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — mỗi lần lệch ~25-40 phút (BE+FE)

[1 BE sửa API: 20'] → [2 Merge: 5'] → [3 Cập nhật docs: hay bỏ] ← GỐC LỖI
→ [4 FE gọi bản cũ: 10'] → [5 Hỏi chat: 10-15'] ← BOTTLENECK
→ [6 BE gửi mẫu: 10'] → [7 FE sửa lại: 15-30']
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi bắt đầu task mới, tôi muốn gom requirement đang nằm rải ở nhiều chỗ vào một nơi, để khỏi sót case lạ rồi phải sửa lại |
| Actor | BE nhận task mới trong nhóm dự án |
| Thời điểm / bối cảnh | Đầu task (~2-3 lần/tuần); thông tin nằm ở issue, chat nhóm, docs, comment MR cũ |
| Quy trình hiện tại (3-7 bước) | 1. Nhận task · 2. Đọc mô tả · 3. Xem chat/docs/comment · 4. So với API/flow hiện có · 5. Ghi note case cần nhớ · 6. Bắt đầu code · 7. Nếu sót thì sửa lại |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3-4: xem và đối chiếu — khoảng 15-25 phút (trong tổng ~25-40 phút) |
| Impact (nếu không giải thì sao) | Sót requirement → sửa lại (đã xảy ra 1 lần tuần trước); task chậm; hỏi lại nhiều |
| Success metric (baseline → target) | Thời gian gom requirement: ~25-40 phút → dưới 15 phút/task; số lần sửa lại vì sót: ≥1 lần/tuần → 0 trong 2 tuần |
| Phương án không dùng AI | Checklist ngắn trước khi code (luồng đúng, case lỗi, link nguồn); dán hết vào issue |
| Giả thuyết về AI (nếu có) | AI đọc vài nguồn text rồi liệt kê case còn thiếu; mình vẫn chốt trước khi code |
| Cảm nhận nhanh | Rule hoặc Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — ~25-40 phút/task (chưa kể lúc phải sửa lại)

[1 Nhận task: 5'] → [2 Đọc mô tả: 5']
→ [3 Lục chat/docs: 10-15'] ← BOTTLENECK
→ [4 Đối chiếu API/flow: 5-10'] ← BOTTLENECK phụ
→ [5 Ghi note: 5'] → [6 Code: —]
→ [7 (Nếu sót) Sửa lại: +30-60']
```

### Card muốn pitch nhất

- Card số: 1 (debug webhook / rà log)
- Vì sao: Có số phút cụ thể, đúng việc mình đang làm với PayOS, dễ nói với nhóm
- Câu hỏi muốn nhóm phản biện: Chỗ nghẽn thật là “cuộn log”, hay là “log thiếu mã để lọc”? Chỉ thêm rule log cho chuẩn thì đã đủ chưa, có cần AI không?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Actor Card #1 còn chung chung | Đồng ý | Đổi thành sinh viên BE làm SePay/PayOS |
| Card #2 đang gộp 2 chuyện (quên báo FE và quên cập nhật docs) | Đồng ý một phần | Ghi vào “còn chưa chắc”; trong quy trình đánh dấu bước quên docs |
| Metric Card #1 lẫn cả thời gian sửa code | Đồng ý | Chỉ đo đoạn tìm ra request/JSON sai |
| Có thể chỉ cần Rule, chưa cần AI | Đồng ý | Viết rõ phương án không dùng AI; để cảm nhận Rule/Workflow |
| Card #3 (gom requirement) hơi rộng | Đồng ý | Nói rõ nguồn: issue, chat, docs, comment MR |

---

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
| CP1 Scan | Gợi ý thêm problem sau khi tự scan 5 ý; nhờ chỉnh Job Story bỏ chữ giải pháp | Gợi ý thêm góc docs/webhook/contract FE; nhắc bỏ “tự động” trong Job Story | Một số ý gợi ý quá rộng hoặc trùng pain đã có | Chỉ giữ 3 ý sát trải nghiệm; tự ước lượng rồi sẽ chỉnh số đo theo tuần thật |
| CP2 Problem Card | Nháp 3 card + nhờ AI đóng vai PM hoài nghi phản biện | Chỉ ra actor chung, gộp pain, metric lẫn bước sửa code | Gợi ý Agent/tự động hóa sớm; một số điểm còn giả định | Thu hẹp metric Card #1; tách Card #2 vs #3; bổ sung phương án No AI / Rule |
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
