# Twitter-Sentiment-Analysis
# Twitter Sentiment Analysis using Machine Learning

## 📌 Project Overview
This project is a Machine Learning–based application that analyzes the sentiment of Twitter text and classifies it as **Positive** or **Negative**. 
The system allows users to either enter custom text or fetch recent tweets from a Twitter user and analyze their sentiment.

The application is built using **Streamlit** for the user interface and uses a **TF-IDF vectorizer** with a trained Machine Learning model for sentiment prediction.

---

## ✨ Features
- Sentiment analysis of custom input text
- Fetch and analyze tweets from a Twitter username
- Displays results with colored sentiment cards
- Uses pre-trained Machine Learning model
- Simple and interactive web interface

---

## 🛠 Technologies Used
- Python  
- Streamlit  
- Scikit-learn  
- NLTK  
- TF-IDF Vectorizer  
- Nitter (Twitter scraping)  
- Pickle  

---

## ⚙ How It Works
1. User selects input type (manual text or Twitter username).
2. Text data is cleaned by removing special characters and stopwords.
3. Cleaned text is transformed using a TF-IDF vectorizer.
4. The trained Machine Learning model predicts sentiment.
5. Results are displayed as **Positive** or **Negative** sentiment.

---

## 🚀 How to Run the Project
1. Clone the repository
2. Install required libraries
