Geometric Brownian Motion Stock Price Simulator

A Python-based financial modeling tool that simulates stock price paths using the discrete GBM formula. The simulator generates realistic price trajectories by modeling logarithmic returns as normally distributed increments, incorporating both deterministic drift and stochastic volatility components.

Key Features:

Discrete-time GBM implementation with log-normal price evolution
Monte Carlo simulations for multi-path trajectory generation
Configurable drift (μ), volatility (σ), and time steps (Δt)
Visualization of price paths with confidence intervals
Statistical analysis: mean prices, quantiles, and distribution at terminal time
Pandas/NumPy-based efficient computation
Matplotlib visualization of simulated and empirical paths

Use Cases:

Options pricing baseline (European/American)
Portfolio risk analysis and VaR estimation
Trading strategy backtesting
Educational tool for quantitative finance concepts

Technical Stack:

NumPy for vectorized random sampling
Pandas for time-series management
Matplotlib for path visualization
SciPy for statistical validation
