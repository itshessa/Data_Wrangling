<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Project README</title>
</head>
<body>
    <h1>Introduction</h1>
    <p>This project aims to analyze and visualize performance data of ODI cricket players and the market trends of top cryptocurrencies. By cleaning and preparing the datasets, we address data quality and tidiness issues, enabling insightful analysis. The project focuses on exploring player performance over time in cricket and examining cryptocurrency price movements and trading volumes.</p>

    <h2>1. Gather data</h2>
    
    <h3>1.1. Problem Statement</h3>
    <p><strong>Dataset Description and Gathering Method:</strong> I have chosen a dataset for One Day International (ODI) cricket batting statistics. This dataset was downloaded manually from a cricket statistics website, which is a reliable source for comprehensive and up-to-date cricket data.</p>
    <p>The dataset contains the following columns:</p>
    <ul>
        <li><strong>Player:</strong> The name of the cricket player.</li>
        <li><strong>Span:</strong> The years during which the player was active in ODI cricket.</li>
        <li><strong>Mat:</strong> The total number of matches played by the player.</li>
        <li><strong>Inns:</strong> The total number of innings batted by the player.</li>
        <li><strong>NO:</strong> The number of times the player was not out at the end of an innings.</li>
        <li><strong>Runs:</strong> The total number of runs scored by the player.</li>
        <li><strong>HS:</strong> The highest score achieved by the player in a single innings.</li>
        <li><strong>Ave:</strong> The batting average, calculated as the total number of runs divided by the number of times the player got out.</li>
        <li><strong>BF:</strong> The total number of balls faced by the player.</li>
        <li><strong>SR:</strong> The strike rate, calculated as the total number of runs scored per 100 balls faced.</li>
        <li><strong>100:</strong> The number of centuries (scores of 100 or more runs in a single innings) scored by the player.</li>
        <li><strong>50:</strong> The number of half-centuries (scores of 50 or more runs but less than 100 in a single innings) scored by the player.</li>
        <li><strong>0:</strong> The number of times the player got out without scoring any runs (duck).</li>
    </ul>
    
    <p><strong>Problem I'm looking for:</strong></p>
    <p>The ODI cricket batting dataset allows for comprehensive analysis, including identifying top-performing batsmen by their averages, strike rates, and high scores, and evaluating the impact of not-outs and match contributions. It facilitates comparison of players across different eras, roles, and pressure situations, while also examining career longevity and improvement trends. Additionally, the dataset helps investigate the correlation between high-scoring performances and match outcomes, providing insights into how individual achievements influence team success.</p>

    <h3>1.2. Problem Statement</h3>
    <p><strong>Dataset Description and Gathering Method:</strong> I have chosen a cryptocurrency dataset that includes historical data for five major cryptocurrencies: Bitcoin (BTC-USD), Ethereum (ETH-USD), Binance Coin (BNB-USD), Ripple (XRP-USD), and Cardano (ADA-USD). This dataset was obtained through an API provided by yfinance that aggregates cryptocurrency market data.</p>
    <p>The dataset contains the following columns:</p>
    <ul>
        <li><strong>Date:</strong> The date of the recorded data.</li>
        <li><strong>Symbol:</strong> The ticker symbol of the cryptocurrency.</li>
        <li><strong>Open:</strong> The opening price of the cryptocurrency on that date.</li>
        <li><strong>High:</strong> The highest price reached by the cryptocurrency on that date.</li>
        <li><strong>Low:</strong> The lowest price reached by the cryptocurrency on that date.</li>
        <li><strong>Close:</strong> The closing price of the cryptocurrency on that date.</li>
        <li><strong>Volume:</strong> The trading volume of the cryptocurrency on that date.</li>
    </ul>
    
    <p><strong>Problem I'm looking for:</strong></p>
    <p>The cryptocurrency dataset provides insights into price trends and volatility for five major coins, including Bitcoin and Ethereum. It allows for comparison of price movements and trading volumes, analysis of correlations between different coins, and examination of how major events impact the market. Additionally, it can be used to identify trends, predict future prices, and compare the overall performance and stability of the cryptocurrencies.</p>
</body>
</html>
