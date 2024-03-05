## Data Curation Project

### Explanation

This is a project I did for my BYU Stat 386 class. Our task was to curate a data set by web scraping that we could use to answer questions of interest.

### Details

The English Premier League (EPL) is widely recognized as the top soccer (or football) league in the world. I am a huge fan of the EPL. One of the biggest events that happens each year in the EPL isn’t actually a game; rather, it is the transfer window (in other sports, this may be known as the trade deadline or trade window). One of the biggest talking points throughout the season is which players will get transferred to where.

My obsession with EPL has led me to wonder about how much the top players’ Estimated Transfer Values (ETVs) are, and also what teams they play for. In order to answer questions of this topic, I will use data scraped from [this website](https://www.footballtransfers.com/us/players/uk-premier-league) (Football Transfers).

### Contents of Repo

This repository contains the file I used to scrape the data using Selenium. It also contains a csv file of the data set after it was scraped.

What follows is an explanation of the variables in the csv file:
* **name** - name of the player
* **position** - position of the player
    - GK - goalkeeper
    - D - defender
    - M - midfielder
    - DM - defensive midfielder
    - AM - attacking midfielder
    - F - forward
    - (CRL) - center, right, left
* **skill** - a player's skill, measured by the influence the player has on the team for which he plays (input variables are age, minutes played, type of match, strength of league and opponent, number of goals scored and conceded by the player's team)
* **pot** - a player's potential, measured by the maximum skill level a player is expected to reach throughout his career based on his development to date
* **etv** - estimated transfer value (in millions of pounds)

Please reach out to me with any questions concerning this project!