# Combined Mean-Reversion/Momentum Strategy

## Key results:
2.45 gross Sharpe (1.55 mean-reversion only, 2.27 momentum only)

## Dependencies:
python-binance, pandas, numpy, sklearn, statsmodels, cvxpy

## Project Summary:
This project first identifies a correlated basket in the cryptocurrency market, with the target cryptocurrency being Bitcoin. During the process of refining the reversal strategy, a momentum strategy was uncovered, which accounts for the bullish markets that started to emerge in 2024. The strategies have been combined to account for the different trends that occur when bearish, bullish, or mean-reverting markets dominate.

Intraday pricing data on 23 crypto assets was obtained from Binance; the assets are as follows: Bitcoin, Ethereum, Ripple, Solana, Binance Coin, Polkadot, Chainlink, Litecoin, Uniswap, Aave, Cardano, Avalanche, Dogecoin, Ethereum Classic, NEAR Protocol, Stellar, Bitcoin Cash, Sui, Artificial Superintelligence Alliance, Internet Computer, Render, Floki, and Shiba Inu.  The test data are the tickers' prices and returns from January 2024 to January 2025; the training data are the prices and returns from January 2019 to the end of 2023.
