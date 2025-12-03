# Credit Card Fraud Detect

<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>

## Short descriptions
- Dự án tập trung phát triển một mô hình phát hiện gian lận cho nền tảng Fintech, nơi dữ liệu có tính mất cân bằng nghiêm trọng và hành vi gian lận liên tục thay đổi. Nhiều mô hình như Random Forest, XGBoost, KNN, AdaBoost và các mô hình học sâu tự đề xuất như CNN-base, Bi_LSTM base đã được triển khai để so sánh. Kết quả cho thấy mô hình đề xuất đạt AUC và Recall lần lượt là 0.990% và 0.953% cao hơn so với các phương pháp còn lại (dao động từ 90-92), giúp phát hiện tốt hơn các giao dịch gian lận hiếm gặp. Dự án đồng thời giải quyết các thách thức lớn như nhiễu trong dữ liệu, phân bố lớp lệch và nguy cơ cảnh báo sai, hướng đến một hệ thống cảnh báo gian lận chính xác và ổn định hơn cho môi trường tài chính số.

## Project Organization

```
├── LICENSE            <- Open-source license if one is chosen
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default mkdocs project; see www.mkdocs.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│       |
|       |__credit_card_fraud_detect.ipynb           <- the creator's initials, and a short `-` delimited description, e.g.
|                                                        `1.0-jqp-initial-data-exploration`.
│                         
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         src and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.cfg          <- Configuration file for flake8
│
└── src   <- Source code for use in this project.

```

# Hướng dẫn

## Giới thiệu
- Dự án tập trung xây dựng một hệ thống phát hiện gian lận (Fraud Detection) cho các giao dịch tài chính trên nền tảng Fintech, nơi khối lượng giao dịch lớn và hành vi gian lận ngày càng tinh vi. Mục tiêu chính là phát triển mô hình học máy có khả năng phát hiện bất thường theo thời gian thực, giảm thiểu thiệt hại và tăng mức độ an toàn cho người dùng.

- Dữ liệu được sử dụng bao gồm các đặc trưng giao dịch như thời gian, số tiền, loại giao dịch, hành vi người dùng, cùng các đặc điểm ngữ cảnh khác. Do tập dữ liệu thường mất cân bằng nghiêm trọng (tỷ lệ gian lận rất thấp), dự án áp dụng các kỹ thuật xử lý như SMOTE, ADASYN, SMOTE-ENN, kết hợp với các mô hình mạnh như Random Forest, XGBoost, KNN, AdaBoost, CNN/BiLSTM đề xuất (cho dữ liệu tuần tự).

- Hệ thống được đánh giá bằng các chỉ số phù hợp cho bài toán mất cân bằng như AUC-ROC, Precision, Recall, F1-score, đặc biệt tập trung vào khả năng giảm False Negatives (bỏ sót gian lận). Kết quả kỳ vọng giúp nền tảng Fintech tăng cường khả năng nhận diện gian lận một cách tự động, chính xác và kịp thời, góp phần nâng cao độ tin cậy và trải nghiệm người dùng.

## Công cụ và thư viện cần thiết
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- tensorflow
- imbalanced-learn
- xgboost
- lightgbm

## Quy trình hoạt động
![Mô tả quy trình](system_process.png)

# Liên hệ
Nếu bạn có bất kỳ câu hỏi hoặc góp ý nào thì liên hệ với mình qua Email:[lehoanggiavi21082004@gmail.com], [quynhanhnguyenngoc081@gmail.com], [hoangvu26104@gmail.com]

# Liên kết hữu ích
- Bạn nên đọc các papers có trong folder Ciatation

# Tác giả 
Được thực hiện bởi Lê Hoàng Gia Vĩ(Leader), Nguyễn Ngọc Quỳnh Anh và Hoàng Nguyên Vũ-Một nhóm sinh viên cùng chung đam mê và chí hướng, cùng đồng hành trên con đường chinh phục lĩnh vực Khoa Học Dữ Liệu và AI
--------

