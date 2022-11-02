# Netflix-Recommendation-System-using-Python
Netflix is a subscription-based streaming platform that allows users to watch movies and TV shows without advertisements. One of the reasons behind the popularity of Netflix is its recommendation system. Its recommendation system recommends movies and TV shows based on the user’s interest. If you are a Data Science student and want to learn how to create a Netflix recommendation system, This codebase will take you through how to build a Netflix recommendation system using Python.

Here’s How Netflix Recommendation System Works
The recommendation system of Netflix shows you movies and TV shows according to your interests. Netflix has a lot of data because of its user base. Its recommendation system predicts a personalised catalogue for you based on factors like:

your viewing history
the viewing history of other users with similar tastes and preferences as yours
genres, category, description, and more information about the content that you watched in the past

The genre of the content is one of the most valuable factors that helps Netflix recommend more content even to new users. I hope you have understood how Netflix recommends content to its users. You can learn more about it here. In the section below, I will take you through how to build a Netflix recommendation system using Python.

Netflix Recommendation System using Python
The dataset I am using to build a Netflix recommendation system using Python is downloaded from Kaggle. The dataset contains information about all the movies and TV shows on Netflix as of 2021. You can download the dataset from here.

Now let’s import the necessary Python libraries and the dataset we need for this task:

In the first impressions on the dataset, I can see that the Title column needs preparation as it contains # before the name of the movies or tv shows. I will get back to it. For now, let’s have a look at whether the data contains null values or not:

The dataset contains null values, but before removing the null values, let’s select the columns that we can use to build a Netflix recommendation system:

As the name suggests:

The title column contains the titles of movies and TV shows on Netflix
Description column describes the plot of the TV shows and movies
The Content Type column tells us if it’s a movie or a TV show
The Genre column contains all the genres of the TV show or the movie
Now let’s drop the rows containing null values and move further:

Now I will clean the Title column as it contains some data preparation:

Now let’s have a look at some samples of the Titles before moving forward

So this is how you can build a Netflix Recommendation System using the Python programming language.

Summary
The recommendation system of Netflix predicts a personalised catalogue for you based on factors like your viewing history, the viewing history of other users with similar tastes and preferences, and the genres, category, descriptions, and more information of the content you watched. 

