# House-Price-Prediction
Advanced Regression ML based Predictive modelling

source - https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques

# Steps involved-
## 1. Null Treatment
-- Removed columns with null values more than 20% to avoid data reliability issues
## 2. Outlier Detection
-- Almost all the numerical columns have extreme outliers, so capping or dropping them would cause data reliability issue,
-- so we can proceed with the data without any actions.
## 3. Univariate, Bivariate, Multivariate analysis
-- Refer the notebook for detailed analysis.
## 4. Model Building
-- Since numerical features are not normally distributed, and sheer presence of extreme outliers leaves us to choose tree based / Ensemble models.
-- Loss Function - RMSE is choosen as the loss function for the given regression problem.
-- Our objective is to build a model with least RMSE score. 
Hyper parameter tuned XGBOOST model was the best optimal model in my case.
## 5. Future Enhancements
-- Increase Model complexity -  Polynomial Feature Engineering 
-- Advanced architectures - CNN, RNN

S
