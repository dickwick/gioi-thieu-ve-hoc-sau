Bài 1:
- Đọc file howlongwelive.csv vào DataFrame
- Hiển thị dữ liệu đầu và cuối
- Kiểm tra shape, cột, thống kê
- Xóa cột Hepatitis B và Population
- Chuyển Status sang dạng số
- Đổi tên cột thinness
- Tách X và y sang NumPy
KQ: ((2938, 19), (2938,))

Bài 2:
- Kiểm tra dữ liệu thiếu
- Điền NaN bằng mean
- Groupby theo Country để tìm tuổi thọ cao nhất và thấp nhất
- Groupby theo Status để so sánh Developed và Developing
- Tạo DataFrame Noise_level
- Merge dữ liệu theo Country
KQ: 
Country	Year	Status	Life expectancy	Adult Mortality	infant deaths	Alcohol	percentage expenditure	Measles	BMI	...	Total expenditure	Diphtheria	HIV/AIDS	GDP	thinness 1-19 years	thinness 5-9 years	Income composition of resources	Schooling	ID	Noise_level
0	Afghanistan	2015	0	65.0	263.0	62	0.01	71.279624	1154	19.1	...	8.16	65.0	0.1	584.25921	17.2	17.3	0.479	10.1	Afghanistan	0.550096
1	Afghanistan	2015	0	65.0	263.0	62	0.01	71.279624	1154	19.1	...	8.16	65.0	0.1	584.25921	17.2	17.3	0.479	10.1	Afghanistan	0.888925
2	Afghanistan	2015	0	65.0	263.0	62	0.01	71.279624	1154	19.1	...	8.16	65.0	0.1	584.25921	17.2	17.3	0.479	10.1	Afghanistan	0.375118
3	Afghanistan	2015	0	65.0	263.0	62	0.01	71.279624	1154	19.1	...	8.16	65.0	0.1	584.25921	17.2	17.3	0.479	10.1	Afghanistan	0.547983
4	Afghanistan	2015	0	65.0	263.0	62	0.01	71.279624	1154	19.1	...	8.16	65.0	0.1	584.25921	17.2	17.3	0.479	10.1	Afghanistan	0.043724 
5 rows × 22 columns
