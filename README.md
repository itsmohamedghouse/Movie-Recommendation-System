# Movie-Recommendation-System

The rapid growth of data collection has led to a new era of information. Data is being used to create more efficient systems and this is where Recommendation Systems come into play. Recommendation Systems are a type of information filtering systems as they improve the quality of search results and provides items that are more relevant to the search item or are realted to the search history of the user.

They are used to predict the rating or preference that a user would give to an item. Almost every major tech company has applied them in some form or the other: Amazon uses it to suggest products to customers, YouTube uses it to decide which video to play next on autoplay, and Facebook uses it to recommend pages to like and people to follow. Moreover, companies like Netflix and Spotify depend highly on the effectiveness of their recommendation engines for their business and success.

### There are basically three types of recommender systems:-

  - Demographic Filtering- They offer generalized recommendations to every user, based on movie popularity and/or genre. The System         recommends the same movies to users with similar demographic features. Since each user is different , this approach is considered to     be too simple. The basic idea behind this system is that movies that are more popular and critically acclaimed will have a higher       probability of being liked by the average audience.
  
  - Content Based Filtering- They suggest similar items based on a particular item. This system uses item metadata, such as genre,           director, description, actors, etc. for movies, to make these recommendations. The general idea behind these recommender systems is     that if a person liked a particular item, he or she will also like an item that is similar to it.
  
  - Collaborative Filtering- This system matches persons with similar interests and provides recommendations based on this matching.         Collaborative filters do not require item metadata like its content-based counterparts.
  
### We will be using Collaborative filtering

Let's first understand how recommendation works in a nutshell

We use simple heuristics to suggest items. Like,

  - User based
      - Let’s say we want to show recommendations to user A.
      - In this method, we try to find a similar user B who also tends to like items that user A likes.
      - So, we recommend user B‘s other liked items to user A.
      - Logic behind this is, similar people may like similar items.
      
  - Item based
      - Let’s say one user buy item P.
      - Now, from all the user’s data, there’s one item S which users bought almost all time whenever item P get bought.
      - So, we recommend item S to users whenever they buy item P.
      - Logic behind this is, similar items may be sold together.
      
      
 Above 2 methods are very basic ones. But they shows how simple recom mendation algorithms work.
 
 ### Latest recommendation systems we see in day to day lives in Netflix & Amazon uses much more data like user's personal information etc.


## Dataset Info

The data used in the following analysis is the MovieLens data of 100K movie ratings. The data was collected through the MovieLens website (movielens.umn.edu) during the seven-month period from September 19th, 1997 to April 22nd, 1998. This data set consists of 100,000 ratings (1-5) from 943 users on 1682 movies. The data has been filtered such that each user has rated at least 20 movies.

## Content

We have 2 files

1. Movies.csv
  * MovieId - Only movies with at least one rating or tag are included in the dataset.
  * Title - Full name of movie.
  * Genre - Comma separated list of genres for this movie.
  
2. Ratings.csv
  * userId - MovieLens users were selected at random for inclusion. Their ids have been anonymized.
  * movieId - the movie that this user has rated.
  * rating - Ratings are made on a 5-star scale, with half-star increments (0.5 stars - 5.0 stars).
  * timestamp - Timestamps represent seconds since midnight Coordinated Universal Time (UTC) of January 1, 1970.
  
  
  
  ## Output
  
  
  
  ## Conclusion
  
  
