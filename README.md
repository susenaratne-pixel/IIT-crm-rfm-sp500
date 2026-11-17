# S&P 500 Stock Segmentation Using Adapted RFM

**Module:** 6BUIS017W CRM & CM with Business Intelligence
**Coursework:** Coursework CWK1
**Student:** S U Senaratne, 20232030 / 2054071

## What this project does
Segments S&P 500 shares in two ways and compares the results:
1. Risk and return: mean weekly return and weekly beta
2. Trading activity: adapted Recency, Frequency and Monetary (RFM)
Both use Ward agglomerative clustering and K-means.

## Data
- Ticker list: Wikipedia, List of S&P 500 companies (retrieved 18/11/2026)
- Prices and volume: yfinance, 1 Jan 2021 to 1 Jan 2025 (end exclusive)
- Benchmark: ^GSPC

## How to run
Open the notebook in Google Colab, then choose Runtime > Run all.

## Folders
- notebooks/ : Colab notebook
- data/ : saved datasets and feature table
- figures/ : charts and dendrograms
