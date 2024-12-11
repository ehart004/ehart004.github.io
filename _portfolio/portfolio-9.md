---
title: "Simulations reveal how long liquidity providers will remain in a position given market dynamics"
excerpt: "A Laplace distribution better captures the "expected move" for most Uniswap V3 pools and we can use this to predict how long we will be in a position on average given the drift and volatility. <br/> <br/> <img src='/images/project_figures/resized/drift_vol_sims_comparison.png'>"
collection: portfolio
---

Modeling the probability of the price moving outside a liquidity provider's range given a certain drift and volatility is crucial for understanding the risks of LPing and optimizing the range. A Laplace distribution does a better job than a Gaussian at capturing the "expected move" of most LP pools, and simulations show how long we can expect to be in a position given the market dynamics.       
