# Module-3-V2.1
<<<<<<< HEAD
# Capstone-Project
=======

## Overview
My objective is to build a classifier to predict whether a customer will ("soon") stop doing business with SyriaTel, a telecommunications company. 
The assumption is that obtaining a new customer is more expensive than retaining an existing customer; I'll be looking for overall accuracy of each model, as well as the recall. 

## Outline
- Descriptive values of dataset
- Calculate churn percentage
- EDA: bar chart by state, zip code, etc.
- Change intl plan, vm plan to binary. one hot endcode states (prepare dataset to be modeled)
- Remove redundant columns, target
- Build feature matrix and standardize
- Build ROC curve to determine how we will handle imbalanced target size
- Build four models with normalized confusion matrix for each model
- Get feature importance from whichever model performs best

The models evaluated were: Logistic Regression, Decision Tree, Gradient Boosting, and XGBoost. XGBoost proved to be the most accurate. 
I also used GridSearchCV to find the best parameters for XGBoost; this resulted in an accuracy score of 97%.

Finally, I plotted the feature importance of the XGBoost model (using gain) to determine the features our telecommunications company should focus on to reduce churn.
>>>>>>> e5dee6e320330835602303bb621ec30d145ba731
