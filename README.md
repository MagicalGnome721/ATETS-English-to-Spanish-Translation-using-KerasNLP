# ATETS: English-to-Spanish Translation using KerasNLP

## 📌 Giới thiệu
Dự án này xây dựng một mô hình dịch máy (Neural Machine Translation - NMT) từ tiếng Anh sang tiếng Tây Ban Nha, sử dụng Transformer-based model của KerasNLP và TensorFlow.

## 🔥 Tại sao không dùng Google Dịch?
- **Hiểu rõ công nghệ Transformer** – Đây là nền tảng của các mô hình AI hiện đại như ChatGPT, BERT, T5.
- **Tuỳ chỉnh mô hình theo nhu cầu** – Google Dịch không thể tinh chỉnh theo từng lĩnh vực cụ thể.
- **Chạy offline & kiểm soát dữ liệu** – Không cần internet, đảm bảo quyền riêng tư.
- **Ứng dụng rộng rãi** – Kiến thức từ dự án này có thể áp dụng vào chatbot, tóm tắt văn bản, phân tích ngữ nghĩa...

## 📚 Dữ liệu
- **Nguồn**: [Anki English-Spanish Dataset](http://storage.googleapis.com/download.tensorflow.org/data/spa-eng.zip)
- **Mô tả**: Gồm 118,964 cặp câu song ngữ Anh - Tây Ban Nha, được trích xuất từ các nguồn đối thoại thực tế.

## 🛠 Công nghệ sử dụng
- **Python** (TensorFlow, KerasNLP)
- **Transformer Model** (Self-Attention, Multi-Head Attention)
- **Tokenization bằng WordPiece**
- **Seq2Seq Learning với Positional Encoding**

## 🚀 Cách chạy project
### 1️⃣ Cài đặt thư viện
```bash
pip install -q tensorflow keras-nlp rouge-score
```

### 2️⃣ Chạy notebook
Mở **Jupyter Notebook** hoặc **Google Colab** và chạy từng cell để train mô hình.

### 3️⃣ Kiểm thửs mô hình
Sau khi train, nhập một câu tiếng Anh và nhận kết quả dịch sang tiếng Tây Ban Nha.

## 🗘 Kết quả mong đợi
| Câu gốc (English) | Google Translate | Model Output |
|------------------|-----------------|-------------|
| Hello, how are you? | Hola, ¿cómo estás? | Hola, ¿cómo estás? |
| I love machine learning. | Me encanta el aprendizaje automático. | Me gusta el aprendizaje de máquinas. |

## 📌 Kết luận
Project này giúp bạn hiểu rõ cách hoạt động của dịch máy bằng Transformer, đồng thời có thể tùy chỉnh mô hình theo nhu cầu.

📢 **Nếu bạn thấy dự án hữu ích, đừng quên thả ⭐ trên GitHub!** 🚀

