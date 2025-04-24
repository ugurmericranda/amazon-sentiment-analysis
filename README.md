# 🛒 Amazon Review Sentiment Analysis

This project is a Natural Language Processing (NLP) application that classifies Amazon product reviews as **positive** or **negative** based on the text content.

The dataset focuses on **hygiene products** and comes from Kaggle.

## 🎯 Project Objective

To develop a machine learning model that can predict the **sentiment of a product review** by analyzing the written text — without relying on star ratings. This helps detect mismatches between star ratings and actual sentiment.

## 📁 Dataset

- Source: [Kaggle - Consumer Reviews of Amazon Products](https://www.kaggle.com/datasets/datafiniti/consumer-reviews-of-amazon-products)
- Format: CSV
- Columns used: `reviews.text`, `reviews.rating`

## 🧠 Techniques Used

- Text Preprocessing (stopword removal, lowercasing, punctuation cleaning)
- NLP with TF-IDF Vectorization
- Classification using Multinomial Naive Bayes
- Handling class imbalance (undersampling)
- Performance metrics: Accuracy, Precision, Recall, F1-Score, Confusion Matrix
- Bonus: User comment input + real-time sentiment prediction

## 🔧 Tools & Libraries

- Python
- Pandas, NumPy
- scikit-learn
- NLTK
- Seaborn, Matplotlib
- Google Colab

## 📊 Sample Results

- Accuracy: ~86% on balanced dataset
- Successfully distinguishes between genuinely positive and negative reviews

## 🚀 How to Run

1. Upload the dataset (`1429_1.csv`) into your Colab environment
2. Run the notebook cells in order
3. Try entering your own product review to see the model prediction

## 🎬 Demo

---

✅ Clean, simple and effective!

