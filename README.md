Nowdays there's alot of issues of negative comments on social media. With the help of this project i aim to find the number of positive vs negative comments on social media platform X or twitter. 
With the help of our analysis we will divide the text into positive, negative and neutral.

The sentiment analysis is performed using the VADER sentiment analysis tool, which is particularly effective for analyzing social media text. The analysis involves:
Calculating sentiment scores for each tweet.
Categorizing sentiments as Positive, Negative, or Neutral based on compound scores.

DATA
The dataset used for this project contains tweets with the following columns:

post_id: Unique identifier for each tweet
post_created: Timestamp of when the tweet was created
post_text: Content of the tweet
user_id: Unique identifier for the user who posted the tweet
followers: Number of followers the user has
friends: Number of friends the user has
favourites: Number of tweets the user has liked
statuses: Total number of tweets the user has posted
retweets: Number of retweets

Libraries used : 
matplotlib.pyplot 
pandas
seaborn
VADER
