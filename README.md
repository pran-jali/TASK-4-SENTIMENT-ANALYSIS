# TASK-4-SENTIMENT-ANALYSIS
Name=Pranjali Pradeep Shinde
Company=Codetech IT Solutions 
Intern ID=CT08HVO
Domain=Data Analyst 
Duration=30th December 2024 to 30th January 2025 
Mentor= NeelaSantosh 
Sentiment analysis, also known as opinion mining, is a natural language processing (NLP) technique used to determine the sentiment or emotional tone behind a piece of text. It typically classifies text into categories such as positive, negative, and neutral by analyzing linguistic patterns, word usage, and contextual meaning.
Applications of sentiment analysis include:
- **Social Media Monitoring:** Analyzing user sentiments in tweets, comments, or reviews to gauge public opinion about products, services, or events.
- **Customer Feedback Analysis:** Understanding customer satisfaction through feedback and reviews.
- **Market Research:** Identifying trends and consumer attitudes in a competitive landscape.
- **Brand Reputation Management:** Tracking shifts in brand perception over time.
Sentiment analysis models range from simple rule-based systems to sophisticated machine learning approaches, such as Naive Bayes classifiers, Support Vector Machines (SVMs), or deep learning methods like recurrent neural networks (RNNs) and transformers.
In the Jupyter Notebook, you will leearn how I carried out the following steps for the project:
Import Libraries
Tweets Mining
Data Cleaning
Location Geocoding
Tweets Processing
Data Exploration
Sentiment Analysis
To reach the ultimate goal, there was a need to clean up the individual tweets. To make this easy, I created a function "preProcessTweets" in my Python program which I further applied to the "Tweets" to produce the desired results. This user-defined function was used to remove punctuations, links, emojis, and stop words from the tweets in a single run. Additionally, I used a concept known as "Tokenization" in NLP. It is a method of splitting a sentence into smaller units called "tokens" to remove unnecessary elements. Another technique worthy of mention is "Lemmatization". This is a process of returning words to their "base" form. A simple illustration is shown below.



Word Cloud Generation
To get the most common words used to describe 2020, I made use of the POS-tag (Parts of Speech tagging) module in the NLTK library. Using the WordCloud library, one can generate a Word Cloud based on word frequency and superimpose these words on any image. In this case, I used the Twitter logo and Matplotlib to display the image. The Word Cloud shows the words with higher frequency in bigger text size while the "not-so" common words are in smaller text sizes.
Visulizing Most Common Words
The Plot below was genrated using Plotly Library for Python.
Sentiment Analysis
For this analysis, I went with TextBlob. Text Blob analyzes sentences by giving each tweet a Subjectivity and Polarity score.  Based on the Polarity scores, one can define which tweets were Positive, Negative, or Neutral. A Polarity score of < 0 is Negative, 0 is Neutral while > 0 is Positive. I used the "apply" method on the "Polarity" column in my data frame to return the respective Sentiment Category. The distribution of the Sentiment categories is shown below. You can also see the Sentiment Category distribution per country and continent in the Tableau dashboard HERE
Some of the insights I generated are stated below:
Tweet Sentiments: I was not surprised by the proportion of the sentiment categories because, for most people, the end of the year is a time to show gratitude and hope for a better year ahead. However, this year has been filled with so many unpalatable events, hence, 31% of the tweets being Negative. *Please note that this is not indicative of the entire Twitter community as only a subset of tweets were mined for this analysis.
Countries with Most Tweets: About 40% of the total tweets emanated from the United States, England and Canada. Since a good number of Twitter users do not have their exact location on their profiles, their tweet locations were classified as "Unknown location".
Hour of the day with the Most Tweets: It was interesting to see that most tweets were created at 5 PM (GMT). Thinking about it, in the US & Canada, this is lunchtime while in countries like Nigeria and England, it is when most individuals finish the work-day, so they have ample time to tweet.
Hour of the day with Least Tweets: 9 AM (GMT) was the hour of the day with the least number of tweets. The reason is this is when most people start their day at work in countries like Nigeria and England while it is still bed-time in other countries like the US & Canada.
Most Retweeted and Liked Tweet: For the period of 12th to 25th December 2020, the tweet with the most retweets was about a Korean boy band: "BTS" and their songs with 10,873 RTs. The most liked tweet from a user who tweeted about how "2020 was a good year for his dog who did not have to be alone for a second". The tweet had 42,295 likes.
Relevant Links
Tableau Dashboard
Jupyter Notebook
Personal Website
Medium Article
LinkedIn
Twitter
DataTech Space Community
