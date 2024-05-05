# Prediction of Stock Price Direction
 
The task is to predict the day price direction of Amazon.com, Inc. (AMZN).

The stock market is very complex and highly volatile. In order to be profitable, we do not need to predict the correct price, but rather, the price direction: whether it will be higher or lower than the price that is today. If we predict it to be higher, we might as well buy some stocks, else, we should probably sell. Therefore, the target would be a binary classification whether the next day closing price will be higher than the opening price.

We have data for the period from 1997 up to the year 2020 that we have split into training (1997-2016), validation (2016-2018) and testing (2018-2020) periods. The data is available in the AMZN_train.csv, AMZN_val.csv and AMZN_test.csv files, respectively.

Table of contents:
1. [Data Exploration](#data-exploration)
2. [Feature Engineering](#feature-engineering)
3. [Classical Machine Learning Algorithms](#classical-machine-learning-algorithms)
    - [Logistic regression](#logistic-regression)
    - [Decision tree](#decision-tree)
    - [Random forest](#random-forest)
    - [Gradient boosting ensemble](#gradient-boosting-ensemble)
4. [Deep Learning Algorithm](#deep-learning-algorithm)
5. [Conclusion](#conclusion)


After using the above mentioned ML algorithms, the gradient boosting classifier provided the best AUC score on the validation set. It is a common machine learning practice to train multiple models on the same train/validation data set and provide a model that works best.
