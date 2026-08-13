# AC Price Tracker

Daily price tracking for two split air conditioners, sold within Switzerland:

- Climaexpert Cool Air Split 4.3 Eco
- Midea Porta Split

`price_history.json` holds the lowest price seen so far for each product, plus
a full history log. A scheduled Claude Code cloud routine updates this file
daily and sends a push notification when a new all-time-low price is found.
