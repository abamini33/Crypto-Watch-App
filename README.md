# Crypto Watch Tower

Market data : `https://api.coingecko.com/api/v3/global`

All coins data : `https://api.coingecko.com/api/v3/coins/markets?vs_currency=usd&order=market_cap_desc&per_page=250&page=1&sparkline=false&price_change_percentage=1h%2C24h%2C7d%2C14d%2C30d%2C200d%2C1y`

Coin price chart : `https://api.coingecko.com/api/v3/coins/${coinId}/market_chart?vs_currency=usd&days=${duration}${duration > 32 ? "&interval=daily" : ""}






Description:

This repository contains the source code of a cryptocurrency tracking application developed using React. The application enables users to monitor real-time prices, fluctuations, and trends of various cryptocurrencies.






Features:

Real-Time Price Tracking: The application displays real-time prices of major cryptocurrencies by fetching data from a cryptocurrency market API.

Cryptocurrency List: Users can browse an exhaustive list of cryptocurrencies with details such as current price, volume, market capitalization, etc.

Trend Charts: For each cryptocurrency, the application provides interactive charts allowing users to visualize price trends over different periods (hourly, daily, weekly, monthly).

Favorites and Alerts: Users can mark certain cryptocurrencies as favorites and set price alerts to be notified when the price reaches a certain threshold.

Virtual Wallet: Users have the ability to create a virtual wallet where they can track the value of their investments and transactions.

News and Analysis: Integration of a relevant news and analysis feed on the cryptocurrency market to assist users in making informed decisions.







Technologies Used:

React: JavaScript library for building the user interface.
Redux: For managing the global state of the application.
Cryptocurrency Market API: Utilization of a third-party API to fetch real-time data.
 
 
