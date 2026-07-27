# Phase 7 — Individual Reflection

**Học viên:** Đồng Đại Huy  
**Mã học viên:** 2A202601901  
**Nhóm:** Group Day 02  
**Vai trò trong nhóm:** Validation và Thu thập Evidence  

---

## 1. Tôi đã tham gia vào phần nào?

| Hoạt động | Tôi đã làm gì? | Kết quả / Ảnh hưởng đến kết quả nhóm |
|---|---|---|
| **Scan cá nhân (Phase 1)** | Scan 10 vấn đề từ góc nhìn sinh viên trong trường (đăng ký học, thủ tục hành chính, Q&A nhóm lớp, tìm sách thư viện, lỗi hệ thống, phòng học trống...). | Giúp nhóm có nguồn dữ liệu đa dạng về các vấn đề tra cứu thông tin và quy trình học vụ. |
| **Pitch Problem Card (Phase 2)** | Pitch **Problem Card #3** (*Câu hỏi dịch vụ trường bị hỏi lại trong nhóm học tập*) tập trung vào pain point tìm kiếm thông tin bị trôi và mất thời gian đính chính. | Đóng góp 1 ý tưởng thuộc cụm *Knowledge Discovery & Retrieval*, giúp nhóm thấy rõ tầm quan trọng của semantic search và citation source. |
| **Gom trùng & Cluster (Phase 3)** | Thảo luận gom 10+ ý tưởng thành 5 clusters; tham gia chấm điểm Shortlist giữa 3 candidate: *Tra cứu Video + Slide*, *Dataset Discovery*, *Baseline Reproduction*. | Thống nhất chọn candidate **Tra cứu Video + Slide** (34/35 điểm) vì scope vừa sức trong lab, workflow và evidence rất rõ ràng. |
| **Validation / Research (Phase 4)** | Phụ trách chính bước **Validation**: phỏng vấn nhanh 4 sinh viên CNTT và chạy mini poll với 6 sinh viên về thói quen xem lại video/slide. | Thu thập được tín hiệu xác nhận: 3/4 sinh viên mất nhiều thời gian tua video; 5/6 sinh viên đồng ý giải pháp Q&A/Semantic retrieval sẽ hỗ trợ tốt. Làm rõ bottleneck chính nằm ở bước *tua/nghe thử vô định*. |
| **Workflow nhóm (Phase 5)** | Đóng góp nhận xét vào workflow Current State (42 phút) và Future State (6 phút); làm rõ bước **Human Boundary** (sinh viên kiểm tra lại timestamp và slide page gốc). | Đảm bảo workflow nhóm không thần thánh hóa AI, bắt buộc phải có bước con người đối chiếu lại với nguồn gốc (provenance). |
| **Problem Statement (Phase 5)** | Phản biện các field trong Problem Statement v0; làm rõ Success Metric (từ 35–45 phút xuống <5 phút) và Boundary (không tự sửa code, không thay thế video gốc). | Giúp Problem Statement v1 của nhóm chặt chẽ, có tiêu chí đo lường rõ ràng và phạm vi an toàn. |
| **Rule / Workflow / Agent & Decision (Phase 6)** | Đưa ra bằng chứng từ validation để nhóm so sánh Keyword Search vs Semantic Retrieval; ủng hộ chọn mức **Workflow** thay vì **Agent**. | Nhóm thống nhất mức **Workflow** (ASR/OCR → Chunking → Semantic Search → Ranking → Human Review) và quyết định **Go với scope nhỏ** (1 video 2 tiếng + slide). |

---

