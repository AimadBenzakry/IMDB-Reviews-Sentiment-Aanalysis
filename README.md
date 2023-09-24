# IMDB-Reviews-Sentiment-Aanalysis

This mini project is a quick start to learn how to apply Sentiment Analysis on user reviews.
I used data from IMDB movie reviews, and bert-base-multilingual-uncased model finetuned for sentiment analysis to analyze and preprocess text of each review.

How it works briefly:  

1. Input: You start with a movie title.
2. IMDbPY Search: You use the IMDbPY package to search for user reviews related to that specific movie.
3. Bert Model: You apply your BERT (Bidirectional Encoder Representations from Transformers) model to the reviews. BERT is a powerful pre-trained natural language processing model known for its performance on various NLP tasks.
4. Sentiment Scores: The BERT model provides sentiment scores for each review. These scores indicate the sentiment or emotion expressed in each review.


## Installation
make sure to install pytorch properly from the official website https://pytorch.org/
and then install the following dependencies in your terminal:

  pip3 install imdbpy 
  
  pip3 install transformers requests
