# Construct Optimal Portfolio Using Fama-French factors
## STEP 1
UsedFama-Frenchfactorstoconstructoptimalportfolios:Market,SizeandValue,pickedthetop10ETFsforeachfactor and searched daily historical data from 2010 to 2019 in ETF database and Yahoo Finance, computed their daily return.
## STEP 2
Ran linear regression on each factor using Python, filtered these ETFs based on the condition of R2>0.7 and Sharpe Ratio>0, ranked them based on the coefficient of each factor, selected top 3 ETFs to construct portfolio within each factor.
## STEP 3
Calculated the weight of 3 ETFs by using three different strategies: Equal-Weighted, Mean-Variance Efficiency and Minimum Variance, chose MVE method to form an ultimate optimal porfolio using each factors optimal portfolio.
