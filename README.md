# NBA-games-visualisation-and-shooting-success-probability
This Sports Analytics project aims at creating a visualization tool for basketball games, incorporating the shooting success probability at any time.

## Project decomposition

This project has three main components:
- A Logistic Regression model which outputs, given the distances between the ball carrier, the defender that is closest to him and the basket, a shooting success probability. This model has been created using the `shot_logs.csv`file and can be found in the `model`folder.
- The `data_transformation.ipynb` noteboook that takes the .json games files that contain the positions of the ball and of the ten players on the court, completes and transforms it to prepare it for the animtation.
- The `animation.py` file that displays the games' plays with the associated shooting success proability.

## Data

The `shot_logs.csv` file used to build the shooting success probability model can be found [on kaggle](https://www.kaggle.com/dansbecker/nba-shot-logs). It contains data on shots taken during the 2014-2015 season, who took the shot, where it was on the court, where was the closest defender, and more.
