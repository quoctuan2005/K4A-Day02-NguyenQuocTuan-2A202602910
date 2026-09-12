# Group Report — Day 02

## Thành viên nhóm

| STT | Họ và tên        | Mã học viên | Vai trò trong nhóm |
| --- | ---------------- | ----------- | ------------------ |
| 1   | Đào Đức Anh      | 2A20262567  | Nhóm trưởng        |
| 2   | Trần Thu Phương  | 2A202602366 | Thành viên         |
| 3   | Nguyễn Quốc Tuấn | 2A202602910 | Thành viên         |
| 4   | Lê Tuấn Hưng     | 2A202602665 | Thành viên         |
| 5   | Nguyễn Mạnh Hải  | 2A202602988 | Thành viên         |

---

# Tổng hợp top 3 problems của các thành viên

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh |
|---|---|---|---|---|---|
| 1 | Nguyễn Quốc Tuấn | Số hóa tài liệu giấy photo/sách in thành file Word | Sinh viên, nghiên cứu sinh | Vẽ lại khung bảng trong Word và copy-paste từng ô dữ liệu | Workflow rõ ràng, impact đo được tốt, dễ gặp lỗi nếu bảng phức tạp |
| 2 | Nguyễn Quốc Tuấn | Video call / nói chuyện online với đối tác nước ngoài | Sinh viên, Intern | Không theo kịp giọng nói nhanh hoặc accent lạ trong thời gian thực | Pain thật khi đi làm, nhưng xử lý audio real-time có latency cao |
| 3 | Nguyễn Quốc Tuấn | Viết báo cáo tuần của khoa / lab | Sinh viên, nghiên cứu sinh | Gom thông tin phân tán và viết tóm tắt khó khăn kỹ thuật | Lặp lại hàng tuần, dễ giải quyết bằng template kết hợp AI |
| 4 | Đào Đức Anh | PM phải gom feedback từ nhiều nguồn để tạo weekly insight | Product Manager | Tìm kiếm và tổng hợp thông tin phân tán từ Slack, Support, Call | Impact lớn (2–6h/tuần), bài toán quen thuộc của PM |
| 5 | Đào Đức Anh | PM phải tự nhóm các feedback giống nhau thành các pain point | Product Manager | Manual clustering + taxonomy không nhất quán; phân biệt wording khác nhau | Điểm nghẽn semantic rất rõ, cực kỳ phù hợp với AI, candidate mạnh nhất |
| 6 | Đào Đức Anh | PM phải kiểm chứng một "customer pain" bằng evidence từ nhiều nguồn | Product Manager | Cross-source investigation, truy vết context qua nhiều hệ thống | Giá trị cao cho roadmap nhưng scope rộng và phụ thuộc data access |
| 7 | Nguyễn Mạnh Hải | Luật sư rà soát hợp đồng (NDA) tìm điều khoản rủi ro thủ công | Luật sư, pháp chế | Đọc và đối chiếu từng điều khoản để phát hiện rủi ro | Impact lớn nhưng khó tiếp cận dữ liệu thật để validate trong lab |
| 8 | Nguyễn Mạnh Hải | Chuyên viên tín dụng thẩm định hồ sơ vay SME thủ công | Chuyên viên tín dụng | Thu thập và thẩm định báo cáo tài chính qua nhiều bước | Quy trình phức tạp, giá trị cao nhưng khó tiếp cận domain ngân hàng |
| 9 | Nguyễn Mạnh Hải | Ghi biên bản họp & theo dõi action item thủ công | PM, BA, thư ký | Chuyển note thô sang bản minute hoàn chỉnh và trích xuất task | Gần gũi, dễ làm nhưng impact thời gian tương đối nhỏ (~30 phút/buổi) |
| 10 | Lê Tuấn Hưng | Tự động phân rã yêu cầu tính năng thành user story và test case | BA, Tech Lead, PO | Phân tích logic đa bước và dự báo xung đột kiến trúc tiềm ẩn | Rất tham vọng, thể hiện rõ vai trò AI nhưng scope quá lớn cho lab |
| 11 | Lê Tuấn Hưng | Nghe lại recording/transcript cuộc họp để chắt lọc action items | Thành viên dự án, thư ký | Lọc thủ công các đoạn ghi âm dài, dễ sót việc không có keyword rõ | Nhu cầu thường xuyên, tối ưu tốt bằng LLM + workflow |
| 12 | Lê Tuấn Hưng | Viết mô tả Pull Request (PR description) và tóm tắt code diff | Software Developer | Tóm tắt ngữ cảnh thay đổi trong git diff cho người review | Hữu ích cho dev hàng ngày nhưng tính cấp thiết chưa vượt trội |
| 13 | Trần Thu Phương | Debug code/test mất nhiều thời gian do phải thử sửa nhiều lần | Sinh viên thực tập AI/Software | Phân tích traceback và context phân tán; thử sửa và test lặp lại | Nỗi đau thực tế của dev (20–40 phút/lỗi), impact đo lường rất rõ |
| 14 | Trần Thu Phương | Setup môi trường Python và xử lý dependency lặp lại | Sinh viên thực tập, dev mới | Cài đặt thủ công, xung đột package/version Python khó tìm nguyên nhân | Thường gặp nhưng Rule/Script (Docker, Conda) giải quyết tốt hơn AI |
| 15 | Trần Thu Phương | Hỏi mentor hỗ trợ debug bị thiếu thông tin nên phải hỏi qua lại | Sinh viên gặp lỗi, Mentor | Context debug thu thập không theo chuẩn, thiếu traceback và command | Pain giao tiếp thực tế, giải quyết được bằng format chuẩn hóa |

