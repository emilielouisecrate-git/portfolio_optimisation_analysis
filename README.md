# Portfolio Optimisation Analysis (Microsoft, Ebay and Intel)

## Overview
This project explores portfolio optimisation using real-world stock data from Microsoft (MSFT), eBay (EBAY) and Intel (INTC). The aim is to analyse the trade-off between risk and return, construct efficient portfolios and identify the optimal allocation using mean-variance optimisation. 

## Key features
- Computation of **log returns**
- Descriptive statistics (mean, variance, volatility)
- Covariance and correlation analysis
- Portfolio simulation across different weight combinations
- Identification of:
    - Efficient Frontier
    - Inefficient Portfolios
    - Minimum Variance Portfolio
- Visualisation of risk-return trade offs.

## Data 
- Source : NASDAQ historical data
- Period : January 2025 - December 2025
- Assets :
  - eBay (EBAY)
  - Microsoft (MSFT)
  - Intel (INTC)

## Key Insights
- Intel exhibits the **highest returns but also the highest volatility**, making it the riskiest asset.
- Microsoft provides **stable, lower-risk returns**, acting as a defensive asset.
- eBay lies between the two, offering moderate risk-return characteristics.
- All assets are **positively correlated**, but not perfectly, allowing for diversification benefits.
- A diversified portfolio significantly reduces risk compared to holding Intel alone.

As shown in the analysis a portfolio such as : 
30% eBay, 40% Microsoft, 30% Intel
achieves a strong return while reducing overall volatility. 

## Efficient Frontier
The efficient frontier represents the set of optimal portfolios offering the highest reurn for a given level of risk. Portfolios below the frontier are **inefficient**, and potential, rational investors should always choose portfolios on the frontier. 

## Minimum Variance Portfolio 
The minimum variance portfolio minimises the overall risk. With no constraints, and short selling allowed, the approximate weights are: 
- eBay : 33.7%
- Microsoft : 69.4%
- Intel : -3.1% (short selling allowed)

This demonstrates how optimisation can even involve short positions. 

## Conclusion 
This project highlights the importance of diversification and portfolio construction in achieving optimal risk-return trade offs. Rather than investing in a single asset, combining assets with imperfect correlation leads to more efficient outcomes. 

## Tools used
- Excel for the simulation grid and data
- Data visualisation libraries. 
