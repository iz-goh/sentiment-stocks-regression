# Regression Analysis of Stocks with Large Positive Online Sentiment

## Description
In this analysis, I attempt to study whether the performance of stocks with large amounts of positive online sentiment can be explained by market interest rate levels, the previous day's market benchmark movement, and the previous day's crypto market benchmark movement -- items that tend to garner significant attention by market participants, much like high sentiment stocks.

## Data sets used
* Positive sentiment stocks -- VanEck Social Sentiment ETF (ticker: BUZZ)
* Interest rate -- CBOE 10 Year Treasuries Yield
* Stock market benchmark -- S&P 500
* Crypto market benchmark -- S&P Cryptocurrency LargeCap Ex-MegaCap Index 

## Packages used
Pandas is for our data cleaning, Statsmodels to perform the Ordinary Least Squares (OLS) regression, the subsequent residual analysis, and data transformations, as well as matplotlib to visualise our residuals.

## Usage
Feel free to download the project and experiment with the regression, and create a pull request should you have any suggestions for improvement of the project.