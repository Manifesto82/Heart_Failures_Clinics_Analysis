# Heart Failures Clinics Data Analysis Project

# Mục tiêu
Mục tiêu của dự án là xây dựng một mô hình dự đoán tỷ lệ tử vong do suy tim dựa trên các thông tin lâm sàng và các yếu tố liên quan. Dự án sử dụng bộ dữ liệu chứa thông tin về bệnh nhân suy tim, bao gồm các thuộc tính lâm sàng và biến mục tiêu DEATH_EVENT (bệnh nhân có tử vong trong thời gian quan sát hay không).

# Dữ liệu
Bộ dữ liệu: Chứa các thông tin lâm sàng về bệnh nhân suy tim, bao gồm các thuộc tính như age, anaemia, creatinine_phosphokinase, diabetes, ejection_fraction, high_blood_pressure, platelets, serum_creatinine, serum_sodium, sex, smoking, time, và DEATH_EVENT.

Biến mục tiêu: DEATH_EVENT (1: Bệnh nhân tử vong, 0: Bệnh nhân không tử vong).

# Tiền xử lý dữ liệu

Dữ liệu được đọc từ file CSV và kiểm tra các giá trị đặc biệt, trùng lặp.

Các bước tiền xử lý bao gồm:

Kiểm tra và xóa các giá trị trùng lặp.

Đếm số lượng giá trị riêng biệt trong từng cột.

Dữ liệu đã ở dạng số hóa nên không cần thêm bước chuyển đổi.

# Các thuật toán sử dụng

Logistic Regression:

Chia dữ liệu thành tập huấn luyện (70%) và tập kiểm tra (30%).

Huấn luyện mô hình và tính toán độ chính xác (accuracy).

Sử dụng Confusion Matrix và Classification Report để đánh giá hiệu suất mô hình.

Support Vector Machine (SVM):

Sử dụng kernel tuyến tính và các tham số C=10, Gamma=1.

Huấn luyện mô hình và tính toán độ chính xác.

Đánh giá mô hình thông qua Confusion Matrix và Classification Report.
