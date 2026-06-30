# 1. Industry Risk Snapshot

### Industry Risk Snapshot: Education/AI Tutor (Education Sector)

| Câu hỏi | Mức độ | Vì sao |
| :--- | :--- | :--- |
| Nếu AI sai, có thể gây hại đến thể chất không | Low | Hệ thống chủ yếu hỗ trợ học tập, không tác động vật lý lên người học. |
| AI có ảnh hưởng đến quyết định hệ trọng không | Medium | Ảnh hưởng đến lộ trình học tập, đánh giá năng lực và tâm lý học đường của học viên. |
| Hệ thống có động đến dữ liệu nhạy cảm không | Critical | Lưu trữ thông tin định danh (PII), tiến độ học tập và dữ liệu hành vi của trẻ em/học sinh. |
| Nếu sai, hậu quả có khó đảo ngược lại không | Medium | Kiến thức sai lệch có thể gây hiểu lầm kéo dài nếu không được điều chỉnh kịp thời qua feedback. |
| Nếu triển khai rộng, blast radius có lớn không | High | Lỗi logic hoặc kiến thức sai sẽ ảnh hưởng đồng loạt đến trải nghiệm của toàn bộ học viên. |
| Có cần human review hay escalation không | High | Cần giám sát để đảm bảo nội dung phù hợp lứa tuổi và kiến thức sư phạm chuẩn xác. |
| **Risk profile tổng thể** | **High** | Sự kết hợp giữa dữ liệu nhạy cảm của học sinh và tầm quan trọng của tính chính xác trong giáo dục. |

# 2. Case Studies - Education Sector

### Case Study 1: Trợ giảng AI Jill Watson (Georgia Tech)

| Field | Nội dung |
| :--- | :--- |
| **Tên case** | Jill Watson (Georgia Tech) |
| **Ngành** | Giáo dục |
| **Tổ chức / sản phẩm** | Đại học Georgia Tech |
| **Use case AI** | Trợ giảng ảo giải đáp thắc mắc cho sinh viên |
| **Thời điểm** | 2016 |
| **Case xảy ra chuyện gì?** | Hệ thống AI được tích hợp vào diễn đàn lớp học trực tuyến để tự động phản hồi các câu hỏi của sinh viên. Jill Watson hoạt động 24/7 và đạt hiệu suất cao như trợ giảng con người. |
| **Stakeholder bị ảnh hưởng** | Sinh viên và giảng viên |
| **Số liệu chính** | Đạt tỷ lệ chính xác từ 75% đến 97% |
| **Trích nguồn ngắn** | Hệ thống Jill Watson đã chứng minh khả năng hỗ trợ đắc lực trong môi trường đại học với độ chính xác cao. |
| **Nguồn 1** | Georgia Tech Research, 2024, https://research.gatech.edu/georgia-techs-jill-watson-outperforms-chatgpt-real-classrooms |
| **Nguồn 2** | arXiv Paper, 2024, https://arxiv.org/html/2405.11070v1 |
| **Ghi chú độ tin cậy** | Primary (nguồn chính từ tổ chức nghiên cứu) |
---

### Case Study 2: Hệ thống cảnh báo sớm (Ivy Tech Community College)

| Field | Nội dung |
| :--- | :--- |
| **Tên case** | Project Early Success |
| **Ngành** | Giáo dục |
| **Tổ chức / sản phẩm** | Ivy Tech Community College |
| **Use case AI** | Phân tích dự báo để hỗ trợ sinh viên |
| **Thời điểm** | 2017 |
| **Case xảy ra chuyện gì?** | Trường triển khai hệ thống phân tích dữ liệu để phát hiện sớm các sinh viên có nguy cơ trượt môn. Giảng viên nhận được cảnh báo để can thiệp kịp thời ngay từ đầu học kỳ. |
| **Stakeholder bị ảnh hưởng** | Sinh viên và đội ngũ nhân sự nhà trường |
| **Số liệu chính** | Giúp 3.000 sinh viên cải thiện kết quả học tập trong một kỳ |
| **Trích nguồn ngắn** | Việc ứng dụng phân tích dự báo đã giúp cải thiện đáng kể tỷ lệ thành công của sinh viên. |
| **Nguồn** | SiliconANGLE, 2017, https://siliconangle.com/2017/11/10/ivy-tech-community-college-uses-predictive-analytics-improves-student-grades-pworld17/ |
| **Ghi chú độ tin cậy** | Primary (báo cáo trường hợp thực tế từ tổ chức) |

