# Twitter Entity Sentiment Analysis

### Introduction
This is an entity-level sentiment analysis dataset of twitter. Given a message and an entity, the task is to judge the sentiment of the message about the entity. There are three classes in this dataset: Positive, Negative and Neutral. We regard messages that are not relevant to the entity (i.e. Irrelevant) as Neutral.

### Workflow Diagram
![Workflow Diagram of Twitter Entity Sentiment Analysis](https://github.com/ratul-07/Twitter-Sentiment-Analysis/blob/main/Images/Workflow%20Diagram%20TwitterSA.png)

### About the Dataset
There are three classes in this dataset: Positive, Negative and Neutral. We regard messages that are not relevant to the entity (i.e. Irrelevant) as Neutral. It contains 69,491 unique values in the tweets column. The columns are: 
* TweetID - Id of the accounts tweeting the particular tweets
* Entity - Entities the particular tweet is about
* Sentiment - The sentiment of the particular tweet i.e. positive, negative, neutral, irrelevant
* Tweet Content - Contents of the tweet
