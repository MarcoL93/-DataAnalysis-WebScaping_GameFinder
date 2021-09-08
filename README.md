# Find the best Tv Series thanks to Python

I wanted to follow the project about Tv Series and Movies, with one about videogames, but failing to find a good dataset I decided it was time to created one that could fit my needs. So thanks to a Firefox addon i was able to scrap data from Metacritic: in particular all of the 49 pages about the videogame avaible on PC. [https://www.metacritic.com/browse/games/score/metascore/all/pc]

Once i collected almost 50 files of csv raw data (available in RawData folder), i was able to clean the data into a usable dataset (the script and the final .csv file are available in the DataSet folder). After that I created a script that ask the users for a particular game genre and created an excel file with all the games, order by rating* with two different sheets: one for singleplayer games and one for the ones with multiplayer game modes.

*The rating system is based on a weighted average between both Metascore (an average of the votes from the critics) and the User Score (an average of the votes collected from users reviews). The Metascore weight is equal to the 70% of the total rating. The reason is avoid to penalise the tiles that are affected by review bombing from the users site.
