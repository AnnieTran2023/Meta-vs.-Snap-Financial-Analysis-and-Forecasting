# Meta vs. Snap: Financial Analysis and Forecasting

This project presents a detailed analysis of the stock prices of Meta Platforms Inc. (META) and Snap Inc. (SNAP) over a five-year period. By sourcing historical stock data from Yahoo Finance, the project aims to uncover trends and correlations, test hypotheses, and forecast future price movements using time series analysis.

## Project Overview

The primary objective of this project is to analyze the financial performance and relationship of two tech giants, Meta and Snap. By examining the data, we can identify potential trends, compare the performance, and predict future stock prices for these companies.

### Key Features

- Descriptive statistics (mean, median, variance, etc.)
- Correlation analysis between the stock prices of Meta and Snap
- Hypothesis testing using t-tests to assess significant differences
- Time series forecasting using Exponential Smoothing models

## Data Source

The data for this project is obtained from [Yahoo Finance](https://finance.yahoo.com/), covering a five-year period. Daily adjusted closing prices of Meta (META) and Snap (SNAP) were selected for this analysis.

## Analysis Techniques

1. **Descriptive Statistics** - Summarizing key statistics such as mean, median, standard deviation, etc., to understand basic stock price behavior.
  
2. **Correlation Analysis** - Investigating the correlation between Meta and Snap stock prices to understand potential relationships.
  
3. **Hypothesis Testing (t-test)** - Conducting t-tests to evaluate if there is a significant difference between Meta and Snap’s average stock prices.

4. **Forecasting with Exponential Smoothing** - Building a time series model using exponential smoothing to predict future price trends.

## Results

Our findings from the analysis can be summarized as follows:

- **Descriptive Statistics** - Both stocks exhibit unique trends, with varying volatilities and average price levels.
- **Correlation Analysis** - The correlation coefficient suggests a [relationship/absence of relationship] between Meta and Snap stock prices.
- **Hypothesis Testing** - The t-test results indicate [significance/no significance] in the average price difference between the two stocks.
- **Forecasting** - The exponential smoothing model provides a forecast indicating [anticipated trend] for both companies.

## Getting Started

### Prerequisites

To run this project locally, you’ll need the following Python packages:

- `pandas`
- `numpy`
- `yfinance`
- `scipy`
- `statsmodels`
- `matplotlib`

You can install the required libraries by running:

```bash
pip install pandas numpy yfinance scipy statsmodels matplotlib
