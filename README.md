# Stock Data Analysis with Python

This project involves analyzing stock market data using Python, primarily utilizing pandas for data manipulation, matplotlib and seaborn for visualization, and numpy for numerical computations.

## Project Overview

The project is structured around analyzing historical stock market data obtained from the NASDAQ exchange. The dataset spans from 1962 to 2024 and includes various financial metrics such as opening price, closing price, high, low, adjusted close, and trading volume for numerous stocks listed on NASDAQ.

### Files in the Project

- `NASDAQ 1962-2024.csv`: CSV file containing historical stock market data.
- `NASDAQ-EDA.ipynb`: Python script containing functions for data analysis and visualization.

### Libraries Used

- **pandas**: A powerful data manipulation library in Python.
- **numpy**: A fundamental package for numerical computing in Python.
- **matplotlib**: A plotting library for creating static, animated, and interactive visualizations.
- **seaborn**: A Python visualization library based on matplotlib that provides a high-level interface for drawing attractive statistical graphics.

## Project Structure

The project is organized into functions implemented within `NASDAQ-EDA.ipynb` to perform various analyses and visualizations on the stock market data. Here's an overview of the functions and their purposes:

1. **calculate_daily_returns**: Computes daily returns based on the closing prices.
2. **plot_closing_price**: Plots the closing price of a specified stock over time.
3. **plot_trading_volume**: Plots the trading volume of a specified stock over time.
4. **plot_correlation_heatmap**: Generates a heatmap showing the correlation between closing prices of selected stocks.
5. **calculate_moving_averages**: Calculates the moving average of a specified stock's closing price.
6. **calculate_annualized_metrics**: Computes annualized return and volatility of a specified stock.
7. **calculate_sharpe_ratio**: Calculates the Sharpe Ratio of a specified stock.
8. **suggest_stocks**: Suggests stocks to invest in based on Sharpe Ratio, considering a risk-free rate.

## How to Execute Functions

To use the functions provided in `NASDAQ-EDA.ipynb` for analyzing and visualizing stock market data, follow these steps:

1. **Prerequisites**:
   - Ensure you have Python installed on your system. You can download it from [python.org](https://www.python.org/downloads/).
   - Install the necessary libraries if you haven't already. You can install them using pip:
     ```bash
     pip install pandas numpy matplotlib seaborn
     ```

2. **Dataset**:
   - Place your historical stock market data CSV file in the same directory as `NASDAQ-EDA.ipynb`. The CSV file should contain columns such as Date, Ticker, Open, High, Low, Close, Adj Close, and Volume.

3. **Executing the Script**:
   - Open a terminal or command prompt.
   - Navigate to the directory containing `NASDAQ-EDA.ipynb` and your CSV file.

4. **Running the Script**:
   - To run the script and execute different functions, use the following command:
     ```bash
     python NASDAQ-EDA.ipynb
     ```

5. **Function Usage**:
   - Once `NASDAQ-EDA.ipynb` is executed, various functions will generate plots and provide analysis based on the data.
   - Functions like `plot_closing_price`, `plot_trading_volume`, `plot_correlation_heatmap`, and others will generate plots based on the data in your CSV file.

6. **Interpreting Results**:
   - Review the generated plots and outputs to gain insights into stock price movements, trading volumes, correlations between stocks, moving averages, annualized metrics, Sharpe Ratio, and investment suggestions.

7. **Customization**:
   - Modify parameters within the functions or expand upon them to tailor the analysis to your specific requirements or integrate them into larger projects involving financial data analysis.

By following these steps, you can effectively utilize the functions provided in `NASDAQ-EDA.ipynb` to analyze, visualize, and derive insights from historical stock market data.

## Example Outputs

Here are some examples of the outputs you can generate using the functions in `NASDAQ-EDA.ipynb`:

### Closing Price Plot

The following plot shows the closing price of a specific stock over time:

![Closing Price Plot](closing_price_plot_github.png)

### Trading Volume Plot

This plot illustrates the trading volume of a specific stock over time:

![Trading Volume Plot](trading_volume_plot.png)

### Correlation Heatmap

The correlation heatmap displays the correlation between closing prices of selected stocks:

![Correlation Heatmap](correlation_heatmap.png)

### Moving Averages Plot

The following plot demonstrates the 30-day moving average overlaid on the closing price of a stock:

![Moving Averages Plot](moving_averages_plot.png)

## Conclusion

This project provides tools to analyze historical stock data, visualize trends, and make investment suggestions based on financial metrics like Sharpe Ratio. You can modify and expand upon the functionality to suit your specific analysis needs or integrate it into larger projects related to financial data analysis.

Feel free to explore and utilize the provided functions to gain insights into stock market trends and make informed investment decisions.
