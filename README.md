TSLA Momentum Tracker: Advanced Power BI Dashboard for Stock Analysis & Predictive Insights
This repository houses a comprehensive Power BI dashboard built to dissect Tesla (TSLA) stock performance from 2016-2021, leveraging technical indicators, risk metrics, and predictive modeling.

Core Visualizations (Page 1: Overview Dashboard):

Multi-metric table summarizing monthly averages for SMA/EMA/RSI/close/Sharpe/returns, with conditional formatting for BUY/SELL alerts.
Gauges for RSI (oversold/overbought zones), cumulative returns, and Sharpe (risk-adjusted benchmarks >1.0).
Line charts for close price trends with EMA/SMA overlays and forecasts; combo volume-close bars highlighting activity spikes.
Yearly high/low bars and stacked cumulative returns, synced via date slicers for dynamic filtering.
Pie chart breaking down signal distribution (96% HOLD, 3% BUY/SELL), weighted by return impact for alpha attribution.


Advanced Analytics (Page 2: Forecast Lab):

ARIMA Python visual (via statsmodels) for 30-day daily returns forecasts, conditioned on signals—backtests show +12% timing edge in 2020-21 bull runs.
