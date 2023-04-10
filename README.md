# Predicting Pokemon Battles

## The Goal
For this project, the goal is to predict the outcome of Pokémon battles based on individual Pokémon characteristics as well as results from previous battles. The models and predictions will be utilized by professional Pokémon players in order to stay ahead of the ever-evolving strategy, meta, of the game. In turn, those professional Pokémon players will consistently do well at tournaments.

## Data
All three files can be found on [Kaggle.](https://www.kaggle.com/datasets/terminus7/pokemon-challenge)

pokemon.csv contains all the information on the Pokemon characteristics like HP, attack, defense, etc.
combats.csv contains 50,000 simulated battles built by a custom algorithm
tests.csv can be used to predict Pokemon battles

## Conclusion
The best model that could predict Pokemon battles was the XGBoost model with an r2 score of .71. While the model isn't as accurate as it could be, it can still produce a faster timeline for professional players to find the best meta in the game.
