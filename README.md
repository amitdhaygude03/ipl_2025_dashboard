IPL 2025 Statistics Dataset

image : ![Screenshot 2025-10-27 131023](https://github.com/user-attachments/assets/59c0132e-3f80-41bf-883a-d6f85ee183f5)

image : ![Screenshot 2025-10-27 131053](https://github.com/user-attachments/assets/f2e61d18-ef3b-4763-a5d4-5abf873ed5e3)

This repository contains comprehensive batting and bowling statistics from the Indian Premier League (IPL) 2025 season.
Dataset Overview
The dataset consists of two CSV files:

IPL2025Batters.csv - Batting statistics for all players
IPL2025Bowlers.csv - Bowling statistics for all players

File 1: IPL2025Batters.csv
Description
Contains batting performance data for all players who participated in IPL 2025.
Columns
ColumnDescriptionPlayer NameName of the playerTeamTeam abbreviation (GT, MI, RCB, LSG, PBKS, RR, DC, SRH, CSK, KKR)RunsTotal runs scoredMatchesNumber of matches playedInnNumber of innings battedNoNumber of times not outHSHighest score (with * indicating not out)AVGBatting average (Runs / Dismissals)BFBalls facedSRStrike rate (Runs per 100 balls)100sNumber of centuries scored50sNumber of half-centuries scored4sNumber of fours hit6sNumber of sixes hit
Key Statistics

Total Players: 149
Top Run Scorer: Sai Sudharsan (GT) - 759 runs
Highest Strike Rate (min 100 runs): Nicholas Pooran (LSG) - 196.25
Most Centuries: Sai Sudharsan - 1 century (multiple players with 1 each)
Most Fifties: Virat Kohli (RCB) - 8 fifties

Team Abbreviations

CSK - Chennai Super Kings
DC - Delhi Capitals
GT - Gujarat Titans
KKR - Kolkata Knight Riders
LSG - Lucknow Super Giants
MI - Mumbai Indians
PBKS - Punjab Kings
RCB - Royal Challengers Bangalore
RR - Rajasthan Royals
SRH - Sunrisers Hyderabad

File 2: IPL2025Bowlers.csv
Description
Contains bowling performance data for all players who bowled in IPL 2025.
Columns
ColumnDescriptionPlayer NameName of the bowlerTeamTeam abbreviationWKTTotal wickets takenMATNumber of matches playedINNNumber of innings bowledOVRTotal overs bowledRUNSTotal runs concededBBIBest bowling in an innings (format: wickets/runs)AVGBowling average (Runs per wicket)ECOEconomy rate (Runs per over)SRStrike rate (Balls per wicket)4WNumber of 4-wicket hauls5WNumber of 5-wicket hauls
Key Statistics

Total Bowlers: 102
Top Wicket Taker: Prasidh Krishna (GT) - 25 wickets
Best Economy Rate (min 10 wickets): Jasprit Bumrah (MI) - 6.67
Best Bowling Average: Jaydev Unadkat (SRH) - 15.90
Best Strike Rate: Vignesh Puthur (MI) - 12.00 balls per wicket
5-Wicket Hauls: Hardik Pandya (MI), Mitchell Starc (DC) - 1 each

Notable Bowling Performances

Most 4-Wicket Hauls: Yuzvendra Chahal (PBKS), Harshal Patel (SRH) - 2 each
Most Overs Bowled: Prasidh Krishna (GT) - 59 overs
Most Economical (qualified): Jasprit Bumrah (MI) - 6.67 economy rate

Data Quality Notes

Some players appear in both datasets (all-rounders)
Average (AVG) for batters may show "-" when a player was never dismissed
Bowling figures use format "runs/wickets" for BBI (Best Bowling in Innings)
Strike rates are calculated differently:

Batting SR: (Runs / Balls Faced) × 100
Bowling SR: Balls Bowled / Wickets Taken



Usage
These datasets can be used for:

Performance analysis and player comparisons
Team strategy evaluation
Fantasy cricket team selection
Statistical modeling and predictions
Visualization of player and team performances

Data Format
Both files are in CSV (Comma-Separated Values) format with headers in the first row.
Season Information

Tournament: Indian Premier League 2025
Format: T20 Cricket
Teams: 10 franchises
