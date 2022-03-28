# Lasso-Regression-to-Predict-NBA-Regular-Season-Records

##### Goals:
- Use lasso regression on data from prior NBA seasons to determine which statistics are most important in predicting a team's regular season record

##### Project Sections: 
1. Import Packages
2. Clean Data
3. Explore Data with Visualizations
4. Train and Test a Lasso Regression Model
5. Bonus Analysis of Timberwolves 2021-2022 Season

##### Data:
- Downloaded from https://www.basketball-reference.com/
- 150 observations: 30 NBA teams' data from the following 5 regular seasons: 2015-2016, 2016-2017, 2017-2018, 2018-2019, 2020-2021
- 1 response variable: 
    - W: Regular season wins
- 31 predictor variables:
    - MP: Average minutes played per game
    - FG: Average number of field goals per game
    - FGA: Average number of field goal attempts per game
    - FG%: Field goal percentage
    - 3P: Average 3 point shots made per game
    - 3PA: Average 3 point shots attempts per game
    - 3P%: 3 point shot percentage
    - 2P: Average 2 point shots made per game
    - 2PA: Average 2 point shot attempts per game
    - 2P%: 2 point shot percentage
    - FT: Average free throws made per game
    - FTA: Average free throws attempted per game
    - FT%: Free throw percentage
    - ORB: Average offensive rebounds per game
    - DRB: Average defensive rebounds per game
    - TRB: Average total rebounds per game
    - AST: Average assists per game
    - STL: Average steals per game
    - BLK: Average blocks per game
    - TOV: Average turnovers per game
    - PF: Average personal fouls per game
    - PTS: Average points scored per game
    - Age: Average age of the players on the team
    - eFG%: Effective field goal percentage - similar to FG% except more weight is given to 3 pointers than 2 pointers
    - TOV%: Turnover percentage - number of turnovers per 100 plays
    - ORB%: Offensive rebound percentage 
    - FT/FGA: Free throws per field goal attempt
    - OeFG%: Opponents' effective field goal percentage
    - OTOV%: Opponents' turnover percentage
    - DRB%: Defensive rebound percentage 
    - OFT/FGA: Opponents' free throws per field goal attempt
