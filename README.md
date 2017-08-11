# Kaggle_HomeDepot
Kaggle Machine Learning competition for Home Depot dataset

Competition link: https://www.kaggle.com/c/home-depot-product-search-relevance

## Project Description

### Software used: spark, ipython, mongodb, pymongo, nltk, gensim 

### Feature engineering 
1. Full search text match 
2. Unigram search text match 
3. Combination of full search text and unigram search text match 
4. Synonym search using gensim
5. Bigram search text match 
6. LDA topic model using NLTK

### Data processing pipeline
1. Read data from mongoDB
2. Tokenization using NLTK
3. Using feature engineering to define similarity calculator for each model 
4. Train RandomForestRegressor & RandomForestClassifier  model using PySpark
5. Evaluate and make prediction using the model
6. Store the prediction result in mongoDB 