---

# Group convergence

| Cluster                              | Candidate examples                                                                                                           | Pattern chung                                                                                                   |
| ------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- |
| **Research / tổng hợp thông tin**    | Đọc paper dài để tìm key; tóm tắt paper tương tự; tra cứu docs thư viện AI                                                   | Đọc nhiều nguồn → tìm thông tin quan trọng → tổng hợp lại                                                       |
| **Báo cáo / chuyển đổi nội dung**    | Viết báo cáo tuần; chuyển Word → slide; báo cáo tiến độ thiếu summary                                                        | Lấy nội dung/data có sẵn → cấu trúc → viết lại thành output cho người khác                                      |
| **Meeting / follow-up**              | Ghi meeting minutes; theo dõi action items; call với đối tác nước ngoài                                                      | Thu thập thông tin trong cuộc họp → ghi nhận → tổng hợp → follow-up                                             |
| **Developer / Kỹ thuật & Debug**     | Debug code/test; setup môi trường Python; viết mô tả Pull Request                                                           | Gặp lỗi phân tán, môi trường không đồng nhất → mất nhiều thời gian tra cứu và thử sửa thủ công                  |
| **Product feedback / PM operations** | Gom feedback từ nhiều nguồn; re-tag/regroup khi chuẩn bị roadmap; cluster feedback thành themes; tìm evidence cho pain point | **PM phải xử lý lượng lớn thông tin phân tán → tìm pattern → tổng hợp thành insight để ra quyết định sản phẩm** |

---

# Shortlist và score

| Candidate                             | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Có human boundary rõ | **Tổng** |
| ------------------------------------- | -------: | ----------: | ---------------: | -------------: | ------------: | -----------------: | ---------------: | -------------------: | -------: |
| **Customer Feedback Clustering – PM** |    **5** |       **5** |            **5** |          **5** |         **5** |              **5** |            **5** |                **5** |   **40** |
| Weekly Report                         |        5 |           5 |                4 |              5 |             5 |                  5 |                5 |                    4 |   **38** |
| Debug Code & Automated Testing        |        5 |           5 |                5 |              4 |             4 |                  5 |                5 |                    4 |   **37** |
| Meeting Minutes + Action Items        |        5 |           5 |                4 |              4 |             5 |                  5 |                5 |                    4 |   **37** |
| Research / Paper Summarization        |        5 |           4 |                5 |              4 |             5 |                  4 |                4 |                    4 |   **35** |
| Word → Presentation Slides            |        5 |           5 |                3 |              4 |             5 |                  4 |                5 |                    4 |   **35** |
| Document / OCR Conversion             |        4 |           4 |                4 |              4 |             5 |                  3 |                4 |                    4 |   **32** |

