# 🎓 VinUniversity AI Talent Program — Track 1: AI Product Management
## Day 24: AI Product Financial Model & Unit Economics Lab!

### THÔNG TIN HỌC VIÊN
* **Họ và tên:** Trương Ái Linh
* **MSSV:** 2A202601496
* **Tên dự án:** StudyPilot (AI Study Planning Assistant)

---

### 📝 DECISION NOTE (BẢO VỆ MÔ HÌNH TÀI CHÍNH)

**1. Căn cứ chọn ARPU và CAC:**
StudyPilot hướng tới phân khúc sinh viên đại học Việt Nam. ARPU được đặt ở mức 99,000 VND/tháng (Base) - tương đương ~$4, dựa trên willingness-to-pay thực tế của sinh viên cho các công cụ học tập như Quizlet Plus, Duolingo Super hay Notion AI. 
Mức CAC 120,000 VND (Base) là khả thi vì mô hình tăng trưởng dựa nhiều vào Product-Led Growth, viral loops trong campus (chia sẻ lịch học, referral), và marketing vào các group học tập tập trung thay vì chạy ads diện rộng.

**2. Giải trình AI Hidden Costs:**
AI Hidden Costs được thiết lập ở mức 4,000 VND (tương đương 57% API Cost). Đây là con số bắt buộc để hệ thống sống sót, bao gồm:
- **Data Labeling & Prompt Tuning:** Liên tục cập nhật template đề cương môn học mới.
- **Human QA:** Kiểm tra ngẫu nhiên các study session để đảm bảo AI không chia nhỏ sai khối lượng (hallucination).
- **Model Retraining:** Phân tích dữ liệu học tập thực tế để cải thiện thuật toán gợi ý thời gian học.

**3. Kịch bản Pessimistic & Plan B:**
Trong kịch bản Pessimistic, khi Churn Rate tăng lên 12% (1.5x Base) và CAC đội lên 200,000 VND do cạnh tranh, LTV/CAC giảm xuống 2.5 (Watch) nhưng Runway vẫn đảm bảo >= 24 tháng nhờ việc chuẩn bị Initial Cash dồi dào (900M VND) và tối ưu Fixed Cost (giữ team tinh gọn). Plan B nếu gặp cú sốc tài chính là cắt giảm server phụ, giảm tần suất gọi API (caching plan), và tập trung retention khách hàng hiện tại thay vì scale nóng.
