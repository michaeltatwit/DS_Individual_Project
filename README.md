# DS_Individual_Project

## Introduction
This project will be examining trends in player stats among National Basketball Association (NBA) end of season awards. First, it is important distinguish the awards that will be examined, as well as what they mean for a player to recieve the award. What separates this project from the other NBA data analysis projects is that this examines every individual player stats in the league, and gets into depth for individual end of season awards, rather than team performance and success.

#### Awards Overview

Most Valuable Player (MVP): Arguably the most prestigious award of them all, the MVP award goes to the overall "best" player of the NBA season, which is usually the player that is most important to the team. However, fans don't always agree with the chosen MVP and there is constant debate on who it should be.

All-NBA First Team: At the end of the season, there are three teams of players from different teams named to an All-NBA team. The All-NBA teams consist of three teams, All-Nba 1st, 2nd, and 3rd team, in which 1st is the most prestigous of the three. The 1st team consists of 5 players who have played the best basketball out of anyone in the league in the previous season, and also consists of the NBA MVP. It is important to note that the ALL-NBA First team is in the same format as the starting 5 in basketball: 2 guards, 2 forwards, and a center.

Most Improved Player (MIP): This award is given to the player who has shown the most growth between last season and the current season. It is usually given to an under the radar player, but can also be given to a big name if they improve enough.

#### Analysis of Awards

For Most Valuable Player, this project will explore the historical data to identify the minimum statistical thresholds across the main categories (points, assists, rebounds, steals, and blocks) that players have achieved in past seasons to win the MVP award. Additionally, we will examine the team performance aspect, specifically the minimum team seed required for a player to be considered for the MVP. This analysis aims to establish a benchmark for what it takes statistically and team-success-wise to win the MVP award and to predict who might win the MVP in the 2023-24 season based on current statistics and team standings.

For the All-NBA First team, the project focus will be on determining the relationship between a player’s scoring efficiency, particularly true shooting percentage, points per game (PPG), and their likelihood of being named to the All-NBA First Team. By analyzing historical data, we aim to understand how scoring efficiency correlates with selection for the All-NBA First Team and use this relationship to forecast the 2023-24 All-NBA First Team selections based on players’ performance metrics during the current season.

For Most Improved player, this project will investigate the statistical benchmarks, such as increases in points per game, shooting percentages, and rebounds per game, that are common among past winners of the NBA Most Improved Player award. The goal is to identify a set of significant performance improvements that indicate a player's eligibility for the MIP award and use these benchmarks to predict the 2023-24 MIP based on the current season's data.

## Data

The data that was used was chosen to incorporate all players. The reason being because superstars are much more common to be included in these discussions, but this project aims to exclude any of that and solely look at the stats. All NBA players are included in the current season and previous season files, and every MVP, MIP, and first team is located in their respective files as well, so no data is left behind. 

Some of the data was tricky to handle, as columns meant the same thing but were labeled differently. This was handled by comparing them at the beginning, and just using the current columns as the basis for the rest of the code:
![](graph/DifferentColumnNames.png)

### Sources of data

Every single NBA player's stats in the current 2023-24 season, ordered by points per game: https://www.espn.com/nba/stats/player

Every very previous NBA MVP and their stats: https://www.basketball-reference.com/awards/mvp.html

Every NBA first team, and each player's stats: https://www.espn.com/nba/history/awards/_/id/44

All Most improved players and their stats for the year they won: https://www.espn.com/nba/history/awards/_/id/36

2022-23 player stats for comparison with this years for MIP: https://www.basketball-reference.com/leagues/NBA_2023_per_game.html


## Methods
- Linear Regression to identify relationships between player stats and award winnings, predicting MVP based on statistical benchmarks.
  
- Logistic Regression to predict the likelihood of a player being named to the All-NBA First Team based on efficiency metrics 
  like true shooting percentage.

- Time Series Analysis for tracking improvements in player performance over seasons, aiding in Most Improved Player predictions.
