# Social-Media Sentiment Analysis using Machine Learning
*Depression and Anxiety Detection using NLP on Social Media Messages .*

## Abstract
Social media platforms have become integral sources for expressing opinions, sentiments, and emotions on diverse topics. Analyzing this vast amount of textual data is challenging but holds immense value for businesses, brands, and researchers. This abstract introduces a machine learning (ML) approach to sentiment analysis on social media data.

The primary objective is to develop a robust sentiment analysis model capable of discerning and categorizing sentiments expressed in user-generated content on social media.

The methodology employs Natural Language Processing (NLP) and machine learning techniques. Initially, data is collected from social media platforms, encompassing a range of user-generated texts. Preprocessing steps include tokenization, stemming, and removal of stop words. Feature extraction is performed using techniques like TF-IDF or word embeddings.

Several ML algorithms, such as Support Vector Machines (SVM), Naive Bayes, or deep learning architectures like Recurrent Neural Networks (RNN) or Transformers, are trained on labeled datasets for sentiment classification. The model is fine-tuned iteratively to enhance performance.



## About The Project
The project is classfied into 5 steps:
- Step 1: Gathering Data 
- Step 2: Cleaning Data
- Step 3: Data Analysis
- Step 4: Model
- Step 5: Testing and Analysing Model

## Step 1: Gathering Data
 The databases used are:
 -  https://www.kaggle.com/gargmanas/sentimental-analysis-for-tweets
 -  https://www.kaggle.com/kazanova/sentiment140
 



## Step 2: Cleaning Data

Enhancing the quality of provided data for more accurate predictions is a crucial stage. The data cleansing procedure employs a variety of tools and libraries to refine data through actions such as:
- Eliminating stop words
- Applying lemmatization (transforming words to their root form)
- Eliminating non-word characters, single characters, spaces, URLs, etc.

## Step 3: Data Analysis

The analysis of the refined data included the generation of word clouds. Three distinct word clouds were crafted to enhance data visualization:
- Word Cloud depicting sentiments related to depression.
- Word Cloud illustrating tweets containing both depressive and negative content.
- Word Cloud showcasing positive tweets.

## Step 4: Model

Key Steps:
- Splitting data into train and test sets
- Vectorizing input to input into model

## Step 5: Testing and Analysing Model
The  summary of the observations of this step is given below:

              precision    recall  f1-score   support

          -1       0.93      0.70      0.80       430
           0       0.78      0.75      0.76    160202
           4       0.76      0.79      0.78    161431

    accuracy                           0.77    322063
    macro avg       0.82      0.75     0.78    322063
    weighted avg     0.77      0.77    0.77    322063


## Local Installation:

Download the databases and put them in the same directory as this project and Run Jupyter Notebook on this directory.
