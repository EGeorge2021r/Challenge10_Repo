# Challenge10_Repo
Crypto Clustering - Combining financial Python programming with unsupervised learning

# User Story
Role: Advisor FinTech Consulting Firm

Goal: The project goal is combine financial Python programming with unsupervised learning create a Jupyter notebook that clusters cryptocurrencies by their performance in different time periods and also plot the results so that you can visually show the performance to the board

Reason: As competitors are fiece, I am proposing a novel approach to assembling investment portfolios that are based on cryptocurrencies. Instead of basing my proposal on only returns and volatility, I am including other factors that might impact the crypto market—leading to better performance for my portfolio. I am also creating a prototype for submitting my crypto portfolio proposal to the company board of directors.

# General information about the analysis
• Import the Data (provided in the starter code)
• Prepare the Data (provided in the starter code)
• Find the Best Value for k Using the Original Data
• Cluster Cryptocurrencies with K-means Using the Original Data
• Optimize Clusters with Principal Component Analysis
• Find the Best Value for k Using the PCA Data
• Cluster the Cryptocurrencies with K-means Using the PCA Data
• Visualize and Compare the Results


# Technology
Jupyter notebook that contains data preparation, analysis, and visualizations for key risk and return metrics. Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations. GitHub repository Python import os import requests import json import pandas as pd from dotenv import load_dotenv import alpaca_trade_api as tradeapi from MCForecastTools import MCSimulation

%matplotlib inline

# Libraries used in the analysis
• A single DataFrame imported from a CSV file that has a DateTimeIndex. import os import requests import json import pandas as pd from dotenv import load_dotenv import alpaca_trade_api as tradeapi from MCForecastTools import MCSimulation

# Analysis
Evaluate the Cryptocurrency Wallet by Using the Requests Library Evaluate the Stock and Bond Holdings by Using the Alpaca SDK Evaluate the Emergency Fund Create a Financial Planner for Retirement Analyze the Retirement Portfolio Forecasts Create the Monte Carlo Simulation Forecast Cumulative Returns in 10 Years