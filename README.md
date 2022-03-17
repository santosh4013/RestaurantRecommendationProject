# RestaurantRecommendationProject
It is a Machine Learning Review based restaurant recommendation model

A recommendation system model that could recommend people restaurants near their location based on restaurant reviews from other people, drawing on sentiment analysis that could potentially improve the recommendation suggestions that you see on common food delivery apps like Deliveroo, GrabFood, and FoodPanda.

# DataSet
The dataset that I built my models on was taken from the Yelp Dataset, which has been made publicly available for personal, educational, and academic purposes.

We taken 2 lakth rows inorder to manage Ram, Storage and Time issues

# Model 1

We used TfidfVectorizer to get the features and analyse them

As we tired to use collaborative filtering due to Ram and huge size of data we used content based filtering

# Model 2

Content Based Filtering
Restaurant Recommendation for old users using Vader Lexicon sentiment analysis
For Old or already existing users they can enter the restaurant they wanted to visit our model will recommand the similar restaurants using the score the model generates for every restaurants (stars given by users + compound_score * positive_score)

# Model 3

Restaurants Recommendations for new users using Bert model and semantic similarity
Recommending restaurants to users according to the required category

# Model 4

Recommending restaurants to new users by entering the type of restaurants they wanted and according to semantic similarity generated using cosine similarity will recommend top 10 restaurants