### Vì sao Customer Feedback Clustering đứng đầu?

| Tiêu chí           | Lý do                                                                                        |
| ------------------ | -------------------------------------------------------------------------------------------- |
| **Actor rõ**       | PM là owner trực tiếp của workflow                                                           |
| **Workflow rõ**    | Collect → Normalize → Cluster → Generate Theme → Review                                      |
| **Pain rõ**        | Semantic clustering và regroup feedback phải làm thủ công                                    |
| **Evidence**       | Hàng trăm feedback/tuần, khoảng **120 phút/tuần** theo giả định ban đầu                      |
| **Impact**         | Clustering sai có thể làm sai frequency → ảnh hưởng prioritization                           |
| **AI fit**         | Semantic similarity, clustering, theme generation và evidence extraction đều phù hợp với AI  |
| **So sánh R/W/A**  | Có thể phân biệt rõ: Rule xử lý deterministic → Workflow orchestration → Agent tự quyết định |
| **Human boundary** | PM có thể kiểm tra Accept / Merge / Split / Rename / Reject                                  |
| **Lab fit**        | Scope đủ nhỏ để pilot nhưng đủ phức tạp để đánh giá AI intervention                          |

Lý do không chỉ vì điểm cao nhất, mà vì đây là candidate có **đủ cả 4 yếu tố: workflow lặp lại + bottleneck semantic rõ + impact đo được + AI intervention point cụ thể**, đồng thời cho phép nhóm kiểm chứng rõ quyết định **Rule vs Workflow vs Agent**.

# Quick Validation

Nhóm thực hiện validation bằng cách research các topic liên quan đến thời gian tổng hợp feedback, hình thành pain point trên Reddit.

Insight thu được:

- Mỗi tuần PM mất khoảng 2 giờ đọc và nhóm hàng trăm customer feedback thành các pain point, trong đó việc xác định những feedback khác cách diễn đạt nhưng thực chất nói về cùng một vấn đề là bottleneck lớn nhất.

---

# Research giải pháp đã có

Research thực tế cho thấy ít nhất 3 hướng giải quyết rất gần với problem. Nhóm quyết định tham khảo các workflow đã có sẵn này

