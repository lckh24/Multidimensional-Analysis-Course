*Chi tiết: stress_analysis.html*
# Stress Analysis

Phân tích căng thẳng và sức khỏe tâm thần của 1100 học sinh qua 21 yếu tố (lo âu, trầm cảm, giấc ngủ, áp lực học tập, v.v.) từ StressLevelDataset.csv.

## Tổng quan
- Khanh Le  
- **Ngày:** 17/06/2024  
- **Mục tiêu:** Xác định yếu tố chính ảnh hưởng đến căng thẳng và đề xuất cải thiện.

## Phương pháp
- **EDA:** Histogram, boxplot, scatter 3D.  
- **Tương quan:** Căng thẳng liên quan mạnh đến trầm cảm (0.73), lo âu (0.74), giấc ngủ (-0.75).  
- **PCA:** 4 thành phần (72.3% phương sai).  
- **EFA:** 3 nhân tố chính (KMO = 0.97).  
- **Thống kê:** MANOVA/ANOVA (p < 0.05).

## Kết quả chính
- **Tiền sử sức khỏe tâm thần:** Học sinh có tiền sử tâm thần có mức lo âu (~13), trầm cảm (~15), và căng thẳng (~1.5) cao hơn nhóm không có tiền sử (~9, ~10, ~0.5).  
- **Yếu tố sinh lý:**  
  - 50% (550/1100) báo cáo giấc ngủ kém (điểm ≤ 2/5).  
  - 50.5% (556/1100) thường xuyên đau đầu (điểm ≥ 3/5).  
  - Huyết áp trung bình: 2.18/3, nghiêng về mức cao.  
- **Yếu tố môi trường:**  
  - 25% (274/1100) sống trong môi trường tiếng ồn cao (điểm ≥ 4/5).  
  - 16.7% (184/1100) cảm thấy không an toàn (điểm = 1/5).  
  - 49.8% (548/1100) chưa đáp ứng nhu cầu cơ bản (điểm ≤ 2/5).  
- **Yếu tố học tập:**  
  - 51% (561/1100) có thành tích dưới trung bình (điểm ≤ 2/5).  
  - Khối lượng học trung bình: 2.62/5, vừa phải.  
  - 33.7% (371/1100) lo ngại tương lai nghề nghiệp (điểm ≥ 4/5).  
- **Yếu tố xã hội:**  
  - 96.45% (1061/1100) từng bị bắt nạt (điểm ≥ 1/5).  
  - 41.6% (458/1100) có hỗ trợ xã hội mạnh (điểm ≥ 3/3).  
  - 96.9% (1066/1100) tham gia ngoại khóa (điểm ≥ 1/5).  

## Đề xuất
Dựa trên kết quả, các giải pháp cụ thể để giảm căng thẳng bao gồm:  
- **Cải thiện môi trường học tập:**  
  - Giảm tiếng ồn bằng cách lắp đặt vật liệu cách âm tại lớp học hoặc khu ký túc xá (25% học sinh bị ảnh hưởng).  
  - Tăng cường an ninh trường học (hỗ trợ 16.7% học sinh cảm thấy không an toàn) qua camera giám sát hoặc nhân viên bảo vệ.  
- **Hỗ trợ sức khỏe tâm thần:**  
  - Triển khai chương trình tư vấn tâm lý miễn phí cho học sinh có tiền sử tâm thần (mức căng thẳng cao hơn ~1.5 điểm).  
  - Tổ chức workshop về quản lý lo âu và trầm cảm, nhắm đến 33.7% học sinh lo lắng về tương lai.  
- **Chăm sóc giấc ngủ:**  
  - Xây dựng lịch học linh hoạt, giảm bài tập về nhà để cải thiện giấc ngủ cho 50% học sinh ngủ kém.  
  - Cung cấp hướng dẫn về vệ sinh giấc ngủ (sleep hygiene) như hạn chế thiết bị điện tử trước giờ ngủ.  
- **Giảm áp lực xã hội:**  
  - Phát động chiến dịch chống bắt nạt (96.45% học sinh bị ảnh hưởng) với các buổi hội thảo và quy tắc xử phạt rõ ràng.  
  - Tăng cường câu lạc bộ ngoại khóa và mạng lưới hỗ trợ bạn bè để củng cố hỗ trợ xã hội (41.6% hiện có).  

## Kết luận
* Phân tích cho thấy căng thẳng ở học sinh không chỉ xuất phát từ áp lực học tập mà còn từ các yếu tố sinh lý (giấc ngủ, đau đầu), môi trường (tiếng ồn, an toàn), và xã hội (bắt nạt). Mối quan hệ chặt chẽ giữa căng thẳng với lo âu (0.74) và trầm cảm (0.73) nhấn mạnh tầm quan trọng của can thiệp sớm. Việc áp dụng các đề xuất trên không chỉ giảm căng thẳng mà còn nâng cao chất lượng cuộc sống và thành tích học tập. Nghiên cứu này cung cấp cơ sở dữ liệu để các nhà giáo dục và phụ huynh hành động, đặc biệt với nhóm học sinh có tiền sử tâm thần.
---
