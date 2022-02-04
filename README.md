# New-York-City-Taxi-Fare-Prediction

## Problem Statement
The main goal is to predict the fare amount (inclusive of tolls) for a taxi ride in New York City given the pickup and dropoff locations. The basic estimate can be found, based on just the distance between the two points. However, this will result in an RMSE of $5 - $8, depending on the model used. The main challenge is to reduce the current RMSE to around $3 by using improved Machine Learning Models. This improvement can be carried out through Hyperparameter Tuning.

## Tasks Performed
1. Downloading Required Dataset.
2. Loading Training and Test Dataset.
3. Exploring the Training and Test Datasets.
4. Splitting the Training Dataset into Training and Validation Datasets.
5. Selecting Input and Target Columns.
6. Training and Evaluating Hardcoded Model.
7. Training and Evaluating Baseline Model.
8. Making Predictions and Submitting the Results to Kaggle Competition (Received a score of 9.41 on Kaggle)
9. Performing Feature Engineering.
10. Removing Outliers According to the Test Dataset.
11. Training and Evaluating: a. Ridge Regression (Received a score of 6.93 on Kaggle), b. Random Forest Regression (Received a score of 4.49 on Kaggle), c. Gradient Boosting Model (Received a score of 4.06 on Kaggle)
12. Performing Hyperparameter Tuning for the best model (Gradient Boosting)
13. Training the Final Gradient Boosting Model.
14. Evaluating the Final Gradient Boosting Model (Received a score of 3.82 on Kaggle)

#### Dataset Source: https://www.kaggle.com/c/new-york-city-taxi-fare-prediction/data

## Results
1. Developed several Machine Learning Models.
2. Compared the models according to a set of criteria and determined the best fit.

## Models Used
1. Linear Regressor
2. Ridge Regressor
3. Random Forest Regressor
4. XGB Regressor

##### Best Model: XGB Regressor (Gradient Boosting Model)
##### Mean Squared Error(M.S.E.):
##### Training Set: $3.37
##### Validation Set: $4.44
##### Kaggle Score: $3.82
