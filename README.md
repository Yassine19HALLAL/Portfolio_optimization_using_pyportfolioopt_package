# Portfolio_optimization_using_pyportfolioopt_package
# Introduction :

In this work, we have conducted portfolio optimization using the mean-variance optimization technique implemented through the powerful pyportfolioopt library in **Python**. 

Mean-variance optimization is based on **Harry Markowitz**’s 1952 classic paper, which spearheaded the transformation of portfolio management from an art into a science. The key insight is that by combining assets with different expected returns and volatilities, one can decide on a mathematically optimal allocation.

The primary objective of this work is to **construct and analyze three distinct portfolios** with varying optimization goals.

- **Minimum Volatility** : The first portfolio aimed to minimize volatility, emphasizing stability and capital preservation. 
- **Unconstrained Maximum Sharpe ratio** : The second portfolio, unconstrained in its approach, focused on maximizing the Sharpe ratio, which balances risk and reward.
- **Constrained Max Sharpe ratio Portfolio (L2 Regularization)** : Finally, the third portfolio incorporated L2 regularization as a constraint, striving to strike a balance between risk management and performance optimization.

To evaluate the effectiveness of these portfolios, we plotted the efficient frontier, which represents the set of portfolios that offer the highest expected return for each level of risk. This visualization provides valuable insights into the risk-return trade-offs and allows for a comprehensive comparison of the three optimized portfolios.

The analysis and comparison of these three portfolios on the efficient frontier enable us to understand the impact of different optimization strategies on risk, return, and the overall portfolio composition.

## Data informations :

The financial data used corresponds to 10 US companies operating in different sectors, The date ranges from **01 January 2015** to **01 January 2020.** :

- **Apple Inc. (AAPL)** - Technology sector
- **Johnson & Johnson (JNJ)** - Healthcare sector
- **Procter & Gamble Co. (PG)** - Consumer goods sector
- **JPMorgan Chase & Co. (JPM)** - Financial sector
- **Exxon Mobil Corporation (XOM)** - Oil and gas sector
- **Amazon.com Inc. (AMZN)** - E-commerce/Technology sector
- **Coca-Cola Company (KO)** - Beverage sector
- **Microsoft Corporation (MSFT)** - Technology sector
- **Barrick Gold Corporation (GOLD)** - Gold mining sector
- **Chevron Corporation (CVX)** - Oil and gas sector

we are going to import the data from Yahoo Finance using the corresponding python package (yfinance), and we are going to retrieve the **Adjusted Close** price as it takes into consideration dividends and stock splits.

# References :

## Biblio

- Stewart, S. D., Piros, C. D., & Heisler, J. C. (2019). Portfolio Management: Theory and Practice. John Wiley & Sons.
- Brugière, P. (2020). Quantitative Portfolio Management with applications in Python. In Springer texts in business and economics. Springer International Publishing.
- PyPortfolioOpt documentation.

## Web :

- Various YouTube channels.
- GitHub Repos.
- And of course, StackOverflow.
