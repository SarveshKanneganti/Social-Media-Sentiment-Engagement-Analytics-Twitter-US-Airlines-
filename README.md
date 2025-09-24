Social Media Sentiment & Engagement Analytics: A Deep Dive into US Airline Twitter Data


This project delivers a comprehensive Natural Language Processing (NLP) and data analytics solution for analyzing public sentiment and engagement on Twitter, using a dataset of tweets directed at major US airlines. It leverages a robust Python toolkit to process, analyze, and visualize thousands of tweets, providing actionable insights into customer perception and brand reputation.

** Project Overview**

The objective of this project is to uncover patterns and trends in customer feedback by performing a multi-faceted analysis of social media data. By classifying tweets as positive, negative, or neutral, we can quantify public sentiment towards specific airlines and identify the key drivers behind customer complaints and praise. This analysis is crucial for companies seeking to understand their audience, improve customer service, and refine their brand strategy.

Key Features


•	Sentiment Analysis: Utilizes both TextBlob and VADER (Valence Aware Dictionary and sEntiment Reasoner) for accurate, lexicon-based sentiment classification of tweets.

•	Data Visualization: Generates compelling and insightful visualizations, including:

    o	Distribution of sentiments across different airlines.

    o	Frequency of negative reasons for each airline.

    o	Word clouds to highlight the most common words in positive and negative tweets, providing a visual summary of feedback.

•	Tweet Engagement Analysis: Explores metrics like retweet counts and timestamps to understand which tweets resonate most with the public.

•	Advanced Text Preprocessing: Includes steps for cleaning and preparing raw text data, such as removing special characters, stopwords, and emojis, to ensure the accuracy of the analysis.

•	Topic Clustering: Employs K-Means clustering with TF-IDF Vectorization to group tweets by topic, helping to identify distinct themes within the customer feedback.

Technologies Used

The project is built entirely in Python and uses a modern data science stack to ensure efficiency and scalability.

•	Core Libraries:

    o	pandas: For data manipulation and analysis.
    
    o	numpy: For numerical operations.

•	Natural Language Processing (NLP) & Machine Learning:

    o	nltk: A leading library for NLP tasks, including tokenization, stopword removal, and lemmatization.

    o	TextBlob: Provides a simple API for common NLP tasks.

    o	VADER: Specifically for sentiment analysis of social media text.

    o	scikit-learn: For implementing machine learning models like KMeans and TfidfVectorizer.

•	Data Visualization:

    o	matplotlib: For static plots.

    o	plotly: For creating interactive, high-quality visualizations.

    o	seaborn: For aesthetically pleasing statistical graphics.

    o	wordcloud: To generate word cloud visuals.

•	Other:

    o	emoji: For handling and analyzing emojis in tweets.

Results & Insights: 

•	Overall Sentiment: 

    o	The analysis of US airline tweets reveals a higher proportion of negative sentiment, indicating a need for improved social media customer service.

•	Key Negative Drivers:

    o	A significant amount of negative feedback is due to customer service issues and flight delays.

    o	Cancellations and luggage problems are also major sources of customer dissatisfaction.

•	Word Cloud Insights: 

    o	Words like "late," "flight," and "service" are prominent in negative tweets, confirming the primary reasons for complaints.

•	Airline Performance:

    o	United and US Airways show a higher percentage of negative tweets, suggesting greater challenges in customer satisfaction.

    o	American Airlines has a more balanced sentiment.

    o	Virgin America has a higher proportion of positive tweets, indicating successful customer engagement.

•	Actionable Insights:

    o	Airlines can use these insights to proactively respond to negative feedback in real-time.

    o	The data can be used by operational teams to address the root causes of customer dissatisfaction.

    o	Airlines can amplify positive feedback to build brand trust and show appreciation for customers.

## Thank You



