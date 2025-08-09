# Sentiment-Analysis
# ✈️ Sentiment Analysis on Airline Tweets

## 📌 Overview
This project is part of my **CODTECH Internship - Task 4**.  
The goal is to perform **sentiment analysis** on textual data (tweets) to classify them as **Positive, Neutral, or Negative** using **Natural Language Processing (NLP)** techniques.

---

## 📂 Dataset
- **Source**: Airline Tweets Dataset
- **Columns Used**:  
  - `text` → Tweet content  
  - `airline_sentiment` → Target sentiment label  
- The dataset contains tweets mentioning different airlines, labeled with sentiment.

---

## ⚙️ Steps Performed
1. **Data Loading** and exploration
2. **Text Preprocessing**:
   - Lowercasing
   - Removing mentions, hashtags, URLs
   - Removing punctuation & digits
   - Stopword removal
   - Lemmatization
3. **Vectorization** using TF-IDF
4. **Model Training** with Logistic Regression
5. **Evaluation** using Classification Report & Confusion Matrix

---

## 📊 Results
- **Best Performance**: Negative sentiment classification
- **Challenges**: Some confusion between Neutral and Positive tweets
- **Possible Improvements**:
  - Use deep learning models (LSTM, BERT)
  - Hyperparameter tuning
  - Expand dataset

---

## 📌 Requirements
To run the notebook:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn nltk wordcloud
