# Insurance Data, EDA and Statistics

> Language: Tiếng Việt 🇻🇳 \
> Dataset: [Link](https://www.kaggle.com/datasets/timka01/insurance-csv) 

**Mục tiêu:**  
Phân tích bộ dữ liệu chi phí bảo hiểm để xác định các yếu tố ảnh hưởng chính và xây dựng mô hình hồi quy dự đoán chi phí y tế.

**Các bước thực hiện:**  
- Tiền xử lý dữ liệu (**data cleaning**): xử lý giá trị thiếu, mã hóa biến phân loại, kiểm tra ngoại lệ.  
- Thực hiện **phân tích khám phá dữ liệu (EDA)**: trực quan hóa phân phối, mối tương quan và quan hệ giữa các biến.  
- Áp dụng **hồi quy tuyến tính** và **hồi quy có điều chuẩn** (Ridge, Lasso) để xử lý đa cộng tuyến.  
- Sử dụng **K-Fold cross-validation** để đánh giá độ ổn định của mô hình.  

**Kết quả:**  
- Hiệu năng ổn định với **Train R² = 0.608**, **Test R² = 0.605**.  
- Xác định **tình trạng hút thuốc, tuổi và BMI** là các yếu tố ảnh hưởng mạnh nhất đến chi phí y tế.  
- Đề xuất mở rộng bằng **mô hình ML phi tuyến** hoặc **hồi quy có trọng số** để cải thiện kết quả.  

**Công cụ sử dụng:** Python (pandas, scikit-learn, matplotlib, seaborn), Thống kê (Hồi quy, Cross-validation).


