# ETL-project

Our project was about eSports and Video Games. We compared two kaggle data sets - eSports earnings & Video Game Sales.

https://www.kaggle.com/jackdaoud/esports-earnings-for-players-teams-by-game
https://www.kaggle.com/gregorut/videogamesales

First we cleaned the data by removed nan values, dups, etc, etc. (bad data)
Then we transformed that data to see similarities or any games that were in both sets
Then we loaded that data in pgAdmin

Our results on yielded one game that was in both sets, which was interesting to see but kind of makes sense because most competitive games need a mass of players, which would give us more insight as to why the most competitive games are free.

We also found that loading the cleaned data separately made more sense than just loading the results of our analysis. I also find this as a more sustainable approach, as this loaded data was still clean, but not so specific as to not be useful for anything else in the future.
