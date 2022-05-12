# Nhận diện và phân loại biển báo giao thông 
## Giới thiệu
- Mục tiêu của dự án này là phát hiện và phân loại biển báo giao thông của Đức
- Đào tạo các mô hình phân loại: KNN, SVM, RF, CNN
- Bài toán phân loại 1 ảnh nhiều lớp
- Input: Một ảnh hoặc video chứa biển báo giao thông.
- Output: Nhận dạng và phân loại biển báo giao thông đó.

## Dataset 
Tập dữ liệu được sử dụng để đào tạo bộ phân loại biển báo giao thông là [Germen Traffic Sign Recognition Benchmark (GTSRB)](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign) 
  - Tập dữ liệu công khai tại Kaggle, được cập nhật bởi cộng đồng những người làm việc trong lĩnh vực ML, AI mỗi ngày và là một trong những thư viện tập dữ liệu trực tuyến lớn nhất.
  - Ngoài ra, GTSRB là một thử thách phân loại nhiều lớp, được tổ chức tại International Joint Conference on Neural Networks (IJCNN) 2011.
  - Tập dữ liệu gồm có hơn 50.000 hình ảnh, gồm 43 lớp 

![43 Classes Meta](https://user-images.githubusercontent.com/85627308/167721365-159d000f-5664-46b3-a048-019d69366696.png)

## Công cụ và Framework hỗ trợ
- [Tensorflow](https://www.tensorflow.org/)
- [Sk-learn](https://scikit-learn.org/)
- [Keras](https://keras.io/)
- [Opencv](https://opencv.org/)
- [Matplotlib](https://matplotlib.org/)
- [Numpy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [Tkinter](https://docs.python.org/3/library/tkinter.html)

## Phương pháp tiếp cận
- Load dữ liệu
- Khám phá, phân tích tập dữ liệu
- Trực quan hóa dữ liệu
- Tiền xử lí (Resizing, Grayscaling, Histogram equalization,...)
- Create model
- Train model
- Fit
- Prediction
- Đánh giá mô hình

![](https://user-images.githubusercontent.com/85627308/167726238-4da1b184-7ab9-41d3-a2ee-e9149001ca7c.png)

## Kết quả thực nghiệm
