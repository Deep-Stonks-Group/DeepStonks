# Retrieving and Formatting Data

The purpose of this portion is to create an easy way for people designing algorithms to get data. Since the process of getting data tends to be redundant, but also needs to be precise, there is a need for a method of doing this quickly and easily. There are a variety of types of data that someone might need to retrieve, so it is up to you to figure how to get the data efficiently, and ensure that it is formatted quickly.

- Needs to get different types of data:
  1. All stock/crypto historic data.
  2. Specific stock/crypto historic data.
  3. All stock financial data:
     * Income sheet
     * Balance Statement
     * Cash flow
  4. Social media data.
  5. Intraday data if possible.
  6. Technical Analysis data.
- Needs to be able to reformat the data so that there is a set of training data x associated with a label y.
- Output:
  1. X:
     * Needs to be able to format data such that the output is simple where each row corresponds to a single time iteration.
  2. Y:
     * The data label
     * This can be the closing price of the next minute / hour / day / next week / next month / 10 days from now etc.
