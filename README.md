# Overview:
This project uses sabermetrics and other personally deveolped equations to construct an optimal lineup. Optimal lineups for my favorite MLB team, the Detroit Tigers, as well as a lineup for the entire MLB. I use www.baseball-reference.com for my 2019 player data sets. I used R Studio to add two addition columns (wOBA and wRC+) to the csv files as well as filter players with less than 200 plate appearances in 2019.

Found the best player at each position using wRC+ then applied sabermetric guidelines to choose the player at each part in the lineup.

# Assumptions: 
- Defensive skills are not values.
- Pitchers will not hit, allowing a designated hitter to hit in their place.
- Accounted for players that are utility, middle infielder, corner infielders, and outfielders.
