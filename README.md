# Sentiment-Analysis
# ✈️ Task 4- Sentiment Analysis on Airline Tweets

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: SIDDHI RAMESH VISHE

*INTERN ID*: CT08DH665

*DOMAIN*: DATA ANALYTICS

*DURATION*: 8 Weeks

*MENTOR* : NEELA SANTOSH

## 📌 Overview
The goal is to perform **sentiment analysis** on textual data (tweets) to classify them as **Positive, Neutral, or Negative** using **Natural Language Processing (NLP)** techniques.

---

## 📂 Dataset
- **Source**: Airline Tweets Dataset
### 📂 Dataset
The dataset used in this project is `Tweets.csv`, sourced from:
[Twitter US Airline Sentiment - Kaggle](https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment)

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
