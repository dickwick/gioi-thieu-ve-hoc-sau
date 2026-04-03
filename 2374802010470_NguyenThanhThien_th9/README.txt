Bài 1 – Dự đoán chuỗi thời gian bằng LSTM
Công nghệ sử dụng
Python
TensorFlow / Keras
LSTM
NumPy
Matplotlib
Scikit-learn (MinMaxScaler)
Cách hoạt động
Dữ liệu chuỗi thời gian được chuẩn hóa và chia thành train/test.
Dùng sliding window để tạo:
X: các giá trị trước đó
y: giá trị tiếp theo
Mô hình LSTM học quy luật theo thời gian và dự đoán giá trị mới.
Kết quả được so sánh bằng biểu đồ.


Bài 2 – Dự đoán từ tiếp theo bằng LSTM
Công nghệ sử dụng
Python
TensorFlow / Keras
LSTM
HuggingFace Dataset (Wikipedia tiếng Việt)
NumPy
Gradio
Pickle
Cách hoạt động
Văn bản tiếng Việt được xử lý và chuyển thành số bằng Tokenizer.
Tạo dữ liệu:
X: các từ trước
y: từ tiếp theo
Mô hình LSTM học mối quan hệ giữa các từ.
Người dùng nhập câu trên web, hệ thống dự đoán từ tiếp theo.