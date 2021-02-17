# Movie Analysis Project
Author: Justin Giovatto
## Overview
This project analyzes top performing films by different genres based on factors such as profit, gross, popularity, and rating. This analysis can be used to determine which types of films should be made going forward in creating a successful film studio. 
## Business Problem
Microsoft wants to start a movie film company and wants recommendations on the types of films to make.
## Data
I will analyze data from the following datasets in order to generate three concrete business recommendations for them to use in creating their new film studio:

data/bom.movie_gross.csv.gz 
>Contains data on films' domestic and foreign gross.

data/imdb.title.basics.csv.gz 
>Contains data on titles listed by genres.

data/imdb.title.ratings.csv.gz 
>Contains data on films' average ratings.

data/tmdb.movies.csv.gz 
>Contains data on films' popularity.

data/tn.movie_budgets.csv.gz 
>Contains data on production budget and worldwide gross data.
## Methods
Using specific columns from the data provided I created a new dataframe consisting of a sample of 44 different films to base my analysis off of. Using this new sample of films dataframe, I then grouped the films according to the most important factors that I felt would help in answering the business problem. The main methods I used in my analysis were to sort the films by genre and then analyze the top performing genres according to profit, gross, popularity, and ratings. I then created graphs based off these methods and analzyed my findings. Finally I broke the genres out into broader main genres using a function and then graphed this information by total profit to determine the most profitable main genres within the dataset.

## Results & Conclusions  

Based on the analysis, my three main business recommendations are as follows:

Based on the findings from the data the best sub-genres of films I recommend to make going forward are "Action, Adventure, Sci-Fi", "Action, Adventure, Comedy", and "Action, Adventure, Fantasy". These types of films outperform all other sub-genres in terms of profit according to the data.

Based on the findings from the data the main genres of films I recommend to make going forward are Action, Adventure, Fantasy, and Animation. These types of films outperform all other main genres in terms of profit according to the data.

Based on the findings from the data two sub-genres of films I would reccomend to make are "Biography, Drama, Thriller" and "Drama, Mystery, Thriller". These types of films outperform other higher profit sub-genres in terms of popularity according to the data. This could indicate an untapped market for these types of films with a high demend for them and not enough supply.

## For More Information
## Repository Structure
