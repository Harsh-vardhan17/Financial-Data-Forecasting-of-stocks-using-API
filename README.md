# Stock Market Sentiment Analysis

This repository contains code and a dataset for analyzing the sentiment of stock market news articles and their potential effect on stock price movements. By utilizing sentiment analysis, we aim to assess how positive or negative news correlates with stock ticker performance.

## Project Overview

### Goal

The main objective of this project is to analyze financial news and derive insights from the sentiment conveyed in the articles. The sentiment analysis is then linked to stock tickers mentioned in the articles to identify potential patterns in stock market behavior.

### Approach

1. ### Data Collection: The dataset provided consists of news articles related to stock markets and includes a variety of fields, such as title, URL, publication time, authors, and sentiment scores.
2. ### Sentiment Scoring: Each article is analyzed for its sentiment score and categorized as either bullish, neutral, or bearish, based on both overall and ticker-specific sentiment scores.
3. ### Stock Market Impact: By correlating the sentiment with stock tickers, the analysis reveals how news sentiment might influence stock market trends.

## Dataset Description
The dataset (preprocessed_news_sentiment.csv) comprises 267 records.

![Tableau EDA Dashboard](https://github.com/user-attachments/assets/c782bf68-7676-4527-9233-3a3710f509bb)

## Analysis Pipeline

### Step 1: Data Exploration
The notebook starts by loading the dataset and examining its structure and contents.
Key attributes like sentiment scores, authors, and topics are explored to understand the data distributions and missing values.

### Step 2: Data Cleaning and Preprocessing
Handle missing values in certain columns, such as authors, and convert categorical data (e.g., day of the week) into a format suitable for analysis.
Convert date and time data to datetime format to enable time-based analysis.
Normalize sentiment scores to ensure that values fall within a comparable range.

### Step 3: Sentiment Analysis
Overall Sentiment: Evaluate the overall sentiment score for each article. Articles are labeled as "Bullish," "Neutral," or "Bearish" based on the sentiment score.
Ticker Sentiment: Each article's sentiment is also broken down by the stock tickers it mentions. This gives insight into the expected performance of individual stocks based on news sentiment.

### Step 4: Visualization and Insights
Sentiment trends over time are visualized, providing insights into how market sentiment fluctuates throughout the week.
Sentiment by topic and stock ticker is analyzed to see if certain sectors (e.g., Technology, Financial Markets) have more bullish or bearish sentiments.

### Step 5: Stock Market Impact Analysis
Correlate the sentiment scores with stock price data to analyze the impact of news sentiment on stock market movements. For example, how does a "Bullish" sentiment on a Friday affect the stock price on the following Monday?
Identify the top tickers that show the highest correlation between news sentiment and stock price changes.

## Results and Findings
The analysis reveals distinct patterns of how news sentiment influences stock price performance.
Certain stock tickers show strong correlations with sentiment scores, indicating potential opportunities for sentiment-based trading strategies.

# Contributing
Contributions are welcome! If you have suggestions for improvements or additional features, feel free to submit a pull request or open an issue.
