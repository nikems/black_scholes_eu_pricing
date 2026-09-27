# Black-Scholes EU Pricing
Pricing European call and put options with the Black-Scholes model, using real market data (AAPL) to estimate volatility and compute the Greeks.

The pipeline of the project: 
- Download real market data — daily adjusted close prices of Apple (AAPL) from Yahoo Finance.
- Analyse the asset — log-returns, historical volatility, and max drawdown.
- Price the options — European call and put with the Black-Scholes-Merton model.
- Compute the Greeks — delta, gamma, vega, theta, rho for risk analysis.
- Compute the put-call parity
