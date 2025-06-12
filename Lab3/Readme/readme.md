1.1 Biến Đổi Cường Độ Ảnh (Negative Transformation)
Thực hiện phép biến đổi âm bản để đảo ngược giá trị cường độ điểm ảnh, giúp làm nổi bật các vùng tối hoặc sáng trong ảnh.

Kết quả:![alt text]({2A8D5F4F-3D50-40F2-97A4-77573A551C26}.png)


1.2 Thay Đổi Chất Lượng Ảnh Với Power Law (Gamma Correction)
Sử dụng phép biến đổi gamma để điều chỉnh độ sáng ảnh. Khi gamma > 1, ảnh sẽ tối hơn; khi gamma < 1, ảnh sẽ sáng hơn.

Kết quả:![alt text]({24357CF9-9B71-4A22-BEC2-F7A7C491DCB9}.png)


1.3 Thay Đổi Cường Độ Điểm Ảnh Với Log Transformation
Biến đổi ảnh sử dụng hàm logarit giúp làm rõ các chi tiết trong vùng tối bằng cách nén các giá trị sáng.

Kết quả:![alt text]({E5FFA5AE-D476-41FC-85F9-0209B74C519E}.png)


1.4 Cân Bằng Lược Đồ Histogram (Histogram Equalization)
Tăng độ tương phản ảnh bằng cách phân bố đều cường độ điểm ảnh trong toàn ảnh, sử dụng kỹ thuật cân bằng histogram.

Kết quả:![alt text]({DD90177F-74AB-411E-B47D-7FA32E0D4A11}.png)


1.5 Thay Đổi Với Contrast Stretching
Tăng độ tương phản bằng cách dàn trải giá trị cường độ điểm ảnh từ min-max về 0–255.

Kết quả:![alt text]({FED98582-4845-4EBF-91A8-0CF1606FB094}.png)


1.6.1 Biến Đổi Fourier Nhanh (FFT)
Chuyển ảnh sang miền tần số để quan sát thành phần tần số không gian của ảnh.

Kết quả:![alt text]({A2121460-7E65-42AB-87EC-27C7FCAD88E4}.png)


1.6.2 Lọc Ảnh Trong Miền Tần Số
Butterworth Lowpass Filter
Giảm nhiễu và làm mịn ảnh bằng cách loại bỏ tần số cao.

Kết quả:![alt text]({2385113D-5A49-4316-9073-832BC1A4DF2A}.png)


Butterworth Highpass Filter
Làm nổi bật các cạnh và chi tiết nhỏ bằng cách giữ lại tần số cao.

Kết quả:![alt text]({7944C4BB-4E0C-4A1A-805D-B2C2A0B18DAD}.png)