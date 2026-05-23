# 🎬 Sentiment Analysis using NLP & Machine Learning

A Natural Language Processing (NLP) project that analyzes movie reviews and predicts whether the sentiment is **Positive** or **Negative** using Machine Learning techniques.

---

## 🚀 Project Overview

This project focuses on text classification using NLP and Machine Learning.  
The model learns from thousands of movie reviews and predicts the emotional sentiment behind each review.

The project demonstrates the complete NLP workflow including:

- Text preprocessing
- Feature extraction using TF-IDF
- Machine Learning classification
- Model evaluation
- Sentiment prediction on custom text

---

## 🧠 Problem Statement

Given a movie review, the goal is to classify it into:

- ✅ Positive Review
- ❌ Negative Review

Example:

| Review | Prediction |
|---|---|
| "This movie was amazing!" | Positive |
| "Terrible and boring film." | Negative |

---

## 📊 Dataset

Dataset used:
- IMDb Movie Reviews Dataset

The dataset contains:
- 50,000 movie reviews
- Positive and negative sentiments

---

## ⚙️ Workflow

The project follows these steps:

1. Import Libraries
2. Load Dataset
3. Data Exploration
4. Label Encoding
5. Train-Test Split
6. Text Vectorization using TF-IDF
7. Model Training
8. Prediction
9. Model Evaluation
10. Testing Custom Reviews

---

## 🛠️ Technologies Used

- Python 🐍
- Pandas
- Matplotlib
- Scikit-learn
- NLP
- TF-IDF Vectorization

---

## 🤖 Machine Learning Model

### Logistic Regression

The model was trained using Logistic Regression for binary sentiment classification.

---

## 🧪 NLP Technique

### TF-IDF Vectorization

TF-IDF converts text data into numerical vectors so Machine Learning models can process text efficiently.

---

## 📈 Evaluation Metrics

The model was evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix

---

## 📊 Example Prediction

### Positive Review

```python
"This movie was absolutely amazing!"
➡️ Positive
