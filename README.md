# A Sentiment Analysis of COVID-19 Tweets and its effects on Likeability and Retweet-ability
Data Analytics (Capstone) Project for Ryerson University CIND 820, Fall 2020

## Overview

This capstone project was created for Ryerson University course CIND 820 - Big Data Analyst Project.

In this project, we attempted to create new features using NLTK library to and then build regression models to predict whether sentiment score contribute to retweets or likes with the intention to better understand whether a tweet’s sentimentality can influence how it resonates with other readers.

## Approach

The summary of approach is as follows:

1. Download and Prepare Dataset
2. Hydrate Dataset
3. Preload Setup
4. Import Dataset
5. Perform Data Cleaning
6. Conduct Sentiment Analysis
7. Conduct Basic Analysis
8. Build Prediction Model for "Favourite Count" with Linear Regression
9. Build Prediction Model for "Retweet Count" with Linear Regression
10. Build Linear Regression with k-Fold
11. Build Polynomial Regression
12. Build Polynomial Regression with k-Fold

## Results

Our regression models were able to predict `favorite_count` and `retweet_count` to some extent. However, based on observations from sampling the scatterplots, there are reasonable doubts that under count of less than 20 for `favorite_count` and less than 25 for `retweet_count` will not yield any meaningful prediction. `Favorite_count` and `retweet_count` is highly correlated with each other and has the highest coefficient; significantly contribute to each other’s prediction model. 

For more details, read AndyLee-FinalReport.docx.

