# Prediction-of-Wild-Blueberry-Yield

[Competition Overview](https://www.kaggle.com/competitions/playground-series-s3e14/overview)

## Files:

- **blueberry_data_exploration**
  - *Purpose:* This notebook explores the top 5 attributes strongly correlated with wild blueberry yield, offering simple visualizations to clarify their relationships.

- **equal_weights_ensemble_gradient_boosting_random_forest**
  - *Purpose:* Implements an ensemble model with equal weights between Gradient Boosting and Random Forest. Achieves an MAE of 356.694.

- **performance_based_weights_ensemble_gradient_boosting_random_forest**
  - *Purpose:* Implements a performance-based ensemble model with Gradient Boosting and Random Forest. Mean MAE using 10-fold cross-validation is 344.543.

- **voting_regressor_ensemble_lgbm_catboost**
  - *Purpose:* Implements a VotingRegressor ensemble model with LightGBM and CatBoost. Mean MAE using 10-fold cross-validation is 344.039.
  
- **xgb_regressor**
  - *Purpose:* Implements an XGBoost (XGBRegressor) model. Mean MAE using 10-fold cross-validation is 373.724.
  
- **sample_submission.csv**
  - *Description:* Sample submission file sourced from Kaggle, demonstrating the proper submission format.
  
- **test.csv**
  - *Description:* Testing dataset sourced from Kaggle, used for generating submissions.

- **train.csv**
  - *Description:* Training dataset sourced from Kaggle, used to train the models.
