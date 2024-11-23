# Business Question
### Selecting the best 11 players (cricket team) from (2008-2020) Indian Premier League Cricket Data.

Team composition should be

2 x Opening Batsmen

2 x Middle Order Batsmen

1 x Wicket Keeper

3 x All Rounders

3 x Bowlers

### Assumptions
All the players in the dataset are available for selection

No restriction on number of overseas players in final 11

### This Data has information about 605 Players who played IPL from 2008 to 2020.


# Definitions for the columns

Batting Average (batting_avg): The average number of runs scored per time the batsman gets out.

Batting Strike Rate (batting_strike_rate): The number of runs scored by the batsman for every 100 balls faced. or ratio of runs scored to the number of balls faced

Boundaries Percentage (boundaries_percent): Boundaries percentage is the proportion of a batsman's runs that come from hitting fours and sixes.

Bowling Economy Rate (bowling_economy): Bowling economy rate is how many runs a bowler concedes per over they bowl.

Bowling Average (bowling_avg): Bowling average is the average number of runs a bowler concedes per wicket they take.

Bowling Strike Rate (bowling_strike_rate): Bowling strike rate is how frequently a bowler takes wickets. It's the average number of balls bowled by the bowler for each wicket they take.


# Opening Batsmen
We are looking for an ideal opening batsmen with below criteria.

Batting average > 30

Batting strike rate > 130

Matches > 5

Boundaries percent > 19

# Middle Order Batsmen
Filtering Middle Order Batsmen with the below criteria.

Batting average > 30

Batting strike rate <= 130

Batting strike rate >= 100

Matches > 10

Balls Faced / Match > 24

# Wicket Keeper
Filtering Wicket keepers with below criteria.

Stumpings > 8

Batting Average > 130

Matches > 15

# Allrounders

Filtering Allrounders with below criteria.

Batting average > 15

Batting strike rate > 100

Balls faced > 100

Wickets > 10

Balls bowled > 400

Bowling economy < 10

Bowling strikerate < 24

# Bowlers
Filtering bowlers with below criteria.

Balls bowled > 300

Bowling economy < 8

Bowling strike rate < 20

Bowling average < 23

Wickets > 20

# Key findings based on the analysis:
1. Top Performers Identification: Identified the top performers in terms of total runs scored, wickets taken, catches taken and Allround performance shedding light on the most influential players in the league.

2. Performance Correlation Analysis: Conducted a analysis to understand the relationship between batting average and batting strike rate. Discovered a positive correlation between batting average and batting strike rate, indicating that players who score more runs tend to do so at a faster pace.

3. Identification of Optimal Team Composition: Utilized performance metrics to find the best possible team lineup comprising 11 players. Leveraged data from key metrics to formulate a balanced team.

# Future improvements
1. Collect Current Auction Prices: Incorporating data on each player's current auction price would enhance team selection strategies by considering their market value and aligning it with the team's budgetary constraints.

2. Include Player Age: Introducing a column for player age would facilitate the selection of athletes at their peak physical fitness and performance, aiding in crafting a competitive team.

3. Yearly Performance Metrics: Creating columns for runs scored, wickets taken, and matches played per year would provide insights into a player's performance trajectory over time. This granularity enables the evaluation of current form and consistency, aiding in informed decision-making during player selection.

4. International Representation: Adding a column indicating each player's international representation would enable teams to strategize around player availability during the IPL season, optimizing team composition and reducing conflicts with international commitments.

5. Local vs. Foreign Players: Introducing a column categorizing players as local or foreign allows teams to adhere to league regulations mandating a maximum of four foreign players per team, facilitating compliance and team structuring.

6. Player Categories: Incorporating a column to distinguish player categories, such as batsmen, bowlers, or all-rounders, provides valuable insights into player specialties and roles within the team, aiding in evaluating the data with ease.
