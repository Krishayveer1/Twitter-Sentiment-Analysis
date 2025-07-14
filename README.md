# 🐦 Twitter Sentiment Analysis

This project performs sentiment analysis on a dataset of tweets to classify them as **positive** or **negative**. It combines natural language processing (NLP) techniques with machine learning models to detect sentiment in short text formats such as tweets.

## 📌 Objectives
- Clean and preprocess raw tweet text data.
- Use NLP techniques such as tokenization and stemming.
- Apply both rule-based (`TextBlob`) and statistical (`Naive Bayes`) sentiment classifiers.
- Evaluate model performance and visualize results.

## 🧰 Tools & Libraries
- Python  
- Kaggle API  
- Pandas, NumPy  
- NLTK, TextBlob  
- Scikit-learn  
- Matplotlib  

## 📁 Dataset
The dataset used is from [Kaggle's Twitter Sentiment Analysis dataset](https://www.kaggle.com/kazanova/sentiment140). It includes thousands of tweets labeled with sentiment polarity (`0 = negative`, `4 = positive`).

## ⚙️ Workflow

1. **Data Collection**
   - Downloaded dataset using Kaggle API.
   
2. **Text Preprocessing**
   - Lowercased text
   - Removed stopwords, punctuation, and special characters
   - Applied stemming using NLTK
   - Tokenized text

3. **Exploratory Data Analysis**
   - Visualized class distribution
   - Reviewed sample tweets and sentiment polarity

4. **Sentiment Classification**
   - **TextBlob**: Used as a baseline rule-based classifier.
   - **Naive Bayes**: Trained using `CountVectorizer` and `MultinomialNB`.

5. **Model Evaluation**
   - Evaluated using accuracy, precision, recall, and F1 score.
   - Plotted confusion matrix and sentiment distributions.



