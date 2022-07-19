# Simple Twitter Sentiment Analyzer Engine

Simple analyzer engine that allow us to choose a topic on twitter and analyze the data related to these topics using sentiment analysis. As result will be shown a pie chart

## Setting Environment
Create the environment with conda  
`conda create --name [your-environment-name]`

Activate the environment  
`conda activate [your-environment-name]`

Install the dependencies:  
`pip install python=3.6.8 numpy pandas matplotlib nltk regex tweepy textblob`

Go to [twitter developer Platform](https://developer.twitter.com/en):
- Sign in or Sign up in 
- create an app
- receive the consumer keys and access keys.

You will apply your own credential to use the API insted of mine as shown here in the code [sentimentAnalyzer.py](sentimentAnalyzer.py#48)

```
consumerKey = config.consumerKey  
consumerSecret = config.consumerSecret  
accessToken = config.accessToken  
accessTokenSecret = config.accessTokenSecret
```
---  

## Execute the script
`python sentimentAnalyzer.py`
