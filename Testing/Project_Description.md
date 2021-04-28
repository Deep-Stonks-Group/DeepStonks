# Testing System

This portion of the project will be resposible for testing the algorithms created to predict the stock market. The goal is to develop a systemized method for
testing the algorithms so that there is a consistent way to compare results across methods. We need a dedicated team to creating this, because testing is redundant 
across all algorithms, and we need to ensure that it is done correctly for each algorithm so that we know we can trust the results. It is important to be confident
that these testing functions work properly so that we do not end up using faulty algorithms. 

There are several basic goals:
1. Convert a dataset into a testing, training and validation dataset and labels.
2. Call a function and pass the predictions / testing labels, and produce the standardized results.

- Takes all data as input and outputs the training / validation / testing data.
- Systemized testing methods for all algorithms.
  1. Testing on different date ranges (Not just the data at the end).
  2. Standardized metrics for testing:
      * Sharpe ratio
      * Loss
      * Accuray
- Types of tests
  1. Testing on specific stock/crypto or on all data in specific markets.
  2. Tests under different periods of data:
      * Hourly
      * Minute
      * Day
      * Weekly
      * Monthly
  2. Tests under different forecast periods
      * Next minute
      * Next hour
      * Next day
      * Next week
      * Next Month
      * Next year
  2. Tests under different goals
      * If price is going up or down
      * Exact price prediction
- Maybe eventually should take labels / predictions and produce consistent results so that methods can be easily compared.




