**Portfolio Selection Strategies**

This project aims to compare the performances of seven different computational investment strategies. They are the “Buy and Hold” strategy, “Equally weighted” portfolio strategy, “Minimize variance” portfolio strategy, “Maximum Sharpe ratio” portfolio strategy, “Equal risk contributions” portfolio strategy, “Leverage equal risk contributions” portfolio strategy and “Robust mean-variance optimization” portfolio strategy.

The data used for the comparison of
performance is Daily_closing_prices.csv and Daily_closing_prices20082009.csv. The portfolio
is composed of 20 stocks. The total period is 2 years, from November 2019 to December 2021
for the first csv and from November 2007 to December 2009 for the second csv. There are 12
holding periods and each holding period is 2 months. The portfolio can be rebalanced a
maximum of 12 times. Every time the portfolio is rebalanced, there is a transaction cost. The
transaction cost is the difference between the selling and bidding price of the stock and is 0.5%
of the traded volume. 

The initial value of the portfolio is $ 1000013.0. The initial cash account is zero USD,
and the cash account needs to remain nonnegative. The cash account does not have any interest
and is used for buying stocks at the next portfolio rebalance. Buying and selling a non-integer
number of shares is not allowed, so the number of shares bought or sold needs to be rounded to
integer values and subtract transaction fees. CPLEX and IPOPT optimization solver are used to complete the project.

After comparing the outputs, the daily value of the portfolio, maximum drawdown of the
portfolio, and the dynamic changes in portfolio allocation, the “Maximum Sharpe
ratio” strategy is selected for 2020-2021 and the “Minimize
variance” strategy is selected for 2008-2009. 
