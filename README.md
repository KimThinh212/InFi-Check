# 📌 InFiCheck - Hệ thống kiểm tra và phân tích thông tin (NLP)

## 📖 Giới thiệu

Trong thời đại bùng nổ thông tin, việc phân biệt giữa thông tin chính xác và thông tin sai lệch (misinformation) trở nên ngày càng quan trọng. Đề tài **InFiCheck** được xây dựng nhằm giải quyết bài toán này bằng cách ứng dụng các kỹ thuật trong lĩnh vực **Xử lý Ngôn ngữ Tự nhiên (Natural Language Processing - NLP)** và **Học máy / Học sâu (Machine Learning / Deep Learning)**.

Hệ thống cho phép phân tích nội dung văn bản và đánh giá độ tin cậy của thông tin, từ đó hỗ trợ người dùng nhận diện tin giả và nâng cao chất lượng tiếp nhận thông tin.

---

## 🎯 Mục tiêu đề tài

- Xây dựng một pipeline xử lý văn bản hoàn chỉnh
- Áp dụng các mô hình Machine Learning / Deep Learning vào bài toán phân loại thông tin
- Đánh giá hiệu quả mô hình trên dữ liệu thực tế
- Minh họa ứng dụng NLP trong bài toán phát hiện thông tin sai lệch

---

## 🧠 Công nghệ sử dụng

### 🔹 Ngôn ngữ lập trình
- Python

### 🔹 Thư viện xử lý dữ liệu
- NumPy
- Pandas

### 🔹 Thư viện NLP
- NLTK
- SpaCy
- Transformers (tuỳ triển khai)

### 🔹 Machine Learning / Deep Learning
- Scikit-learn
- PyTorch / TensorFlow

### 🔹 Trực quan hóa
- Matplotlib
- Seaborn

---

## ⚙️ Kiến trúc & Pipeline hệ thống

Hệ thống được xây dựng theo pipeline chuẩn trong NLP:

### 1. Thu thập dữ liệu
- Dữ liệu văn bản từ các nguồn như:
  - Tin tức
  - Mạng xã hội
  - Dataset có gán nhãn (true/false)

---

### 2. Tiền xử lý dữ liệu (Preprocessing)
- Chuẩn hóa văn bản (lowercase)
- Tokenization
- Loại bỏ stopwords
- Stemming / Lemmatization
- Loại bỏ ký tự đặc biệt

---

### 3. Biểu diễn văn bản (Feature Engineering)
- Bag of Words (BoW)
- TF-IDF
- Word Embedding:
  - Word2Vec
  - GloVe
  - BERT (nâng cao)

---

### 4. Huấn luyện mô hình
- Các mô hình được sử dụng:
  - Logistic Regression
  - Naive Bayes
  - Support Vector Machine (SVM)
  - Deep Learning models (LSTM, Transformer,...)

---

### 5. Đánh giá mô hình
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## 📊 Dataset

Dataset sử dụng trong đề tài bao gồm các văn bản đã được gán nhãn:
- Thông tin đúng (True)
- Thông tin sai (Fake)

📌 Có thể bao gồm:
- Dataset tin tức (Fake News Detection)
- Dữ liệu từ mạng xã hội

---

## 🚀 Hướng dẫn cài đặt và chạy chương trình

### 1. Clone project
```bash
git clone <repository_link>
cd InFiCheck
### 2. Cài đặt thư viện
pip install -r requirements.txt

###3. Chạy chương trình
python main.py
📁 Cấu trúc thư mục
InFiCheck/
│
├── data/                  # Dữ liệu đầu vào
├── models/                # Mô hình đã huấn luyện
├── notebooks/             # Notebook thử nghiệm
├── src/                   # Source code chính
│   ├── preprocessing/     # Xử lý dữ liệu
│   ├── features/          # Feature engineering
│   ├── training/          # Huấn luyện mô hình
│   ├── evaluation/        # Đánh giá mô hình
│
├── main.py
├── requirements.txt
└── README.md

---

📈 Kết quả đạt được
Hệ thống có khả năng phân loại thông tin với độ chính xác cao
Pipeline rõ ràng, dễ mở rộng
Có thể áp dụng vào thực tế trong:
Phát hiện tin giả
Hỗ trợ kiểm chứng thông tin

---

🔮 Hướng phát triển
Áp dụng các mô hình tiên tiến:
BERT, RoBERTa, DistilBERT
Tối ưu hiệu năng và tốc độ xử lý
Xây dựng giao diện người dùng (Web/App)
Mở rộng sang đa ngôn ngữ (Vietnamese NLP)

---

👨‍💻 Thông tin Nhóm:
Họ tên thành viên:
- Nguyễn Hữu Trí
- Đặng Tiến Thuật
- Nguyễn Viết Trường Toàn
- Võ Bạch Kim Thịnh
- Phan Trọng Nguyên
Trường: HUIT
Môn học: Xử lý Ngôn ngữ Tự nhiên (NLP)
