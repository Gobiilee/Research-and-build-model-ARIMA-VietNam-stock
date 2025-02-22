# Trực quan bằng mô hình ARIMA

## 1. Tạo mô hình ARIMA tự động
- Mô hình ARIMA được tạo tự động để dự đoán dữ liệu.
- Các tham số của mô hình được tinh chỉnh dựa trên tiêu chí thông tin **AIC** (Akaike Information Criterion), một phương pháp phổ biến để đánh giá mức độ phù hợp của mô hình thống kê.
- Mục tiêu: Chọn mô hình có **AIC thấp nhất**, cho biết mức độ phù hợp tốt nhất với dữ liệu.
- Kết quả: Mô hình tốt nhất là **ARIMA(2,0,1)** với chỉ số AIC là **1205.343**.

## 2. Dự đoán giá cổ phiếu
- Sử dụng mô hình ARIMA(2,0,1) để dự đoán giá cổ phiếu trong **50 ngày tiếp theo**.
- Dữ liệu được lấy từ giá cổ phiếu **ACB** của Ngân hàng thương mại cổ phần Á Châu.
- Tập dữ liệu:
  - **Tập huấn luyện:** 1560 mẫu.
  - **Tập kiểm tra:** 15 mẫu.

## 3. Trực quan hóa kết quả
- Dự đoán giá trị cho 50 ngày tiếp theo và tính toán khoảng tin cậy.
- Tạo chuỗi dữ liệu thời gian cho các dự đoán, kết hợp với khoảng tin cậy.
- Trực quan hóa dữ liệu thực tế và dự đoán trên biểu đồ:
  - Khoảng tin cậy được đánh dấu bằng màu xám để biểu thị sự không chắc chắn trong dự đoán.

## 4. Kết quả dự đoán
- Giá cổ phiếu ACB trong dự đoán không có biến động lớn, thường cố định ở mức **25 nghìn đồng**.
- Điều này cho thấy sự ổn định về giá cổ phiếu của ngân hàng này.

## Hình ảnh minh họa
1. **Hình 5.1:** Kết quả của mô hình ARIMA(2,0,1).
2. **Hình 5.2:** Lựa chọn tập dữ liệu huấn luyện và kiểm tra.
3. **Hình 5.3:** Biểu đồ dự đoán giá cổ phiếu SAB.
4. **Hình 5.4:** Giá cổ phiếu SAB được dự đoán.
