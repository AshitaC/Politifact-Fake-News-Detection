# PolitiFact Fake News Classifier 🕵️‍♂️

![GitHub](https://img.shields.io/badge/Language-Python-blue)
![GitHub](https://img.shields.io/badge/Library-Scikit_Learn-orange)
![GitHub](https://img.shields.io/badge/Tool-spaCy-green)
![GitHub](https://img.shields.io/badge/Dataset-PolitiFact-yellow)

A machine learning model to classify news articles as **"real"** or **"fake"** using the **PolitiFact dataset**. This project combines **linguistic features**, **sentiment analysis**, and **social network features** to detect fake news effectively.

---

## 🚀 **Overview**

Fake news has become a significant issue in the digital age, spreading misinformation and impacting public trust. This project aims to combat fake news by building a supervised learning model that classifies news articles based on their content and social context.

### Key Features:
- **Linguistic Analysis**: Extracted features like word count, POS tagging, negation count, and punctuation usage.
- **Sentiment Analysis**: Used **VADER** to analyze the emotional tone of news articles.
- **Social Network Features**: Incorporated user engagement metrics (shares, followers) and network centrality measures.
- **Machine Learning Model**: Trained a **Random Forest Classifier** to achieve high accuracy in fake news detection.

---

## 📊 **Results**

The model achieved the following performance metrics:
- **Accuracy**: 78.4%
- **Precision**: 81.075%
- **Recall**: 75.723%
- **F1-Score**: 78.099%
- **AUROC**: 86.241%

---

## 🛠️ **Technologies Used**

- **Programming Language**: Python
- **Libraries**:
  - **Data Processing**: Pandas, NumPy
  - **NLP**: spaCy, NLTK, VADER
  - **Machine Learning**: Scikit-learn
  - **Visualization**: Matplotlib, Seaborn
- **Dataset**: [PolitiFact Fake News Dataset](https://www.politifact.com/)

---

## 📂 **Dataset**

The dataset includes:
- **News Articles**: 240 articles (120 real, 120 fake).
- **Social Network Data**:
  - User-User Relationships: 23,865 nodes and 574,744 edges.
  - News-User Relationships: 32,791 edges.
- **Features**: Linguistic, sentiment, and social network features.

---

## 🧩 **Features Extracted**

### 1. **Linguistic Features**
- Word count, words per sentence, negation count.
- Punctuation, quotes, and Part-of-Speech (POS) tags (nouns, verbs, adjectives, etc.).
- Stopwords and uppercase word counts.

### 2. **Sentiment Features**
- Positive, negative, and neutral sentiment scores using **VADER**.

### 3. **Social Network Features**
- Total shares, unique users, average shares per user.
- Average followers and followings of users sharing the news.
- Degree centrality of users in the network.

---
