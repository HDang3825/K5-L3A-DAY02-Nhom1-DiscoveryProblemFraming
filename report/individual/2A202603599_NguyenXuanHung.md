**Nhân vật:** Nhi là y tá tổng hợp tại khoa Phục hồi chức năng / Vật lý trị liệu (phụ trách khoảng 15–20 bệnh nhân/ngày, dùng Google Sheets, sổ theo dõi ca và nhóm chat Zalo). Mỗi ngày, các y tá phụ trách từng buổi tập ghi chép hoạt động của bệnh nhân; cuối ngày Nhi phải gom, đối chiếu các ghi chú này để viết báo cáo tổng hợp gửi bác sĩ điều trị.

## 2. Scan problem (CP1)

Nhi scan ra 5 problem.
| # | Lăng kính | Job Story | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---:|---|---|---|---|
| 1 | Tốn thời gian | Khi đến cuối ngày, tôi muốn gom nhanh ghi chú từ các ca tập và sinh hiệu ở một chỗ, để viết báo cáo gửi bác sĩ đúng giờ. | Y tá tổng hợp (Nhi), Bác sĩ | Tự bấm giờ 3 ngày gần nhất: trung bình 30 phút/báo cáo |
| 2 | Tốn thời gian | Khi cần xem lại buổi tập trước, tôi muốn tìm ngay đúng ghi chú của bệnh nhân, để kiểm tra tiến triển mà không phải rà từng file lưu trữ. | Y tá | Tự đo mỗi ngày mất khoảng 15 phút (3 lượt tìm, ~5 phút/lượt) |
| 3 | Pain từ người khác | Khi gửi báo cáo cuối ngày, tôi muốn biết chắc đã đủ các mục lâm sàng bác sĩ cần theo từng bệnh lý, để không bị trả về bổ sung. | Bác sĩ, Y tá | Lần gần nhất báo cáo bị trả về, Nhi mất thêm 15 phút kiểm tra và bổ sung |
| 4 | Cần đọc, tổng hợp nhiều thông tin | Khi nhận bàn giao ca, tôi muốn tách rõ việc nào đã xong và việc nào còn chờ trong nhóm chat, để không bỏ sót y lệnh của bệnh nhân. | Y tá, Bác sĩ, Bệnh nhân | Tuần trước 1 ca bị nhắc uống thuốc/chườm đá trễ 45 phút do tin nhắn bị trôi |
| 5 | Cần đọc, tổng hợp nhiều thông tin | Khi tổng hợp báo cáo hoặc khi bác sĩ đọc báo cáo, tôi muốn các ghi chú giữa các y tá và các ngày được diễn đạt đồng nhất, để đối chiếu tiến triển mà không phải hỏi lại. | Y tá ghi chép, Y tá tổng hợp (Nhi), Bác sĩ | Mỗi y tá ghi tắt/mô tả một kiểu; mỗi lần mơ hồ Nhi (hoặc bác sĩ) phải nhắn/gọi hỏi lại người ghi mất ~10 phút |

## 3. Top 3 Problem Cards (CP2)

