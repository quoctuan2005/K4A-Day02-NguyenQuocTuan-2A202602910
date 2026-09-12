# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Nguyễn Quốc Tuấn
- Mã học viên: 2A202602910
- Nhóm: B - ILV
- Candidate problem nhóm chọn: Customer Feedback Clustering (Phân cụm phản hồi khách hàng theo ngữ nghĩa để xác định pain point cốt lõi)

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Quét 10 problems thực tế từ việc học và làm việc | Đóng góp góc nhìn đa dạng từ sinh viên & intern cho pool ý tưởng |
| Pitch Problem Card | Pitch bài "Số hóa tài liệu giấy" 2 phút | Nhóm đánh giá cao tính khả thi, đưa vào vòng cân nhắc |
| Challenge bài của bạn khác | Đặt câu hỏi về cách phân biệt feedback khác từ ngữ nhưng cùng ý | Giúp nhóm khoanh vùng đúng bottleneck ở bước 4–5 |
| Gom trùng / cluster | Hỗ trợ phân loại 12 ý tưởng thành 4 cụm chủ đề | Giúp nhóm gom nhanh các bài toán trùng lặp về reporting & analysis |
| Chọn candidate problem | Cùng nhóm chấm điểm ma trận và bỏ phiếu | Nhóm đồng thuận chọn Customer Feedback Clustering |
| Validation / research | Khảo sát các công cụ thị trường (Dovetail, Thematic, Productboard) | Nhóm nắm được điểm mạnh/yếu của các giải pháp hiện có |
| Workflow nhóm | Cùng vẽ lại 7 bước xử lý feedback của PM | Xác định rõ 2 bước nghẽn và vị trí con người kiểm tra (human boundary) |
| Problem Statement | Viết và hoàn thiện các chỉ số đo lường (metric) | Định lượng rõ mục tiêu: giảm từ 120' xuống <30' với ≥90% agreement |
| Rule / Workflow / Agent | Phân tích vì sao Keyword Rules thất bại trước ngữ nghĩa tự nhiên | Thống nhất chọn mức độ Workflow/Agentic có PM review |
| Decision | Đánh giá rủi ro sai sót và điều kiện dừng (rollback) | Nhóm chốt quyết định Go kèm kịch bản pilot trên 200 feedback |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của tôi là phần nghiên cứu đối chuẩn (research benchmark) các công cụ phân tích feedback trên thị trường và đề xuất ranh giới kiểm tra thủ công (human boundary) để PM luôn kiểm soát chất lượng trước khi chốt roadmap.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý thêm góc nhìn problem cho sinh viên/intern | Mở rộng thêm lăng kính Speech và Vision | Gợi ý ý tưởng quá rộng (tự động giải đề) | Lọc bỏ, chỉ giữ lại các việc có workflow thực tế |
| Problem Card | Phản biện điểm yếu của bài toán số hóa tài liệu | Nhắc nhở nguy cơ vỡ layout bảng biểu | Khen ngợi giải pháp một chiều | Tự thêm cơ chế Fallback khi AI nhận diện sai bảng |
| Workflow | Gợi ý cấu trúc luồng trước và sau | Tách bạch rõ các bước bàn giao (handoff) | Hay gộp bước đọc context và phân cụm | Tách riêng bước so sánh ngữ nghĩa vì đó là bottleneck |
| Research | Tìm kiếm các giải pháp thị trường tương tự | Liệt kê nhanh Dovetail, Thematic, Productboard | Đưa ra số liệu tiết kiệm thời gian không nguồn | Tự tra cứu tính năng chính thức trên website công cụ |
| Problem Statement | Nhờ AI phản biện tiêu chí đo lường (metric) | Chỉ ra lỗi viết chung chung kiểu "nhanh hơn" | Đề xuất tự động hóa 100% không an toàn | Bổ sung mốc baseline cụ thể (120' → <30') và người duyệt |
| Rule / Workflow / Agent | Phân tích ưu/nhược điểm của Keyword Rules vs AI | Làm rõ giới hạn của taxonomy tĩnh | Đòi làm Agent tự lập kế hoạch quá phức tạp | Cùng nhóm chốt phương án Workflow kết hợp AI có review |
| Decision | Gợi ý tiêu chí cho pilot và kịch bản dừng | Đưa ra các rủi ro về sai lệch dữ liệu | Không tính đến quy mô tài nguyên thực tế | Tự đưa số lượng mẫu pilot (200 feedback) và điều kiện rollback |

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?

**Reflection:**

```text
Khi lắng nghe top 3 problems của các bạn trong nhóm, tôi nhận ra bài toán số hóa tài liệu của mình dù rất thiết thực nhưng mang tính cá nhân, trong khi bài Customer Feedback Clustering lại giải quyết điểm nghẽn mang tính chiến lược tác động tới toàn bộ đội ngũ sản phẩm. Lúc đầu, nhóm tôi cũng từng rơi vào bẫy solution-first khi có thành viên đề xuất xây dựng một Autonomous Agent tự động gom nhóm rồi gửi thẳng đề xuất roadmap cho ban giám đốc để trông cho thật ngầu. Tuy nhiên, khi cùng nhau mổ xẻ workflow 7 bước hiện tại, tôi đã thuyết phục nhóm rằng ngôn ngữ phản hồi của khách hàng có độ biến thiên rất cao, nên việc để AI tự quyết định hoàn toàn là vô cùng rủi ro. Đóng góp rõ nét nhất của tôi vào artifact cuối là phần nghiên cứu các công cụ sẵn có như Dovetail và Thematic, giúp nhóm nhận ra bài toán này cốt lõi nằm ở phân cụm ngữ nghĩa (Semantic Clustering) chứ không phải bộ lọc từ khóa đơn thuần. Phần khó nhất đối với tôi khi viết Problem Statement là xác định Boundary, nhóm đã phải tranh luận khá gay gắt để thống nhất rằng AI chỉ đóng vai trò trợ lý đề xuất theme và lập luận lý do, còn quyền merge hay split cuối cùng vẫn thuộc về con người. Trải nghiệm từ bài lab này giúp tôi thấu hiểu sâu sắc rằng một giải pháp AI giá trị không nằm ở độ phức tạp của mô hình, mà nằm ở việc chọn đúng điểm can thiệp và thiết lập được ranh giới kiểm soát an toàn.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI
