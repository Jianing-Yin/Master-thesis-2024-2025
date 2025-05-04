Master-thesis-2024-2025
# Title: Data-driven modelling for optimization of chemical dosing in drinking water production.
This is a repository for thesis modelling study. 
# Table of Contents
# Baseline models
Here, the Historical Mean Baseline Model is used. The historical average of train data is calculated and applied as the predicted value for the future test set. Then, this predicted value is compared with test data to calculate the evaluation metrics, then evaluting the performance of this 'model'. This method is only the historical data of turbidity, which is the target of this case study. Rather than saying a model, this simple calculation just give a reference point for further modeling and discussion. 
# Statistical models
* ARIMA
* SARIMA
* SARIMAX
* FB Propeht
# Machine Learning models
* KNN Regressor
* LightGBM
* XGBoost
# Deep learning models 
* LTSM
* TFT
* N-BEATS
# Results and discussion
* Feature selection -> Result-driven -> More features (i.e. meteorological features and water quality features together). Feature-driven -> feature engineering & feature selection -> feature importance -> interpretability (SHAP vs. tree-based models feature importance)
* Anomaly detection and remove -> Different methods own their own effects. -> Directly applied techniques on original time series data and decompose time series data, remove outliers from residuls component, then reconstruct three components show different results.
*  Resample (i.e. hourly -> daily -> weekly-> monthly -> yearly)
*  Model performance comparison. 
