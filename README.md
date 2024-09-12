# Flipkart Sentiment Analysis

![Flipkart Logo]([https://example.com/path/to/flipkart_logo.png](https://th.bing.com/th/id/OIP.Zbwq8CMb4CD6oaapV2vgSgHaEK?w=266&h=180&c=7&r=0&o=5&dpr=1.3&pid=1.7))



## Overview

This project performs sentiment analysis on product reviews collected from Flipkart. The objective is to classify reviews as positive, negative, or neutral using Natural Language Processing (NLP) techniques. The project utilizes the NLTK library for text preprocessing and a Naive Bayes classifier for sentiment classification. Evaluation of the model is done using various metrics, including accuracy, precision, recall, and F1-score.

## Dataset

The dataset for this project was collected from Kaggle and contains reviews of products from Flipkart. Each review is labeled as positive, negative, or neutral. The dataset is available in CSV format and should be placed in the project directory.

## Project Workflow

1. **Data Collection:** Reviews were collected from Kaggle.
2. **Data Preprocessing:** Clean and prepare the text data for analysis.
3. **Model Training:** Train a Naive Bayes classifier on the preprocessed data.
4. **Evaluation:** Evaluate the model using standard metrics such as accuracy, precision, recall, and F1-score.
5. **Prediction:** Use the trained model to predict the sentiment of new reviews.

## Preprocessing

The text data is preprocessed using the NLTK library. The following steps are performed:

- **Tokenization:** Splitting text into individual words.
- **Lemmatization:** Reducing words to their base or root form.
- **Stopword Removal:** Removing common words that do not add much meaning to the text (e.g., "and," "the").
- **Part-of-Speech Tagging:** Tagging words with their respective parts of speech.

## Model Implementation

We use a **Naive Bayes Classifier** for sentiment analysis. The steps for training the model are:

1. Vectorize the text data using **CountVectorizer**.
2. Split the data into training and test sets.
3. Train the Naive Bayes model on the training data.
4. Predict the sentiment of reviews in the test set.

## Evaluation Metrics

The model's performance is evaluated using the following metrics:

- **Accuracy:** Measures the percentage of correct predictions.
- **Precision:** Measures the percentage of true positive predictions out of all positive predictions.
- **Recall:** Measures the percentage of true positive predictions out of all actual positives.
- **F1-Score:** A weighted average of precision and recall.


