# NLP_Homework
rep for nlp homework

import os

import pandas as pd

from dotenv import load_dotenv

import nltk as nltk

nltk.download('vader_lexicon')

from nltk.sentiment.vader import SentimentIntensityAnalyzer

analyzer = SentimentIntensityAnalyzer()

from newsapi import NewsApiClient

nltk.download('stopwords')

nltk.download('punkt')

nltk.download('wordnet')

%matplotlib inline

load_dotenv()

# Sentiment of Cryptos
Assessing the sentiment related to BTC and ETH across various news outlets via newapi and visualising them.
