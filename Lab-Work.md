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

| Tiêu chí | Nội dung chi tiết |
| :--- | :--- |
| **AI được dùng để làm gì?** | Tự động hóa việc giải đáp các câu hỏi thường gặp của sinh viên trong khóa học trực tuyến. |
| **Chuyện gì đã xảy ra?** | Triển khai hệ thống AI làm trợ giảng cho lớp học 300 sinh viên, hoạt động 24/7. |
| **Ai bị ảnh hưởng?** | Sinh viên và giảng viên đại học. |
| **Số liệu** | Hệ thống đạt tỷ lệ chính xác 97%, xử lý 10.000 câu hỏi mỗi học kỳ. |
| **Đủ dữ kiện để điền worksheet?** | Có, đây là mô hình thành công về tối ưu hóa vận hành. |
| **Nguồn uy tín** | [Georgia Tech Research](https://research.gatech.edu/georgia-techs-jill-watson-outperforms-chatgpt-real-classrooms); [arXiv Paper](https://arxiv.org/html/2405.11070v1). |

---

### Case Study 2: Hệ thống cảnh báo sớm (Ivy Tech Community College)

| Tiêu chí | Nội dung chi tiết |
| :--- | :--- |
| **AI được dùng để làm gì?** | Sử dụng phân tích dự báo (Predictive Analytics) để xác định sớm sinh viên có nguy cơ trượt môn (mức điểm D) hoặc bỏ học. |
| **Chuyện gì đã xảy ra?** | Nhà trường thực hiện can thiệp nhắm mục tiêu dựa trên các cảnh báo từ AI trong 2 tuần đầu học kỳ. |
| **Ai bị ảnh hưởng?** | Sinh viên có nguy cơ bỏ học hoặc trượt môn. |
| **Số liệu** | 98% sinh viên được can thiệp cải thiện điểm số lên mức C trở lên; giúp ngăn chặn 3.000 sinh viên trượt môn trong một kỳ. |
| **Đủ dữ kiện để điền worksheet?** | Có, đây là ví dụ mạnh nhất về tác động thực tế tới kết quả học tập của sinh viên. |
| **Nguồn uy tín** | [SiliconANGLE - Ivy Tech Community College Case Study](https://siliconangle.com/2017/11/10/ivy-tech-community-college-uses-predictive-analytics-improves-student-grades-pworld17/). |

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


