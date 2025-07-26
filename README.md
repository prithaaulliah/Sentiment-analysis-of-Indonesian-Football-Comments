# Sentiment-analysis-of-Indonesian-Football-Comments

---

Sentiment Analysis of Football Comments on Twitter

This project aims to analyze the sentiment of Twitter users' comments related to football. The analysis was conducted using a machine learning-based approach using Euclidean comparison and Cosine Similarity methods. Data was collected through web scraping directly from Twitter.

Objective

To analyze public opinion on football through Twitter comments, based on:

* Sentiment Categories: Positive, Negative, Neutral
* Aspects Assessed: Quality, Price, Camera

Note: Aspects such as "price" and "camera" were used as experiments to classify opinions based on multi-faceted contexts and are not direct attributes of football.

Tools and Technologies

* Python
* snscrape or tweepy (for Twitter scraping)
* pandas, numpy
* scikit-learn
* NLTK or Sastrawi (for preprocessing)
* Matplotlib or Seaborn (for visualization)

2. Workflow

1. Scraping data from Twitter using football-related keywords
2. Text preprocessing:
-Case folding
-Tokenization
-Stopword removal
-Stemming
3. Feature extraction using TF-IDF
4. Sentiment classification based on:

* Euclidean distance
* Cosine similarity
5. Accuracy evaluation and comparison
6. Results visualization

Generated Output

* Sentiment distribution graph (positive, negative, neutral)
* Euclidean vs. Cosine performance comparison graph
* Analysis by aspect (quality, price, camera)

