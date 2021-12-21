# Theoretical Options Pricing Application

Link to program: https://colab.research.google.com/drive/141lBRTDzgnNfaDxW6UyRIpdv2lw_D0DU?usp=sharing

## What is this?
This Python script takes real-time data from Yahoo Finance and calculates the theoretical value of stock options contracts utilizing Black-Scholes pricing model. The user is able to input any valid ticker on the U.S. stock exchanges and select from the available expiry dates. The application will then calculate the theoretical pricing for these given inputs for every strike price that is offered. It also displays the current market value for those same contracts, allowing the user to compare and analyze the theoretical prices against the actual prices.

## Why?
As I found myself getting deeper into the more complex and quantitative side of trading, I found myself looking to trade options, as it also results in a higher reward, though with a higher risk. As I looked further into it, I started the notice that even when a stock was trading flat, both the short-term call options, and the short-term put options tend to decrease in value, even though the underlying security has barely moved. With that, I wanted to learn more about the way in which the prices of options contracts were calculated. After finding Black-Scholes model, I looked to understand more about the effect of Implied Volatility and Time Decay, as I believed understanding the way the many factors in which an options contract's price is affected, the better I am able to manage my risk as I trade these derivatives. 

# Technologies
* Jupyter Notebooks and Google Colaboratory
* Python
* Matplotlib
* yFinance module (For Yahoo Finance API)
* pandas
* numPy
