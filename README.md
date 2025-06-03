# 📰 Fake News Detection using Machine Learning

This project uses Natural Language Processing (NLP) and Machine Learning techniques to detect whether a news article is **real** or **fake** based on its content.

## 🚀 Project Overview

Fake news is a growing problem with widespread social, political, and economic implications. This project builds an ML pipeline that:
- Cleans and preprocesses text data.
- Transforms text using TF-IDF vectorization.
- Trains and evaluates multiple classifiers:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Gradient Boosting

A simple UI/command-line interface allows users to input news articles and get predictions from each model.

---

## 📁 Dataset

The dataset used is a labeled collection of real and fake news articles separately containing:
- `title`
- `text`: Full news content.
- `date`
- `subject`

You can download the dataset from the repository itself
---

## 🛠️ Features

- Text Cleaning Pipeline (punctuation removal, case normalization, etc.)
- Modular ML Pipelines using `scikit-learn`
- Evaluation using Accuracy, Precision, Recall
- Comparison of model performances
- Saved models using `joblib` for reuse
- Batch predictions on new articles
- Flask-based frontend (in progress)

