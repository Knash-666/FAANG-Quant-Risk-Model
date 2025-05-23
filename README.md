# FAANG Quant Risk Model

A quantitative finance project analyzing the risk and performance of a FAANG (Facebook, Amazon, Apple, Netflix, Google) portfolio against the S&P 500 (SPX). This project calculates key metrics like Monthly Return, Average Daily Return, Standard Deviation, Beta, Treynor Ratio, and Value at Risk (VaR) to assess the portfolio’s risk-return profile.

## Project Overview

- **Data**: Daily price data for FAANG stocks (e.g., FB from Jan-Feb 2014) and SPX.
- **Analysis**: Calculated performance metrics (returns), risk metrics (Std Dev, VaR), and risk-adjusted metrics (Treynor Ratio).
- **Portfolio**: Assumes equal weights for FAANG stocks.

## File

- [`FAANG_Risk_Model.xlsx`](./FAANG_Risk_Model.xlsx): Excel file containing daily price data, calculated metrics, and visualizations.

## Key Findings

1. NFLX outperforms with the highest monthly return (3.32%) and avg daily return (0.11%), but also has the highest risk (Std Dev: 12.06%, VaR 99%: -32.86%).
2. GOOG has the lowest monthly return (1.46%) and risk-adjusted performance (Treynor: 1.06%), but also the lowest volatility (Std Dev: 6.80%).
3. The FAANG Portfolio (Monthly Return: 2.36%, Treynor: 1.67%) outperforms SPX (0.86%) with moderate systematic risk (Beta: 1.30).
4. NFLX and AMZN show high market sensitivity (Beta: 1.49 and 1.34), while AAPL is the least sensitive (Beta: 1.19) among FAANG stocks.

## Visualizations

- **Monthly Returns**: Compares monthly returns across FAANG stocks, the portfolio, and SPX.  
  ![Monthly Returns](monthly_returns.png)

- **Standard Deviation**: Shows volatility for FAANG stocks and SPX.  
  ![Standard Deviation](std_dev_chart.png)

- **Treynor Ratio**: Displays risk-adjusted performance (return per unit of systematic risk).  
  ![Treynor Ratio](treynor_ratio.png)

- **Value at Risk (VaR)**: Highlights downside risk at 95% and 99% confidence levels.  
  ![Value at Risk](var_chart.png)

## Skills Demonstrated

- Quantitative Finance
- Risk Management
- Financial Modeling
- Data Visualization (Excel)

## Tools Used

- Excel (for data analysis, calculations, and charting)
- GitHub (for project hosting and sharing)
