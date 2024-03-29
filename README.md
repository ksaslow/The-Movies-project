# The-Movies-project
Network Analysis and Applied Statistics Project

### Work in progress
### Using this dataset: https://www.kaggle.com/rounakbanik/the-movies-dataset?select=credits.csv

# MOVIES' RETURN OF INVESTMENT
### What makes a movie successful
## DATA SOURCE:
Exploring a kaggle data set for clues on what's responsible
https://www.kaggle.com/rounakbanik/the-movies-dataset
Please download:
* movies_metadata.csv
* credits.csv
## NOTEBOOK
* return_of_investment_(thomas).ipynb
## TASKS
* cleaning and subsetting
* regressing against actors
* regressing against directors
* regressing against if movie is part of a franchise
* regressing against genres
* significance check

# RATINGS OF A SUCCESSFUL MOVIE
### Exploring  features responsible for great ratings in the movie dataset. 
## DATA SOURCE:
Explored the movies_metadata.csv from kaggle dataset merging with two other datasets of ratings_small.csv,and
a subset of actors from credits.csv data set.

### AIM:
The aim of this analysis is to explore different features that contributes to high ratings in a successful movie. 
Please download:
* credits.csv
* ratings
* movies_metadata.csv
## NOTEBOOK
* Exploring_movie_ratings.Victoria.ipynb
## TASKS
* cleaning, exploding and subsetting
*  Highest and lowest rated movies
* Highest rated movies based on popularity, actors, original_language and genres


# NETWORK ANALYSIS OF THE HOTTEST ACTORS IN HOLLYWOOD
### Who are the most booked actors
## DATA SOURCE:
Exploring the credits.csv file from the Kaggle dataset. Subsetted to include only cast members per movie_id. Then I isolated the top 200 actors. I also conducted a network analysis on the top 100 female actors and the top 100 male actors. 
Please download:
* credits.csv
## NOTEBOOK
* Network-Analysis-by-Gender-Kate.ipynb
* Network-analysis-Top200-Actors-Kate.ipynb
## TASKS
* cleaning, exploding, cleaning original csv files
* preparing pandas dataframes for use with Networkx package
* visualizing the network of the most frequently booked actors 
* visualizing the network of the most frequently male and female actors respectively
* finding the degrees of each node (actor) and the actor's network centrality and visualizing in dataframe
