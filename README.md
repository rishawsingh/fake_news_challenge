# fake_news_challenge

## Objectives of this project-
- The objective of this project is to apply Supervised Machine Learning classifiers in order to detect the fake news by scraping data from web.
- We have done web scraping in order to collect data from “politifact” website that contains various news along with the labels(Fake/Real) of news. In order to make our prediction system we have taken 4870 records.

## Steps Of Implementation(Pipeline Of Building the System):
1) We started with Web scraping which was done using python library called BeautifulSoup
2) Data preprocessing of the data gathered after scraping which was followed by stemming and Word Cloud Formation.
3) Applied Modelling Feature extraction methods such as count vectorizer and TF-IDF
4) Data visualization
5) Multinomial naïve baye’s and logistic regression classifier
6) Fake news prediction system (we got naive bayes as best classifier model among all classifiers).

## Libraries Used for Fake News Detection System
numpy
pandas
matplotlib
re
nltk
sklearn 
TfidfVectorizer
seaborn

## Libraries Used for Web Scraping
BeautifulSoup
pandas
requests
urllib
time

## Result
the final result we got is that naive bayes is best model among all classifiers, so we are going to use Naive Bayes for our prediction. As Naive Bayes gave accuracy of 94.2% on training data and 90.3 % on testing data by using tf-idf.
