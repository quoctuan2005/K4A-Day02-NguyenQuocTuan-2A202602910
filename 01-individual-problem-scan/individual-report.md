# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Nguyễn Quốc Tuấn
- Mã học viên:2A202602910
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): Sinh viên năm 4
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem): 
    - Tham gia các buổi học trên trường
    - Làm bài tập trên trường
    - Làm việc ở công ty
    - Tìm kiếm tài liệu học tập

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 |Tốn thời gian |Đọc paper dài (có thể lên tới trăm trang) để tìm ra key và các tham số|Sinh viên, nghiên cứu sinh |2-3h / 1 bản |
| 2 |Tốn thời gian |Tóm tắt các bài báo có chủ đề tương tự để phục vụ báo cáo hoặc làm literature review|Sinh viên, nghiên cứu sinh |2-3h / 1 bản |
| 3 |Lặp lại |Viết báo cáo tuần của khoa |Sinh viên, nghiên cứu sinh |1-2h / 1 bản |
| 4 |Pain từ người khác |Báo cáo tiến độ thiếu tóm tắt cốt lõi khiến mentor phải hỏi lại |Mentor, GV hướng dẫn, SV |Bị nhắc sửa 2 lần/tháng, tốn thêm 30 phút |
| 5 |AI có thể tốt hơn |Tra cứu cú pháp thư viện AI mới (LangChain, vLLM) bị vướng docs cũ |SV, Lập trình viên mới |40–60 phút/lần debug |
| 6 |Lặp lại |Chuyển nội dung báo cáo Word thành slide thuyết trình |Sinh viên, nghiên cứu sinh |1–2 giờ/bản |
| 7 |AI có thể tốt hơn |Video call / nói chuyện online với đối tác / bạn bè người nước ngoài |Sinh viên,Intern |Họp 30–45 phút (2–3 buổi/tuần); sau họp mất thêm 20–30 phút hỏi lại thông tin |
| 8 |Tốn thời gian |Vẽ phác thảo sơ đồ hệ thống/flowchart trên giấy sau đó vẽ lại bằng Draw.io/Figma|Nhóm phát triển, sinh viên |1-2h/lần |
| 9 |AI có thể làm tốt hơn |Chuyển tài liệu giấy photo/sách in thành file Word/Pdf mà vẫn giữ nguyên bố cục|Sinh viên, nghiên cứu sinh |1–2 giờ/bản |
| 10 |Tốn thời gian |Sắp xếp / làm tag /backlog trên Notion sau khi làm việc với khách hàng |Sinh viên,Quản lý dự án |45–60 phút/buổi (cuối ngày làm việc hoặc đầu ngày hôm sau) |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi:
- Ý dùng được:
- Ý bỏ vì không phải pain thật:

**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [x] Dùng ít nhất 3/4 lăng kính
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Số hóa tài liệu giấy | Workflow rõ, mất nhiều thời gian ở dựng bảng, metric đo lường tốt | Bảng biểu phức tạp, tài liệu scan bị mờ hoặc nghiêng |
| 2 | Video call với đối tác | Pain thật khi đi làm, AI hỗ trợ speech-to-text và dịch rất phù hợp | Độ trễ thời gian thực và xử lý accent nặng |
| 3 | Báo cáo tuần của khoa | Tần suất lặp lại cao, giải quyết pain cho cả sinh viên và mentor | Tiêu chuẩn đánh giá nội dung tóm tắt thế nào là "đủ tốt" |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Số hóa tài liệu giấy thành file Word

