# WNBA 2016 Stats Analysis

## Overview
This project analyzes player statistics from the 2016 WNBA season. Using a dataset of 174 players, we explore individual and team performance through univariate, bivariate, and trivariate data analysis.

## Data Source
- The data was sourced from [Basketball Reference: WNBA 2016 Totals](https://www.basketball-reference.com/wnba/years/2016_totals.html).
- The table was converted to CSV format and cleaned for analysis in R.
- The dataset includes player name, team, position, games played/started, minutes, field goals, 2pt/3pt stats, free throws, rebounds, assists, steals, blocks, turnovers, fouls, and points.

## Data Cleaning
- Duplicate columns for Games (G) and Minutes Played (MP) were removed.
- Percentage columns were renamed to use 'P' instead of the '%' symbol for R compatibility.

## Analysis Steps
- **Univariate Analysis:** Explored distributions of games started, field goal percentage, and assists.
- **Bivariate Analysis:** Compared team free throw percentages and examined the relationship between free throw attempts and makes.
- **Trivariate Analysis:** Investigated how player position relates to two-point and three-point shots made.

## Key Findings
- Many players did not start games, but some consistently started over 30.
- Shooting and assist stats highlight both individual skill and team play.
- Team and position influence performance patterns, with clear differences in shot selection and success.

## Conclusion
The 2016 WNBA stats reveal the depth and diversity of talent in the league. Players contribute in many ways beyond just scoring, and the data provides a detailed look at what drives team and individual success.