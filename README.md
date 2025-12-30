# 🎬 Movie Review Sentiment Analysis using Machine Learning

This project performs **sentiment analysis on movie reviews** using **TF-IDF vectorization** and **Logistic Regression**.  
The goal is to classify reviews as **Positive** or **Negative** based on their textual content.

---

## 📌 Project Overview

Sentiment analysis is a Natural Language Processing (NLP) task that identifies emotional tone behind text.  
In this project, we:
- Use real movie review text samples
- Convert text to numerical features using **TF-IDF**
- Train a **Logistic Regression** classifier
- Evaluate the model using classification metrics
- Predict sentiment for new unseen reviews

---

## 🧠 Technologies Used

- Python  
- Scikit-learn  
- NumPy  
- TF-IDF Vectorizer  
- Logistic Regression  

---

## 📂 Dataset Description

- The dataset consists of **15 movie reviews**
- Labels:
  - `1` → Positive review  
  - `0` → Negative review  

Example:
```python
texts = ["Great movie!", "Worst film ever"]
labels = [1, 0]
