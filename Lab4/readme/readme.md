1. Biến Đổi Cường Độ Ảnh
1.1. Biến Đổi Âm Bản (Negative Transformation)
Thực hiện phép biến đổi âm bản để đảo ngược giá trị cường độ điểm ảnh, giúp làm nổi bật các vùng tối hoặc sáng trong ảnh.
![ketqua]({D23AF21D-2376-43D2-9021-F6BD53F86972}.png)

1.2. Thay Đổi Chất Lượng Ảnh với Power Law (Gamma Correction)
Sử dụng phép biến đổi gamma để điều chỉnh độ sáng ảnh.
Khi gamma > 1, ảnh tối hơn
Khi gamma < 1, ảnh sáng hơn
![ketqua]({00435E50-B015-4B3D-8DAE-750D043667EE}.png)

1.3. Thay Đổi Cường Độ Điểm Ảnh với Log Transformation
Biến đổi ảnh sử dụng hàm logarit giúp làm rõ các chi tiết trong vùng tối bằng cách nén các giá trị sáng.
![ketqua]({1A040CCD-4839-4E3D-A7CF-EAD4AAFAE220}.png)

1.4. Cân Bằng Lược Đồ Histogram (Histogram Equalization)
Tăng độ tương phản ảnh bằng cách phân bố đều cường độ điểm ảnh trong toàn ảnh.
![ketqua]({8B7023C5-CA15-4EE8-AF7B-2E389B2B6C52}.png)

1.5. Tăng Tương Phản với Contrast Stretching
Tăng độ tương phản bằng cách dàn trải giá trị cường độ điểm ảnh từ min-max về khoảng 0–255.
![ketqua]({74BB07FD-F7D0-46B3-9074-E7219B759125}.png)

2. Biến Đổi Ảnh Trong Miền Tần Số
2.1. Biến Đổi Fourier Nhanh (Fast Fourier Transform - FFT)
Chuyển ảnh sang miền tần số để quan sát các thành phần tần số không gian, phục vụ phân tích kết cấu ảnh.
![alt text]({D13E0436-D23D-4ADB-BF17-52F590644BCF}.png)

2.2. Lọc Ảnh với Butterworth Lowpass Filter
Giảm nhiễu và làm mịn ảnh bằng cách loại bỏ các thành phần tần số cao.
![ketqua]({7CD90B40-1291-46AC-A258-88E575067CC8}.png)

2.3. Làm Nét Ảnh với Butterworth Highpass Filter
Làm nổi bật các cạnh và chi tiết nhỏ trong ảnh bằng cách giữ lại các thành phần tần số cao.
![ketqua]({AB138210-43B0-455A-8120-69B288F2FA4D}.png)

3. Biến Đổi Kênh Màu RGB Kết Hợp Các Phép Biến Đổi Cường Độ (Từ Câu 1)
Đổi thứ tự các kênh màu RGB một cách ngẫu nhiên, sau đó áp dụng ngẫu nhiên một trong các phép biến đổi: Negative, Gamma, Log, Histogram Equalization, hoặc Contrast Stretching.
![ketqua]({12EF0058-9260-4232-98E3-44D6AEFA4A46}.png)

4. Biến Đổi Kênh Màu RGB Kết Hợp Các Phép Biến Đổi Tần Số (Từ Câu 2)
Đổi thứ tự các kênh RGB một cách ngẫu nhiên, sau đó áp dụng ngẫu nhiên một trong ba phép biến đổi: FFT, Butterworth Lowpass hoặc Butterworth Highpass Filter.
![ketqua]({4F07343D-05D2-402C-938D-192EEAFCC791}.png)