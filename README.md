# Reliance_StockPrice_Analysis
This project performs exploratory data analysis (EDA) and visualization on historical stock data of Reliance Industries

 Project Highlights
✅ Loaded and cleaned Reliance stock price data (handled missing values, set datetime index).
✅ Calculated daily returns to analyze day-to-day performance.
✅ Computed volatility (standard deviation of daily returns) as a measure of stock risk.
✅ Plotted moving averages (20-day and 50-day) to identify price trends.
✅ Visualized price and trading volume together for deeper insight.
✅ Calculated and plotted cumulative return to see growth over time.

 Dataset
File: Reliance.csv

Columns used:

Date

Adj Close

Volume

Other standard OHLC data (optional for further analysis)

Visualizations
📌 Daily Return Plot: Line plot showing % change in adjusted closing price.

📌 Moving Averages: Overlays 20-day and 50-day moving averages on price chart.

📌 Price + Volume: Combined price line chart with volume bars on twin axes.

📌 Cumulative Return: Shows growth of investment over time if held continuously.

Tools & Libraries
Python

Pandas

NumPy

Matplotlib

 Example Metrics
Volatility: Measures daily price fluctuation (standard deviation of returns).

Cumulative Return: Tracks compounded growth of stock value.

Future Enhancements
Add Bollinger Bands or RSI for technical analysis.

Compare Reliance’s performance with sector indices or peers.

Integrate candlestick charts for detailed price action view.
