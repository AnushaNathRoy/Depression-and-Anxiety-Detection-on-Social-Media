# Depression-and-Anxiety-Detection-on-Social-Media
*Depression and Anxiety Detection using NLP on Social Media Messages .*

## Abstract
This project dives into the working of Natural Language Processing for Sentiment Analysis applying concepts of Data Sciences and Machine Learning. The project explores in detail the process of sentiment analysis right from tagging and labelling data and classifying sentiments manually to creating a ML Model to automate this prediction.

Depression and Anxiety are alarmingly becoming common in today's mordern stressful world. It leads to adverse effects and consequences both for the person themselves and all their loved ones. Early prediction especially using text messages on social media platform will help people seek help and prevent adverse consequence.



## About The Project
The project can be divided into 5 step process:
- Step 1: Gathering Data 
- Step 2: Cleaning Data
- Step 3: Data Analysis
- Step 4: Model
- Step 5: Testing and Analysing Model

## Step 1: Gathering Data
 The databases used are:
 -  https://www.kaggle.com/gargmanas/sentimental-analysis-for-tweets
 -  https://www.kaggle.com/kazanova/sentiment140
 

**Labelling the data and analysising sentiments:**
The csv file contains manual labeling of sentiment words and manual analysis of sentiment. This has been recorded along with a sentiment analyser's output.
[https://github.com/AnushaNathRoy/Depression-and-Anxiety-Prediction-on-Social-Media/blob/main/SentimentAnalysisData.csv]

**Analysis and observations on sentiment analysis:**
This manual labelling gave a lot of insights on the drawbacks of automation of sentiment analysis and scopes for improvement.
[https://github.com/AnushaNathRoy/Depression-and-Anxiety-Prediction-on-Social-Media/blob/main/SentimentAnalysis.pdf]

## Step 2: Cleaning Data

Cleaning the given data for better prediction is an important step. The cleaning process used various tools and libraries to clean data by: 
- Removing stop words 
- Lemmatization (Coverting to Root Words)
- Removing non-word charecters, single charecter, spaces , URLs, etc.

## Step 3: Data Analysis

Data analysis of the cleaned data involved creating wordclouds. There are 3 wordclouds created for better data visualisation:
- WordCloud on Depression Sentiments
- WordCloud on Depressive + Negative Tweets
- WordCloud on Positive Tweets

## Step 4: Model

Key Steps:
- Splitting data into train and test sets
- Vectorizing input to input into model

## Step 5: Testing and Analysing Model
The observation made in this step can be summarised below:

              precision    recall  f1-score   support

          -1       0.93      0.70      0.80       430
           0       0.78      0.75      0.76    160202
           4       0.76      0.79      0.78    161431

    accuracy                           0.77    322063
    macro avg       0.82      0.75     0.78    322063
    weighted avg     0.77      0.77    0.77    322063


## Local Installation:

Download the databases and put them in the same directory as this project and Run Jupyter Notebook on this directory.
