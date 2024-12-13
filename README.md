# Sentiment_Analysis(In Progress)
Building a social media sentiment analysis model

Project Description: In this project, I am performing sentiment analysis on Twitter data using PySpark. The goal is to analyze the sentiments expressed in tweets  and gain insights into the overall sentiment. These sentiments can be potentially be further analyzed to gain insigts of public opinion towards various topics like elections, geo-political events and more.

## The Approach:

### STEP 1

In the first phase of the project I employed the fundamental process of sentiment analysis utilising python and sklearn libraries.

I performed the following steps:

1. Importing libraries
2. Read and load data
3. EDA
4. Data visualisation
5. Splitting data
6. Data preprocessing
7. Vector transformation
8. Model building and evaluation
9. Hyperparameter tuning
10. Saving model
11. Loading model

### Model Used
1. Bernoulli Naive Bayes Classifier
2. SVM (Support vector machine)
3. Logistic regression   


### STEP 2

Next phase of the project involves transitioning the above process in to a distributed framework using pysparks. This step will help address the scalability issue and improve the processing time.

Additionally, the pysparks library will enable implementation of the below features which can help improve the performance of the model.

### Features 
Hashing TF-IDF
Count Vectorizer TF-IDF
ChisQSelector
1-Gram, 2-Gram, 3-Gram

Furthermore, this step will enable the deployement of this offline project into real-time processing.

### STEP 3

In the final phase of this project I will implement an ETL process for sentiment analysis of tweets in real time. The idea here is to use the best model tested offline and deploy it online for real-time analysis. For this, I will be using Docker, Apache Kafka and Spark Streaming. 
