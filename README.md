# Shopee review clustering
Dự án phân cụm đánh giá sản phẩm trên Shopee nhằm nhóm các bình luận có nội dung tương tự,
giúp người bán và người mua dễ dàng hiểu các chủ đề chính như: chất lượng, giao hàng, giá cả,
dịch vụ, đóng gói, v.v.
##Table of Contents
📖 Objectives
🔧 Technologies
📊 Dataset
🚀 Workflow
🔗 Clone repo
📜 Results
## Objectives
- Phân tích dữ liệu đánh giá sản phẩm từ Shopee
- Làm sạch và tiền xử lý dữ liệu văn bản tiếng Việt
- Trích xuất đặc trưng bằng TF-IDF
- Áp dụng thuật toán K-Means / K-Medoids để phân cụm
- Đánh giá và diễn giải kết quả phân cụm
## Technologies
- Python
- Pandas, NumPy
- Underthesea (tách từ tiếng Việt)
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook
## Dataset
- Dữ liệu: shopee.csv
- Nội dung: các đánh giá sản phẩm từ Shopee
- Số dòng: ...
- Các cột chính: review_text, rating, product_id, ...
## Workflow
1. Thu thập dữ liệu
2. Làm sạch dữ liệu (loại ký tự đặc biệt, emoji, stopwords)
3. Tách từ tiếng Việt
4. Vector hóa bằng TF-IDF
5. Phân cụm bằng K-Means / K-Medoids
6. Phân tích và trực quan hóa kết quả
## How to Run
1. Clone repo:
   git clone https://github.com/Hoai25124/shopee-review-clustering.git
2. Mở file shopee-review-clustering.ipynb
3. Chạy lần lượt các cell trong Jupyter Notebook
## Results
- Các đánh giá được chia thành ... cụm
- Mỗi cụm đại diện cho một chủ đề chính
- Kết quả giúp hiểu hành vi và phản hồi của khách hàng
