
# Predict Bike Sharing Demand with AutoGluon

This project explores leveraging AutoGluon, an open-source AutoML library from AWS, to forecast bike-sharing demand using the Kaggle Bike Sharing Demand dataset. The primary goal is to utilize AutoGluon's Tabular Prediction capabilities to quickly build accurate baseline models while minimizing the challenges typically associated with tasks such as data cleaning, feature engineering, hyperparameter tuning, and model selection.




## Approach

The dataset was downloaded and analyzed to understand its features and characteristics. A baseline model was trained using AutoGluon’s Tabular Prediction with default settings, and initial predictions were submitted to Kaggle for ranking.
Comprehensive exploratory data analysis (EDA) was performed to assess the impact of dataset modifications on model performance, followed by feature engineering to enhance predictive accuracy. These enhancements were implemented using AutoGluon’s automated default configurations.
After the initial analysis and feature adjustments, multiple model iterations were conducted to refine performance. During these iterations, the feature-engineered dataset was used to train the model, with select hyperparameters fine-tuned to achieve further improvements.

