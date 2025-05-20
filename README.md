### Bitcoin Sentiment Analysis Project

This project analyzes the relationship between Bitcoin's price movements and social media sentiment, specifically focusing on tweets mentioning Bitcoin. This project was made for the UC San Diego course COGS 108 (Data Science in Practice)

### Video Link

[Project Video](https://www.google.com/search?q=https://youtu.be/jjbkAn3vpIs)

### Names

  * Parv Chordiya: Data Wrangling, Sentiment Analysis, EDA2
  * Vivek Rane: Finding Datasets, Data Cleaning, EDA, Correlation Matrix
  * Sonakshi Mohanty: Discussion, Limitations, Conclusion, Analyzing Code for Description, Team Expectations
  * Rahul Bulsara: Overview, Discussion, Ethics and Privacy Concerns

### Overview

The project aims to analyze the trend of Bitcoin's value in comparison to discussions on social media, particularly tweets. Data was gathered from Kaggle, including historical Bitcoin prices and related tweets. The analysis sought to find a relationship between Bitcoin's price and social media sentiment. The findings suggest that there is no direct relationship where positive or negative trends in tweets significantly influence the cryptocurrency's value.

### Research Question

Can a measurable correlation be identified between specific social media sentiment indicators (such as counts of positive, neutral, and negative posts) on platforms like X (formerly Twitter) and key Bitcoin price metrics? Specifically, this project aimed to analyze whether changes in sentiment on these platforms are associated with variations in Bitcoin’s price volatility, daily closing price, and trading volume over defined time frames. Sentiment was measured by categorizing posts as positive, neutral, or negative based on commonly used sentiment indicators.

### Hypothesis

It was hypothesized that a positive correlation exists between social media sentiment towards Bitcoin and Bitcoin's price metrics.

  * **Positive Sentiment Hypothesis**: Increases in the proportion of positive Bitcoin mentions on social media (categorized by optimistic words like "bullish," "gains," or "buy") would correlate with an increase in Bitcoin's closing price, trading volume, or price volatility.
  * **Negative Sentiment Hypothesis**: Conversely, increases in negative mentions (identified by pessimistic terms like "bearish," "losses," or "sell") would correlate with a decrease in these metrics.

### Data

The project utilized two main datasets:

  * **Bitcoin Historical Data**

      * [Link to the dataset](https://www.google.com/search?q=https://www.kaggle.com/datasets/mczielinski/bitcoin-historical-data/data%3Fselect%3Dbtcusd_1-min_data.csv)
      * Number of observations: \~6,712,281
      * Number of variables: 6
      * This dataset includes historical Bitcoin market data at 1-minute intervals, with important variables such as 'Open', 'Close', and 'Volume'. The data, starting from 2012, was filtered to include observations from 2021 to the present to align with the tweets dataset.

  * **Bitcoin Tweets**

      * [Link to the dataset](https://www.kaggle.com/datasets/kaushiksuresh147/bitcoin-tweets)
      * Number of observations: \~4,689,354
      * Number of variables: 13
      * This dataset contains tweets with '\#Bitcoin' and '\#Btc' hashtags, updated daily since June 2, 2021. Key variables include 'date' (UTC time of tweet) and 'text' (actual tweet content), used for sentiment analysis.

### Results

The sentiment was found to be very noisy. After scaling both Bitcoin prices and sentiment scores, a mild positive correlation was observed between average sentiment and Bitcoin's price variables (open, high, low, and close). The scatterplot specifically showed a correlation coefficient of **0.37** between Average Sentiment and BTC Price Low.

### Conclusion

Our study aimed to investigate the causal relationship between social media sentiment and Bitcoin market behavior. The findings from this dataset indicate that social media sentiment did not have a significant impact on predicting Bitcoin market behavior and price action. Instead, the study learned that there is a strong causal relationship between Bitcoin market behavior and social media sentiment. This suggests that rather than social media driving Bitcoin prices, Bitcoin's price movements may influence discussions and sentiment on social media platforms.
