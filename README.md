# Real-Time Twitch Comment Analysis Using Snowflake, Python, and ChatGPT

## Abstract 

This project analyzes real-time Twitch comments using Snowflake, Python, and ChatGPT. We perform sentiment analysis, track KPIs like subscriptions and active users, and visualize data in Tableau for real-time insights on user engagement and sentiment.

## Introduction

Social media platforms have become a goldmine of user-generated data. With the rise of live streaming platforms like Twitch, capturing and analyzing real-time comments can provide valuable insights into user sentiment and engagement. In this project, we scrape comments from a Twitch live stream, perform data wrangling and preprocessing using Snowflake and Python, and utilize ChatGPT APIs for sentiment analysis and topic extraction. We then visualize the results in Tableau, enabling real-time tracking of key performance indicators related to subscriptions, users, sentiment, and more. 

## Setting Up the Data Pipeline 

To begin our analysis, we set up a data pipeline that allows us to capture and process comments in real-time. The pipeline consists of three main components: Twitch comment scraping, Snowflake database integration, and Python . 

### Twitch Comment Scraping: 

Using appropriate APIs and libraries, we connect to the Twitch live stream and collect data in real time. This involves subscribing to the Twitch APIs to receive comment updates as they occur during the live stream. 

### Snowflake Database Integration 

We import the real-time comment data into a Snowflake database. Snowflake's cloud based data warehousing solution provides scalability, security, and ease of integration with other tools and programming languages. 

### Python-ChatGPT Integration for Sentiment Analysis and Topic Extraction 

Once the comment data is in Snowflake, we connect it to Python using the Snowflake Connector. We then connect with ChatGPT APIs, enabling sentiment analysis and topic extraction from the Twitch comments. 

## Real-Time Sentiment Analysis and Topic Extraction

To gain deeper insights from the comments, we utilize the power of ChatGPT APIs. ChatGPT's natural language processing capabilities allow us to perform sentiment analysis and topic extraction in real time. 

### Sentiment Analysis 

By passing comments through ChatGPT, we can determine the sentiment of each comment. This provides an overview of the overall sentiment of the Twitch chat in real time. 

### Topic Extraction 

Using ChatGPT's API, we also extract the main topics of discussion from the comments. This allows us to identify what the users are talking about, enabling us to gain insights into trending topics and themes during the live stream. 

## Real-Time KPI Tracking with Tableau

After performing sentiment analysis and topic extraction, we visualize the results using Tableau. The visualizations enable real-time tracking of key performance indicators related to user engagement and sentiment. The following KPIs were tracked and visualized in real time: 

### 1) Amount of Subscriptions Received 

Using Tableau's real-time data connection to Snowflake, we created a visual representation of the number of subscriptions received during the live stream. This provided an instant overview of the growth in subscriber count.

### 2) Most Active Users in the Last 5 Minutes 

Tableau allowed us to track the most active users in the chat by displaying a dynamic leaderboard that updated every 5 minutes. This information helped us identify influential users and engage with them effectively.

### 3) Viewer Summary 

We created a summary dashboard in Tableau that displayed the topic/theme that users are talking about.

### 4) Chat WordCloud

To visualize the most frequently used words in the chat, we generated a word cloud using Tableau. This helped us identify popular topics or keywords that dominated the conversation during the live stream.

### 5) Viewer Sentiment 

Tableau's visualizations allowed us to track the sentiment of the Twitch chat in real-time. By representing sentiment scores on a sentiment meter or line chart, we could understand how users' sentiments evolved throughout the stream.

### 6) Number of Active Users in the Chat

We created a dynamic visualization in Tableau that displayed the number of active users in the chat, updating every minute. This helped us monitor chat activity and identify peak chat times.

## Conclusion 

In this project, we demonstrated the power of combining real-time data scraping, Snowflake integration, Python data wrangling, ChatGPT sentiment analysis, and Tableau visualizations to gain valuable insights from Twitch live stream comments. By tracking KPIs such as subscriptions, active users, sentiment, and viewer summaries, we obtained a holistic understanding of user engagement and sentiment patterns. This approach can be applied to other live streaming platforms, social media platforms, or any data source that involves real-time user-generated content. Leveraging the capabilities of cutting-edge technologies like ChatGPT and Snowflake allows for powerful real-time analysis and opens up exciting possibilities for understanding user behavior in the digital realm.


