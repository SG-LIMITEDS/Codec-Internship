# 🧠 Data Science Internship Projects – Sentiment Analysis & Recommender System

This repository includes two beginner-friendly machine learning projects developed during my internship at Codec Technologies. Both projects leverage real-world datasets and demonstrate key applications in Natural Language Processing and Recommendation Systems.

---

## 📌 Project 1: Real-Time Sentiment Analysis Dashboard

### 🎯 Objective
To build a real-time sentiment analysis dashboard using NLP techniques to classify text data (e.g., tweets or product reviews) into Positive, Neutral, or Negative sentiments.

### 📂 Dataset
- **File Name:** `tweets_sample.csv`
- **Columns:** `tweet_id`, `timestamp`, `text`
- **Source:** Dummy tweet data (can be replaced with Twitter API data)

### 🛠 Tools & Libraries Used
- Python 3.x
- Pandas
- TextBlob
- Matplotlib / Seaborn
- Google Colab

### 🚀 Key Tasks
- Text preprocessing and cleaning
- Sentiment classification using TextBlob polarity
- Data visualization (bar graph, pie chart)
- Real-time-like output simulation using time-based grouping

### ✅ Outcome
- Sentiment distribution visualization
- Cleaned, labeled dataset with sentiment tags
- Understanding of polarity-based classification

### 🧠 Learnings
- Practical use of TextBlob for sentiment scoring
- Visualization techniques for NLP outputs
- Importance of data preprocessing in text analytics

---

## 📌 Project 2: Recommender System for E-Commerce

### 🎯 Objective
To develop a recommendation engine using collaborative filtering to suggest products to users based on ratings and behavioral similarity.

### 📂 Dataset
- **File Name:** `ratings_sample.csv`
- **Columns:** `userId`, `productId`, `rating`
- **Source:** Simulated user-product rating data

### 🛠 Tools & Libraries Used
- Python 3.x
- Pandas
- scikit-surprise (`surprise`)
- NumPy
- Google Colab

### 🚀 Key Tasks
- Loading and exploring rating data
- Building a similarity-based recommendation model using `KNNBasic`
- Evaluating model performance with RMSE
- Predicting top-N product recommendations for users

### ✅ Outcome
- User-user similarity matrix
- Predicted top recommendations
- Performance evaluation using RMSE

### 🧠 Learnings
- Use of `surprise` library for collaborative filtering
- Similarity metrics and their role in recommendations
- Practical understanding of recommender engine workflows
