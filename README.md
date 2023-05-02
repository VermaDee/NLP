# Natural Languagse Processing

Technologies Used:
1. Pandas for EDA, Data Cleaning
2. re, string library for text cleaning
3. word_tokenize, stopwords, SentimentIntensityAnalyzer from nltk library for sentiment analysis

Dataset :
Downloaded from Kaggle

Columns for Clothing Data Set:
Clothing, ID Age Title ReviewText,Rating Recommended,IND,Positive,Feedback,Count,Division,Name,Department,Name,Class,Name

Columns for Hotel Review Data Set:
'Title', 'PositiveReview', 'NegativeReview', 'Score', 'GuestName','GuestCountry', 'RoomType', 'NumberOfNights', 'VisitDate', 'GroupType','PropertyResponse'

Approach :
- Did Sentiment Analysis of Title and Review Column after removing the stopwords and all the punctutations, calculated polarity score using SentimentIntensityAnalyzer.
