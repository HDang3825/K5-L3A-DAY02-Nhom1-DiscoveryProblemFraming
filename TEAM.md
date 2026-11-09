# Team

> Điền file này trên repo chung do nhóm trưởng fork. Nhóm điền phần **Thông tin nhóm** và **Thành viên**. Mỗi người tự điền phần của mình trong **Cá nhân**. Không copy file này sang repo khác.

## Thông tin nhóm

- Tên nhóm: Nhóm L3A-01
- Candidate problem nhóm chọn (1 câu): Tra cứu quy định pháp lý & thủ tục hành chính cho hộ kinh doanh cá thể.
- Quyết định cuối (Go / Not Yet / No-Go): **Go** (Pilot phạm vi hẹp cho ngành F&B/quán ăn nhỏ).

## Thành viên

| STT | Họ và tên | MSSV | Vai trò trong nhóm | Tài khoản GitHub |
|---:|---|---|---|---|
| 1 | Võ Lê Hải Đăng | 2A202603577 | Đề xuất bài toán, phụ trách Quy trình & Problem Statement | |
| 2 | Đạt | 2A202603581 | Phản biện, hỗ trợ kiểm chứng thực tế | |
| 3 | Nguyễn Xuân Hùng | 2A202603599 | Phụ trách Research giải pháp có sẵn | https://github.com/XuanHung1703 |
| 4 | Nguyễn Hữu Tiến | 2A202603598 | Phản biện, hỗ trợ đánh giá rủi ro kỹ thuật | |



Không ghi email hay số điện thoại vào bảng này, vì repo có thể để public.

Gợi ý vai trò (một người có thể giữ nhiều vai): điều phối thời gian, ghi chép, người phản biện chính, phụ trách kiểm chứng (phỏng vấn/survey), phụ trách research, vẽ quy trình, viết Problem Statement.

## Phân công theo checkpoint

| Checkpoint | Người chính | Người hỗ trợ | Sản phẩm |
|---|---|---|---|
| CP3 — Hội tụ nhóm | Đăng | Cả nhóm | Cluster, cây OST, bảng chấm điểm |
| CP4 — Kiểm chứng | Đạt, Tiến | Đăng | Assumption map, snapshot phỏng vấn |
| CP4 — Research | Hùng | Đăng | Bảng research có link |
| CP5 — Quy trình trước/sau | Đăng | Tiến | Quy trình Before/After + bảng so sánh |
| CP5 — Problem Statement v0 | Đăng | Đạt | Problem Statement v0 |
| CP6 — Mức can thiệp + Problem Statement v1 | Đăng | Cả nhóm | Ma trận, AI Canvas, eval, Problem Statement v1 |
| CP6 — Quyết định | Cả nhóm | Đăng | 4 rủi ro + Quyết định Go kèm ngưỡng dừng |

## Cá nhân

Mỗi thành viên thêm một mục theo mẫu dưới đây, tiêu đề là `HoVaTen-MSSV`.

### VoLeHaiDang-2A202603577

**Phần việc phụ trách:**

- Đề xuất và thuyết trình (pitch) candidate problem về tra cứu quy định pháp lý cho hộ kinh doanh.
- Phụ trách xây dựng sơ đồ Quy trình Trước/Sau (Before/After) chi tiết kèm các điểm ranh giới (boundary) và phương án quay về (fallback).
- Soạn thảo và hoàn thiện Problem Statement v0 và v1, tiêu chí đánh giá AI (Eval) và ngưỡng dừng cho quyết định Go.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Trình bày Problem Card #1, giải đáp các thắc mắc phản biện của các thành viên về rủi ro ảo giác pháp lý.
- Dựng bảng so sánh Before/After chỉ ra mức giảm thời gian từ 420 phút xuống dưới 60 phút.
- Đề xuất kiến trúc Workflow (kết hợp Rule + AI + HITL) thay vì Agent tự động hoàn toàn nhằm đảm bảo tính an toàn pháp lý.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `group_report.md`: Mục 2 (Candidate được chọn), Mục 4 (Sơ đồ quy trình 4.1 và 4.2), Mục 5 (Problem Statement v0), Mục 6 và 7 (Mức can thiệp Workflow và Problem Statement v1).
- Báo cáo cá nhân: `report/individual/2A202603577_VoLeHaiDang.md`.

**Điều mình học được từ phần nhóm:**

