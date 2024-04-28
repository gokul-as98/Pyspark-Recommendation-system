# Pyspark-Recommendation-system
Recommendation system implemented in Python-Pyspark

## Recommendation Engines

Recommendation Engines or a recommender system is a tool that analyses data in order to make suggestions for an item (product or services like movies, songs) user might be interested in. The data can be the history of the items the user interacted with or behaviour of similar users. Some of the common examples are Netflix movie recommendation system, Amazon recommended products etc.

## Working of a recommendation System:

Basically a recommendation system uses data such as browser history, preferences and ratings of different items made by the users to assign ratings to new items and rank them according to this. This also helps the to sort the items which are liked by most users. We can also find different items that are similar each other, which might appeal to the same user.


## Approaches:
There are mainly two kinds of recommender systems:-

1. Content-Based Filtering- Recommends similar items based on a particular item. The general idea behind these recommender systems is that if a user likes a particular item, that user will also like an item that is similar to it. This system uses item metadata, such as genre, director, description, actors, etc. for movies, to make these recommendations.

2. Collaborative Filtering- It produces recommendations based on the collective knowledge of users’ attitude to items, that is it uses the "wisdom of the crowd" to recommend items. Collaborative filters do not require item metadata like its content-based counterparts.

   ![Collaborative filtering](https://upload.wikimedia.org/wikipedia/commons/5/52/Collaborative_filtering.gif)

Some other recommender systems include Demographic filtering-offer generalised recommendations based on users with demographic features,  Hybrid Systems- which takes in to account different type of information for reducing the issues  when working with one kind of Recommender systems.

In this project we will be building Recommender system using collaborative filtering implementation in PySpark.
