# 🎯 Sentiment Analysis Vietnamese

Dự án phân tích cảm xúc (Sentiment Analysis) cho tiếng Việt, tập trung vào việc phân tích comment trên các sàn thương mại điện tử

## 📋 Mục Tiêu Dự Án

- **Phân tích cảm xúc** comment trên các sàn thương mại điện tử
- **Xử lý ngôn ngữ tự nhiên** cho tiếng Việt với các đặc thù như teencode, emoji
- **So sánh hiệu suất** giữa các mô hình ML truyền thống và transformer models
- **Xây dựng pipeline** hoàn chỉnh từ thu thập dữ liệu đến triển khai model
- **Phân tích từ vựng** và trích xuất cụm từ quan trọng
## 🏗️ Cấu Trúc Dự Án

```
Sentiment-Analysis-Vietnamese/
├── 📊 BERT.ipynb                           # Huấn luyện và tinh chỉnh mô hình BERT
├── 🤖 Bert_svm_model.pkl                   # Mô hình BERT và SVM được lưu 
├── 🧠 best_model.pkl                       # Mô hình TF-IDF và SVM được lưu
├── 📈 PhoBERT.ipynb                        # Huấn luyện và tinh chỉnh mô hình PhoBERT
├── 🔀 phobert_sentiment_model.pkl          # Mô hình PhoBert được lưu
├── 📝 test.crash                           # Tập dữ liệu dành cho việc test
├── 📝 Train.crash                          # Tập dữ liệu dành cho việc train
├── 📝 Tf_idf_SVM.ipynb                     # Huấn luyện mô hình TF-IDF + SVM
└── 📖 README.md                            # Tài liệu chính này
```

## 🔧 Các Tính Năng Chính
### 1. **Thu Thập Dữ Liệu**
- Dữ liệu được thu thập từ Kaggle
### 2. **Tiền Xử Lý Dữ Liệu**
- **Chuẩn hóa teencode**: 50+ từ viết tắt phổ biến (ko→không, dc→được, etc.)
- **Vietnamese Character Support**: Hỗ trợ đầy đủ ký tự tiếng Việt
### 3. Xây dựng các mô hình
- Sử dụng TF-IDF để trích xuất vector cho hai mô hình SVM và BERT
- Sử dụng SVM để tiến hành phân loại
- SỬ dụng BERT để tiến hành phân loại
- Xây dựng mô hình PhoBERT cho việc phân loại tiếng Việt

## 🎯 Kết quả 

Mô hình PhoBERT thể hiện sự ưu việt tuyệt đối với Accuracy đạt 90.86%


## 📝 License

Dự án này được phát triển cho mục đích học tập và nghiên cứu.
