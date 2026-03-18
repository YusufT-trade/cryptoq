# cryptoq
My Crypto Ai
This system (CryptoQV SaaS Platform) is a highly comprehensive and professional AI-Powered Crypto Analysis Bot running in the background. Based on the codebase, it fundamentally performs the following 6 core tasks:

1. 📊 Real-Time Market Data Collection
The system connects directly to exchanges like Binance (via 

websocketkritpoveri.py
) to fetch data every second. It tracks not just the price, but also Spot trading volume, Futures trading volume, and 24-hour high/low levels.

2. 🐋 Whale (Large Investor) Tracking
The system continuously monitors blockchains (

balinahareketerli.py
). It specifically captures massive money (whale) transfers on the BTC and ETH networks. It analyzes wallets for insights like "A $10 million BTC transfer was sent to the exchange; selling pressure might follow."

3. 📰 News & Social Sentiment Analysis
It scans crypto news across the web. When positive or negative news surfaces about a selected coin (e.g., Ethereum), the system determines whether its impact on the market will be "High," "Medium," or "Low."

4. 📈 Advanced Technical & Derivatives Analysis
Going far beyond simple price tracking, it automatically calculates the mathematical metrics used by professional traders:

Technical Indicators: Computes RSI (Overbought/Oversold), MACD, EMA (20 and 50-day moving averages), Bollinger Bands, and VWAP.
Derivatives Market: Tracks Funding Rates, Open Interest, and Liquidations (blown-up long/short positions) to calculate the probability of a "Short Squeeze."
Order Book Data: Measures the Bid/Ask ratio to determine whether buyers or sellers are currently dominating the market.
5. 🤖 SatoshiNakamoto AI (The AI Commentator)
The core brain of this platform is located in 

ai_service.py
. It analyzes all the complex data collected above and synthesizes it into a highly readable, human-like summary report. It outputs:

Risk Level: Low, Medium, High, Extreme.
Trading Signal: BUY, STRONG BUY, SELL, HOLD.
Probability Scenarios: It provides mathematically driven scenarios, such as "65% probability of a bullish trend, Target: $50,000" or "30% probability of a drop, Target: $45,000."
6. 💻 User Interface (React Frontend)
Finally, it visualizes all this complex aggregated data, background logs, and AI commentary on a sleek web Dashboard that an end-user can easily understand and interact with.

In summary: It acts like a professional multi-tasking hedge fund manager—constantly watching the market, running technical indicators, stalking whale wallets, reading the news, and combining all of this to tell you exactly: "Here is the current state of this coin, here is the risk, and here is the signal."
