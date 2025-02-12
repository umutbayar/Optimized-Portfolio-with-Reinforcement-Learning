Optimized-Portfolio-with-Reinforcement-Learning is a reinforcement learning-based model designed to optimize investment portfolios by dynamically balancing risk and return. 
It leverages Mean-Variance Optimization and Proximal Policy Optimization (PPO) to efficiently allocate assets among selected stocks.

Features are:
Data Collection: Retrieves historical stock data using Yahoo Finance.
Mean-Variance Optimization: Calculates optimal portfolio weights using convex optimization.
Reinforcement Learning: Utilizes PPO to learn dynamic asset allocation strategies.
Performance Analysis: Evaluates the model's performance against benchmark portfolios.

Usage:
Download Stock Data:
The model retrieves historical data for selected stocks (e.g., AAPL, GOOGL, MSFT) from Yahoo Finance.
Mean-Variance Optimization:
Computes mean returns and covariance matrices to determine initial optimal weights.
Reinforcement Learning Training:
Trains the PPO model on custom PortfolioEnv to learn dynamic allocation strategies.
Performance Analysis:
Compares the trained model's performance with a benchmark portfolio using cumulative returns and risk metrics.
