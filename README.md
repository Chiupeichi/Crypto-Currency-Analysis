# Crypto Market Volatility & Correlation (BTC/ETH/SOL)

## Project Overview
This project performs a comprehensive analysis of cryptocurrency market data (Bitcoin, Ethereum, Solana) using the CoinGecko API. It includes data ingestion, cleaning, and visualization of price trends and volatility.

## Repository Structure
- `final_project.ipynb`: The primary analysis notebook containing the end-to-end workflow.
- `src/`: Source code for modularized tasks.
  - `get_data.py`: Handles API requests and data fetching.
  - `visualize_results.py`: Generates statistical plots and charts.
- `data/`: Directory for storing raw and processed datasets.
- `results/`: Directory for output visualizations.

## Getting Started
### Prerequisites
To run this project, ensure you have the following Python packages installed:
```bash
pip install requests pandas matplotlib



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
