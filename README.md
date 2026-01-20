The project uses kaggle datasets from the March Machine Learning Mania 2025 to build features from which a logistic regression model
can predict outcomes of tournament games. The features are comprised of regular season data, to reflect how a person would predict before 
making their own tournament bracket. The initial features chosen are Net Rating difference, Assists to Turnover Ratio difference, Effective Field Goal Percentage difference, True Shooting Percentage difference, and Seed Difference, with possibility to be changed in the future. These features were chosen from the regular season detailed dataset. The current ROC AUC score with a logistic regression model is 76% and log loss is at 0.58.

Currently: Switching over to an XGBoost model with hopes of better performance overall, as well as adding strength of schedule and some other features!
