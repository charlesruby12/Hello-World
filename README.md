# My First Repository
This is a sample README.md file comparing and analyzing batting stats of players on the Milwaukee Brewers. This repository contains 
a description of the project, tools and files used, and how the program was executed.

## Table of Contents

- [PROJECT TITLE](#Project-Title)
- [DESCRIPTION](#Description)
- [TOOLS USED](#Tools-Used)
- [FILES USED](#files-used)
- [HOW TO RUN PROGRAM](#How-to-run-program)
- [ADDITIONAL INFORMATION](#additional-information)

## Project Title

*Hello World - My First Repository Analyzing the Milwaukee Brewers' Batting Stats*

## Description

In this project, I compiled batting stats of every Milwaukee Brewers player from the 2026 season and ranked the players who
met certain thresholds. After stats were compiled from an external file, I decided that the best statistic to rank players by
was OPS (on base plus slugging). To clarify, for a batter to be qualified in my ranking, they needed to have at least 100
at bats in the regular season.

Once all the stats were read into my code, I looped through the statistics, and printed the output which was the ranking of the
players. The Brewers had 15 qualified batters according to my criteria, and Jake Bauers was ranked number one with an OPS of 
.873. Luis Rengifo was the lowest qualified batter with an OPS of .534. Overall, I was able to create a solid ranking of 
batters on the Brewers because OPS combines the two biggest indicators of batting success with on base percentage and slugging
percentage, which is average number of bases per at bat.

## Tools Used

Some tools that I used in this project were Excel and Python. I used Excel to compile hitting stats, exported them to a text file,
and read the text file into Python where I coded the statistics to the output of my player rankings.

## Files Used

- Screenshot 2026-10-7 144852.png
- qgofpeunax8fbak4cfnf.jpg
- The first file contains batting stats from qualified Brewers players from the 2026 regular season, and the second file is an image
  of the team celebrating after their walkoff win on October 4, 2026 against the Padres.
- URL: https://www.mlb.com/brewers/stats/at-bats/regular-season
- URL: https://img.mlbstatic.com/mlb-images/image/upload/ar_16:9,g_auto,q_auto:good,w_1024,c_fill,f_jpg/mlb/qgofpeunax8fbak4cfnf

## How to Run Program 

First, the text file with player stats needs to be read in. Then, a a loop needs to be created where it retrieves each individual 
player's OPS, and sorts them from highest to lowest. Finally, the output needs to be printed. 

Hello_World/
└── 
    │── README.md
    │── brewers_hitting_stats_2026.txt
    
## Additional Information
   
There is no perfect predictor to rank players based off of stats, however, I determined that OPS is the best statistic to rank 
players solely based on hitting. 

