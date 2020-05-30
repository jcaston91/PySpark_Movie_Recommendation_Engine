# PySpark_Movie_Recommendation_Engine

Jontavius Caston
May 20, 2020

In this exercise we will create a movie recommendation engine from the supplied data

a. Prepare Data
Load the data from the ratings.csv and movies.csv files and combine them on movieId. The resultant data set should contain all of the user ratings and include movie titles.

b. Train Recommender
Using the data you prepared in the step a we will create a movie recommendation model using collaborative filtering.

Before training the recommendation model, we will split the data into a training dataset and a testing dataset using the randomSplit dataframe method. Use 80% of your data for training and 20% for testing.

After fitting the model using the training dataset, calculate the predictions on the test dataset and use the RegressionEvaluator to calculate the root-mean-square error of the model.

c. Generate top 10 movie recommendations
Using the recommendation model, generate the top ten recommendations for each user. Using the show method, print the recommendations for the user IDs, 127, 151, and 300. We will not truncate the results and so should call the show method like this recommendations_127.show(truncate=False), this allows us to see the full output.
