<p align="center">
  <img src="banner.png" alt="Airline Sentiment Analysis Banner" width="100%">
</p>
## Project Preview

Below are key visual outputs generated in this project.

### 1) Sentiment Distribution
<p align="center">
  <img src="outputs/figures/fig_01_sentiment_distribution.png" width="85%">
</p>

### 2) Tweets per Airline
<p align="center">
  <img src="outputs/figures/fig_02_tweets_per_airline.png" width="85%">
</p>

### 3) Top Negative Reasons
<p align="center">
  <img src="outputs/figures/fig_03_top_negative_reasons.png" width="85%">
</p>

### 4) WordCloud (Negative Tweets)
<p align="center">
  <img src="outputs/figures/fig_04_wordcloud_negative_tweets.png" width="85%">
</p>

### 5) Confusion Matrix (TF-IDF + Logistic Regression)
<p align="center">
  <img src="outputs/figures/fig_05_confusion_matrix_tfidf_logreg.png" width="70%">
</p>

### 6) Airline vs Sentiment Breakdown
<p align="center">
  <img src="outputs/figures/fig_06_airline_sentiment_breakdown.png" width="85%">
</p>
Airline Sentiment Analysis using NLP and Transformers
AirlineSentimentAI
NLP Sentiment Analysis of Airline Tweets

This project builds an end-to-end Natural Language Processing (NLP) pipeline to classify airline tweets into negative, neutral, and positive sentiment using machine learning and transformer models.

The dataset used is the Twitter US Airline Sentiment dataset from Kaggle, containing 14,640 customer tweets directed at major US airlines.

Project Objectives

The main goal of this project is to analyse airline customer feedback on Twitter and build models that automatically classify sentiment.

Key objectives:

Understand airline customer feedback patterns

Perform exploratory data analysis

Build a baseline machine learning model

Evaluate model performance

Explore modern transformer models for improved sentiment classification

Dataset

Source: Kaggle – Twitter US Airline Sentiment

Key features of the dataset:

14,640 tweets

Sentiment labels:

Negative

Neutral

Positive

Airlines included:

United

American

Delta

Southwest

US Airways

Virgin America

The primary feature used for modeling is the tweet text.

Project Workflow

The project follows a structured NLP pipeline:

Data Loading

Exploratory Data Analysis

Sentiment Distribution Analysis

Negative Tweet Insights

Text Cleaning & Preprocessing

Feature Engineering using TF-IDF

Logistic Regression Baseline Model

Model Evaluation

WordCloud Visualization

Feature Importance Analysis

Transformer Model Upgrade (DistilBERT)

Exploratory Data Analysis

The dataset shows a strong imbalance toward negative sentiment, reflecting common airline complaints.

Frequent complaint topics include:

Flight delays

Customer service issues

Flight cancellations

Long wait times

Visualizations include:

Sentiment distribution

Tweets per airline

Negative complaint reasons

WordCloud Analysis

A WordCloud was generated using negative tweets to highlight common complaint keywords.

Common terms included:

delay

cancelled

hours

customer service

hold

This provides insight into the most frequent airline service issues.

Baseline Model

A baseline sentiment classifier was built using:

TF-IDF + Logistic Regression

This approach converts text into numerical features using TF-IDF and trains a classifier to predict tweet sentiment.

Evaluation metrics include:

Accuracy

Precision

Recall

F1 Score

Confusion Matrix

Model Evaluation

Model performance was evaluated on a test dataset.

The confusion matrix helps visualize:

correct predictions

misclassifications

class imbalance effects

Feature Importance

Logistic Regression coefficients were analyzed to identify words strongly associated with each sentiment category.

Examples:

Negative words

delay

cancelled

worst

hours

customer service

Positive words

thanks

great

appreciate

awesome

This provides transparency into how the model interprets language.

Advanced Model (Transformer)

To improve performance, the project introduces DistilBERT, a transformer-based NLP model.

Benefits of transformer models:

better contextual understanding

improved semantic representation

stronger performance on complex language patterns

DistilBERT provides a modern deep-learning alternative to traditional TF-IDF models.

Technologies Used

Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
WordCloud
PyTorch
HuggingFace Transformers

Future Improvements

Possible extensions include:

Hyperparameter tuning

Fine-tuning DistilBERT

Error analysis of misclassified tweets

Deploying the model with Streamlit

Real-time sentiment monitoring dashboards

Author

Noor Saba
Aspiring Data Scientist | AI & Machine Learning Enthusiast