# Covid19-Vaccine-Twitter-data-Analysis
This project focuses on analyzing sentiment towards COVID-19 vaccines using tweets collected with QnScrape, a web scraping tool, and processed with TextBlob and a Recurrent Neural Network (RNN).

## Collecting the Data
To collect tweets about COVID-19 vaccines, we used QnScrape to scrape Twitter for relevant tweets. QnScrape allows for easy scraping of Twitter and other websites using keywords and other search parameters.

We collected 63000 tweets about COVID-19 vaccines using QnScrape

## Preprocessing the Data
Before running sentiment analysis, we preprocessed the tweets by removing URLs, user mentions, and special characters using Python's regular expressions library.

We also used TextBlob, a Python library for processing textual data, to tokenize the tweets and remove stopwords.

Finally, we split the preprocessed data into training and testing sets.

## Sentiment Analysis
We used two methods for sentiment analysis: TextBlob and a Recurrent Neural Network (RNN).

TextBlob uses a pre-trained sentiment analysis model to assign a polarity score to each tweet. The polarity score ranges from -1 (negative sentiment) to 1 (positive sentiment).

The RNN was trained on the preprocessed data using Keras, a deep learning framework in Python. The RNN model takes in the preprocessed tweet text and outputs a polarity score.

## Results
Here we obtain 45.57% of total tweets with positive sentiments, 37.10% of total tweets with neutral sentiments and 17.33% of total tweets with negative sentiments.

## Conclusion
In this project, we analyzed sentiment towards COVID-19 vaccines using tweets collected with QnScrape, preprocessed with TextBlob, and analyzed with an RNN. The results showed that the negative sentiments still exists among people with respect to vaccination.

This project demonstrates the potential of machine learning in analyzing public sentiment towards important issues such as vaccination during a pandemic.
