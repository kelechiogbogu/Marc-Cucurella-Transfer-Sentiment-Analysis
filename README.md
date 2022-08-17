# Sentiment Analysis of the news of Marc Cucurella's transfer to Chelsea Football Club.
On the 5th of August an official announcement was made by the Chelsea football club official twitter handle, confirming the news of their new contract with Spanish Professional footballer, Marc Cucurella. This announcement sparked a lot of reactions from Twitter users as the transfer was widely tweeted about. The aim of this project is to get an overview of how Twitter Users reacted to the news using Natural Language Processing. For this project, I downloaded and installed packages from different Python libraries which I used to scrape data from twitter, clean my data, process my texts and futher carry out the sentiment analysis.

## Data Cleaning and Text processing
For the Data cleaning step, I ensured that the data types were formatted correctly, I checked for null and duplicate values, I also deleted rows that were not relevant for the analysis. I followed the basic Text proccessing steps to further prepare my data for the sentiment analysis. The steps I took in the text processing are:

* Removal of URLs and mentions
* Convertion of text to lower case
* Tokenization of tweet text
* Removal of punctuations
* Removal of stop words and common words
* Lemmatization

## Sentiment Analysis
After cleaning and processing the tweet text, a polarity score was assigned to each tweet to determine if it expresses positive, neutral or negative sentiment.

## Data Visualization
At the end of the analysis, the sentiment distribution was plotted in a pie chart for easier visualization.

## Final Result
The result of the analysis showed that 45.4% of the tweets expressed positive sentiment, 41% was neutral and only 13.6% was negative.