| Rank | Problem                  | Vì sao chọn                                     | Điều còn chưa chắc                                       |
| ---: | ------------------------ | ----------------------------------------------- | -------------------------------------------------------- |
|    1 | Báo cáo cuối ngày (#1)   | Quy trình rõ, lặp lại hằng ngày, có baseline đo | Làm sao đảm bảo AI không tóm tắt sót dấu hiệu bất thường |
|    2 | Đối chiếu hoạt động (#5) | Pain thật của cả y tá tổng hợp và bác sĩ đọc    | AI chuẩn hóa từ viết tắt chuyên ngành có chính xác không |
|    3 | Tìm ghi chú cũ (#2)      | Nhiều y tá gặp hằng ngày, impact rộng           | Dữ liệu lưu trữ phân tán, phạm vi tìm kiếm dễ bị rộng    |

### Problem Card #1 — Báo cáo cuối ngày

| Trường                  | Nội dung                                                                                                                               |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story               | Khi đến cuối ngày, tôi muốn tổng hợp hoạt động của bệnh nhân từ ghi chú của các y tá trong ngày, để gửi báo cáo đầy đủ cho bác sĩ.     |
| Actor                   | Y tá tổng hợp báo cáo (Nhi) tại khoa Phục hồi chức năng / Vật lý trị liệu.                                                             |
| Thời điểm / bối cảnh    | Cuối ca chiều, trước khi gửi báo cáo bàn giao cho bác sĩ điều trị.                                                                     |
| Quy trình hiện tại      | 1. Xác định danh sách buổi tập · 2. Mở ghi chú các ca · 3. Gom thông tin · 4. Tổng hợp & viết nhận định tiến triển · 5. Kiểm tra & gửi.|
| Bottleneck              | Bước 3 & 4 — Gom thông tin rời rạc và viết tổng hợp diễn biến từng bệnh nhân (22 phút).                                                |
| Impact                  | Mất khoảng 30 phút mỗi cuối ngày; nếu ca chiều đông bệnh nhân dễ gửi báo cáo trễ giờ giao ban.                                         |
| Success metric          | Giảm thời gian làm báo cáo từ 30 phút xuống 10 phút, đảm bảo đủ 100% các mục bác sĩ yêu cầu và không sai lệch số liệu.                 |
| Phương án không dùng AI | Dùng bảng ghi chú chung và mẫu báo cáo cố định (giảm thời gian gom, nhưng vẫn phải đọc và viết tóm tắt thủ công).                      |
| Giả thuyết về AI        | Rule gom ghi chú về 1 bảng → AI soạn nháp báo cáo và đánh dấu ca bất thường → Nhi đối chiếu nguồn và duyệt trước khi gửi.              |
| Cảm nhận nhanh          | Workflow — AI hỗ trợ soạn nháp trong quy trình cố định, y tá kiểm duyệt cuối.                                                          |

```text
HIỆN TẠI — Tổng thời gian: 30 phút

[1 Xác định buổi tập: 2'] → [2 Mở ghi chú: 3'] → [3 Gom thông tin: 10']
→ [4 Viết tổng hợp & nhận định: 12'] ← BOTTLENECK CHÍNH (Bước 3 + 4 = 22')
→ [5 Kiểm tra và gửi: 3']
```

### Problem Card #2 — Đối chiếu hoạt động giữa các ngày

| Trường                  | Nội dung                                                                                                                                             |
| ----------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story               | Khi tổng hợp hoặc đọc báo cáo, tôi muốn đối chiếu ghi chú giữa các ngày và làm rõ mô tả mơ hồ, để nắm đúng tiến triển của bệnh nhân.                 |
| Actor                   | Y tá tổng hợp (Nhi), các y tá ghi chép từng ca, và Bác sĩ điều trị đọc báo cáo.                                                                      |
| Thời điểm / bối cảnh    | Cuối ngày khi Nhi tổng hợp báo cáo từ nhiều y tá, hoặc khi bác sĩ đọc báo cáo mà thuật ngữ/thông số không đồng nhất.                                 |
| Quy trình hiện tại      | Mở ghi chú các ngày → đối chiếu tiến triển → phát hiện chỗ ghi tắt/mơ hồ → nhắn/gọi hỏi lại y tá ghi chép → cập nhật lại báo cáo.                    |
| Bottleneck              | Bước 4 — Phải liên hệ hỏi lại y tá ca trước (hoặc bác sĩ hỏi lại Nhi); thời gian chờ phụ thuộc việc y tá đó có đang rảnh hay đã tan ca (10 phút).    |
| Impact                  | Mất khoảng 18 phút cho mỗi ca có ghi chú mơ hồ (riêng bước hỏi lại và chờ phản hồi mất ~10 phút); làm chậm tiến độ chốt báo cáo.                     |
| Success metric          | Giảm thời gian làm rõ từ 18 phút xuống dưới 5 phút/ca; giảm số lần bác sĩ phải hỏi lại báo cáo do mô tả khó hiểu.                                    |
| Phương án không dùng AI | Quy định bộ từ viết tắt và biểu mẫu nhập chuẩn (nhưng thực tế y tá bận vẫn hay ghi chú tự do theo thói quen).                                        |
| Giả thuyết về AI        | AI chuẩn hóa mô tả tự do của các y tá về thuật ngữ chuẩn để dễ đối chiếu, đồng thời cảnh báo ngay chỗ thiếu thông số/mơ hồ trước khi nộp.            |
| Cảm nhận nhanh          | Workflow — AI chuẩn hóa thuật ngữ và gắn cờ chỗ mơ hồ; y tá xác nhận, AI không tự bịa thông số chưa có.                                              |

```text
HIỆN TẠI — Tổng thời gian mỗi ca cần làm rõ: 18 phút

[1 Mở ghi chú: 2'] → [2 Đối chiếu mô tả giữa các ngày: 3'] → [3 Đánh dấu chỗ mơ hồ: 1']
→ [4 Liên hệ hỏi lại y tá ghi chép: 10'] ← BOTTLENECK
→ [5 Cập nhật báo cáo: 2']
```

### Problem Card #3 — Tìm ghi chú cũ

| Trường                  | Nội dung                                                                                                                     |
| ----------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| Job Story               | Khi cần xem lại một buổi tập trước, tôi muốn tìm đúng ghi chú của bệnh nhân theo triệu chứng/hoạt động, để kiểm tra lịch sử. |
| Actor                   | Y tá cần tra cứu lịch sử tập luyện và phản ứng của bệnh nhân ở các buổi trước.                                               |
| Thời điểm / bối cảnh    | Khi làm báo cáo đối chiếu hoặc khi bác sĩ yêu cầu kiểm tra lại một buổi tập cụ thể trước đó.                                 |
| Quy trình hiện tại      | 1. Xác định bệnh nhân và thông tin cần tìm · 2. Mở các file lưu trữ · 3. Rà tìm qua các ngày · 4. Đọc kiểm tra đúng ghi chú. |
| Bottleneck              | Bước 3 — Phải mở và rà thủ công qua nhiều ngày/file vì không nhớ chính xác ngày xảy ra triệu chứng đó.                       |
| Impact                  | Mất khoảng 15 phút/ngày (trung bình 3 lượt tìm/ngày, ~5 phút/lượt; những ca phức tạp không nhớ ngày có thể mất 10–15 phút).  |
| Success metric          | Giảm thời gian tìm kiếm từ 5–10 phút/lượt xuống dưới 1 phút/lượt, tìm đúng ngay buổi tập cần đối chiếu.                      |
| Phương án không dùng AI | Lập bảng tra cứu tập trung theo mã bệnh nhân và ngày tập (giải quyết được khi nhớ ngày, nhưng khó tìm theo mô tả triệu chứng).|
| Giả thuyết về AI        | Khi không nhớ ngày tập, AI hỗ trợ tìm kiếm ngữ nghĩa (Semantic Search) theo mô tả hoạt động/triệu chứng; y tá kiểm tra lại.  |
| Cảm nhận nhanh          | Workflow — AI truy xuất đoạn ghi chú khớp mô tả, y tá xác nhận trên hồ sơ gốc.                                               |

```text
HIỆN TẠI — Tổng thời gian mỗi lượt tìm khó (không nhớ ngày): 15 phút

[1 Xác định thông tin: 2'] → [2 Mở nơi lưu trữ: 1']
→ [3 Rà các file theo ngày: 10'] ← BOTTLENECK
→ [4 Kiểm tra ghi chú: 2']
```

**AI phản biện card #1:**

| Điểm yếu AI chỉ ra                                                   | Đồng ý?          | Đã sửa gì                                                                                     |
| -------------------------------------------------------------------- | ---------------- | --------------------------------------------------------------------------------------------- |
| Nếu bottleneck chỉ là gom thông tin thì mẫu chung đã đủ, chưa cần AI.| Đồng ý           | Tách rõ bước gom (dùng Rule/bảng chung) và bước viết tổng hợp diễn biến (dùng AI soạn nháp).  |
| Làm nhanh hơn nhưng có nguy cơ tóm tắt sót dấu hiệu lâm sàng.        | Đồng ý           | Thêm tiêu chí đủ 100% mục bác sĩ cần và giữ boundary y tá bắt buộc duyệt trước khi gửi.       |
| Gợi ý để AI tự động gửi báo cáo cho bác sĩ cuối ngày.                | Không đồng ý     | Giữ nguyên bước Nhi kiểm tra và gửi vì báo cáo y tế không được phép sai số liệu.              |

**AI phản biện card #2:**

| Điểm yếu AI chỉ ra                                                       | Đồng ý? | Đã sửa gì                                                                                      |
| ------------------------------------------------------------------------ | ------- | ---------------------------------------------------------------------------------------------- |
| AI có thể suy đoán sai từ viết tắt hoặc tự điền thông số khi ghi chú mơ hồ.| Đồng ý  | Đặt boundary: AI chỉ chuẩn hóa thuật ngữ đã rõ và gắn cờ chỗ thiếu/mơ hồ để y tá xác nhận.     |
| Mẫu ghi chú chung (No-AI) có thể giảm bớt việc mỗi y tá viết một kiểu.   | Đồng ý  | Đưa mẫu chung vào phương án No-AI, nhưng giữ AI cho phần mô tả diễn biến tự do của từng ca.    |

**AI phản biện card #3:**

| Điểm yếu AI chỉ ra                                                       | Đồng ý? | Đã sửa gì                                                                                      |
| ------------------------------------------------------------------------ | ------- | ---------------------------------------------------------------------------------------------- |
| Chưa nhất quán giữa 15 phút/ngày ở CP1 và 15 phút/lượt ở Card #3.        | Đồng ý  | Làm rõ: trung bình 15 phút/ngày (3 lượt), riêng lượt khó (không nhớ ngày tập) mất tới 15 phút. |
| Bảng tra cứu theo Mã BN + Ngày tập (No-AI) đã giải quyết được phần lớn.  | Đồng ý  | Ghi rõ AI chỉ cần thiết khi tìm theo ngữ nghĩa triệu chứng/hoạt động mà không nhớ ngày tập.    |
