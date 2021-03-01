# Movie Data Exploration + Analysis

If the 'movies_shows_data.ipynb' file doesn't load, please use the following link to view the code and visuals:
[movies_shows_data.ipynb](https://nbviewer.jupyter.org/github/calvintirrell/Movie_Data/blob/main/movies_shows_data.ipynb)

Merged 3 different CSV files of data into 1 large single dataframe (df) using SQL-like syntax.
Looked into the columns ('tag', 'timestamp_y') with missing data. 
These columns had 3,476 values compared to 102,677 values in the other columns.
This equates to over 96% of data that is lacking in these 2 columns.

The most common 'tag' is "In Netflix queue" with 55 occurrences.
This isn't particularly surprising given how much new content Netflix updates with, meaning users regularly find more to add to the 'watchlist'.
"Dark Comedy" rounded out the 10th spot with 20 occurrences.

The top 3 most watched movies consist of Pulp Fiction (1994), Forrest Gump (1994) and The Shawshank Redemption (1994).
These movies had 484, 335 and 319 occurrences in the data. Interesting to see they are all from the year 1994.
The top 10 most watched movies didn't have anything newer than 1999 - The Matrix and Fight Club.

Comedy, Drama and Romance or some combination of these genres dominated the top 6 out of 10 most common genres.
Action, Adventure, Thriller and Sci-Fi rounded out the last 4 spots of the 10 most common genres.
The drop off between the 2nd and 3rd most common genres, Drama then Comedy|Romance, was the largest difference at 2,402.

A rating of '4' was the most common rating with 27,208 occurrences but the overall average rating of the movies was '3.5'.
The 2nd most common rating was '3' with 20,189 occurrences and a '5' rating is in 3rd with 13,921 occurrences.

Overall, there are 610 unique users, 9,274 unique movies, 1,543 unique tags and 951 unique genres.
