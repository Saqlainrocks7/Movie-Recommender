# Movie Recommendation System
## Overview
## 1st Part
At first a simple recommendation system is made that recommends the top items based on a certain metric or score.The weighted rating formula is used as a metric/score. Mathematically, it is represented as follows:
WeightedRating(WR)=((v/(v+m)).R)+((m/(v+m)).C)
In the above equation,

    v is the number of votes for the movie;

    m is the minimum votes required to be listed in the chart;

    R is the average rating of the movie;

    C is the mean vote across the whole report.
    
## 2nd Part   
Then, to improve the recommendation system we have used content-based recommendation.I have computed pairwise cosine similarity scores for all movies based on their plot descriptions and recommended movies based on that similarity score threshold.The plot description is available to you as the 'overview' feature in the dataset.I have computed Term Frequency-Inverse Document Frequency (TF-IDF) vectors for each document.The TF-IDF score is the frequency of a word occurring in a document, down-weighted by the number of documents in which it occurs. This is done to reduce the importance of words that frequently occur in plot overviews and, therefore, their significance in computing the final similarity score. 

## Motivation
As a movie lover, I have always wanted to do some machine learning project reagarding recommendation of movies. It is my first attempt to make a movie recommendation system and will try to make more such recommendations in future.
