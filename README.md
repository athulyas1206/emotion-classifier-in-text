# Emotion Classifier 💬

A deployment-ready **Natural Language Processing (NLP)** app that classifies emotions from text input using machine learning. Built with a full pipeline of tools including **NLTK** for advanced preprocessing, **scikit-learn** for modeling, and **Gradio** for a clean, interactive user interface.

---

## 🚀 Features

- Predicts one of six emotions: **Joy**, **Sadness**, **Anger**, **Fear**, **Love**, **Surprise**
- Built using a TF-IDF vectorizer + Logistic Regression model
- Preprocessing with NLTK:
  - Tokenization
  - Stopword removal
  - Stemming
  - Lemmatization
- Deployed with Gradio for instant web-based interaction
- Confusion matrix visualization included

---

## 📊 How to Use This Project

All development and testing were done in **Google Colab**.

To explore or modify the code:
- Open the included `.ipynb` notebook
- Run all cells directly in Colab


---

## 📊 Model Overview

- **Model**: Logistic Regression
- **Vectorizer**: TF-IDF with max 5000 features
- **Accuracy**: ~90% on test data

### Confusion Matrix

![Confusion Matrix](confusion_matrix.png)

The model shows high precision and recall across most classes, with expected confusion between closely related emotions (e.g., *Joy* vs *Love*, *Fear* vs *Surprise*).

---

## 🧾 Example Predictions

| Input Sentence                     | Predicted Emotion |
|-----------------------------------|-------------------|
| I love this place                 | Joy               |
| I saw a dead body                 | Fear              |
| This makes me so angry           | Anger             |
| I miss my best friend            | Sadness           |
| You surprised me with that gift  | Surprise          |


