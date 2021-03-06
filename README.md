#  Build a Smart Streaming Platform

## Purpose:
This is the age of OTT. Streaming is the new way of consumption. 
We want to build a model to provide our members with personalized suggestions to reduce the amount of time and frustration to find something great content to watch.

## Goal:

I have analyzed info from Netflix, Amazon Prime, Hulu and other platforms. I have recommendations for the newbies in the streaming game.
 

## Data Description:

Using web scraping to get the movie dataset from public websites:

•  [data-world-movie-dataset dataset](https://data.world/promptcloud/imdb-data-from-2006-to-2016)

• [grouplens movie dataset](https://grouplens.org/datasets/movielens/)

## Algorithms:

Build the recommendation model using:
1. Content Based Filtering (Item Based)
(IMDB Dataset - 1000 movies)- IMDB Movie rating, genres, actors, populatity, etc.
Content-based filtering uses item features to recommend other items similar to what the user likes, based on their previous actions or explicit feedback


2. Collaborative Filtering (User Based)
 (Kaggle Dataset - 9700 movies)

Collaborative filtering filters information by using the interactions and data collected by the system from other users. It's based on the idea that people who agreed in their evaluation of certain items are likely to agree again in the future.

## Movie Recommendation Engine
Implemented Content based filtering using Cosine Similarity Matrix. Used Movie features - Director, Actors, Genres.

For a User liking the movie 'The Imitation Game', based on my recommendation engine, here's 10 movies that user might like

![](https://github.com/chetana-vyas/BusinessFundamentals/blob/main/Images/top-10-movies.PNG)

## Tools:

* Google spreadsheets - initial Exploratory Data Analysis
* Tableau - interactive dashboards
* Python packages - building the model
* Scikit-learn – build Linear Regression model
* Pandas – manipulating and working on data frames
* NumPy – working with arrays


4 Key Recommendations to focus on:
1. Powerful Recommendation Engine
2. Platform Originals
3. Buy rights for iconic cash machines, basically all time hits
4. Content dubbing - Global Reach and ‘Localisation’ 

