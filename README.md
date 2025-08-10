This repository contains a quant research notebook that builds an end-to-end equities pipeline on the S&P 500: universe construction, feature engineering (RSI, Bollinger Bands, ATR, Garman–Klass), Fama–French factor integration with rolling betas, unsupervised selection via K-Means Machine Learning Algorithm, and portfolio construction with a max-Sharpe optimizer under liquidity and concentration constraints.

The second section includes ingests precomputed sentiment data from Twitter(X) by (date, symbol) and turns it into a monthly cross-sectional signal that can be traded standalone or used to tilt the main portfolio.

The last section adds a daily risk-premium signal (GARCH variance forecast) and combines it with 5-minute RSI/Bollinger conditions for intraday entries. Benchmarks vs SPY/QQQ are included.
