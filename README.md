# Natural Language Processing (NLP) in Machine Learning

This repository stores the Jupyter Notebooks of the Kaggle NLP competitions I participated in before.

The competitions are:

## [BBC News Classification](https://www.kaggle.com/competitions/learn-ai-bbc)

[![Open in Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/dazhengzhu/bbc-news-classification) | [Notebook](https://github.com/zac4j/nlp/blob/main/bbc-news-classification.ipynb)

### Description

Text documents are one of the richest sources of data for businesses.

We’ll use a public dataset from the BBC comprised of 2225 articles, each labeled under one of 5 categories: business, entertainment, politics, sport or tech.

The dataset is broken into 1490 records for training and 735 for testing. The goal will be to build a system that can accurately classify previously unseen news articles into the right category.

The competition is evaluated using Accuracy as a metric.

Following blog has good information on how to look at the problem. https://cloud.google.com/blog/products/gcp/problem-solving-with-ml-automatic-document-classification

### Model Performance

|       |     Model Name     | Accuracy |   Score  |
|-------|:------------------:|:--------:|:--------:|
| Train | LogisticRegression | 0.974497 |          |
|       | MultinomialNB      | 0.970470 |          |
|       | NMF                | 0.948993 |          |
|       | SVC                | 0.977852 |          |
| Test  | SVC                |          | 0.98503  |

## [Natural Language Processing with Disaster Tweets](https://www.kaggle.com/competitions/nlp-getting-started)

[![Open in Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/dazhengzhu/nlp-with-disaster-tweets) | [Notebook](https://github.com/zac4j/nlp/blob/main/disaster_tweets_classification.ipynb)

### Description

This particular challenge is perfect for data scientists looking to get started with Natural Language Processing. The competition dataset is not too big, and even if you don’t have much personal computing power, you can do all of the work in our free, no-setup, Jupyter Notebooks environment called Kaggle Notebooks.

If you want to talk with other users about this competition, come join our Discord! We've got channels for competitions, job postings and career discussions, resources, and socializing with your fellow data scientists. Follow the link here: https://discord.gg/kaggle

### Model Performance

|       | Model Name | Accuracy |   Score  |
|-------|:----------:|:--------:|:--------:|
| Train | RNN        | 0.953125 |          |
|       | DistilBERT | 0.962623 |          |
| Test  | DistilBERT |          |  0.80232 |
