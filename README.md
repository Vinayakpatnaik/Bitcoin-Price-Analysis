# Bitcoin-Price-Analysis

### What is Bitcoin?

Bitcoin is the longest running and most well known cryptocurrency, first released as open source in 2009 by the anonymous Satoshi Nakamoto. Bitcoin serves as a decentralized medium of digital exchange, with transactions verified and recorded in a public distributed ledger (the blockchain) without the need for a trusted record keeping authority or central intermediary. Transaction blocks contain a SHA-256 cryptographic hash of previous transaction blocks, and are thus "chained" together, serving as an immutable record of all transactions that have ever occurred. As with any currency/commodity on the market, bitcoin trading and financial instruments soon followed public adoption of bitcoin and continue to grow. Included here is historical bitcoin market data at 1-min intervals for select bitcoin exchanges where trading takes place

### Aim

This notebook aims to perform EDA on Bitcoin prices over the year and analyze its trends and pattern.

### Dataset

CSV files for select bitcoin exchanges for the time period of Jan 2012 to December March 2021, with minute to minute updates of OHLC (Open, High, Low, Close), Volume in BTC and indicated currency, and weighted bitcoin price. Timestamps are in Unix time.

### Attributes

1. Timestamp:- Start time of time window (60s window), in Unix time,
2. Open:- Open price at start time window,
3. High:- High price within time window,
4. Low:- Low price within time window,
5. Close:- Close price at end of time window,
6. Volume_(BTC):- Volume of BTC transacted in this window, It's the total amount of Bitcoins traded during that period. Higher volume suggests more activity.
7. Volume_(Currency):- Volume of corresponding currency transacted in this window, It's the total value of transactions in regular currency (like the dollar) during that period.
8. Weighted_Price:- VWAP- This is the average price of Bitcoin during that period, calculated based on trading volume. It gives a more accurate idea of the average price.
