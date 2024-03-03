# TWITTER SENTIMENT ANALYSIS

## About:

The following project is about analyzing the sentiments of tweets on social networking website
‘Twitter’. The dataset for this project is scraped from Twitter. It contains 1,600,000 tweets
extracted using Twitter API. It is a labeled dataset with tweets annotated with the sentiment (0 =
negative, 2 = neutral, 4 = positive).
It contains the following 6 fields:

1. target: the polarity of the tweet (0 = negative, 2 = neutral, 4 = positive)

2. ids: The id of the tweet .

3. date: The date of the tweet (Sat May 16 23:58:44 UTC 2009)

4. flag: The query. If there is no query, then this value is NO_QUERY.

5. user: The user that tweeted

6. text: The text of the tweet.

## Problem Statement:

In today's digital age, social media platforms like Twitter have become a crucial medium for individuals to express their opinions and sentiments. For businesses, understanding the sentiment of Twitter users towards their brand is essential for maintaining a positive brand image and making informed marketing decisions. However, manually analyzing thousands of tweets to gauge sentiment is time-consuming and prone to human error. Therefore, there is a need for an automated system that can accurately analyze the sentiment of tweets related to a brand and provide actionable insights for brand management and marketing strategies. Design a classification model that correctly predicts the polarity of the tweets provided in the dataset.

## Model Creation Using LSTM:

The given Dataset has no null values yet the dataset is too big it would take too long and the dataset may underfit or lowerfit the data, so we are selecting a part of the dataset to prepare the model