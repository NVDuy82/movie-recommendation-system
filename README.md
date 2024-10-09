# Movie Recommendation System

## Mô Tả Dự Án
Dự án này là một hệ thống gợi ý phim được xây dựng bằng Python và TensorFlow, sử dụng các phương pháp học sâu để cung cấp các gợi ý chính xác dựa trên sở thích của người dùng. Hệ thống áp dụng các kỹ thuật nhúng (embedding) cho người dùng và phim, cho phép mô hình học từ dữ liệu đánh giá và đưa ra các gợi ý phim tương ứng.

## Tính Năng
- Tính toán các embedding cho người dùng và phim.
- Tính toán độ lớn của các embedding và bias cho phim.
- Sử dụng t-SNE để giảm chiều dữ liệu và hiển thị trực quan các embedding.
- Tìm kiếm các phim tương tự dựa trên tên phim.
- Đánh giá chất lượng gợi ý thông qua số lượng gợi ý tốt và xấu (HR@K).

## Cài Đặt
Để cài đặt và chạy dự án, bạn cần có Python 3.6 trở lên. Hãy đảm bảo rằng bạn đã cài đặt các thư viện cần thiết trước khi tiếp tục.

## Hướng Dẫn Sử Dụng
1. **Chuẩn bị Dữ Liệu**:
   - Tải dữ liệu đánh giá phim từ các nguồn như [The Movies Dataset](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset).
   - Chỉnh sửa dữ liệu và lưu vào các tệp CSV như `ratings_train.csv`, `ratings_test.csv`, và `ratings_new_user.csv`.

2. **Chạy Mô Hình**:
   - Sử dụng Jupyter Notebook hoặc một IDE phù hợp để mở và chạy mã trong các ô mã.
   - Khởi tạo mô hình bằng cách gọi hàm `build_model`, sau đó huấn luyện mô hình bằng hàm `fit`.
   - Lưu mô hình đã huấn luyện để sử dụng trong tương lai.

3. **Gợi Ý Phim**:
   - Sử dụng các hàm như `recommend` và `movie_neighbors` để nhận các gợi ý phim cho người dùng.

4. **Trực Quan Hóa**:
   - Sử dụng các hàm để trực quan hóa embedding phim và bias để phân tích sâu hơn.

## Thông Tin Liên Hệ
Nếu bạn có câu hỏi hoặc cần hỗ trợ, hãy liên hệ với tôi qua email: [duyn.dev@gmail.com]

