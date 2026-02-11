# Crypto Market Volatility & Dynamic Correlation Analysis

## Overview
This project investigates dynamic volatility behavior and time-varying cross-asset correlations in cryptocurrency markets (BTC, ETH, SOL) using daily data from the CoinGecko API.

The goal is to move beyond static correlations and explore how market dependence shifts under different volatility regimes.

## Key Questions
- How does rolling volatility differ across assets?
- Do cross-asset correlations strengthen during high-volatility periods?
- Can time-series feature engineering improve interpretation of market risk?

## Methods
- Daily log returns calculation
- Rolling volatility (window-based estimation)
- Time-varying correlation analysis
- Visualization of regime-like shifts in co-movement

## Results & Insights
- Volatility clustering observed across all major assets
- Correlation strength increased during high-volatility regimes
- Static correlation underestimates tail risk dependence

## Tech Stack
Python, Pandas, NumPy, Matplotlib  
Modularized data ingestion and visualization pipeline

## Repository Structure
- `src/get_data.py`: API ingestion + cleaning
- `src/visualize_results.py`: plotting and statistical visualization
- `final_project.ipynb`: EDA walkthrough
- `results/`: exported figures
