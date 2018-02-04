# Playstation_game_recs
Code for building a recommender system using Playstation trophies

The files psn_profiles_list_k.txt, for k = 1, 2, 3, are lists of Playstation Network users and games that they have trophies for. Each line has the format

user  game  trophy_rank

Trophy rank is a letter S, A, B, C, D, E, or F (in descending order). Higher rank corresponds to more trophies and higher inferred user rating of the game.

PSN game recs v2 is an ipython notebook which contains the code used to scrape this data from the web, along with code for building a user similarity matrix from the data and using it to produce recommendations for a particular user. It also has a couple graphs to illustrate the relevance of the data for this task. Note that the functions for scraping data and for building the similary matrix may takes several days to run.
