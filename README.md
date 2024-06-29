<<<<<<< HEAD
# Streamlit Applications

Đây là một repository chứa ba ứng dụng Streamlit khác nhau: Ứng dụng nhận diện đối tượng từ hình ảnh, Ứng dụng chỉnh sửa từ sai dựa trên khoảng cách Levenshtein, và Ứng dụng ChatBot đơn giản.

## Mục Lục

- [Giới thiệu](#giới-thiệu)
- [Yêu cầu hệ thống](#yêu-cầu-hệ-thống)
- [Cài đặt](#cài-đặt)
- [Ứng dụng nhận diện đối tượng](#ứng-dụng-nhận-diện-đối-tượng)
- [Ứng dụng chỉnh sửa từ sai](#ứng-dụng-chỉnh-sửa-từ-sai)
- [Ứng dụng ChatBot](#ứng-dụng-chatbot)

## Giới thiệu

Repository này chứa ba ứng dụng Streamlit khác nhau:
1. **Ứng dụng nhận diện đối tượng từ hình ảnh:** Sử dụng mô hình MobileNet SSD để nhận diện các đối tượng trong hình ảnh.
2. **Ứng dụng chỉnh sửa từ sai:** Sử dụng khoảng cách Levenshtein để gợi ý từ đúng dựa trên từ điển cho sẵn.
3. **Ứng dụng ChatBot đơn giản:** Sử dụng Hugging Face API để tạo một chatbot đơn giản.

## Yêu cầu hệ thống

- Python 3.6 trở lên
- Các thư viện Python sau:
  - streamlit
  - opencv-python
  - numpy
  - Pillow
  - hugchat

## Cài đặt

1. **Clone repository:**

    ```bash
    git clone https://github.com/username/repository-name.git
    cd repository-name
    ```

2. **Tạo môi trường ảo:**

    ```bash
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. **Cài đặt các gói cần thiết:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Chuẩn bị tệp mô hình và tệp cấu hình:**

    Đảm bảo rằng bạn có các tệp mô hình và tệp cấu hình `MobileNetSSD_deploy.caffemodel` và `MobileNetSSD_deploy.prototxt.txt` trong thư mục `model`.

## Ứng dụng nhận diện đối tượng

1. **Chạy ứng dụng Streamlit:**

    ```bash
    streamlit run object_detection_app.py
    ```

2. **Truy cập ứng dụng:**

    Mở trình duyệt web và vào địa chỉ http://localhost:8501.

3. **Sử dụng ứng dụng:**

    - Tải lên một hình ảnh bằng cách nhấp vào nút "Upload Image".
    - Hình ảnh đã tải lên sẽ được hiển thị.
    - Hình ảnh đã được xử lý và nhận diện đối tượng sẽ được hiển thị dưới hình ảnh gốc.

## Ứng dụng chỉnh sửa từ sai

1. **Chạy ứng dụng Streamlit:**

    ```bash
    streamlit run word_correction_app.py
    ```

2. **Truy cập ứng dụng:**

    Mở trình duyệt web và vào địa chỉ http://localhost:8501.

3. **Sử dụng ứng dụng:**

    - Nhập từ cần kiểm tra vào ô "Word".
    - Nhấn nút "Compute" để xem từ đúng và các khoảng cách Levenshtein tương ứng.

## Ứng dụng ChatBot

1. **Chạy ứng dụng Streamlit:**

    ```bash
    streamlit run chatbot_app.py
    ```

2. **Truy cập ứng dụng:**

    Mở trình duyệt web và vào địa chỉ http://localhost:8501.

3. **Sử dụng ứng dụng:**

    - Nhập tài khoản Hugging Face của bạn ở phần "Login HugChat" bên sidebar.
    - Nhập câu hỏi hoặc lời nhắn vào ô chat để nhận phản hồi từ chatbot.
=======
>>>>>>> cbe708f38086d5b19aa15a97f58b1b6b584361ca

