# Predicting-F1-Pit-Stops
Done as a part of Kaggle's Playground Series Prediction Competition at https://www.kaggle.com/competitions/playground-series-s6e5

## Approach
* Uses a probability-weighted ensemble of XGBoost and LGBM, both tuned with Optuna
* Feature Engineered priors for 3 pairs of features
* 3 features (Driver, Race and Year) were removed from the XGB model on performing shap value analysis, since they did not lead to improvement in cross validated AUC scores.

## Things which did not help:
* Surface temperature data
* Feature Filtering using Mutual Information and Permutation Baseline

## Final Rank 
1142/3022

## Original Notebook Link
https://www.kaggle.com/code/teamaker/optuna-tuned-xgb-lgbm-ensemble-and-feature-eng
