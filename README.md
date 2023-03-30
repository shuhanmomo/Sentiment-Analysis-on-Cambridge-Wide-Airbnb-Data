# Sentiment-Analysis-on-Cambridge-Wide-Airbnb-Data
Sentiment analysis could be used to gather data on how people feel about certain aspects of a building or space. What are the most common words and adjectives used in positive and negative reviews of Airbnb properties in the Cambridge area, and how can this information be visualized through an interactive map to better understand the sentiment distribution? In this project, I used  NLP(Natural Language Processing) techniques such as NLTK and TextBlob python library. The aim is to analyze cambridge-wide Airbnb reviews by using Sentiment Analysis, and visualize some interesting findings.
## About the Repo
'data' is a folder where stores the downloaded cambridge Airbnb data
'Airbnb_Sentiment.ipynb' is the script where I run the sentiment analysis and visulization. It is created by google collab. To run the script, you need to upload the 'data' folder onto google drive and replace the corresponding path in the script
'map.html' is an interative map visualization
## Data Source
The Airbnb dataset is acquired from online platform Inside Airbnb(http://insideairbnb.com/), which provided detailed information under each listing and corresponding reviews  
![data](https://github.com/shuhanmomo/Sentiment-Analysis-on-Cambridge-Wide-Airbnb-Data/blob/048e02a3f2e0c148cfbd81c240fb2b4ad5ec0217/img/sentiment1.png)

## Sentiment Analyzer   
I first compared the NLTK Sentiment Intensity Analyzer and TextBlob Sentiment Analyzer by looking at the sentiment result on same review and overall sentiment distribution in the reviews. It turns out the TextBlob Sentiment Analyzer result makes more sense.

![nltk](https://github.com/shuhanmomo/Sentiment-Analysis-on-Cambridge-Wide-Airbnb-Data/blob/3871d054daae3e0b075bbb4cf5f418026601d83b/img/sentiment9.png)  
![nltk2](https://github.com/shuhanmomo/Sentiment-Analysis-on-Cambridge-Wide-Airbnb-Data/blob/3871d054daae3e0b075bbb4cf5f418026601d83b/img/sentiment2.png)  
![textblob](https://github.com/shuhanmomo/Sentiment-Analysis-on-Cambridge-Wide-Airbnb-Data/blob/3871d054daae3e0b075bbb4cf5f418026601d83b/img/sentiment10.png)  
![textblob2](https://github.com/shuhanmomo/Sentiment-Analysis-on-Cambridge-Wide-Airbnb-Data/blob/3871d054daae3e0b075bbb4cf5f418026601d83b/img/sentiment3.png)  

## Visualization Result
Here is some visualization results from the script
### Word Cloud of Positive Comments
![wordcloud1](https://github.com/shuhanmomo/Sentiment-Analysis-on-Cambridge-Wide-Airbnb-Data/blob/3871d054daae3e0b075bbb4cf5f418026601d83b/img/sentiment4.png)
### Most Common Adjective Word In Positive Comments  
![chart1](https://github.com/shuhanmomo/Sentiment-Analysis-on-Cambridge-Wide-Airbnb-Data/blob/3871d054daae3e0b075bbb4cf5f418026601d83b/img/sentiment5.png)
### Word Cloud of Negative Comments
![wordcloud1](https://github.com/shuhanmomo/Sentiment-Analysis-on-Cambridge-Wide-Airbnb-Data/blob/3871d054daae3e0b075bbb4cf5f418026601d83b/img/sentiment6.png)
### Most Common Adjective Word In Negative Comments  
![chart1](https://github.com/shuhanmomo/Sentiment-Analysis-on-Cambridge-Wide-Airbnb-Data/blob/3871d054daae3e0b075bbb4cf5f418026601d83b/img/sentiment7.png)
### Sentiment Analysis Map 
![map](https://github.com/shuhanmomo/Sentiment-Analysis-on-Cambridge-Wide-Airbnb-Data/blob/3871d054daae3e0b075bbb4cf5f418026601d83b/img/sentiment8.png)
