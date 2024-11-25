# CapX-Assignment

## Stock Movement Prediction Based on Social Media Sentiment

### Overview
This repository predicts stock price movements by analyzing social media sentiment using Reddit data.

### Steps:

How to Run:

1) Scrape Reddit data:
--python scrape_reddit.py

2) Preprocess the data:
--python preprocess_data.py

3) Train and evaluate the model:
--python train_model.py

1. Scrape data from subreddits like `r/stocks` and `r/investing`.
2. Preprocess data: Clean text and perform sentiment analysis.
3. Train and evaluate a machine learning model to predict stock movements.

**Libraries used**
--> pip install praw nltk scikit-learn matplotlib pandas
--> import praw
--> import pandas as pd
--> import numpy as np
--> import re
--> from nltk.corpus import stopwords
--> from nltk.tokenize import word_tokenize
--> from nltk.stem import PorterStemmer
--> import nltk
--> from sklearn.ensemble import RandomForestClassifier
--> from sklearn.model_selection import train_test_split, GridSearchCV
--> from sklearn.metrics import classification_report, accuracy_score

