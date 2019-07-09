# The challenge: Steam Gaming

> Background: Steam is one of the largest gaming networks in the world with over 100 million active gamers. The Steam dataset covers 109 million user accounts, 196 million friendships, 3 million groups, 384 million owned games, and a collective 1 million years of playtime.

You can find out more here about the details of each dataset: https://steam.internet.byu.edu/

Data:

- [Small version](https://workable.com/nr?l=https%3A%2F%2Fstorage.googleapis.com%2Fdatatonic-steam-gaming-challenge%2Fsteam_gaming_small.zip) (46 MB)
- [Large version](https://workable.com/nr?l=https%3A%2F%2Fstorage.googleapis.com%2Fdatatonic-steam-gaming-challenge%2Fsteam_gaming_large.zip) (1.3 GB)
Feel free to use whichever you can comfortably work with on your machine.



# Exercise 1: Data Engineering

This exercise should be completed using PySpark (although feel free to use any of the APIs). [Here](https://medium.com/tinghaochen/how-to-install-pyspark-locally-94501eefe421) is a guide on how to install PySpark on your local machine.

Install and run PySpark.
Load .csv for Player_Summaries, Game_Publishers, Game_Genres, Game_Developers, Games_1 into PySpark dataframes.
Join all `Games_` tables into one dataframe.
Count the number of games per `publisher` and per `genre`.
Find day and hour when most new accounts were created (based on Player_Summaries table) e.g. 8pm on 14th August 2005.
Please send your code as per the instructions below.



# Exercise 2: Analytics

**Business case**

Your client is a mental health expert from an NGO who is interested in understanding more about gaming and the potentially addictive effect it can have on some individuals. You are meeting the client in a few days and they would like you to extract and present insights from the Steam dataset to help them in their research.

Please use whichever tools you feel the most comfortable with.



# Exercise 3: Advanced

If you still have time ... be creative and impress us with something novel, do an analytics deep-dive or show off some machine learning. For instance, use supervised methods to make predictions or recommendations, or use network analysis on the friends table.
