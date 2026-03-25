# AlphaPulse — Investment Risk & Volatility Monitor

A financial analytics project that analyzes portfolio risk 
for a boutique investment firm using real stock market data.

## What This Project Does

Takes real stock price data for 5 major companies and tells 
you exactly how risky your investment portfolio is and what 
it might be worth in one year.

## Stocks Analyzed
- Apple (AAPL)
- Google (GOOGL)
- Microsoft (MSFT)
- Amazon (AMZN)
- Tesla (TSLA)

## How It Works

First I pulled 2 years of real stock data using the yfinance 
library. Then I calculated daily returns and risk for each 
stock. The main analysis is a Monte Carlo simulation that 
runs 10,000 different future scenarios for the portfolio 
and shows the range of possible outcomes after one year.

## Key Results

- Ran 10,000 portfolio simulations
- Calculated Value at Risk (VaR)
- Found stock correlations
- Built 30 day rolling volatility tracker
- Interactive Power BI dashboard for executives

## Tech Used

- Python and Pandas for data processing
- yfinance for real stock data
- NumPy for mathematical calculations
- Matplotlib and Seaborn for charts
- Power BI for interactive dashboard
- Google Colab for cloud computing

## Files

- alphapulse_analysis.ipynb — complete Python code
- portfolio_summary.csv — risk and return per stock
- var_summary.csv — Value at Risk calculations
- correlation_matrix.csv — how stocks move together
- rolling_volatility.csv — 30 day volatility tracker
- AlphaPulse.pbix — Power BI dashboard

## How to Run

1. Open alphapulse_analysis.ipynb in Google Colab
2. Run all cells in order
3. Open AlphaPulse.pbix in Power BI Desktop

