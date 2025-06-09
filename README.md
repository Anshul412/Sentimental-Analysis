This project analyzes recent tweets related to a given keyword or hashtag to determine the overall sentiment — positive, negative, or neutral — using Python, Flask, Tweepy, and sentiment libraries like VADER and TextBlob.

🔍 Features
Fetches real-time tweets using the Twitter API

Preprocesses tweet text (removes mentions, links, special characters)

Uses TextBlob for polarity and subjectivity analysis

Uses VADER for compound sentiment scoring

REST API endpoint (/analyze) returns structured sentiment data in JSON

🛠️ Tech Stack
Backend: Python, Flask

APIs: Twitter API (via Tweepy)

Sentiment Analysis: VADER (from NLTK), TextBlob
