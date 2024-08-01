# Introduction
This project aims to analyze and visualize performance data of ODI cricket players and the market trends of top cryptocurrencies. By cleaning and preparing the datasets, we address data quality and tidiness issues, enabling insightful analysis. The project focuses on exploring player performance over time in cricket and examining cryptocurrency price movements and trading volumes.

## 1. Gather data

### 1.1. Problem Statement
**Dataset Description and Gathering Method:** I have chosen a dataset for One Day International (ODI) cricket batting statistics. This dataset was downloaded manually from a cricket statistics website, which is a reliable source for comprehensive and up-to-date cricket data.

The dataset contains the following columns:

- **Player:** The name of the cricket player.
- **Span:** The years during which the player was active in ODI cricket.
- **Mat:** The total number of matches played by the player.
- **Inns:** The total number of innings batted by the player.
- **NO:** The number of times the player was not out at the end of an innings.
- **Runs:** The total number of runs scored by the player.
- **HS:** The highest score achieved by the player in a single innings.
- **Ave:** The batting average, calculated as the total number of runs divided by the number of times the player got out.
- **BF:** The total number of balls faced by the player.
- **SR:** The strike rate, calculated as the total number of runs scored per 100 balls faced.
- **100:** The number of centuries (scores of 100 or more runs in a single innings) scored by the player.
- **50:** The number of half-centuries (scores of 50 or more runs but less than 100 in a single innings) scored by the player.
- **0:** The number of times the player got out without scoring any runs (duck).

**Problem I'm looking for:**

The ODI cricket batting dataset allows for comprehensive analysis, including identifying top-performing batsmen by their averages, strike rates, and high scores, and evaluating the impact of not-outs and match contributions. It facilitates comparison of players across different eras, roles, and pressure situations, while also examining career longevity and improvement trends. Additionally, the dataset helps investigate the correlation between high-scoring performances and match outcomes, providing insights into how individual achievements influence team success.

### 1.2. Problem Statement
**Dataset Description and Gathering Method:** I have chosen a cryptocurrency dataset that includes historical data for five major cryptocurrencies: Bitcoin (BTC-USD), Ethereum (ETH-USD), Binance Coin (BNB-USD), Ripple (XRP-USD), and Cardano (ADA-USD). This dataset was obtained through an API provided by yfinance that aggregates cryptocurrency market data.

The dataset contains the following columns:

- **Date:** The date of the recorded data.
- **Symbol:** The ticker symbol of the cryptocurrency.
- **Open:** The opening price of the cryptocurrency on that date.
- **High:** The highest price reached by the cryptocurrency on that date.
- **Low:** The lowest price reached by the cryptocurrency on that date.
- **Close:** The closing price of the cryptocurrency on that date.
- **Volume:** The trading volume of the cryptocurrency on that date.

**Problem I'm looking for:**

The cryptocurrency dataset provides insights into price trends and volatility for five major coins, including Bitcoin and Ethereum. It allows for comparison of price movements and trading volumes, analysis of correlations between different coins, and examination of how major events impact the market. Additionally, it can be used to identify trends, predict future prices, and compare the overall performance and stability of the cryptocurrencies.
