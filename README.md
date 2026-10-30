# Data-Science
For my data cleaning project, I used two different datasets from Kaggle,
netflix_titles and titles. The netflix_titles dataset contains information about
both Netflix movies and TV shows such type, cast, director. The titles datset 
still focused on Netflix movies and TV shows but contains IDMB scores and number
of users that reviewed the movie or show. For this project, I wanted to just 
focus on TV shows and IDMB scores.


First, I filtered the Netflix dataset to include only rows where the type was 
"TV Show". I also filtered the second dataset to include only rows where the
type was "SHOW". 

I then standardizing titles by converting titles to lowercase, replacing & with
"and", removing punctuation and replacing with a space. I also removed rows with
missing titles from both datasets.

I removed tv show rows that did not have an IMDB score. Also removed exact
duplicates

I used inner join to connect the datasets using the standardized title column.