## 2. Bảng dùng AI trong reflection

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| **Phase 1: Scan** | Gợi ý thêm các góc nhìn scan vấn đề quanh đời sống sinh viên. | Gợi ý thêm các pain point về thủ tục hành chính và mượn sách thư viện. | Gợi ý một số giải pháp AI chung chung như "Chatbot tư vấn học tập" mà chưa có workflow rõ ràng. | Bỏ các gợi ý chatbot chung chung, quay về mô tả đúng hiện trạng lặp lại, tốn thời gian và người chịu ảnh hưởng thật. |
| **Phase 2: Problem Card** | Hỗ trợ cấu trúc bảng Problem Card và chuyển mô tả hiện trạng thành Mermaid diagram. | Giúp vẽ luồng Current/Future workflow nhanh, trực quan. | AI từng gộp bước *tìm video* và *kiểm tra nội dung* thành 1 bước, làm mờ đi bottleneck. | Tách riêng bước *tua video/nghe thử vô định* (15 phút) vì đây mới là điểm nghẽn thực sự tốn nhiều thời gian nhất. |
| **Phase 3: Group Convergence** | Nhờ AI hỗ trợ đặt tên 5 clusters từ danh sách các problem card của 5 thành viên. | Đặt tên các cluster khá chuẩn (*Knowledge Discovery*, *Rules & Compliance*, *Technical Problem Solving*...). | AI đề xuất ưu tiên bài toán phức tạp (*Baseline Reproduction*) chỉ vì nghe "mang tính kỹ thuật cao". | Cùng nhóm chấm điểm lại dựa trên tính khả thi trong lab và chọn bài toán *Tra cứu Video + Slide* có evidence rõ hơn. |
| **Phase 4: Validation & Research** | Soạn dàn ý câu hỏi phỏng vấn nhanh 6 câu cho sinh viên CNTT. | Tạo ra bộ câu hỏi phỏng vấn ngắn gọn, đi thẳng vào pain point tua video và lướt slide. | AI đưa ra một số câu hỏi mang tính định hướng ("Bạn có thích công cụ AI này không?"). | Sửa thành câu hỏi mở về trải nghiệm thực tế ("Lần gần nhất bạn tìm lại bài giảng là khi nào?", "Mất bao lâu?"). |
| **Phase 5: Problem Statement** | Nhờ AI đóng vai "Phản biện khó tính" để chỉ ra điểm chưa rõ trong Problem Statement v0. | Chỉ ra field *Success Metric* và *Boundary* của nhóm còn hơi chung chung. | AI đề xuất thêm các tính năng agentic nâng cao (tự tạo bài tập, tự sửa code...). | Giữ nguyên scope bài toán retrieval, loại bỏ các tính năng lan man ngoài scope tra cứu timestamp + slide page. |
| **Phase 6: Rule / Workflow / Agent** | Hỏi AI ví dụ thực tế về sự khác biệt giữa Rule Search và Semantic Search đối với bài toán video lecture. | Cho ví dụ rất hay về từ đồng nghĩa/paraphrase (ví dụ: "container không nối được DB" vs "Docker Compose same network"). | AI xu hướng khuyên nên dựng Agent tự động tương tác multi-turn. | Nhóm quyết định dừng lại ở mức **Workflow** vì luồng tuyến tính cố định đã đủ giải quyết bài toán với latency thấp và rủi ro thấp. |

---

## 3. Reflection câu hỏi mở

### 3.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?
Khi nghe các bạn trong nhóm trình bày Top 3 (ví dụ: bài toán Debugging/Git conflict của Trung, Baseline Reproduction của Bình, hay Dataset Discovery của Minh), tôi nhận ra rằng:
- Rất nhiều vấn đề kỹ thuật của sinh viên CNTT xuất phát từ việc **thiếu công cụ tra cứu ngữ cảnh (contextual retrieval)** chứ không phải thiếu tài liệu.
- Mọi người thường có xu hướng nghĩ đến giải pháp "viết script" hoặc "dùng LLM trả lời ngay", nhưng khi phân tích kỹ workflow thì bottleneck thực sự lại nằm ở bước **xác định đúng vị trí dữ liệu gốc (provenance/citation)** để đối chiếu.

### 3.2. Nhóm có lúc nào bị solution-first không?
Có. Ở đầu Phase 3, khi bàn về bài toán tra cứu bài giảng, một số thành viên lập tức đề xuất "xây một AI Agent tự tóm tắt video và tạo quiz cho sinh viên". 
Tuy nhiên, nhờ đối chiếu với tiêu chí trong Worksheet và kết quả phỏng vấn nhanh (Phase 4), nhóm đã kịp dừng lại: sinh viên không cần một agent tự tạo bài tập, sinh viên chỉ cần **tìm chính xác đoạn video (timestamp) và trang slide** đang giảng về kiến thức đó để tự học và làm bài. Việc quay lại tập trung vào Problem & Bottleneck giúp nhóm tiết kiệm scope và đi đúng hướng.

