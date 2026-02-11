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
## Key Results

### Rolling Volatility (30-Day)
![Rolling Volatility](results/rolling_volatility.png)

Volatility clustering observed across all assets. SOL shows the highest regime spikes, while BTC remains relatively stable.

---

### Correlation Heatmap
![Correlation Heatmap](results/price_correlation_heatmap.png)

Cross-asset correlation increases during high-volatility periods, suggesting stronger systemic dependence.

---

### Volume vs Volatility
![Volume vs Volatility](results/volume_vs_volatility.png)

Higher trading volume tends to coincide with elevated volatility, particularly in ETH and SOL.

---

### Price Trends
![Price Trends](results/daily_price.png)

## Tech Stack
Python, Pandas, NumPy, Matplotlib  
Modularized data ingestion and visualization pipeline

## Repository Structure
- `src/get_data.py`: API ingestion + cleaning
- `src/visualize_results.py`: plotting and statistical visualization
- `final_project.ipynb`: EDA walkthrough
- `results/`: exported figures

## Reproducibility

### Install Dependencies
pip install -r requirements.txt

### Run Data Pipeline
python -m src.get_data
python -m src.visualize_results

All output figures will be saved to the `results/` directory.


requests
pandas
numpy
matplotlib