| Nguồn / tool / case                 | Link                                                                                                                                                  | Họ giải quyết phần nào?                                                                                               | Điểm mạnh                                                               | Khoảng trống / rủi ro                                                  | Bài học cho nhóm                                                                     |
| ----------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------- | ---------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| **Dovetail**                        | [Dovetail Customer Intelligence](https://dovetail.com/?utm_source=chatgpt.com)                                                                        | Centralize feedback; AI tự động tìm **themes, trends, signals**; AI Channels có thể cluster tickets, reviews, surveys | Bao phủ nhiều nguồn; semantic/AI analysis; có evidence gốc và citations | Là một platform khá rộng; problem nhỏ hơn có thể không cần cả platform | Semantic clustering + evidence từ feedback là pattern đã được validate               |
| **Dovetail for Product Management** | [Dovetail for Product Management](https://dovetail.com/roles/product-management/?utm_source=chatgpt.com)                                              | Automatically categorize/cluster feedback, quantify themes và đưa evidence vào roadmap                                | Gần như trùng trực tiếp với workflow của PM                             | Khó cạnh tranh nếu chỉ xây một clustering tool generic                 | Nếu build riêng, phải có **specific workflow advantage** thay vì chỉ "AI clustering" |
| **Productboard**                    | [Productboard Insights](https://www.productboard.com/product/insights/?utm_source=chatgpt.com)                                                        | Thu thập feedback từ Slack, Zendesk, Gong... rồi capture/curate/route và identify actionable insights                 | Tích hợp feedback → product planning/roadmap                            | Nặng hơn nhu cầu "weekly clustering" đơn thuần                         | Giá trị không chỉ nằm ở clustering mà ở việc nối theme với product decision          |
| **Chattermill**                     | [Chattermill AI-native CX Intelligence](https://chattermill.com/?utm_source=chatgpt.com)                                                              | Unify feedback từ surveys, reviews, support, social, calls; AI tag/categorize và phát hiện themes                     | Xử lý volume lớn, theme taxonomy, context enrichment                    | Enterprise-oriented; có thể overkill cho một PM/team nhỏ               | Taxonomy + semantic classification + context là pattern quan trọng                   |
| **Productboard Spark**              | [Productboard Spark AI Feedback Analysis](https://www.productboard.com/blog/productboard-spark-ai-customer-feedback-analysis/?utm_source=chatgpt.com) | Ingest feedback từ nhiều channel, tự detect themes và nối insights với features/roadmaps                              | Rất gần với AI-agent hypothesis ban đầu                                 | Cho thấy "AI tự cluster feedback" đã là feature của incumbent          | Agent nên giải quyết **workflow end-to-end**, không chỉ clustering                   |

### Research takeaway

- Productboard hiện mô tả rõ việc gom feedback từ các nguồn như Zendesk, Gong và Slack vào một nơi, sau đó dùng sorting/filtering/segmentation để phục vụ product decisions. ([Productboard][2])

- Dovetail còn đi xa hơn: AI Channels có thể **cluster raw feedback thành themes và rank theo frequency**, sau đó cho phép PM đưa evidence vào Productboard/Jira. ([Dovetail][1])

- Chattermill cũng cho phép AI áp theme vào từng feedback và tổ chức theme theo category; ví dụ category có thể là "Checkout experience" và theme bên dưới là "Receipt/email confirmation". ([Chattermill][3])

Các sản phẩm hiện tại đã giải quyết:

```text
feedback
   ↓
centralize
   ↓
AI classification / clustering
   ↓
theme
   ↓
frequency / sentiment / evidence
   ↓
product decision
```

---

# Workflow before/after

## Current workflow

### CURRENT WORKFLOW

![Current Workflow](./current-workflow.drawio.png)

### Workflow detail

| Bước       | Actor | Input                                   | Output                     | Thời gian / tần suất | Ghi chú                            |
| ---------- | ----- | --------------------------------------- | -------------------------- | -------------------- | ---------------------------------- |
| 1. Collect | PM    | Slack, support tickets, interview notes | Raw feedback set           | Hàng tuần            | Feedback nằm ở nhiều nguồn         |
| 2. Read    | PM    | Raw feedback                            | Hiểu context từng feedback | Hàng tuần            | Cần đọc context, không chỉ keyword |
| 3. Tag     | PM    | Individual feedback                     | Category/tag               | Hàng tuần            | Có thể dùng taxonomy có sẵn        |
| 4. Compare | PM    | Tagged feedback                         | Candidate similarities     | **~30–45 phút**      | **Bottleneck chính**               |
| 5. Cluster | PM    | Candidate similarities                  | Pain-point groups          | **~30–45 phút**      | Semantic similarity khó xác định   |
| 6. Name    | PM    | Pain-point groups                       | Theme + description        | ~15–20 phút          | Cần tạo label có ý nghĩa           |
| 7. Review  | PM    | All clusters                            | Final themes               | ~15–20 phút          | Merge/split sai phải sửa           |

---

## Future workflow

### FUTURE WORKFLOW

![Future Workflow](./future-workflow.drawio.png)

### Boundary quan trọng

AI **không được tự quyết định final taxonomy**.

```text
AI:
"Feedback #12, #38, #71, #92 có thể thuộc
theme: Checkout performance"

              ↓

PM:
[Accept] [Merge] [Split] [Rename] [Reject]

              ↓

Final theme
```

### Fallback

```text
AI cluster không hợp lý
        ↓
PM reject / split / merge
        ↓
PM tự chỉnh cluster
        ↓
Final dataset vẫn do PM kiểm soát
```

### Workflow detail

| Bước                                  | Actor               | Input                                          | Output                                                       | Thời gian / tần suất | Ghi chú                                                                    |
| ------------------------------------- | ------------------- | ---------------------------------------------- | ------------------------------------------------------------ | -------------------- | -------------------------------------------------------------------------- |
| **1. Thu thập phản hồi**              | PM / Hệ thống       | Slack, support tickets, interview notes, calls | Raw feedback set                                             | Hàng tuần            | Thu thập feedback từ nhiều nguồn về một nơi                                |
| **2. Chuẩn hóa feedback**             | **Workflow / Rule** | Raw feedback set                               | Feedback đã chuẩn hóa, loại trùng                            | Tự động              | Chuẩn hóa format, loại duplicate, làm sạch dữ liệu                         |
| **3. Phân nhóm**                      | **AI**              | Feedback đã chuẩn hóa                          | Candidate clusters                                           | **Tự động**          | AI nhóm các feedback có **ý nghĩa tương đồng**, không chỉ dựa trên keyword |
| **4. Tạo chủ đề/pain point**          | **AI**              | Candidate clusters                             | Theme + description + evidence + feedback count + confidence | **Tự động**          | AI tạo bản tóm tắt có cấu trúc để PM dễ kiểm tra                           |
| **5. PM review**                      | **PM**              | AI-generated themes                            | Accepted / merged / split / renamed / rejected themes        | **~15–20 phút**      | **Human boundary** — PM chịu trách nhiệm quyết định cuối cùng              |
| **6. Danh sách pain point cuối cùng** | **PM + Hệ thống**   | Reviewed themes                                | Final pain-point list                                        | Hàng tuần            | Danh sách đã xác nhận, dùng cho product planning và roadmap                |

---

## Before / After impact

| Metric                   |                                   Trước |                               Sau kỳ vọng | Ghi chú                                          |
| ------------------------ | --------------------------------------: | ----------------------------------------: | ------------------------------------------------ |
| Tổng thời gian           |                               ~120 phút |                              **<30 phút** | Target ban đầu                                   |
| Số bước                  |                                       7 |                                         6 | Một số bước được tự động hóa                     |
| Bước clustering thủ công |                            2 bước chính |                     AI candidate clusters | PM vẫn review                                    |
| Số feedback PM phải đọc  |                               Hàng trăm |            Có thể vẫn cần review evidence | Không nên giả định AI loại bỏ hoàn toàn việc đọc |
| Final decision           |                                      PM |                                        PM | Không thay đổi                                   |
| Bottleneck               | Semantic comparison + manual clustering |             **PM review / merge / split** | Bottleneck mới là acceptable                     |
| Risk                     |                 Duplicate / wrong merge |     AI wrong cluster / hallucinated theme | Mitigate bằng evidence + human review            |
| Output                   |                         Pain-point list | Pain-point + cluster evidence + frequency | Giàu context hơn                                 |

---

# Problem Statement v0

| Field              | Nội dung                                                                                                                                                                                                                 |
| ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Actor**          | Product Manager chịu trách nhiệm tổng hợp customer feedback để phục vụ product planning và roadmap review.                                                                                                               |
| **Workflow**       | Hằng tuần, PM thu thập feedback từ Slack, support tickets và interview notes, đọc từng feedback, phân loại, tìm các feedback có cùng underlying problem, gom thành pain-point clusters, đặt tên và review lại các nhóm.  |
| **Bottleneck**     | Việc xác định các feedback khác cách diễn đạt nhưng cùng underlying problem đòi hỏi PM phải đọc, so sánh và phán đoán thủ công; dễ tạo duplicate themes hoặc merge nhầm các vấn đề khác nhau.                            |
| **Impact**         | Với vài trăm feedback mỗi tuần, workflow có thể tiêu tốn khoảng 2 giờ/tuần theo giả định ban đầu. Clustering không nhất quán cũng làm sai lệch frequency của pain points và có thể ảnh hưởng đến product prioritization. |
| **Success Metric** | Giảm thời gian clustering từ ~120 phút xuống <30 phút trên cùng một tập feedback; đạt ≥90% agreement với PM về cluster membership.                                                                                       |
| **Boundary**       | AI chỉ đề xuất clusters, theme names và evidence; PM là người quyết định merge/split/rename/reject và phải review output trước khi sử dụng cho roadmap/product planning.                                                 |

# Rule/Workflow/Agent

| Mức          | Phương án                                                                                                                         | Khi nào đủ                                                                                                | Rủi ro                                                                                            | Chọn?                                                                       |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------- |
| **Rule**     | Fixed rule để thu thập feedback, chuẩn hóa format, loại duplicate, filter theo thời gian/nguồn                                    | Đủ nếu bài toán chủ yếu là **data processing có cấu trúc**, không cần hiểu semantic meaning               | Không hiểu được feedback khác wording nhưng cùng pain point; rule ngày càng nhiều và khó maintain | **Không chọn làm toàn bộ**, nhưng dùng cho **Collect + Normalize + Dedupe** |
| **Workflow** | `Collect → Normalize → AI Semantic Clustering → AI Generate Theme → PM Review`                                                    | Phù hợp khi quy trình **tuyến tính, các bước tương đối cố định**, AI chỉ xử lý các bước cần hiểu ngôn ngữ | AI clustering/theme có thể sai; cần PM kiểm duyệt; workflow phải xử lý exception                  | **Chọn**                                                                    |
| **Agent**    | Agent tự tìm feedback từ Slack/Support/Interview, quyết định cách phân tích, tự cluster/merge/split, yêu cầu thêm dữ liệu khi cần | Chỉ cần khi quy trình có **nhiều nhánh**, nhiều nguồn/tool và agent cần tự quyết định bước tiếp theo      | **Quá phức tạp**, khó kiểm soát quyết định merge/split; nhiều quyền truy cập và khó audit         | **Chưa chọn**                                                               |

### Kết luận

**Chọn Workflow + Rule + AI**, chưa cần Agent.

Lý do chính:

> **Bài toán hiện tại có workflow khá tuyến tính và predictable. Bottleneck nằm ở việc hiểu semantic similarity và tổng hợp feedback, nên AI nên được đặt vào đúng các bước đó thay vì dùng một Agent tự quyết toàn bộ quy trình.**

**Rule** xử lý phần deterministic → **AI** xử lý phần semantic → **PM** giữ quyền quyết định cuối cùng.

## Problem Statement v1

| Field                            | Nội dung                                                                                                                                                                                                                                                      |
| -------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Actor**                        | Product Manager chịu trách nhiệm tổng hợp customer feedback hằng tuần để xác định pain points và phục vụ product planning / roadmap review.                                                                                                                   |
| **Workflow**                     | Thu thập feedback từ Slack, support tickets, interview notes → chuẩn hóa & loại trùng → phân nhóm theo semantic similarity → tạo theme/pain point → PM review → đưa vào danh sách pain point cuối cùng.                                                       |
| **Bottleneck**                   | PM phải đọc và so sánh hàng trăm feedback để nhận ra các feedback **khác cách diễn đạt nhưng cùng underlying problem**. Đây là bước cần nhiều thời gian và phán đoán, đồng thời dễ xảy ra merge nhầm hoặc tạo duplicate themes.                               |
| **Impact**                       | Với vài trăm feedback mỗi tuần, PM có thể mất khoảng **120 phút/tuần** cho việc clustering và tổng hợp. Clustering không nhất quán có thể làm sai frequency của pain points và ảnh hưởng đến product prioritization.                                          |
| **Success Metric**               | Giảm thời gian xử lý từ **~120 phút xuống <30 phút/tuần** trên cùng một tập feedback; đạt **≥90% agreement với PM về cluster membership**.                                                                                                                    |
| **Boundary**                     | AI chỉ **đề xuất** cluster, theme name, description và evidence. AI không tự quyết định merge/split/reject và không đưa output trực tiếp vào roadmap. **PM phải review và quyết định cuối cùng.**                                                             |
| **AI intervention point**        | Sau bước **Normalize + Dedupe**, AI thực hiện **Semantic Clustering + Generate Theme**; sau đó chuyển output cho PM review.                                                                                                                                   |
| **Mức chọn**                     | **Workflow:** Rule/Workflow xử lý collect + normalize/dedupe; AI xử lý semantic clustering + theme generation; PM review và quyết định cuối cùng.                                                                                                             |
| **Rủi ro & người thật kiểm tra** | **Risk:** AI nhóm sai các feedback khác nhau, bỏ sót feedback, tạo theme không chính xác hoặc confidence không phản ánh đúng chất lượng. **Người kiểm tra:** PM review cluster membership, evidence và thực hiện merge/split/rename/reject trước khi sử dụng. |

## Final decision

**Decision:**

```text
Go với scope nhỏ — AI-assisted workflow, không dùng Agent.
```

### Pilot nhỏ nhất

- Dùng **data mẫu từ 2–4 tuần feedback gần nhất**.
- Chạy workflow bán tự động:
  `Collect → Normalize/Dedupe → AI Clustering → AI Theme Generation → PM Review`.
- AI chỉ tạo:
  - Candidate clusters
  - Theme name
  - Description
  - Evidence
  - Feedback count
  - Confidence

- PM thực hiện **Accept / Merge / Split / Rename / Reject**.
- Đo:
  - Thời gian PM xử lý.
  - Cluster agreement giữa AI và PM.
  - Số lần PM phải sửa cluster/theme.

### Exit / rollback

- Nếu sau **2 tuần pilot**, PM vẫn phải chỉnh sửa **>30% cluster membership** hoặc không đạt **≥90% agreement**, chưa triển khai rộng; quay về workflow rule/template + hỗ trợ thủ công.
- Nếu AI thường xuyên **merge nhầm các pain point khác nhau**, tăng human review hoặc giảm scope AI xuống **chỉ đề xuất candidate clusters**.
- Nếu AI tạo theme/evidence không đáng tin cậy, **không cho output AI trở thành source of truth**; PM phải xác nhận từ feedback gốc.

### Decision rationale

- **Problem rõ:** bottleneck tập trung ở semantic clustering.
- **Workflow rõ và tuyến tính:** không cần Agent tự quyết định bước tiếp theo.
- **Có thể tách deterministic và AI:** Rule xử lý normalize/dedupe; AI xử lý semantic similarity.
- **AI intervention point rõ:** chỉ can thiệp ở clustering và theme generation.
- **Human boundary rõ:** PM vẫn chịu trách nhiệm quyết định merge/split/reject.
- **Metric đo được:** thời gian xử lý + cluster agreement.
- **Scope nhỏ, dễ pilot:** có thể kiểm chứng trước khi đầu tư một Agent phức tạp.

> **Final choice: Workflow + Rule + AI, với PM là human-in-the-loop. Không chọn Agent ở giai đoạn này.**

---

[1]: https://dovetail.com/roles/product-management/?utm_source=chatgpt.com "Dovetail for Product Managers"
[2]: https://www.productboard.com/product/insights/?utm_source=chatgpt.com "Product Feedback Software Platform | Productboard"
[3]: https://chattermill.com/?utm_source=chatgpt.com "Chattermill: CX Intelligence & Voice of Customer Platform"
