# INSTAGRAM INFLUENCERS (Exploratory Data Analysis)

## About:

Instagram is an American photo and video sharing social networking service founded in 2010 by
Kevin Systrom and Mike Krieger, and later acquired by American company Facebook Inc., now
known as Meta Platforms. The app allows users to share posts that can be shared publicly or
with pre-approved followers.

Instagram is very much used to influence people in a particular way for a specific issue - which
can impact the order in some ways.

## Problem Statement:

Answer the following questions based on the given data set:
1. Are there any correlated features in the given dataset? If yes, state the correlation
coefficient of the pair of features which are highly correlated.
2. What is the frequency distribution of the following features?
○ Influence Score
○ Followers
○ Posts

3. Which country houses the highest number of Instagram Influencers? Please show the
count of Instagram influencers in different countries using barchart.
4. Who are the top 10 influencers in the given dataset based on the following features
● Followers
● Average likes
● Total Likes
5. Describe the relationship between the following pairs of features using a suitable graph
● Followers and Total Likes
● Followers and Influence Score
● Posts and Average likes
● Posts and Influence Score


## EDA Processs:

Before starting EDA process the dataset has to be checked for null values and dealt with it with mean, meadian or mode. After preprocessing the data there goes the EDA process as er the problem statement. 

1. For checking the correlation between the features, I used correlation matrix and heatmap for the correlation distribution. The value of 0.7 to 1 indicates the high possitive correlation and between -0.7 to -1 will show high negative correlation.

2. Frequency distribution of, Influence score, followers and Posts are displayed using histplot by seaborn and matplotlib.

3. Highest number of instagram influencers are ordered by countrywise.

4. Top 10 influencers are displayed by the Followers , Average Likes and Total likes with the help of histplot.

5. The relationship between Followers and Total likes are distributed with like plot.
The relationship between Followers and influence score was distributed by scatterplot.
The relationship between Posts and Average Likes was distributed by Histplot.
The relationship between Posts and Influence Score was distributed by Histplot.