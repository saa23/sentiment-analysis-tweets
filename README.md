# sentiment-analysis-tweets

# 1. Introduction
The Sentiment Analysis project aims to develop an intelligent system based on AI technology to classify sentiments on Twitter using the text analysis method. This system will help obtain positive, negative or neutral opinion sentiment trends from users on the platform.

The dataset used is a collection of tweets from Twitter users during the 2019 Presidential Election. The dataset was obtained through a web scraping process. The data consists of 1815 tweets that contain three categories of sentiment: positive, neutral and negative.

As for the algorithms, using **Random Forest** and **LSTM**.

# 2. Objectives
- Get an overview of public opinion regarding the upcoming 2019 Presidential Election
- Measuring the popularity of presidential election candidates based on public opinion

# 3. Methods
- Exploratory Data Analysis (EDA)
- Text pre-processing
    - Case folding
    - Punctuation removal
    - URL removal
    - Non-alphanumerical characters removal
    - Stopword removal
    - Stemming
    - Text Vectorization
- Split into Train, Validation, and Test set
- Develop Random Forest models
    - Hyperparameter Tuning
    - model evaluation
    - predict on test set
- Develop LSTM models
    - Hyperparameter Tuning
    - model evaluation
    - predict on test set