# Quantitative Momentum Strategy

"Momentum investing" means investing in the stocks that have increased in price the most.

Goal: Build an investing strategy that selects the 50 stocks with the highest price momentum. From there, we will calculate recommended trades for an equal-weight portfolio of these 50 stocks.

# Executive Summary

* Implemented a Quantitative Momentum Strategy to identify the top 50 high-momentum stocks, employing the yfinance library to extract historical stock price data.
  
* Used the Momentum Investing approach, which entails investing in stocks exhibiting the highest price increments.
  
* Refined a realistic momentum strategy to discern between "high quality" and "low quality" momentum stocks, laying emphasis on “slow and steady” outperformance over long durations.
  
* Engaged a strategic approach to identifying HQM stocks by evaluating highest percentiles of 1-month, 3-month, 6-month, and 1-year price returns.
  
* Effectively computed momentum percentile scores for each stock on key metrics: One-Year, Six-Month, Three-Month, and One-Month Price Return.
  
* Devised the HQM Score by computing the arithmetic mean of the four momentum percentile scores, utilizing Python's built-in statistics module for precision.
  
* Systematically selected the 50 best momentum stocks by sorting on the HQM Score, retaining only the top-tier stocks for the equal-weight portfolio.
  
* Employed the XlsxWriter library to generate well-formatted Excel outputs, aiding in efficient data representation and interpretation.
  
* Utilized advanced data visualization techniques to illustrate the results, facilitating a clear understanding of the momentum strategy’s outcomes and potential market impacts.
  
* The number of shares to buy and the HQM scores can be found in momentum_strategy.csv
