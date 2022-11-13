# Simulation of FIFA 2022 World Cup using Machine Learning

This repo contains a project that aims to simulate the World CUp using ML Algorithms. In order to do the predictions, I used the dataset of last 4 years of Football Intenational Games and FIFA's rankings, and created the features. To follow the logic used you can:

- Run, first, the notebook db creator.ipynb, which has the code to create the raw database containing game, tournament, and FIFA ranking of the teams.
- Run features eng.ipynb, which creates features's candidates to the problem.
- Run data analysis.ipynb, which analyses all candidates created, and creates new features that have predictive power based on combination of the first proposed features.
- Run model.ipynb, which creates and analyses the prediction model.
- Run wc simulation.ipynb, which simulate FIFA 2022 World Cup.

The final result was Brazil vs. England at the final, with Brazil winning their sith title.
If you want to read some explanation about the code: https://www.kaggle.com/code/sslp23/predicting-fifa-2022-world-cup-with-ml
