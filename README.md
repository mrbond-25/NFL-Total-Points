# NFL-Total-Points
A project to build and test regression models for total points scored in NFL games, with applications to over/under betting.

## Models

1. Linear Model
2. Neural Network
3. Extreme Gradient Boosting (XGBoost)

All models are regressions to predict the total points scored in each game. The model output is then compared against the over/under betting line to "place" bets.

## Dataset
The dataset `game_data.csv` contains NFL games from 1999, obtained using the R package `nflreadr`.

## Model Features
1. Home and Away Offensive Expected Points Added (EPA) per play
2. Home and Away Defensive EPA per play
3. Game temperature
4. Season type (regular vs playoffs)
