# StocksTracker

## Description
The core idea behind this web application is for tracking stock market trades of a given user. The sole purpose for this application is to act as a mock-up application for stock market trading. Due to the recent developments in the stock market, I wanted to create a portal where users can simulate buy and sell transaction, search stock names, and export their transactions into CSV file. This application offers three novel features; search stocks using their ticker name, buy/sell that stock at current market price, and export their transaction into a CSV format. In addition to buy/sell transactions users also get a SMS on their cell phone whenever their transaction is recorded in the Firebase Cloud Firestore, with the help of Twilio’s API.

## Configuration
```bash
# Clone Repo
git clone https://github.com/karanj798/StocksTracker && cd StocksTracker

# Start Backend Server
npm install && npm start

# Start Frontend Server
cd client && npm install && npm start
```

## Demo
[https://cloud-computing-assignment2.herokuapp.com/](https://cloud-computing-assignment2.herokuapp.com/) (Note: Please Register for an account with valid Cell Phone Number. Please follow the following format: 6471234567)
