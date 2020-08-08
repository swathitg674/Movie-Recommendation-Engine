# Movie-Recommendation-Engine

This repository contains the code for building movie recommendation engine.

The main goal of this machine learning project is to build a recommendation engine that recommends movies to users. This project is designed to help you understand the functioning of how a recommendation system works.

It turns out that there are (mostly) three ways to build a recommendation engine:

1. Popularity based recommendation engine
2. Content based recommendation engine
3. Collaborative filtering based recommendation engine

## Popularity based recommendation engine:
Perhaps, this is the simplest kind of recommendation engine that you will come across. The trending list you see in YouTube or Netflix is based on this algorithm. It keeps a track of view counts for each movie/video and then lists movies based on views in descending order(highest view count to lowest view count).

## Content based recommendation engine:
This type of recommendation systems, takes in a movie that a user currently likes as input. Then it analyzes the contents (storyline, genre, cast, director etc.) of the movie to find out other movies which have similar content. Then it ranks similar movies according to their similarity scores and recommends the most relevant movies to the user.

## Collaborative filtering based recommendation engine:
This algorithm at first tries to find similar users based on their activities and preferences (for example, both the users watch same type of movies or movies directed by the same director). Now, between these users(say, A and B) if user A has seen a movie that user B has not seen yet, then that movie gets recommended to user B and vice-versa. In other words, the recommendations get filtered based on the collaboration between similar user’s preferences (thus, the name “Collaborative Filtering”). One typical application of this algorithm can be seen in the Amazon e-commerce platform, where you get to see the “Customers who viewed this item also viewed” and “Customers who bought this item also bought” list.

## Files contained in the project
1. movie_recommendation_engine.ipynb : jupyter notebook code file
2. movie_recommender.ipynb : google colab blog
3. movie_dataset.csv : movie recommendation dataset.

## Repository Structure
1. movie_recommendation_engine.ipynb : The Jupyter notebook containing code for the recommendation engines
2. Data should be put in data folder

## Software Require
> Jupyter notebook
