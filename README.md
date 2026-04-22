# Movie-Recommender-System
This project performs sentiment analysis on movie reviews from the IMDB dataset using Natural Language Processing (NLP) techniques and a Machine Learning model.

---

## 📌 Project Overview

The goal of this project is to classify movie reviews into:
- 👍 Positive (1)
- 👎 Negative (-1)
- 😐 Neutral (0)

We use text preprocessing, TF-IDF vectorization, and a Linear SVM model for classification.

---

## 📂 Dataset

- IMDB Movie Reviews Dataset
- Columns:
  - review → text data
  - sentiment → label (positive / negative)

---

## ⚙️ Technologies Used

- Python 🐍
- Pandas
- NumPy
- NLTK (Natural Language Processing)
- Scikit-learn
- TF-IDF Vectorizer
- Linear Support Vector Machine (SVM)

---

## 🧹 Data Preprocessing Steps

- Remove HTML tags
- Remove special characters and numbers
- Convert text to lowercase
- Remove stopwords
- Apply Lemmatization

---

## 🔢 Feature Extraction

We used **TF-IDF Vectorizer**:
- max_features = 5000
- Converts text into numerical features for ML model

---

## 🤖 Model Used

- LinearSVC (Support Vector Machine)
- C = 0.01 (regularization parameter)

---

## 📊 Model Performance

- Training Accuracy: ~XX%
- Testing Accuracy: ~XX%

*(Replace XX with your actual results)*

---

## 💬 Recommendation System

The model can also predict sentiment for custom input:

- Score > 0.1 → Recommend Movie 👍  
- Score < -0.1 → Do Not Recommend 👎  
- Otherwise → Neutral 😐  

---

## 🧪 How to Run

1. Open Google Colab or Jupyter Notebook  
2. Upload dataset (`IMDB Dataset.csv`)  
3. Run all cells step by step  
4. Enter custom review for prediction

---

---

## 📈 Key Features

- End-to-end NLP pipeline
- Text cleaning + preprocessing
- Machine Learning classification
- Custom recommendation function
- Overfitting detection

---

## 🚀 Future Improvements

- Replace SVM with Random Forest or Deep Learning
- Improve accuracy using Word Embeddings (Word2Vec / BERT)
- Deploy as web app using Streamlit or Flask

---

## 👨‍💻 Author

Student Machine Learning Project (IMDB Sentiment Analysis)

---
