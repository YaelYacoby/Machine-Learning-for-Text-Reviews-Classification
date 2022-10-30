# Machine-Learning-for-Text-Reviews-Classification

The Film Junky Union, a new edgy community for classic movie enthusiasts, is developing a system for filtering and categorizing movie reviews. 
The goal is to train a model to automatically detect negative reviews. 
You'll be using a dataset of IMBD movie reviews with polarity labelling to build a model for classifying positive and negative reviews.

## Data Description
The data was provided by Andrew L. Maas, Raymond E. Daly, Peter T. Pham, Dan Huang, Andrew Y. Ng, and Christopher Potts. (2011). Learning Word Vectors for Sentiment Analysis. The 49th Annual Meeting of the Association for Computational Linguistics (ACL 2011).
Here's the description of the selected fields:
* `review`: the review text
* `pos`: the target, '0' for negative and '1' for positive
* `ds_part`: 'train'/'test' for the train/test part of dataset, correspondingly

## Workflow Steps
* Categorized IMDB movie reviews into positive and negative clusters using multinominal Naive Bays and logistic regression classifiers.
* Analyzed preliminary data using descriptive statistics and handled anomalies such as duplicates and missing values.
* Developed NLP models for sentiment analysis, working with the NLTK library and creating pipelines to process and find patterns.

