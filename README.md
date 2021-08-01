# Predict_future_sales
This is my attempt for the data science competition on Kaggle - Predict future sales

The link for this competition can be found here: https://www.kaggle.com/c/competitive-data-science-predict-future-sales/overview

1)Simple exploratory data analysis to preprocess outliers

2)Extensive feature generation, included lagged features for target variable as well

3)Normalised numeric features to prevent dependency on features

3)Decided to go with LGBMregressor model 

4)Tuned hyperparameters to prevent overfitting by evaluating train and validation sets

The metric for this competition is Root mean squared error, the score for this model is RMSE=1.01 on the kaggle test set.


