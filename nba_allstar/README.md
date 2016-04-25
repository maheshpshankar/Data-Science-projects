##Prediction models for All-NBA teams
Machine learning, Data mining techniques used to forecast who will be voted to All-NBA basketball teams.

See NBA_predictions_rough.ipynb to look at the various models used for predictions. 

Other ipython notebook's contain scraping functions, preprocessing data and some data analysis.

### Data:

|column_name|name|legend_name|table_name|
| ----------|:-----:|:-------------:| -----:|
|player|Player|PLAYER|Per Game Player Stats|
|pos|Position|POS|Per Game Player Stats|
|age|Age|AGE|Per Game Player Stats
|bref_team_id|Team ID|BREF_TEAM_ID|Per Game Player Stats|	
|g|Games Played|G|Per Game Player Stats|
|gs|Games Started|GS|Per Game Player Stats|
|mp|Minutes Per Game|MP|Per Game Player Stats|
|fg|Field Goals Made Per Game|FG|Per Game Player Stats|
|fga|Field Goal Attempts Per Game|FGA|Per Game Player Stats|
|fg.|Field Goal %|FG%|Per Game Player Stats|
|x3p|3PT Shots Made Per Game|3PM|Per Game Player Stats|
|x3pa|3PT Shot Attempts Per Game|3PA|Per Game Player Stats|
|x3p.|3PT %|3P%|Per Game Player Stats|
|x2p|2PT Shots Made Per Game|2PM|Per Game Player Stats|
|x2pa|2PT Shot Attemps Per Game|2PA|Per Game Player Stats|
|x2p_|2PT Shot %|2P%|Per Game Player Stats|
|ft|Free Throws Made Per Game|FT|Per Game Player Stats|
|fta|Free Throw Attempts Per Game|FTA|Per Game Player Stats|
|ft_|Free Throw %|FT%|Per Game Player Stats|
|orb|Offensive Rebounds Per Game|ORB|Per Game Player Stats|
|drb|Defensive Rebounds Per Game|DRB|Per Game Player Stats|
|trb|Total Rebounds Per Game|TRB|Per Game Player Stats|
|ast|Assists Per Game|AST|Per Game Player Stats|
|stl|Steals Per Game|STL|Per Game Player Stats|
|blk|Blocks Per Game|BLK|Per Game Player Stats|
|tov|Turnovers Per Game|TOV|Per Game Player Stats|
|pf|Personal Fouls Per Game|PF|Per Game Player Stats|
|pts|Points Per Game|PPG|Per Game Player Stats|
|PER|Player Effiecieny Rating||Per Game Player Stats|
|TS%|True Shooting Percentage||Per Game Player Stats|
|3PAr|Three Point Attempt Rate||Per Game Player Stats|
|FTr|Free Throw Attempt Rate||Per Game Player Stats|
|TRB%|Offensive Rebound Percentage||Per Game Player Stats|
|AST%|Assist Percentage||Per Game Player Stats|
|STL%|Steal percentage||Per Game Player Stats|
|BLK%|Block Percentage||Per Game Player Stats|
|TOV%|Turnover Percentage||Per Game Player Stats|
|USG%|Usage Percentage||Per Game Player Stats|
|OWS|Offensive Win Shares||Per Game Player Stats|
|DWS|Defensive Wins Shares ||Per Game Player Stats|
|WS|Win Shares||Per Game Player Stats|
|WS/48|Wins per 48 mins||Per Game Player Stats|
|OBPM|Offensive Box Plus/Minus||Per Game Player Stats|
|DBPM|Defensive Box Plus/Minus||Per Game Player Stats|
|BPM|Box Plus/Minus||Per Game Player Stats|
|VORP|Value Over Replacement Player||Per Game Player Stats|

Data is scraped from: http://www.basketball-reference.com
