# gdax-python3
Global Digital Asset Exchange (GDAX)
- The REST API has endpoints for account and order management as well as public market data.

#### Market Data
The Market Data API is set of endpoints for retrieving market data. These endpoints provide snapshots of market data.

- authentication.py - used to create a request.
- order_book_L2.py - used to get a list of open orders for a product.
- last_tick.py - used to receive information about the last trade, best bid/ask and 24h volume.
- candles.py - used to return historic rates for a product.
- stats.py - used to get 24 hr stats for the product.
- trades.py - used to list the latest trades for a product.

##### For more information please visit https://docs.gdax.com/
