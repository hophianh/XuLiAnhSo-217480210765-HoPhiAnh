# 1. Biến Đổi Cường Độ Ảnh và Hình Học Trong Xử Lý Ảnh Số


## 1. Chọn Đối Tượng Trong Ảnh

Thực hiện cắt vùng quan tâm từ ảnh gốc, giúp tập trung vào khu vực cần xử lý.

![ketqua](orange.jpg)

## 2. Tịnh Tiến Đơn

Dịch chuyển ảnh theo hướng xuống 100 pixel và sang phải 25 pixel.
![ketqua]({8E462763-6C2E-4F3F-8328-899DD5CD49AD}.png)

## 3. Thay Đổi Kích Thước Ảnh

Phóng to và thu nhỏ ảnh theo các tỷ lệ khác nhau để kiểm tra khả năng co giãn của ảnh.

![ketqua]({72F4E177-B67D-4416-91FC-ACE5674E68A1}.png)


## 4. Xoay Ảnh

Xoay ảnh một góc 20 độ với hai chế độ: 
- Có thay đổi kích thước khung chứa (`reshape=True`)
- Giữ nguyên kích thước khung (`reshape=False`)

![ketqua]({A2DE677F-7E12-487C-B175-40AE241C0005}.png)


## 5. Dilation và Erosion

Áp dụng phép **giãn ảnh (dilation)** để làm dày thêm các vùng sáng (trắng) trong ảnh nhị phân.

![ketqua]({7A15F205-F6F7-4B4A-AE31-D5FAA35E7929}.png)


