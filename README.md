# Inpainting-Images-Project
Bài làm phục vụ cho đồ án cuối kỳ của Nhập môn Thị giác máy tính (CTT451): Tìm hiểu và thực hiện một bài toán TGMT

Sinh viên thực hiện:
- Hồ Nhất Trí - 22120380
- Nguyễn Đình Chuẩn - 23120221

## Đường dẫn đến tập dữ liệu chính của đồ án:
Link: [Inpainting_dataset](https://www.kaggle.com/datasets/twean24/inpainting-dataset)

## Cây thư mục
```text
Inpainting-Images-Project
├───checkpoint      # Thư mục lưu trọng số mô hình
├───results         # Thư mục chứa ảnh đầu ra và biểu đồ
├───source          # Thư mục chứa mã nguồn chính
│      ├───inpainting-images.ipynb      # File huấn luyện mô hình
│      ├───prepare-data.ipynb           # File chuẩn bị dữ liệu
│      └───run_model.ipynb              # File thử nghiệm mô hình trên tập test, đo các chỉ số
│
├───data            # Thư mục chứa dữ liệu chính cho đồ án (Tải về thông qua link kaggle ở trên)
       ├───train_mask                   # Tập dữ liệu mặt nạ để train
       ├───tes_mask                     # Tập dữ liệu mặt nạ để test
       ├───train_dataset                # Tập dữu liệu hình ảnh để train
       └───test_dataset                 # Tập dữ liệu hình ảnh để test
│
└───README.md
```
