# comment_classifier
## a python program that uses google-api-client & vaderSentiment to categories comments and give a overall sentiment percentages on Positive, Negative, Neutral


# Libraries used :
           * google-api-client [ googleapiclient.discovery ] -  build
           * vaderSentiment - SentimentIntensityAnalyzer

# how it works :
             1. The python program uses youtube data api v3 function from google-api-client to get comment threads from the requested video id.
             2. Then the Top-level comments and likes are snipped from the comment threads 
             3. Sentiment_Intensity_Analyzer categories each individual comment in three types(Sentiments) :  Positive, Negative, Neutral
             4. its displayed in the order :
                              * comments :
                              * Likes :
                              * Sentiments :
             5. Later the overall sentiment percentage all categories with the count of total comments and likes.
        
      
