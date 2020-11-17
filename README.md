# Topic Modeling Twitter Headlines
This project uses a Kaggle data and fits classification models that balances recall and precision metrics with an emphasis on model interpretability. The dataset includes trip specific data, passenger specific data, and survey data on various components of the air travel experience. The use case for these results is to empower airlines with information regarding passenger's expectations for the air travel experience. With these insights, airlines can triangulate what causes dissastisfaction, optimize the categories causing dissatisfaction, and predict whether a customer is dissatisfied without a customer participating in a post flight survey.

## Data Source: 

Data was scraped from Twitter user accounts of Reuters, AP, BBC, Financial Times, NYTimes, CNN, FoxNews, Daily Mail, ABC, NBC, Wall Street Journal, Bloomberg from 2016-2020.

## Tools Used:

Postgres
Python 3
SNScrape
NLTK
Spacy
Corex
D3
Vader Sentiment Analysis

## Conclusions
The best tool to meet this project's goal is CorEx. The that airline pasengers care about most are as follows:

Inflight Wifi Service
Type of Travel (Business/Personal)
Check In Service
Type of Customer (Loyal/Disloyal)
Cleanliness
Outline of Files
The ipynb files contain exploratory data analyatics and techniques used for model tuning and selection.
The pickle file contains pickles of the final trained logistic regression model, the coeffiecients, and the scaler.
The CSV files contains the Kaggle data set (divided into train and test) and the cleaned dataframe.
The airline_data.py files contains code for the interactive visualization on Streamlit.
The pdf contains the final presentation.