# 3. Harm Map Worksheet

### Harm Map Worksheet: Case Study 1 - Trợ giảng AI Jill Watson (Georgia Tech)

| High-risk moment | Stakeholder | Failure mode | Layer | Harm lens | Severity | Scale | Probability | Frequency | Vì sao? |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Khi AI trả lời sai câu hỏi chuyên môn của sinh viên | Sinh viên | Hallucination | Model | Misinformation | Medium | Medium | Medium | Medium | AI có thể đưa ra thông tin sai lệch dẫn đến hiểu lầm kiến thức, dù có thể sửa chữa sau đó. |

---

### Harm Map Worksheet: Case Study 2 - Hệ thống cảnh báo sớm (Ivy Tech)

| High-risk moment | Stakeholder | Failure mode | Layer | Harm lens | Severity | Scale | Probability | Frequency | Vì sao? |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| AI dự đoán sai, bỏ lỡ sinh viên cần hỗ trợ | Sinh viên | Bias / fairness | Grounding | Opportunity loss | High | Medium | Medium | Low | Nếu dự đoán sai, sinh viên có nguy cơ bị trượt môn do không được can thiệp kịp thời, mất cơ hội học tập. |

# 4. So sánh Risk Profile

| Ngành | Harm dễ gặp nhất | Failure mode hay lặp lại | Layer hay bắt đầu lỗi | Risk profile | Vì sao |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **HR/Tuyển dụng** | Thiên kiến (Bias) & Loại bỏ sai lệch | Đánh giá sai tiềm năng ứng viên | Dữ liệu đầu vào (Training data) | Trung bình | Ảnh hưởng cơ hội nghề nghiệp, rủi ro pháp lý về phân biệt đối xử. |
| **Giáo dục/AI Tutor** | Thông tin sai lệch (Hallucination) | Dạy kiến thức sai hoặc gây hiểu lầm | Logic suy luận (Reasoning) | Trung bình - Thấp | Ảnh hưởng nhận thức, nhưng có thể kiểm chứng qua tài liệu. |
| **Y tế/Symptom Checker/Health Assistance** | Chẩn đoán sai (Missed/False diagnosis) | Đánh giá sai mức độ nghiêm trọng (Triage error) | Retrieval (RAG) / Phân tích dữ liệu | Rất cao | Rủi ro trực tiếp đến tính mạng và sức khỏe con người. |
| **Mobility/Autonomous** | Va chạm vật lý (Collision) | Mất kiểm soát trong tình huống bất ngờ | Cảm biến/Điều khiển thời gian thực | Tối cao | Sai sót dẫn đến thiệt hại hữu hình, tử vong và trách nhiệm pháp lý và hình sự. |
| **Media/News/Social/Political Assistance** | Thao túng thông tin (Misinformation) | Echo chamber & Lan truyền tin giả | Alignment (Dàn hàng ý thức hệ) | Cao | Ảnh hưởng dư luận, niềm tin công chúng và an ninh, chính trị. |
| **Content Creator** | Vi phạm bản quyền/Giảm tương tác | Nội dung "nhạt" hoặc lặp lại (Homogenization) | Creative Generation | Thấp | Chủ yếu rủi ro chất lượng sản phẩm và thương hiệu cá nhân bị ảnh hưởng. |