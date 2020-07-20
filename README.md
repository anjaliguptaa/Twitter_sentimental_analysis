# Sentimental_analysis

Sentiment Analysis: the process of computationally identifying and categorizing opinions expressed in a piece of text, especially in order to determine whether the writer's attitude towards a particular topic, product, etc. is positive, negative, or neutral.

Natural Language Processing (NLP) is a unique subset of Machine Learning which cares about the real life unstructured data. Although computers cannot identify and process the string inputs, the libraries like NLTK, TextBlob and many others found a way to process string mathematically. Twitter is a platform where most of the people express their feelings towards the current context. As humans, we can guess the sentiment of a sentence whether it is positive or negative.

First of all, splitting the dataset into a training and a testing set. The test set is the 10% of the original dataset. For this particular analysis I dropped the neutral tweets, as my goal was to only differentiate positive and negative tweets.
As a next step I separated the Positive and Negative tweets of the training set in order to easily visualize their contained words. After that I cleaned the text from hashtags, mentions and links.
After the vizualization, I removed the hashtags, mentions, links and stopwords from the training set.

Stop Word: Stop Words are words which do not contain important significance to be used in Search Queries. Usually these words are filtered out from search queries because they return vast amount of unnecessary information. ( the, for, this etc. )
As a next step I extracted the so called features with nltk lib, first by measuring a frequent distribution and by selecting the resulting keys.

I used GetOldTweets3
It is a Python 3 library and a corresponding command line utility for accessing old tweets.
