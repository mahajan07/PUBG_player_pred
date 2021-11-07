# PUBG PLAYER PREDICTION ON UNKNOWN BATTLEGROUNBD::
### DESCRIPTION Domain: Gaming
Create a model that predicts players’ finishing placement based on their final stats, on a scale of 1 (first place) to 0 (last place). 
### Problem Statement:  
PlayerUnknown’s BattleGrounds (PUBG) has enjoyed massive popularity. With over 50 million copies sold, it’s the fifth best-selling game of all time and has millions of active monthly players.

Provideddata is with a large number of anonymous PUBG game stats, formatted so that each row contains one player’s post-game stats. The data comes from matches of all types, i.e., solos, duos, squads, and custom. There is no guarantee of having 100 players per match, or at the most 4 players per group. In the game, a player can find and use a variety of weapons, items, and vehicles. Players must also avoid the shrinking “circle”, which pushes players closer together on the map. 

#### Analysis to be done: Perform data preprocessing, build a deep learning prediction model. 

# Steps guide to perform exploration of the data and apply feature engineering on the data to predict players finishing placement.

* Data Exploration:
Check mean, quantile, and max kill </br>
Draw inference by plotting kill counts__
Check signs of cheating

* Feature Engineering:
Creating new features from existing to depict data in a better way
Expressing relative rank instead of absolute in the form of percentage
Dropping redundant features
Dropping cheaters
Grouping and aggregating features

* Model Creation:
Create a sequential model with Keras using Tensorflow backend
Take four dense layers, three dropout layers, three batch normalizations, and use PreLu as an activation function
