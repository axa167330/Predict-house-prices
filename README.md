# Predict-house-prices
In this project I used data on house sales in King County to predict prices using multiple regression. 

# Part 1: 
Explored multiple regression in particular explored the impact of adding features to a regression and measuring error.
 Used SciKit Learn functions to compute the regression weights (coefficients)
 Given the regression weights, predictors and outcome wrote a function to compute the Residual Sum of Squares
 Looked at coefficients and interpreted their meanings

# Part 2:
Used a polynomial regression as a mean to examine this dataset.
 Used a matplotlib to visualize polynomial regressions
 Used a matplotlib to visualize the same polynomial degree on different subsets of the data
 Used a validation set to select a polynomial degree
 Assess the final fit using test data

# Part 3:
Used ridge and Lasso regression multiple times with different L1 and L2 penalties to see which one produces the best fit.
 Used a pre-built implementation of regression to run polynomial regression
 Used matplotlib to visualize polynomial regressions
 Used a pre-built implementation of regression to run polynomial regression, with L1 and L2 penalty
 Used matplotlib to visualize polynomial regressions under L2 regularization
 Chose best L1 and L2 penalty using cross-validation.
 Assessed the final fit using test data.
 For the best fit Lasso regression found the list of significant features.

# Part 4:
For the last part implemented k-nearest neighbors’ regression.
 Predicted the output for the query input using the k-nearest neighbors
 Chose the best value of k using a validation set
