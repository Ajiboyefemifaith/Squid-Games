# Squid-Games
Sentiment analysis to analyze and find the emotions or intents behind fans' tweet


# Overview
Squid Game (Korean: 오징어 게임; RR: Ojing-eo Geim) is a South Korean survival drama television series streaming on Netflix. It was written and directed by Hwang Dong-hyuk, and stars Lee Jung-jae, Park Hae-soo, O Yeong-su, Wi Ha-joon, Jung Ho-yeon, Heo Sung-tae, Anupam Tripathi, and Kim Joo-ryoung.[2] The series was released worldwide on September 17, 2021, and distributed by Netflix.[3][4] The show received overwhelmingly positive reviews, and within a week was one of Netflix's most watched programs in several regional markets.

A group of 456 people from all walks of life are invited to play a series of children's games with life-threatening consequences to have a chance to win a ₩45.6 billion (US$38.7 million) prize


# Data Source

2,000 tweets were scrapped from twitter to find the sentiments of those who have watched the movie. The tweets were cleaned and feature engineering was performed. Several columns were added to the dataframe inluding columns like word count, character count, word density etc.


#EDA

The results of the sentiment analysis carried out is given below, where negative sentiments class had a score less than 0, neutral had a score of 0 and positive class had a score greater than 0. 

Negative    1651
Positive     324
Neutral       25

The most frequently used words in the scrapped tweets are: squid, game, netflix, episode

# Results

82.55% of the tweets scrapped had a negative sentiment while 16.20% and 1.25% had positive and neutral sentiments respectively

A sentiment Analyzer engine with an accuracy of 71% was built to find the sentiments behind the tweets of Squid games' fans
