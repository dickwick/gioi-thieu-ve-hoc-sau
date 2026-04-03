Công nghệ sử dụng

Python, Pandas, Numpy, Scikit-learn, PyTorch, Matplotlib
Dataset: pollution.csv
Feature sử dụng: pm2.5, DEWP, TEMP

Phần 1 – Tiền xử lý dữ liệu

Chuẩn hóa dữ liệu về [0,1] bằng MinMaxScaler.
Tạo chuỗi thời gian với seq_length = 20.
Chia dữ liệu:

70% train
15% validation
15% test

Mục đích: tạo dữ liệu phù hợp cho RNN.

Phần 2 – Mô hình RNN

Xây dựng RNN với:

input_size = 3
hidden_size = 32
output_size = 1

Dùng MSELoss và Adam, huấn luyện 150 epochs.
Theo dõi train loss và validation loss.

Phần 3 – Đánh giá

Dự đoán trên tập test và tính:

MSE
MAE

Vẽ biểu đồ so sánh giá trị thực và dự đoán.

Phần 4 – Nâng cao

Thử thay đổi:

seq_length
hidden_size
epochs

So sánh MSE để chọn mô hình tốt nhất và vẽ biểu đồ lỗi.