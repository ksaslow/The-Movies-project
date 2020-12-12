# The-Movies-project
Module2 Applied Statistics Project

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
