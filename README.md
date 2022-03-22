# Twitter-sentiment-analaysis---Mood-analysis-in-5-US-states
Sentiment analysis using recent tweets with a specific hashtag from a number of states in the US

# Overview:
In this notebook, we will be looking at sentiment analysis using recent tweets with a specific hashtag from a number of states in the US. <br>

This notebook provides the code to:
- Automatically get longitude and lattitude information from geocode.xyz to feed into locator of tweet identifier
- Use tweepy package to extract most recent tweets based on search_word, specified date (all tweets up to this date) and location of users
- Clean extracted tweets
- Analyse sentiments of cleaned tweets using TextBlob by assining a polarity coefficient to each:
    - TextBlob is a Lexicon-based or rule-based sentiment analyser. Each word is given a score based on a predefined word and weight dictionary. The aggregation of these individual scores result in an estimate for the sentence's polarity
- Aggregate findings to map out relative sentiment in locations of interest

<b> Note: </b> Both Twitter API and geocode.xyz API limit the number of searches that you can run using tokens and authentification code
