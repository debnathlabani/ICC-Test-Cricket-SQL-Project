# ICC-Test-Cricket-SQL-Project

Dataset : ICC Test Batting Figures.csv
License: Public
Source: https://www.kaggle.com

Test cricket is the form of the sport of cricket with the longest match duration and is considered the game's highest standard. Test matches are played between national representative teams that have been granted ‘Test status’, as determined and conferred by the International Cricket Council (ICC). The term Test stems from the fact that the long, gruelling matches are mentally and physically testing. Two teams of 11 players each play a four-innings match, which may last up to five days (or longer in some historical cases). It is generally considered the most complete examination of a team's endurance and ability.

The Data consists of runs scored by the batsmen from 1877 to 2019 December.

Tasks to be performed:
1.	Import the csv file to a table in the database.
2.	Remove the column 'Player Profile' from the table.
3.	Extract the country name and player names from the given data and store it in seperate columns for further usage.
4.	From the column 'Span' extract the start_year and end_year and store them in seperate columns for further usage.
5.	The column 'HS' has the highest score scored by the player so far in any given match. The column also has details if the player had completed the match in a NOT OUT status. Extract the data and store the highest runs and the NOT OUT status in different columns.
6.	Using the data given, considering the players who were active in the year of 2019, create a set of batting order of best 6 players using the selection criteria of those who have a good average score across all matches for India.
7.	Using the data given, considering the players who were active in the year of 2019, create a set of batting order of best 6 players using the selection criteria of those who have highest number of 100s across all matches for India.
8.	Using the data given, considering the players who were active in the year of 2019, create a set of batting order of best 6 players using 2 selection criterias of your own for India.
9.	Create a View named ‘Batting_Order_GoodAvgScorers_SA’ using the data given, considering the players who were active in the year of 2019, create a set of batting order of best 6 players using the selection criteria of those who have a good average score across all matches for South Africa.
10.	Create a View named ‘Batting_Order_HighestCenturyScorers_SA’ Using the data given, considering the players who were active in the year of 2019, create a set of batting order of best 6 players using the selection criteria of those who have highest number of 100s across all matches for South Africa.
