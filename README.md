# Crypto Tracker

A Python script to fetch, process, analyze, and store live cryptocurrency data from the CoinGecko API. The script updates an Excel file with live data and analysis every 5 minutes.

## Features

- Fetches top 50 cryptocurrencies by market cap.
- Processes and cleans the data.
- Performs basic analysis (e.g., top 5 cryptos, average price, highest gain, lowest loss).
- Updates an Excel file with live data and analysis.
- Logs all activities and errors for debugging.

## Requirements

- Python 3.x
- Required Python libraries: `requests`, `pandas`, `schedule`, `tenacity`, `openpyxl`

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/crypto-tracker.git
   cd crypto-tracker
