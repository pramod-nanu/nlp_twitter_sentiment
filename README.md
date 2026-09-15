# Twitter Sentiment Analysis using NLP

## Overview
This project classifies tweets as **Positive, Negative, or Neutral** using NLP and Machine Learning.

## Dataset
- **Input:** `text`
- **Target:** `sentiment`

## Workflow
1. Data cleaning
2. Tokenization
3. Stop-word removal
4. Lemmatization
5. Train-test split
6. TF-IDF vectorization
7. Model training
8. Model evaluation

## Models Tried
- Logistic Regression
- Multinomial Naive Bayes
- Linear SVM

## Best Result
**Logistic Regression** with `class_weight="balanced"` achieved about **64.6% accuracy**.

## Tech Stack
Python, Pandas, NLTK, Scikit-learn, Matplotlib, Jupyter Notebook

## Goal
Predict the sentiment of unseen text as **Positive, Negative, or Neutral**.
