# Tales-from-the-Crypto

## News API

The first part of this activity pulls the latest news articles for bitcoin and ethereum from the news api and creates a DataFrame for each with sentiment scores for each coin. We end by creating a summary of the bitcoin and ethereum DataFrames separately. 

#### Questions:

Q: Which coin had the highest mean positive score?

A: Bitcoin had the highest mean score of .0605.

Q: Which coin had the highest compound score?

A: Ethereum had the highest compound score of .1366.

Q: Which coin had the highest negative score?

A: Bitcoin had the highest negative score of .0257.

Q. Which coin had the highest positive score?

A: Ethereum had the highest positive score of .9164.

## Tokenizer

I used NLTK and Python to tokenize the text for each coin.I had to lowercase each word, remove punctuation, remove stopwords and create "Token" columns for each coin.

## NGrams and Frequency Analysis

I looked at the ngrams and word frequency for each coin and used NLTK to produce the n-grams for N = 2. I also listed the top 10 words for each coin.

## Wordclouds

I generated word clouds for each coin to summarize the news for each coin. The words with greater frequency in articles appear larger.

## Named Entity Recognition

In this section, I combined the bitcoin text and the ethereum text separately. I then ran the NER processor on all of the text to categorize and color code the words in the text.