```text
Problem 1 câu:
Sinh viên và nghiên cứu sinh mất từ 60–90 phút để gõ lại tay và vẽ lại bảng biểu khi cần số hóa tài liệu giấy photo, sách in hoặc đề cương thành file Word (.docx) để chỉnh sửa nội dung.

Actor:
Sinh viên năm cuối, nghiên cứu sinh, người làm nghiên cứu cần tái sử dụng tài liệu học tập giấy.

Thời điểm / bối cảnh:
Khi nhận được tài liệu bản cứng (đề cương, phụ lục giáo trình, biểu mẫu photo) và cần bổ sung/chỉnh sửa nội dung trên máy tính trước kỳ thi hoặc đợt nộp báo cáo.

Current workflow 3-7 bước:
1. Chụp ảnh tài liệu giấy bằng điện thoại hoặc máy scan
2. Tải ảnh lên máy tính cá nhân
3. Dùng tool OCR thông thường để lấy text thô (chữ bị mất định dạng, bảng biểu bị bung)
4. Mở Microsoft Word, tự tạo bảng và căn chỉnh số cột/dòng bằng tay
5. Copy-paste từng đoạn text thô vào từng ô trong bảng và tự sửa lỗi chính tả
6. Căn chỉnh lề, font chữ, kích thước cho giống bản gốc

Bottleneck:
Bước 4 và Bước 5: Mất khoảng 40–50 phút chỉ để vẽ lại khung bảng biểu và dán thủ công từng ô dữ liệu bị xô lệch do OCR thông thường không giữ được cấu trúc bảng.

Impact:
Tốn 60–90 phút cho mỗi tài liệu 5–10 trang (tần suất 1–2 lần/tuần). Mất nhiều công sức cơ học thay vì tập trung học tập/nghiên cứu; tỷ lệ gõ sót số liệu ở các bảng phức tạp lên tới 15–20%.

Success metric:
Giảm tổng thời gian số hóa từ 75 phút xuống dưới 5 phút/tài liệu; độ chính xác nhận diện cấu trúc bảng đạt trên 90% (chỉ cần người dùng rà soát nhẹ).

Non-AI alternative:
Dùng phần mềm Scan PDF thông thường (CamScanner/Adobe Scan) -> chỉ xuất ra PDF dạng ảnh hoặc text thô rời rạc, vẫn bắt buộc con người phải tự dựng lại bảng trong Word.

AI hypothesis:
Ứng dụng mô hình Document Layout Analysis kết hợp OCR chuyên sâu (nhận diện vùng chữ, vùng bảng, tọa độ hàng/cột) để tự động xuất thẳng ra cấu trúc file .docx giữ nguyên layout. Con người chỉ đóng vai trò reviewer ở bước cuối.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 75 phút

[1 Chụp ảnh: 3'] 
→ [2 Chuyển ảnh lên PC: 2'] 
→ [3 OCR text thô: 5'] 
→ [4 Vẽ lại bảng trong Word: 30']  <-- bottleneck
→ [5 Nhập liệu từng ô & sửa lỗi: 25']  <-- bottleneck
→ [6 Căn chỉnh lề & font: 10']

FUTURE STATE — 4 phút

[1 Đưa ảnh/tài liệu vào hệ thống: 1'] 
→ [2 Document AI nhận diện layout & bảng: 1'] 
→ [3 Tự động render file .docx chuẩn layout: 30s] 
→ [4 Người dùng mở file rà soát & chỉnh sửa nhẹ: 1.5']  <-- human boundary

Fallback: Nếu bảng biểu quá phức tạp bị lệch dòng -> Hệ thống xuất text thô kèm ảnh gốc bên cạnh để người dùng đối chiếu sửa nhanh.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — Hỗ trợ lắng nghe & dịch khi Video call với đối tác

```text
Problem 1 câu:
Sinh viên và intern khi tham gia video call với đối tác hoặc kỹ sư nước ngoài thường không nghe kịp giọng nói nhanh hoặc accent lạ, dẫn đến bỏ sót thông tin và mất thêm 20–30 phút sau cuộc họp để hỏi lại.

Actor:
Sinh viên đi thực tập (Intern), Kỹ sư phần mềm mới đi làm trong môi trường quốc tế.

Thời điểm / bối cảnh:
Các buổi daily sync, sprint review hoặc trao đổi yêu cầu kỹ thuật trực tuyến (Google Meet/Zoom) với đối tác nước ngoài (Ấn Độ, Âu Mỹ, Nhật Bản).

