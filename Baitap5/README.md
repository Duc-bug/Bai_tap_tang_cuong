# Bài 5:
Tạo một chương trình menu tương tác cho phép người dùng chọn các phép biến đổi sau:
Tịnh tiến (hỏi số pixel di chuyển theo x và y).
Xoay (hỏi góc xoay và chọn reshape=True/False).
Phóng to/thu nhỏ (hỏi hệ số zoom).
Làm mờ Gaussian (hỏi giá trị sigma).
Biến đổi sóng (hỏi biên độ sóng).
Người dùng chọn ảnh từ 3 ảnh bất kì

## Mô tả

Chương trình cho phép người dùng chọn một trong ba ảnh mẫu và thực hiện các phép biến đổi ảnh cơ bản thông qua menu tương tác.

## Các chức năng biến đổi

1. **Tịnh tiến**: Dịch chuyển ảnh theo trục x và y với số pixel do người dùng nhập.
2. **Xoay**: Xoay ảnh một góc bất kỳ, có thể chọn giữ nguyên kích thước ảnh hoặc không.
3. **Phóng to/thu nhỏ**: Thay đổi kích thước ảnh theo hệ số zoom do người dùng nhập.
4. **Làm mờ Gaussian**: Làm mờ ảnh với giá trị sigma do người dùng nhập.
5. **Biến đổi sóng**: Áp dụng hiệu ứng sóng lên ảnh với biên độ sóng do người dùng nhập.

## Hướng dẫn sử dụng

1. Đặt các file ảnh mẫu (`messi.jpg`, `rua.jpg`, `ro.webp`) vào cùng thư mục với file notebook.
2. Chạy file notebook `bai5.ipynb`.
3. Chọn ảnh và phép biến đổi theo hướng dẫn trên màn hình.
4. Ảnh kết quả sẽ được hiển thị sau mỗi phép biến đổi.

## Thư viện sử dụng

- numpy
- matplotlib
- imageio
- scipy.ndimage

## Ghi chú

- Chương trình chạy lặp cho đến khi chọn "0. Thoát".
- Có thể áp dụng nhiều phép biến đổi liên tiếp trên cùng một ảnh.