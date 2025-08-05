IMDb Movie Review Sentiment Analysis
This project is a simple and effective sentiment classification model built using TF-IDF vectorization and LinearSVC, designed to classify IMDb movie reviews as Positive or Negative.

📌 Project Highlights
Dataset: IMDb Movie Reviews (labeled with sentiment)

Model: LinearSVC — performs well on high-dimensional sparse text data

Vectorization: TF-IDF (Term Frequency–Inverse Document Frequency)

Accuracy Achieved: ~89% (without any text cleaning)

🧠 Workflow Overview
Load Dataset
Loaded the IMDb review dataset and checked for null or inconsistent values.

Text Vectorization
Applied TfidfVectorizer to convert raw review text into numeric features.

Model Training
Trained a LinearSVC model on the TF-IDF-transformed data.

Evaluation
Achieved high accuracy (~89%) using a simple train-test split.

Prediction
Built a function to classify any custom review as Positive or Negative.

⚙️ Tech Stack
Python

Scikit-learn

Pandas
