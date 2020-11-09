# Coronavirus_Tweets
Natural Language Processing and Sentiment Analysis project for tag all the coronavirus tweets.

The objective of this project was to apply all the NLP and Sentiment analysis knowledge that I learn with my coursera courses in the 2020 Coronavirus Pandemic, also this project helped me develope a Sentiment Analysis program to participate in the 2020 BBVA Hackathon (another project in this github).

The project has an Exploratory Data Analysis part and three diferent models with many changes.

Exploratory Data Analysis

![alt text](1.JPG)

The number of tweets in march is so much larger than any other month, this is caused because in frebruary 29th the first person died of Coronavirus in the USA.

![alt text](2.JPG)

The chart shows that most of the tweets are positive. This may be correct, and english speakers have good sentiments with the pandemic, or there is bias in the tweet selection.

### Models

![alt text](3.JPG)

In this model we can apreciate almost no overfitting, with 70% of accuracy, this model just has and embedding layer and two recurrent layers, in the next model the preprocessing and the acurracy increases, also there are five categories tha may be confused.

![alt text](4.JPG)

As expected, the extremely positives tweets are confused with the positive tweets, this also occurs with the negative tweets. The next part will be joining this four categories into only two, this may help in the accuracy metric.
