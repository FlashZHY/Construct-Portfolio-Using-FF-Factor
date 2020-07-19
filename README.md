# Construct Optimal Portfolio Using Fama-French factors
### STEP 1
Use Fama-French factors to construct optimal portfolios: Market, Size and Value, pick the top 10 ETFs for each factor and searched daily historical data from 2010 to 2019 in ETF database and Yahoo Finance, compute their daily return.
### STEP 2
Run linear regression on each factor using Python, filter these ETFs based on the condition of R2>0.7 and Sharpe Ratio>0, rank them based on the coefficient of each factor, selected top 3 ETFs to construct portfolio within each factor.
### STEP 3
Calculate the weight of 3 ETFs by using three different strategies: Equal-Weighted, Mean-Variance Efficiency and Minimum Variance, choose MVE method to form an ultimate optimal porfolio using each factors optimal portfolio.