- Nhận ra rằng một bài toán hay không phải là một giải pháp AI phức tạp nhất, mà là bài toán chạm đúng nỗi đau thực tế của người dùng và có thể giải quyết khả thi, an toàn với mức can thiệp đơn giản nhất (Workflow).

---

### Dat-MSSV

*(Phần dành cho bạn Đạt tự điền)*

**Phần việc phụ trách:**

-

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

-

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

-

**Điều mình học được từ phần nhóm:**

-

---

### NguyenXuanHung-2A202603599

**Phần việc phụ trách:**

- Đề xuất và trình bày (pitch) candidate problem về đối chiếu hoạt động và số liệu báo cáo ở giai đoạn hội tụ nhóm (CP3).
- Phụ trách chính phần Research giải pháp có sẵn trên thị trường (CP4 — Mục 3.3) và phân tích khoảng trống/rủi ro cho bài toán của nhóm.
- Tham gia thảo luận gom nhóm (Cluster B), chấm điểm shortlist (CP3) và đánh giá 4 rủi ro để ra quyết định Go kèm ngưỡng dừng (CP6).

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Trình bày Problem Card về đối chiếu hoạt động (Mục 2.1), phân tích lý do bài toán gặp rào cản về quyền truy cập dữ liệu thực tế trong phạm vi buổi lab để nhóm hội tụ sang bài toán thủ tục pháp lý hộ kinh doanh.
- Trực tiếp tra cứu, kiểm chứng đường link và lập bảng phân tích 3 nền tảng hiện có (Cổng Dịch vụ công Quốc gia, Thư Viện Pháp Luật, LuatVietnam), chỉ rõ từng công cụ giải quyết bước nào và còn bỏ trống bước chuyển dịch văn bản luật sang checklist đời thường.
- Đóng góp ý kiến xây dựng tiêu chí đánh giá đầu ra của AI (Eval) về tính chính xác nguồn dẫn chiếu (Grounding) và thiết lập ngưỡng dừng sau 4 tuần pilot.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `group_report.md`: Mục 2.1 (Candidate #3), Mục 2.2 (Cluster B), Mục 2.4 (Chấm điểm shortlist), Mục 3.3 (Bảng Research giải pháp đã có), Mục 8 (Đánh giá 4 rủi ro và Quyết định).
- Báo cáo cá nhân: `report/individual/2A202603599_NguyenXuanHung.md`.

**Điều mình học được từ phần nhóm:**

- Hiểu rõ tầm quan trọng của bước Research giải pháp có sẵn: thay vì tự xây dựng lại nguồn dữ liệu pháp luật từ đầu, nhóm tận dụng nguồn chuẩn từ Cổng Dịch vụ công Quốc gia và chỉ dùng AI (mức Workflow) ở đúng điểm nghẽn là chuyển hóa thông tư phức tạp thành checklist dễ hiểu có con người kiểm duyệt (HITL).

---

### NguyenHuuTien-2A202603598

**Phần việc phụ trách:**

- Phản biện candidate của các thành viên, tập trung rủi ro kỹ thuật và rủi ro AI (hallucination, Rule đủ chưa).
- Hỗ trợ CP4 ở phần assumption / đọc lại kết quả kiểm chứng và kiểm link research.
- Hỗ trợ CP5-CP6 rà boundary, HITL, mức Workflow và ngưỡng dừng quyết định Go.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Pitch Problem Card debug webhook / rà log; nhận phản biện về Rule/grep/alert và đồng ý bài này chưa cần chọn làm bài nhóm.
- Đặt câu hỏi cho Đăng về hallucination pháp lý và nguy cơ tư vấn sai; góp phần để nhóm bổ sung HITL, fallback và boundary “AI không thay luật sư / không tự nộp hồ sơ”.
- Tham gia chấm shortlist, cluster, thống nhất chọn thủ tục hộ kinh doanh F&B; hỗ trợ chốt Go pilot hẹp có ngưỡng dừng.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `group_report.md` mục 2.1 (pitch Tiến; câu hỏi Tiến hỏi Đăng; câu Đạt hỏi Tiến), mục 2.4 (shortlist Debug webhook), mục 4–8 (boundary/HITL/Workflow/Go).
- Báo cáo cá nhân: `report/individual/2A202603598_NguyenHuuTien.md`.

**Điều mình học được từ phần nhóm:**

- Pain dự án không phải lúc nào cũng là bài nhóm tốt nhất; đôi khi Rule hoặc tool sẵn có đã đủ, còn bài pháp lý thì phải ưu tiên boundary và mức can thiệp an toàn hơn lạm dụng dùng AI.

