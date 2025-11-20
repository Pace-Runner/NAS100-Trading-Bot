# NAS100-Trading-Bot
This repository documents the performance and logic of my NAS100 (US100) algorithmic trading bot. The strategy is built around moving average based signals, executed on MetaTrader, and tuned specifically for the NAS100 index’s volatility and structure.

I am sharing the backtest results, strategy explanation, and performance metrics so others can learn from the system’s design.
However, the full MetaTrader code and executable are intentionally not included, as I prefer to keep the implementation private.

📈 Strategy Summary
The bot uses a rules-based moving-average framework to identify trend shifts and momentum continuation setups.
Key components include:

Short-term and long-term moving averages

Trend confirmation filters

Automatic position sizing and risk management

Stop-loss and take-profit structure optimized for NAS100 volatility


These tests cover nearly 6 years using high-quality tick data.

Note: Backtests do not guarantee future performance, but they provide valuable insight into the strategy’s behaviour.

Why the Source Code Isn’t Included

I’m choosing not to provide the EA/executable or MetaTrader code for the following reasons:

The system represents months of work and tuning

Releasing it publicly would remove any competitive edge

Prevents misuse, modification, or resale by others

Protects the internal logic beyond the high-level description here

This is completely normal for algorithmic trading projects. The repo focuses on transparency of results, not providing a free bot.