Current workflow 3-7 bước:
1. Tham gia buổi họp video call trực tuyến
2. Cố gắng lắng nghe và ghi chép nhanh ra giấy/Notion
3. Gặp đoạn nói nhanh hoặc từ khóa chuyên ngành không hiểu kịp thì bị ngắt quãng ghi chép
4. Kết thúc cuộc họp, xem lại ghi chú thấy thiếu sót nhiều thông tin quan trọng
5. Nhắn tin hỏi lại mentor/đồng nghiệp trong team: "Đoạn nãy khách dặn requirement gì thế anh?"
6. Hoặc chờ có video recording để tua đi tua lại nghe lại đoạn bị miss

Bottleneck:
Bước 3: Không theo kịp tốc độ nói và thuật ngữ chuyên ngành trong thời gian thực, dẫn đến ngắt quãng việc ghi chép và bỏ sót ngữ cảnh quan trọng.

Impact:
Mất thêm 20–30 phút sau mỗi buổi họp 45 phút (2–3 buổi/tuần). Gây tâm lý căng thẳng, tự ti trong giao tiếp và tăng nguy cơ làm sai yêu cầu kỹ thuật của khách hàng.

Success metric:
Giảm 80% số lần phải hỏi lại đồng nghiệp sau họp (từ 3–4 câu hỏi/buổi xuống dưới 1 câu); người tham gia nắm được 100% action items ngay khi kết thúc cuộc họp.

Non-AI alternative:
Bật phụ đề tiếng Anh có sẵn của Google Meet/Zoom -> phụ đề chỉ hiện từng dòng rời rạc, không giải thích thuật ngữ chuyên ngành và không tự động lưu lại thành bản tóm tắt có cấu trúc.

AI hypothesis:
Kết hợp Speech-to-Text streaming thời gian thực với LLM tóm tắt theo ngữ cảnh: vừa hiển thị phụ đề dịch từ khóa chuyên ngành vừa tự động bóc tách các mốc quyết định và việc cần làm (action items) vào cuối buổi họp.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 70 phút (45' họp + 25' xử lý sau)

