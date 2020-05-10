# Twitter-Sentiment-Analysis
The objective of this task is to detect hate speech in tweets. For the sake of simplicity, we say a tweet contains hate speech if it has a racist or sexist sentiment associated with it. So, the task is to classify racist or sexist tweets from other tweets.
Formally, given a training sample of tweets and labels, where label ‘1’ denotes the tweet is racist/sexist and label ‘0’ denotes the tweet is not racist/sexist, our objective is to predict the labels on the given test dataset.

## Evaluation Metric
The metric used for evaluating the performance of classification model would be F1-Score.
The metric can be understood as :

* **True Positives (TP)** 
These are the correctly predicted positive values which means that the value of actual class is yes and the value of predicted class is also yes.
* **True Negatives (TN)**
These are the correctly predicted negative values which means that the value of actual class is no and value of predicted class is also no.
* **False Positives (FP)** 
When actual class is no and predicted class is yes.
* **False Negatives (FN)** 
When actual class is yes but predicted class in no.
* **Precision = TP/TP+FP**
* **Recall = TP/TP+FN**
* __F1 Score = 2*(Recall * Precision) / (Recall + Precision)__
* F1 is usually more useful than accuracy, especially if for an uneven class distribution

## The course is divided into below modules:
* Text Preprocessing
* Data Exploration
* Feature Extraction
* Model Building

## Table Of Content
1. Tweets Preprocessing and Cleaning
* Data Inspection
* Data Cleaning
2. Story Generation and Visualization from Tweets
3. Extracting Features from Cleaned Tweets
* Bag-of-Words
* TF-IDF
* Word Embeddings
4. Model Building: Sentiment Analysis
* Logistic Regression
* Support Vector Machine
* RandomForest
* XGBoost
5. Model Fine-tuning
6. Summary
