# Bài 2: Ghép Đu Đủ và Dưa Hấu với Gradient Màu

## Yêu cầu
- Chọn ảnh quả đu đủ và dưa hấu từ Google.
- Đổi màu đu đủ thành gradient từ đỏ sang xanh lá.
- Đổi màu dưa hấu thành gradient từ vàng sang tím.
- Ghép hai quả lên một nền trong suốt (alpha channel) và lưu dưới dạng PNG (`fruit_combo.png`).

## Hướng dẫn thực hiện

1. Đặt hai file ảnh `du du.jpg` (đu đủ) và `dua hau.jpg` (dưa hấu) vào cùng thư mục với notebook.
2. Chạy file notebook `bai2.ipynb`.
3. Kết quả sẽ tạo ra file `fruit_combo.png` với hai quả trên nền trong suốt.

## Thư viện sử dụng
- numpy
- matplotlib
- imageio

## Kết quả
- Ảnh đu đủ được đổi màu theo gradient đỏ → xanh lá.
- Ảnh dưa hấu được đổi màu theo gradient vàng → tím.
- Hai quả được ghép cạnh nhau trên nền trong suốt, có thể xem trực tiếp trong notebook hoặc mở file PNG kết quả.

## Hiển thị kết quả
Notebook sẽ hiển thị:
- Ảnh đu đủ gradient
- Ảnh dưa hấu gradient
- Ảnh ghép hai quả trên nền trong suốt