# Movie-Recommendation-System
Movie Recommendation System in pySpark

Created a functional recommendation system on MovieLens dataset, to provide relevant product recommendations to customers.
Used Hadoop with spark Mllib, for high performance computing and storage of data.

STEPS:

1.  Examined the data - Created Tuples from ratings & movies dataset
2.  Determined ALS parameters 
	  (Regularization, Rank, Iterations, tolerance)
3.  Selected best training model with min RMSE
4.  Added new user ratings to train the model
5.  Generated top 25 recommendations
6.  Finally, selected highest rated recommendations for the new user, filtering out movies with less than 25 ratings
7.  Persisting the model

