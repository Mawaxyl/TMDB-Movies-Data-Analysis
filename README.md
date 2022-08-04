# TMDB-Movies-Data-Analysis

# Project: Investigate a Dataset (TMDB-Movies Analysis)

## Table of Contents
<ul>
<li><a href="#intro">Introduction</a></li>
<li><a href="#wrangling">Data Wrangling</a></li>
<li><a href="#eda">Exploratory Data Analysis</a></li>
<li><a href="#conclusions">Conclusions</a></li>
</ul>

<a id='intro'></a>
## Introduction

> **Note**: This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue.
Certain columns, like ‘cast’ and ‘genres’, contain multiple values separated by pipe (|) characters.
There are some odd characters in the ‘cast’ column.
The final two columns ending with “_adj” show the budget and revenue of the associated movie in terms of 2010 dollars, accounting for inflation over time. 

The [link](https://www.google.com/url?q=https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59dd1c4c_tmdb-movies/tmdb-movies.csv&sa=D&source=editors&ust=1654123023079260&usg=AOvVaw1et0LEq8dQpl_XnX3dMEVJ) to download the dataset

## Questions

The following are the questions that needs answers;
#### Research Question 1 (Which genres are most popular from year to year?!)
#### Research Question 2 (Will the most popular genres make the highest revenue?)
#### Research Question 3 (Which Genre of movies has the highest budget?)
#### Research Question 4 (Are longer movies more popular than shorter movies?)
#### Research Question 5 (Actors that have acted in most movies)
#### Research Question 6 (Top 10 movies by average votes)
#### Research Question 7 (Top 10 movies based on popularity)
#### Research Question 8 (Top 10 Directors by Average Votes)
#### Research Question 9 (The top 10 directors by  popularity)
#### Request Question 10 (Which months release the highest number of movies from 1960 to 2015?)

<a id='conclusions'></a>
## Conclusions

**Results**: Our data suggest that
> 1. Adventure have shown to be the best genre to invest in, as it has the highest popularity, and highest profit. Although, it has the highest budget, however, the profit margin was higher than the other movies.
> 2. Other 2 genres that could be considered are Animation and Science Fiction. 
> 3. The worse set of genre to be considered are Foreign, TV Movie, Documentary and Horror.  
> 4. The last quarter of the year have also shown to be months with highest release of movies.
>5. The longer the movie the higher the popularity.
>6. Other insights that could be gotten are;
    - The top 5 actors with most movies appearance are Nicolas Cage, Robert De Niro, Bruce Willis, Clint Eastwood and Tom Hanks 
    -  Colin Trevorrow, David Leitch and Chad Stahelski are the top 3 most popular directors, that produced Jurassic World, Mad Max: Fury Road and Interstellar respectfully.
    - David Mallet, Saul Swimmer and Curt Morgan are the top 3 directors by average votings, that produced Pink Floyd: Pulse, Queen - Rock Montreal and A Personal Journey with Martin Scorsese Through American Movies respectfully.
 
**Limitations**: There are a couple of limitations with our data:
> 1. '0' showing could be a missing value which need further attention and analysis. Dropping it would lead to huge data loss.
> 2. No positive correlation between budget and revenue
> 3. The dataset is highly skewed which resulted in very high outliers that need treatment for a better generalization and analysis. 
>4. 44 movie directors were missing which is not included in our analysis. 
