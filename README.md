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

# Crypto Market Volatility & Correlation (BTC/ETH/SOL)

## Project Overview
This project analyzes one year of daily crypto market data (BTC, ETH, SOL) using the CoinGecko API.  
It focuses on time-series feature engineering (returns, rolling volatility, dynamic correlations) and reproducible visualization.

## Key Outputs
- Price trajectories
- Rolling volatility profiles
- Correlation heatmaps and time-varying co-movement insights

## Repository Structure
- `final_project.ipynb`: EDA + result walkthrough
- `src/`
  - `get_data.py`: API ingestion + cleaning
  - `visualize_results.py`: plots and report-ready figures
- `data/`: raw and processed datasets
- `results/`: exported figures

## Quickstart
```bash
pip install -r requirements.txt
python -m src.get_data --coins btc eth sol --days 365
python -m src.visualize_results
