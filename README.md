# Recommender-Systems [![](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/Shyamspr/Recommender-Systems/blob/master/LICENSE.txt)

This is the recommender systems built using AutoEncoders. Which is recommend movies to a user.

# Code Requirements
The code is in Python (version 3.6 or higher). You also need to install Pytorch library.

# Description
We will work on a dataset that has exactly the same features as the Netflix dataset: plenty of movies, thousands of users, who have rated the movies they watched. The ratings go from 1 to 5, exactly like in the Netflix dataset, which makes the Recommender System more complex to build.

our final Recommender System will be able to predict the ratings of the movies the customers didn’t watch. Accordingly, by ranking the predictions from 5 down to 1, our Deep Learning model will be able to recommend which movies each user should watch.
 
# About the dataset 
MovieLens data sets were collected by the GroupLens Research Project
at the University of Minnesota. It consists of 

	1. 100,000 ratings (1-5) from 943 users on 1682 movies. 
	2. Each user has rated at least 20 movies. 
    3. Simple demographic info for the users (age, gender, occupation, zip).
