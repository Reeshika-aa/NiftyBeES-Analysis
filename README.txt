 Project Overview:
This project is focused on analyzing the investment strategy based on percentage price drops in the NiftyBEES index. It uses historical stock data from Yahoo Finance to identify significant drops in the price and make investments based on those drops. The analysis provides insights into how a specific investment strategy, triggered by 10% and 25% drops in the price, could generate returns over time.

 Key Features:
Downloads NiftyBEES stock data from Yahoo Finance from January 2020 to December 2024.
Tracks the highest price reached and identifies 10% and 25% drops from that high.
Makes investments of ₹2,00,000 at a 25% drop and ₹1,00,000 at a 10% drop.
Logs the date, price, investment amount, units purchased, and returns for each qualifying drop.
Calculates total investment, units purchased, and returns.
Displays a pie chart showing the distribution of investment and returns.
Plots the price history, investment, and returns over time.


 Dependencies:
yfinance for downloading historical stock data.
pandas for data manipulation and analysis.
matplotlib for plotting graphs and pie charts.


 How to Run:
Install the required libraries:

pip install yfinance pandas matplotlib

Run the script to download the data, calculate investments, and display the results:

python niftybees.py

 Output:
A CSV file niftybees_data.csv containing the historical stock data.
The terminal will display the top rows of the data and the details of investments based on price drops.
A pie chart illustrating the distribution of total investment and returns.
A plot showing the price over time and the investment vs returns over time.
