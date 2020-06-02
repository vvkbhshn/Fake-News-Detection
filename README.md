# Fake-News-Detection
## PROBLEM OVERVIEW:
Develop a machine learning program to identify when a news source may be producing fake news.
'''
We aim to use a corpus of labeled real and fake new articles to build a classifier that can make
decisions about information based on the content from the corpus.
'''
## DATASET DESCRIPTION:
● Train.csv : A full training dataset with the following attributes.
■ id: unique id for a news article
■ title: the title of a news article
■ author: author of the news article
■ text: the text of the article; could be incomplete
■ label: a label that marks the article as potentially unreliable
● 1: unreliable
● 0: reliable
● test.csv: A testing training dataset with all the same attributes at train.csv without the label.
REQUIREMENTS:- numpy , tensorflow , pandas , nltk , gensim , keras , matplotlib , scikitplot
This repository contains three models:-
1. LSTM model
2. Naive-Bayes model
3. SVM model
COMPARISON OF ACCURACY:-
1. LSTM - 93.72 %
2. NAIVE BAYES - 72.31 %
3. SVM - 91.76 %

REFERENCES:-
Kaggle dataset : https://www.kaggle.com/c/fake-news/data
