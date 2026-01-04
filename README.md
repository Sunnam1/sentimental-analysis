Amazon Product Reviews Sentiment Analysis
This project performs sentiment analysis on Amazon product reviews using Python and common NLP libraries. It processes a dataset of 25,000 reviews, cleans the text, and visualizes sentiment distribution.
​

Features
Loads and explores Amazon review dataset with 'Review' and 'Sentiment' columns.
​

Cleans text by removing stopwords using NLTK.
​

Generates word clouds for negative sentiments.
​

Creates visualizations like count plots for sentiment distribution.
​

Tech Stack
Python with Pandas for data handling.
​

NLTK for text preprocessing (punkt, stopwords).
​

Scikit-learn (TfidfVectorizer).
​

Matplotlib and WordCloud for visualizations.
​

Jupyter Notebook environment (Google Colab compatible).
​

Dataset
Uses 'AmazonReview.csv' with ~25,000 entries: reviews labeled as binary sentiment (0: negative, 1: positive) after mapping (1-3→0, 4-5→1).
​

Quick Start
Clone the repo and open Amazon_Product_Reviews_Sentiment_Analysis_in_Python.ipynb in Jupyter/Colab.
​

Place 'AmazonReview.csv' in the same directory.
​

Run cells sequentially: imports, data load, cleaning, and plots will generate automatically.
​

Results
Dataset: 15,000 negative (0), ~10,000 positive (1).
​

Visuals include word clouds and sentiment bar charts
