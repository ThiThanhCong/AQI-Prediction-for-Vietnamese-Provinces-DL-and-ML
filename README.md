# Dự Báo Mức Độ Ô Nhiễm Không Khí Tại Các Thành Phố Ở Việt Nam: Phương Pháp Học Máy và Học Sâu

## Thành Viên Nhóm

1. **Cao Hoài Sang**  
   _Hệ Thống Thông Tin, TP. Hồ Chí Minh, Việt Nam_  
   [21522541@gm.uit.edu.vn](mailto:21522541@gm.uit.edu.vn)

2. **Nguyen Tran Gia Kiet**  
   _Hệ thống thông tin, TP. Hồ Chí Minh, Việt Nam_  
   [21522258@gm.uit.edu.vn](mailto:21522258@gm.uit.edu.vn)

3. **Thi Thành Công**  
   _Hệ Thống Thông Tin, TP. Hồ Chí Minh, Việt Nam_    
   [21521897@gm.uit.edu.vn](mailto:21521897@gm.uit.edu.vn)

4. **Nguyễn Hoàng Đăng Khoa**  
   _Hệ thống thông tin, TP. Hồ Chí Minh, Việt Nam_  
   [21520999@gm.uit.edu.vn](mailto:21520999@gm.uit.edu.vn)

5. **Cù Ngọc Hoàng**  
   _Hệ thống thông tin, TP. Hồ Chí Minh, Việt Nam_  
   [21522086@gm.uit.edu.vn](mailto:21522086@gm.uit.edu.vn)
   
## Tóm tắt
Nghiên cứu này nhằm dự đoán chất lượng không khí tại ba thành phố Hà Nội, Việt Trì, và Đà Nẵng bằng cách kết hợp các thuật toán học máy và học sâu. Các mô hình bao gồm Gauss Newton Method Non-Linear, Residual Convolutional Neural Networks (ResCNN), Neural Hierarchical Interpolation for Time Series Forecasting (N-HiTS), Dynamic Linear Model (DLM), Simple Exponential Smoothing (SES), Linear Regression (LR), Autoregressive Integrated Moving Average (ARIMA), Recurrent Neural Network (RNN), Gated Recurrent Unit (GRU), và Long Short Term Memory (LSTM). Hiệu quả của các mô hình được đo lường bằng Mean Absolute Percentage Error (MAPE) và Root Mean Squared Error để đạt độ chính xác cao nhất trong dự báo chất lượng không khí.

## Giới thiệu
Với sự gia tăng dân số và công nghiệp hóa tại Việt Nam, vấn đề chất lượng không khí trở thành mối quan tâm chính. Nghiên cứu này nhằm dự đoán mức độ chất lượng không khí để hỗ trợ các chiến lược giảm thiểu và can thiệp y tế công cộng. Sử dụng các mô hình học máy và học sâu, nghiên cứu này tận dụng các thuật toán như Gauss Newton Method Non-Linear và Resilient Convolutional Neural Networks (ResCNN) để dự đoán chất lượng không khí.

- Gauss Newton Method Non-Linear
- Residual Convolutional Neural Networks (ResCNN)
- Neural Hierarchical Interpolation for Time Series Forecasting (N-HiTS)
- Dynamic Linear Model (DLM)
- Simple Exponential Smoothing (SES)
- Linear Regression (LR)
- Autoregressive Integrated Moving Average (ARIMA)
- Recurrent Neural Network (RNN)
- Gated Recurrent Unit (GRU)
- Long Short Term Memory (LSTM)

- 
## Dữ Liệu
Bộ dữ liệu được thu thập từ ba thành phố Hà Nội, Việt Trì và Đà Nẵng từ năm 2019 đến năm 2024, bao gồm các chỉ số PM2.5, PM10, O3, NO2, SO2 và CO.

## Thống Kê Mô Tả
Dữ liệu bao gồm các thông số như mean, standard deviation, min, max, và các percentiles cho ba thành phố.

## Kết Quả
Các mô hình được đánh giá dựa trên MAE, MAPE và RMSE. Kết quả cho thấy các mô hình học sâu như RNN và LSTM vượt trội hơn trong việc nắm bắt các phụ thuộc phi tuyến tính và phụ thuộc thời gian dài hạn trong dữ liệu chuỗi thời gian chất lượng không khí.

## Kết Luận
Nghiên cứu đã chỉ ra rằng việc sử dụng kết hợp các mô hình học máy và học sâu có thể cải thiện đáng kể độ chính xác trong dự báo chất lượng không khí. Các mô hình phức tạp như ResCNN và N-BEATS mang lại những lợi thế độc đáo trong việc xử lý các cấu trúc không gian và thứ bậc trong dữ liệu.


## Liên Hệ
- Cao Hoài Sang: 21522541@gm.uit.edu.vn
- Nguyễn Trần Gia Kiệt: 21522258@gm.uit.edu.vn
- Thi Thành Công: 21521897@gm.uit.edu.vn
- Nguyễn Hoàng Đăng Khoa: 21520999@gm.uit.edu.vn
- Cù Ngọc Hoàng: 21522086@gm.uit.edu.vn
