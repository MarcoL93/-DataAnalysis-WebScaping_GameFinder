# Find the best Videogames ever thanks to Python

I wanted to follow the project about TV Series and Movies with one about videogames, but failing to find a good dataset, I decided it was time to created one that could fit my needs. So thanks to a Firefox add-on, I was able to scrap data from Metacritic: in particular, all the 49 pages about the video games available on PC. [https://www.metacritic.com/browse/games/score/metascore/all/pc]

Once I collected almost 50 files of CSV raw data (available in RawData folder), I was able to clean the data into a usable dataset (the script and the final .csv file are available in the DataSet folder). After that I created a script that ask the users for a particular game genre and in return it generates an Excel file with all the games, ordered by rating* with two different sheets: one for singleplayer games and one for the ones with multiplayer game modes.

*The rating system is based on a weighted average between both Metascore (an average of the votes from the critics) and the User Score (an average of the votes collected from users reviews). The Metascore weight is equal to the 70% of the total rating. The reason is to avoid penalizing the titles that are affected by review bombing from the site's users.
