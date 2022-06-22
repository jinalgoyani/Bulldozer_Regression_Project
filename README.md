# Bulldozer_Regression_Project

## Predicting the sales price of bulldozers using Machine Learning.

1. Problem Definition
> How well can we predict the future sale price of a bulldozer given its characteristics and previous record of sales.(Regression Problem).

2. Data
The data is used from kaggle's blue book for bulldozers, link: https://www.kaggle.com/c/bluebook-for-bulldozers/data

There are three main datasets:

Train.csv is the training set, which contains data through the end of 2011.
Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.
Test.csv is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competition.

3. Evaluation
The evaluation metric for this competition is the RMSLE (root mean squared log error) between the actual and predicted auction prices. For more on the evaluation check: https://www.kaggle.com/c/bluebook-for-bulldozers/overview/evaluation

**Note: Our goal for this project will be to build a machine learning model which minimises the RMSLE.**

4. Features
Kaggle provides the data dictionary describing all the features of a dataset. You can view this data dictionary here- https://www.kaggle.com/competitions/bluebook-for-bulldozers/data
