# Bul_dozer_price_prediction
## `Note`: Since all the data files are not uploaded together U can download the from https://www.kaggle.com/c/bluebook-for-bulldozers/data following the data page.
## Predicting the sale price of bulldozers using Machine Learning
In this notebook, we're going to go through an example machine learning project with the goal of predicting the sale price of bulldozers.
## 1.Problem Definations
How well can we predict the future sale price of a bulldozer, given its characteristics and previous examples of
how much similar bulldozers have been sold for?
### 2.Data
The data is downloaded from the Kaggle Bluebook for Bulldozers competition: https://www.kaggle.com/c/bluebook-for-bulldozers/data

There are 3 main datasets:

`Train.csv` is the training set, which contains data through the end of 2011.
`Valid.csv` is the validation set, which contains data from January 1, 2012 - April 30, 2012 
 ## You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.
`Test.csv` is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012.
 Your score on the test set determines your final rank for the competition.
## 3 Evaluations 
The evaluation metric for this competition is the RMSLE (root mean squared log error) between the actual and predicted auction prices.

For more on the evaluation of this project check: https://www.kaggle.com/c/bluebook-for-bulldozers/overview/evaluation

Note: The goal for most regression evaluation metrics is to minimize the error. For example, our goal for this project will be to build a machine learning model which minimises RMSLE.
## 4.Features 
Kaggle provides a data dictionary detailing all of the features of the dataset. You can view this data dictionary on

`u can use Data Dictionary to see all the features`guration - describes operator control configuration


## Features enginering 
in this we will either create a new features or change around the existing features 

## Dependency to be downloaded
install pandas
install numpy
install matplotlib.pyplot
## model to be used 
(# U can use any model here but personaly I have used RandomForestRegressor as it is a versatile machine-learning technique for predicting numerical values. It combines the predictions of multiple decision trees to reduce overfitting and improve accuracy.
`RandomForestRegressor`
