# Portfolio Analysis in R

## Overview
This project performs a portfolio analysis using R, focusing on portfolio performance evaluation and comparison with benchmark indices. The analysis is documented in an R Markdown (PortfolioAnalysis.Rmd) file that combines code, outputs, and explanatory text into a reproducible workflow.

The project is designed to:
- Retrieve financial data (e.g., stock prices, benchmark indices)
- Construct and rebalance a portfolio
- Evaluate portfolio performance metrics (e.g., returns, risk, Sharpe ratio)
- Compare results to benchmarks
- Visualize portfolio composition and performance trends

## Requirements
### R Packages
The following R packages are required:
- quantmod – financial data retrieval and time series analysis
- tidyverse – data wrangling and visualization
- PerformanceAnalytics – performance metrics and risk analysis
- ggplot2 – additional custom visualizations
- knitr – R Markdown rendering

Install these packages if not already present:
install.packages(c("quantmod", "tidyverse", "PerformanceAnalytics", "ggplot2", "knitr"))

## How to Use
1. Clone or download the repository containing this .Rmd file.
2. Open PortfolioAnalysis.Rmd in RStudio.
3. Adjust any parameters for:
   - Portfolio tickers
   - Analysis time period
   - Rebalancing frequency
   - Benchmark index
4. Knit the document to HTML or PDF to produce a full report.

## Outputs
- Portfolio Performance Summary: Return, volatility, Sharpe ratio, and other key metrics
- Comparison with Benchmarks: Plots and tables showing relative performance
- Visualizations: Time series charts, cumulative returns, and allocation breakdown

## File Structure
- PortfolioAnalysis.Rmd: Main analysis file
- data/: (Optional) Folder for any manually downloaded datasets
- plots/: (Optional) Folder for saved figures

## Customization
- Modify the list of portfolio tickers in the code chunk "portfolio_symbols"
- Adjust date ranges and benchmark symbols as needed
- Extend analysis by adding additional metrics (e.g., Value at Risk, Expected Shortfall)


