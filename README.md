# Youtube-Dislike-Button-Removal-Sentiment-Analysis
Used Natural Language Processing techniques to analyze the sentiment of tweets about YouTube before and after the removal of the dislike button.


### A Report of this project can be read here: [Report](https://drive.google.com/file/d/12viM7A_grnAmJCeKxcEuL2jymg1zfD60/view)


## Description

This project gets tweets with the youtube keyword during two different periods of time. Before and After youtube announced the removal of the dislike button. I performed Sentiment Analysis on the tweets to observe the how the tweets' sentiment changed towards youtube after the announcement.

* Used twitter API to scrape tweets with the Youtube keyword and store the dataset in a csv file.

* Cleaned the dataset by removing duplicates, english stop-words and links from the tweets.

* Performed Latent Semantic Analysis on the tweets to extract the topics in the tweets.

*  Used the TextBlob library to perform sentiment analysis on the tweets to observe how the sentiment evolved after the announcement of the removal of the dislike button.

## Technologies Used
* This project was built using Python. The Tweepy library was used to get the tweets into a dataframe using tweepy. The textBlob library was also used to perform the sentiment analysis.
Pandas and Matplotlib libraries were used throughout the project to work with the datasets and visualize some features. 

<div class="row">
  <div class="column">
    <img align="left" src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/640px-Python-logo-notext.svg.png" alt="drawing" width="100"/>
  </div>
  <div class="column">
    <img align="left" src="https://1.bp.blogspot.com/-70-mnYEM1Hk/XZHpa2pka4I/AAAAAAAAB2o/mA9kk8zUTg00i636u2SL5E-MHXZVkyBTACLcBGAsYHQ/s1600/Capture.PNG" width="100"/>
  </div>
  <div class="column">
    <img align="left" src="https://upload.wikimedia.org/wikipedia/commons/0/01/Created_with_Matplotlib-logo.svg" alt="drawing" width="100"/>
  </div>
  <div class="column">
    <img align="left" src="https://upload.wikimedia.org/wikipedia/commons/e/ed/Pandas_logo.svg" alt="drawing" width="200"/>
  </div>
  <div class="column">
    <img align="left" src="https://twilio-cms-prod.s3.amazonaws.com/images/twitter-python-logos.width-808.jpg" width="160"/>
  </div>
</div>
