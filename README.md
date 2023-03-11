# Back-Testing-Trading-Rules
This project aims to explore the effectiveness of using the directional volatility indicator (DVI) signal in back testing trading rules. DVI is a popular signal used by traders in algorithmic trading to identify the trend of a stock's price movement. By back testing the DVI signal, we can simulate how the signal would have performed in the past, and evaluate its effectiveness in predicting stock price movements.

The project requires implementing three functions that analyze the DVI signal using different inputs and parameters. The first function performs a base level back test, where it applies the long and short rule based on a default DVI threshold of 0.5. The function outputs the total number of long and short trades, the percent of time the portfolio is long and short, and the cumulative return from the strategy.

The second function simulates multiple back test periods, using all possible periods within a specified testing period. The function outputs a table containing the means of the five items indicated in the first function and a plot showing the cumulative return from the strategy.

The third function simulates multiple DVI thresholds by varying the threshold from a low value to a high value with specified increments. The function outputs a table showing the total number of long and short trades and the cumulative return from the strategy for each threshold value, along with a plot showing the relationship between the threshold value and cumulative return.
