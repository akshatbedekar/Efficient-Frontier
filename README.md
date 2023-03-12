# Efficient-Frontier
In order to plot Capital Allocation line we took Historical prices
We took 2 asset portfolio
First is SNP500 (SPY)
Second is assets outside of United states (VXUS)
We calculted Daily returns of each day ((that day- previous day)-1)
We calculated Mean, St. deviation, covariance and Risk free rate(we take 2% /252 which is total trading days) using the data
We took different portfolio weights of SPY AND VXUS
-ve indicates short selling
For portfolio statistics we calculted returns
Returns= summation of weights * avg return
similarly we calculted the st dev and sharpe ratio
We want max sharpe ratio
Its formula is (Return- risk free rate)/st dev.
Optimal portfolio is with maximum sharpe ratio
We used a xy scattered plot for plotting the efficient frontier
We also plot Capital Allocation line which is tangent to efficient fronties and point where it is tangent gives us return for optimal portfolio
