# Modeling-Ranked-Match-Outcomes-Using-Early-Game-Performance-Data-in-League-of-Legends

## Project Overview
This project explores how early-game performance metrics influence match outcomes in ranked League of Legends games from Gold to Diamond tiers. Using publicly available match data from the Riot Games API, the analysis focuses on aggregated team-level and role-level statistics—such as gold difference, objective control, and kill participation—to model their relationship with the final outcome of the game.

## Purpose
The goal of this project is educational and analytical: to better understand which early-game factors are most strongly associated with winning ranked matches. The project is intended for research, learning, and portfolio purposes, and it does not target or profile individual players.

## Data Handling & Privacy
- All player identifiers (summoner names, PUUIDs, or account IDs) are removed or anonymized before storage.

- Analysis is conducted at the match and role level only.

- No data is used for real-time advantage or commercial purposes.

- The project complies with Riot Games’ API policies regarding responsible data use.

## APIs Used

- Match: for retrieving match timelines and stats.

- Summoner: for player identification and tier information (used transiently and anonymized).

- Champion: for champion metadata.

## Key Features & Analyses

- Aggregated team and role-level statistics at the 10-minute mark of matches.

- Early-game metrics such as:

  - Gold difference by role

  - Objective control (towers, dragons, heralds)

  - Kill participation percentages

  - Modeling the relationship between these metrics and final match outcomes using machine learning and statistical analysis.

## Results & Outputs

- All results are presented in aggregate form, highlighting trends and correlations at the team and role level.

- Visualizations illustrate early-game factors most strongly associated with winning.

## Getting Started
- The code is organized into notebooks and scripts for data ingestion, feature engineering, and modeling. Users can reproduce the analysis using their own Riot API key.

## Disclaimer
This project is intended solely for educational and research purposes. No individual player data is shared, tracked, or published in any form.