[1 Họp video call: 45'] 
→ [2 Ghi chép ngắt quãng: trong lúc họp]  <-- bottleneck
→ [3 Soát lại note thấy thiếu thông tin: 5'] 
→ [4 Nhắn tin hỏi lại đồng nghiệp / nghe lại record: 20']

FUTURE STATE — 48 phút (45' họp + 3' review)

[1 Họp call có live subtitle + keyword dịch: 45'] 
→ [2 AI tự động trích xuất action items cuối buổi: 1'] 
→ [3 Người dùng rà soát nhanh 3 gạch đầu dòng việc cần làm: 2']  <-- human boundary

Fallback: Nếu âm thanh ồn hoặc accent quá lạ AI dịch sai -> Người dùng dựa vào transcript thô tiếng Anh gốc để đối chiếu lại.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — Tổng hợp báo cáo tuần của khoa / lab

```text
Problem 1 câu:
Sinh viên và nghiên cứu sinh mất từ 1–2 giờ mỗi tuần để tổng hợp kết quả học tập, nghiên cứu và bài tập lab thành báo cáo gửi khoa/mentor, nhưng bản báo cáo thường dài dòng và thiếu tóm tắt điểm nghẽn chính.

Actor:
Sinh viên năm cuối, nghiên cứu sinh, trợ giảng (TA) phụ trách báo cáo tiến độ tuần.

Thời điểm / bối cảnh:
Chiều thứ Sáu hoặc sáng thứ Hai hàng tuần, trước hạn chót nộp báo cáo cho văn phòng khoa hoặc buổi họp tiến độ với Mentor.

Current workflow 3-7 bước:
1. Thu thập thông tin: điểm danh buổi học, tiến độ bài tập lớn, log chạy mô hình trong tuần
2. Mở file mẫu báo cáo tuần của khoa (Word hoặc Google Docs)
3. Điền các mục hành chính và liệt kê chi tiết các công việc đã làm
4. Cố gắng tóm tắt lại các khó khăn kỹ thuật và đề xuất hỗ trợ
5. Định dạng lại phông chữ, bảng biểu cho đúng quy định của khoa
6. Gửi file qua email hoặc hệ thống nộp bài của trường

Bottleneck:
Bước 3 và Bước 4: Mất nhiều thời gian gom nhặt thông tin phân mảnh và viết phần tóm tắt khó khăn kỹ thuật súc tích, khiến bản báo cáo thường bị lan man hoặc thiếu thông tin quan trọng.

Impact:
Mất 60–120 phút/tuần cho mỗi sinh viên. Mentor hoặc giảng viên mất thêm thời gian đọc bản báo cáo dài mà không nắm được ngay học viên đang bị kẹt ở đâu để hỗ trợ kịp thời.

Success metric:
Giảm thời gian viết báo cáo từ 90 phút xuống dưới 20 phút; 100% báo cáo có phần Executive Summary rõ ràng (gồm 3 việc làm được, 1 điểm nghẽn lớn nhất, 1 đề xuất hỗ trợ).

Non-AI alternative:
Cung cấp biểu mẫu (template) có sẵn với các gạch đầu dòng cố định -> giúp chuẩn hóa format nhưng sinh viên vẫn mất thời gian tự tổng hợp và viết nội dung văn bản.

AI hypothesis:
AI tự động nhận dữ liệu đầu vào dạng gạch đầu dòng thô (bullet points) và log thực nghiệm, sau đó cấu trúc lại theo format chuẩn của khoa và tạo bản tóm tắt ngắn gọn. Người viết chỉ cần đọc duyệt lại trước khi gửi.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 90 phút

[1 Gom thông tin & log tuần: 20'] 
→ [2 Điền chi tiết vào template: 35'] 
→ [3 Viết tóm tắt & khó khăn: 25']  <-- bottleneck
→ [4 Format & gửi: 10']

FUTURE STATE — 20 phút

[1 Nhập nhanh gạch đầu dòng việc đã làm: 5'] 
→ [2 AI cấu trúc và viết bản tóm tắt chuẩn format: 2'] 
→ [3 Sinh viên rà soát & chỉnh sửa số liệu: 10']  <-- human boundary
→ [4 Xuất file và gửi: 3']

Fallback: Nếu AI viết văn phong không hợp ý khoa -> Sinh viên sử dụng lại các ý chính do AI bóc tách và tự diễn đạt lại.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #1 — Số hóa tài liệu giấy photo/sách in thành file Word có thể chỉnh sửa mà vẫn giữ nguyên bố cục bảng biểu, căn lề.
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Workflow bài toán rất rõ ràng từ khâu chụp ảnh tài liệu cứng đến việc xuất ra file Word có thể chỉnh sửa được ngay. Về số đo, giải pháp giúp giảm thời gian số hóa từ 60–90 phút gõ và vẽ bảng tay xuống còn dưới 5 phút/tài liệu. Impact rất lớn vì giải phóng sinh viên và nghiên cứu sinh khỏi công việc sao chép định dạng cơ học, đồng thời hạn chế sai sót số liệu trong các bảng biểu phức tạp.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Nếu tài liệu bị cong méo, scan nghiêng hoặc có chữ viết tay đè lên bảng in thì mô hình có nhận diện sai cấu trúc bảng không?
2. Có trường hợp nào bảng biểu quá phức tạp (nhiều ô gộp merge cells) khiến việc sửa lại trên file Word còn tốn thời gian hơn là tự gõ từ đầu không?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: Việc tái tạo định dạng bảng biểu phức tạp (nhiều ô gộp, bảng lồng nhau) trực tiếp sang file .docx rất dễ bị vỡ khung hình hoặc lệch dòng nếu OCR chỉ nhận diện văn bản thuần túy.
- Tôi sửa gì: Bổ sung phương án Fallback: nếu cấu trúc bảng bị lệch quá mức cho phép, hệ thống sẽ xuất song song bảng thô kèm ảnh chụp cắt góc tương ứng để người dùng đối chiếu và chỉnh sửa nhanh.

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
