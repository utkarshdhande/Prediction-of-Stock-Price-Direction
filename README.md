# Prediction of Stock Price Direction
 
The task is to predict the day price direction of Amazon.com, Inc. (AMZN).

The stock market is very complex and highly volatile. In order to be profitable, we do not need to predict the correct price, but rather, the price direction: whether it will be higher or lower than the price that is today. If we predict it to be higher, we might as well buy some stocks, else, we should probably sell. Therefore, the target would be a binary classification whether the next day closing price will be higher than the opening price.

We have data for the period from 1997 up to the year 2020 that we have split into training (1997-2016), validation (2016-2018) and testing (2018-2020) periods. The data is available in the AMZN_train.csv, AMZN_val.csv and AMZN_test.csv files, respectively.
