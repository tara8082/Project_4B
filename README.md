# Topic Modeling & Sentiment Analysis of News Headlines from Media Company's Twitter Accounts
This project uses a Kaggle data and fits classification models that balances recall and precision metrics with an emphasis on model interpretability. The dataset includes trip specific data, passenger specific data, and survey data on various components of the air travel experience. The use case for these results is to empower airlines with information regarding passenger's expectations for the air travel experience. With these insights, airlines can triangulate what causes dissastisfaction, optimize the categories causing dissatisfaction, and predict whether a customer is dissatisfied without a customer participating in a post flight survey.

## Data Source: 

Data was scraped from Twitter user accounts of Reuters, AP, BBC, Financial Times, NYTimes, CNN, FoxNews, Daily Mail, ABC, NBC, Wall Street Journal, Bloomberg from 2016-2020.

## Tools Used:

- Postgres
- Python 3
- SNScrape
- NLTK
- Spacy
- Corex
- D3
- Vader Sentiment Analysis

## Conclusions
The best tool to meet this project's goal is CorEx. The topics discovered using CorEx were categorized into 8 topics:

1. Natural Disasters
2. Police & Crime
3. Domestic Government Affairs
4. International Affairs
5. Economy & Stock Market
6. Big Tech Companies
7. Sports & Entertainment
8. Coronavirus Pandemic

The sentiment was increasingly negative from 2016 to 2020.


## Outline of Files
- The ipynb files contain exploratory data analysis, CorEx topic modeling, and Vader sentiment analysis.
- The miscellaneous support file contains .py and .txt files for stop words.
- The CSVs and pickled dataframes contained 2.5 million preprocessed headlines. The files were too large to upload to Github. I can provide them upon request.
- The json file contains JS code to create a collapsible tree visualization.
- The pdf contains the final presentation.
