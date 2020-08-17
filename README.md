# Sentiment-Analysis
Using tweepy, textblob and wordcloud libraries to perform sentiment analysis on a twitter user's tweets

## What is Sentiment Analysis ?
Sentiment analysis is basically the process of determining the attitude or the emotion of the writer, i.e., whether it is positive or negative or neutral.

## Tweepy
Tweepy is an easy-to-use Python library for accessing the Twitter API with python. The Twitter API gives developers access to most of Twitter’s functionality. You can use the API to read and write information related to Twitter entities such as tweets, users, and trends.

The Twitter API uses OAuth, a widely used open authorization protocol, to authenticate all the requests. Before making any call to the Twitter API, you need to create and configure your authentication credentials. Create a twitter developer account and register an app and state its purpose after heich you will get the authentication credentials under the  Keys and tokens tab.

The Twitter API also imposes rate limits about how frequently you’re allowed to invoke API methods. If you exceed these limits, you’ll have to wait between 5 and 15 minutes to be able to use the API again.

## Word Cloud
A Wordcloud (or Tag cloud) is a visual representation of text data. It displays a list of words, the importance of each being shown with font size or color. This format is useful for quickly perceiving the most prominent terms. Python is totally adapted to draw this kind of representation, thanks to the wordcloud library developed by Andreas Mueller. 

## Text Blob
TextBlob is a Python (2 and 3) library for processing textual data. It provides a simple API for diving into common natural language processing (NLP) tasks such as part-of-speech tagging, noun phrase extraction, sentiment analysis, classification, translation, and more.

The sentiment function of textblob returns two properties, polarity, and subjectivity.

Polarity is float which lies in the range of [-1,1] where 1 means positive statement and -1 means a negative statement. Subjective sentences generally refer to personal opinion, emotion or judgment whereas objective refers to factual information. Subjectivity is also a float which lies in the range of [0,1].
