# Crypto Currency Analysis

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
