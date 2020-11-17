# Topic Modeling & Sentiment Analysis of News Headlines from Media Company's Twitter Accounts
This project uses a data scraped from Twitter to analyze headlines posted by news media outlets from 2016 to 2020. Once the data is preprocessed and an NLP pipeline is created, topic modeling is used to discover topics in the data with an emphasis on topic separability. The 2.5 million headlines are then analyzed using Vader sentiment analysis to measure sentiment (negative, positive, or neutral) over time.

## Data Source: 

Data was scraped from Twitter user accounts of Reuters, AP, BBC World, Financial Times, NYTimes, CNN, Fox News, Daily Mail, ABC, NBC News, Wall Street Journal, Bloomberg, Forbes, Huffington Post, and Washington Post from 2016-2020. A total of 2.5 million headlines were scraped.

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
- The ipynb files contain code to scrape Twitter user accounts wtih SNScrape, exploratory data analysis, an NLP pipeline, CorEx topic modeling, and Vader sentiment analysis.
- The miscellaneous support file contains .py and .txt files for stop words.
- The CSVs and pickled dataframes contain 2.5 million preprocessed headlines. The files are too large to upload to Github. I can provide them upon request.
- The json file contains JS code to create a collapsible tree visualization.
- The pdf contains the final presentation.
