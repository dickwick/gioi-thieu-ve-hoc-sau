BTVN 1:
Sử dụng torch.tensor với requires_grad=True
PyTorch dùng cơ chế autograd để tự động tính đạo hàm của đa thức
KQ: Giá trị y: 363.0
Độ dốc dy/dx tại x=2: 1029.0

BTVN 2:
Áp dụng thuật toán Gradient Descent
Tính gradient bằng backward()
Cập nhật biến x theo learning rate đã cho
KQ: Vòng 1: x = -0.5
Vòng 2: x = -0.875
Vòng 3: x = -1.2546875476837158
Vòng 4: x = -1.7250847816467285
Vòng 5: x = -2.427826166152954
Vòng 6: x = -3.7249975204467773
Vòng 7: x = -6.897680282592773
Vòng 8: x = -18.912006378173828
Vòng 9: x = -119.14640808105469
Vòng 10: x = -4330.74755859375

BTVN 3:
Mô phỏng bài toán hồi quy tuyến tính y = wx + b
Sử dụng hàm mất mát MSE
Cập nhật tham số w và b bằng Gradient Descent qua nhiều vòng lặp
KQ: w = 3.4626882076263428 b = 1.4249447584152222

BTVN 4:
Trường hợp 1: dùng torch.tensor(arr)
torch.tensor() sẽ tạo ra một tensor mới
Tensor này ko dùng chung bộ nhớ với mảng NumPy ban đầu
Trường hợp 2: dùng torch.from_numpy(arr)
torch.from_numpy() tạo tensor dùng chung bộ nhớ với mảng NumPy

BTVN 5:
Tạo tensor bằng empty, zeros, ones, rand
Thay đổi shape tensor bằng view() và view_as()
KQ: tensor([[0., 0.],
        [0., 0.]]) tensor([[0., 0.],
        [0., 0.]]) tensor([[1., 1.],
        [1., 1.]]) tensor([[0.6052, 0.7008],
        [0.5236, 0.0931]]) tensor([[0, 1, 2],
        [3, 4, 5]]) tensor([[0, 1, 2],
        [3, 4, 5]])