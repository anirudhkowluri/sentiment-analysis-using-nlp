# Sentiment Analysis Using NLP

## 📄 Overview
This project implements a **Natural Language Processing (NLP)** pipeline to perform sentiment analysis on text data. It classifies user inputs (e.g., product reviews, tweets) into **Positive, Negative, or Neutral** categories using supervised machine learning techniques.

## 🚀 Features
- Text preprocessing: tokenization, stopword removal, and lemmatization
- Feature extraction using **TF-IDF Vectorization**
- Model training and evaluation with multiple classifiers
- Final sentiment prediction API / script interface

## 🧠 Approach
1. **Data Loading** – Import labeled text data
2. **Preprocessing**
   - Remove noise (punctuation, special characters)
   - Normalize text (lowercasing, lemmatization)
3. **Feature Engineering**
   - Convert text into numerical features via TF-IDF
4. **Model Training**
   - Compare models such as Logistic Regression, SVM, and Naive Bayes
5. **Evaluation**
   - Use accuracy, precision, recall, F1-score, and confusion matrix
6. **Prediction Interface**
   - Simple CLI / function to predict sentiment on new text

## 🛠 Tech Stack
- Python
- NLTK / spaCy
- Scikit-learn
- Pandas & NumPy

## 📦 Usage
1. Clone the repo:
   ```bash
   git clone https://github.com/anirudhkowluri/sentiment-analysis-using-nlp
   
2.Install dependencies:
pip install -r requirements.txt

3.Run sentiment prediction:
python predict_sentiment.py


📈 Evaluation Metrics

Accuracy

Precision, Recall, F1-Score

Confusion matrix visualization

📌 Applications

Customer feedback analysis

Social media sentiment tracking

Brand reputation monitoring
