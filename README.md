# Stock Prices EDA and Visualizations:

This repository contains an exploratory data analysis (EDA) and various visualizations of stock prices using a Jupyter Notebook. The analysis includes time series trends, distributions, and relationships in the stock data to help understand historical price movements and patterns.

Table of Contents:

Overview
Dataset
Features
Installation
Usage
Visualizations
Contributing
License

Overview
The notebook, Stock_prices_EDA_Visualisations.ipynb, provides an EDA on historical stock prices. It covers key analytical questions like trends in opening and closing prices, volume distribution, high and low price movements, and average price analysis over time.

Dataset
The dataset used for this analysis includes historical stock data with the following columns:

Date: The date of the recorded stock prices.
Open: Opening price of the stock on that day.
High: Highest price of the stock on that day.
Low: Lowest price of the stock on that day.
Close: Closing price of the stock on that day.
Adj Close: Adjusted closing price after stock splits, dividends, etc.
Volume: Number of shares traded on that day.
Note: The dataset is not included in this repository. You may need to source or link to it for the analysis to run correctly.

Features
This notebook includes:

Basic Statistical Analysis: Summary statistics and data exploration.
Time Series Analysis: Trends in Open, Close, High, and Low prices.
Volume Analysis: Distribution and yearly trends of trading volume.
Yearly Average Price Analysis: Calculating average Open and Close prices over years.
Interactive Visualizations: Visualizations using libraries such as matplotlib, seaborn, and plotly.
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/Stock_Prices_EDA.git
Install the required packages:
bash
Copy code
pip install -r requirements.txt
The requirements.txt file should include libraries like pandas, numpy, matplotlib, seaborn, and plotly.
Usage
To run the notebook:

Launch Jupyter Notebook:
bash
Copy code
jupyter notebook
Open Stock_prices_EDA_Visualisations.ipynb and run each cell to perform the analysis and view the visualizations.
Visualizations
The notebook includes the following types of visualizations:

Line Plots for tracking price trends over time.
Histograms and Density Plots for distributions of Open, Close, High, and Low prices.
Bar Charts for volume distribution per year.
Pie Charts for proportional analysis of specific metrics.
Scatter Plots to analyze relationships between different stock price metrics.
Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request if you have suggestions for improvements or additional analyses.