### 3.3. Tôi có thay đổi ý kiến sau khi bị challenge không?
Có. Ban đầu tôi rất muốn nhóm chọn **Problem Card #3 của tôi** (*Hỏi đáp quy chế/dịch vụ trường trong nhóm chat*). Nhưng sau khi được nhóm challenge: *"Tài liệu quy chế trường thay đổi theo năm và dữ liệu nhóm chat rất nhiễu, khó tạo dataset chuẩn trong thời gian lab"*, tôi đã đồng ý chuyển sang candidate **Tra cứu Video + Slide**. Bài toán này có nguồn dữ liệu rõ ràng (video ghi hình + file slide PDF), dễ đánh giá ground-truth và dễ đo lường impact hơn trong phạm vi bài tập.

### 3.4. Tôi đóng góp gì thật sự vào artifact cuối của nhóm?
- **Trực tiếp thực hiện phần Quick Validation:** Phỏng vấn 4 sinh viên CNTT và chạy mini poll với 6 sinh viên để thu thập dữ liệu định lượng và định tính thực tế.
- **Xác định chính xác Bottleneck:** Giúp nhóm chỉ ra bước tốn thời gian nhất là *tua video/nghe thử vô định* (15 phút) chứ không phải bước mở video hay lướt slide.
- **Xây dựng Human Boundary:** Kiên trì giữ bước con người đối chiếu (Human Verification) ở cuối Future Workflow để đảm bảo sinh viên luôn mở lại video gốc kiểm tra trước khi áp dụng code/kiến thức.

### 3.5. Điều khó nhất khi viết Problem Statement là gì?
Điều khó nhất là định nghĩa **Success Metric** và **Boundary** thực sự đo lường được:
- Viết "giúp sinh viên tìm nhanh hơn" thì rất dễ, nhưng định nghĩa "giảm thời gian tra cứu từ 35–45 phút xuống dưới 5 phút, trả về đúng Top-K kết quả chứa timestamp và trang slide" đòi hỏi phải hiểu rất rõ baseline hiện tại.
- Giới hạn **Boundary** đòi hỏi sự tỉnh táo: AI chỉ hỗ trợ retrieval/ranking, không được thay thế nguồn sự thật và không tự ý sửa đổi nội dung bài giảng.

### 3.6. Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?
Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở bước **Research giải pháp hiện có (Phase 4)**:
- Tôi sẽ yêu cầu nhóm test trực tiếp với dữ liệu thật trên Google NotebookLM hoặc YouTube Transcript ngay trong giờ lab để thấy rõ hạn chế của Keyword Search đối với video kỹ thuật.
- Việc kiểm chứng thực tế này sẽ giúp nhóm có số liệu baseline thực nghiệm chắc chắn hơn nữa trước khi chốt Problem Statement v1.

---

## 4. Tự kiểm cuối bài

- [x] **[12đ cá nhân]** Cá nhân có 10 problems scan và Top 3 Problem Cards đủ 6 field + workflow draft.
- [x] **[12đ cá nhân]** Đã pitch Problem Card #3 rõ ràng và tích cực challenge/đóng góp ý kiến khi chọn bài toán nhóm.
- [x] **[Nhóm]** Nhóm có nhật ký hội tụ từ các candidate về 1 bài toán thống nhất (*Tra cứu Video + Slide*).
- [x] **[15đ nhóm]** Nhóm có workflow Current State (42') và Future State (6') rõ ràng với bottleneck và boundary.
- [x] **[20đ nhóm]** Nhóm có Problem Statement v0/v1 đầy đủ actor, workflow, bottleneck, impact, success metric, boundary và AI intervention point.
- [x] **[15đ nhóm]** Nhóm có bảng so sánh No AI / Rule / Workflow / Agent và lý do chọn mức Workflow.
- [x] **[10đ nhóm]** Nhóm có quyết định cuối (Go với scope nhỏ) cùng kịch bản pilot và exit/rollback plan rõ ràng.
- [x] **[10đ cá nhân]** Reflection cá nhân thể hiện trung thực vai trò trong nhóm (Validation & Evidence), cách sử dụng AI có chọn lọc, bài học rút ra và hướng cải thiện.
- [x] **[6đ cá nhân]** Tự giải thích được trọn vẹn mạch logic: *Problem → Workflow → Bottleneck → Metric → Boundary → AI Fit (Rule/Workflow/Agent) → Decision*.

---

*_Bản Reflection cá nhân Phase 7 — Học viên Đồng Đại Huy (2A202601901)_*
