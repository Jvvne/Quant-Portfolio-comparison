![image](https://github.com/Jvvne/Quant-DataCleaning/assets/148028363/47e8746f-48ee-4998-baea-a3820708ea91)

# Analyisis Using Pandas with Quantative Metrics

## Project Goal:
The goal of this project is to analyze and compare the performance of various portfolios across multiple metrics, including volatility, returns, risk, and Sharpe ratios. By evaluating these metrics, we can determine which portfolio outperforms the others.

## Project Title: Portfolio Performance Analysis Using Python and Pandas

### Project Objective:
The primary objective of this project is to create a tool that analyzes and visualizes the major metrics of different portfolios, such as algorithmic trading portfolios, whale investor portfolios, and a custom portfolio. The analysis will help determine which portfolio performs best in terms of returns, risk, and overall efficiency.

### Data Overview:
The dataset used for this project includes the following:
- `whale_returns.csv`: Contains returns of famous "whale" investors' portfolios.
- `algo_returns.csv`: Contains returns from in-house trading algorithms.
- `sp500_history.csv`: Contains historical closing prices of the S&P 500 Index.
- Custom Portfolio: Data collected from Google Sheets or provided CSV files (e.g., AAPL, COST, GOOG).

### Project Workflow:

#### 1. Data Import and Initial Analysis:
The first step is to load the CSV data into Pandas DataFrames. We then perform exploratory data analysis (EDA) by summarizing the data with statistical measures and visualizations to understand its characteristics and structure.

#### 2. Data Preprocessing:
To prepare the data for analysis, we clean it by removing null values, converting data types, and ensuring the data is formatted correctly. We also calculate daily returns from the S&P 500 closing prices.

#### 3. Performance Analysis:
We analyze the performance of each portfolio by calculating daily returns and cumulative returns. This analysis helps us identify which portfolio, if any, outperforms the S&P 500.

- **Daily Returns and Cumulative Returns:**
  We calculate and plot daily returns for all portfolios, followed by plotting their cumulative returns to assess long-term performance. 

#### 4. Risk Analysis:
To evaluate the risk associated with each portfolio, we create box plots of the returns, calculate the standard deviation, and determine which portfolios carry more risk compared to the S&P 500.

- **Box Plot and Standard Deviation:**
  Box plots help visualize the distribution and volatility of returns, while standard deviation quantifies the risk level.

#### 5. Rolling Statistics:
We calculate rolling statistics to assess the stability and correlation of the portfolios over time. Specifically, we compute the rolling standard deviation with a 21-day window and analyze the correlation between each portfolio and the S&P 500.

- **Rolling Standard Deviation and Correlation:**
  These metrics help us understand the dynamic risk and similarity between portfolios and the broader market.

#### 6. Sharpe Ratios:
We calculate the Sharpe ratios for each portfolio to measure the return-to-risk ratio. This analysis helps us determine whether the algorithmic strategies outperform the market and whale portfolios.

- **Sharpe Ratios:**
  Visualized in a bar plot, Sharpe ratios provide a clear comparison of portfolio performance relative to their risk levels.

#### 7. Creating a Custom Portfolio:
We create a custom portfolio using a selection of stocks and compare its performance to the other portfolios. This involves calculating weighted returns, analyzing risk, and computing rolling statistics for the custom portfolio.

- **Custom Portfolio Analysis:**
  We assess the custom portfolio's performance using the same metrics applied to the other portfolios, including standard deviation, rolling statistics, correlation, and Sharpe ratios.

### How to Use:
1. Clone the repository to your local machine.
2. Ensure you have the required libraries installed.
3. Open the analysis notebook in Jupyter Notebook or Jupyter Lab.
4. Run the cells to see the analysis and visualizations.

This tool provides a comprehensive analysis of portfolio performance, helping investors make informed decisions based on key financial metrics.

