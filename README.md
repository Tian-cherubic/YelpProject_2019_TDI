# YelpProject_2019_TDI
Yelp dataset project for TDI
Assist customer to discover the best restaurant by using sentiment analysis and recommender algorithm
Whenever I need recommendations for restaurants, I YELP. However, it takes a lot time to read all the reviews if you also find the star ratings lack detail information. More importantly, I would love to get recommendations based on my like/dislike reviews on the restaurants along with other users’ like/dislike reviews. Therefore, I propose to investigate Yelp’s dataset, which included the information of business details, user, customer reviews and photos. By using sentiment analysis and recommender algorithm, I hope to assist customers discover the best restaurants. Yelp’s dataset is avaliable from Yelp’s 2019 dataset challenge (https://www.yelp.com/dataset).

# Outline

# 1, Import and explore Data

1a. read in yelp business data

1b. read in yelp user review data

1c. Filter the yelp business, only select Chinese Restaurant business

1d. Merge the chinese restaurant business dataframe with the customer review dataframe


# 2, Present customer review data using Word Clouds

2a. Review text preprocessing, clean reviews

2b. Word Clouds for Chinese Restaurants


# 3, New features (positive review rate for restaurant) to help user choose restaurant using Sentiment Analysis

3a. Clean Reviews and Review Sentiment Analysis

3b. Calculate the positive review ratio for Chinese restaurant

3c. Explore the relationship between restaurant "stars" rating and positive review ratio


# 4, Restaurant recommender system

4a. Recommender algorithm

4b. Recommendation generation: obtain a restaurant list for a given user
