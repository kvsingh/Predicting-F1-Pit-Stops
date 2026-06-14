# Predicting-F1-Pit-Stops
Done as a part of Kaggle's Playground Series Prediction Competition at https://www.kaggle.com/competitions/playground-series-s6e5

Uses a probability-weighted ensemble of XGBoost and LGBM, both tuned with Optuna, and feature engineered priors for 3 pairs of features. 3 features (Driver, Race and Year) were removed from the XGB model on performing shap value analysis, since they did not lead to improvement in cross validated AUC scores.

Final Rank : 1142/3022
