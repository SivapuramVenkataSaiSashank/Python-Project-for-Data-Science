# Python-Project-for-Data-Science
# Final Assignment - Stock Data Analysis

This notebook is part of the IBM Skills Network course on Python for Data Science. It focuses on retrieving, analyzing, and visualizing historical stock market data using Python libraries.

## Overview

The notebook demonstrates how to:
- Retrieve stock data using the `yfinance` API.
- Scrape financial data using `BeautifulSoup`.
- Perform data manipulation and analysis with `pandas`.
- Create interactive financial charts using `plotly`.

## Libraries Used

- `yfinance` – for downloading historical stock data  
- `pandas` – for data manipulation  
- `requests` and `BeautifulSoup` – for web scraping financial information  
- `plotly` – for interactive visualizations  
- `IPython.display` – for better rendering in Jupyter notebooks  
- `warnings` – to manage warning messages  

## How to Run

1. Make sure you have all dependencies installed:
   ```bash
   pip install yfinance pandas requests beautifulsoup4 plotly
   ```

2. Open the notebook:
   ```bash
   jupyter notebook "Final Assignment.ipynb"
   ```

3. Run each cell sequentially to explore data fetching, processing, and visualization techniques.

## Output

The notebook includes:
- Line plots of stock prices over time  
- Candlestick charts for technical analysis  
- Comparison of multiple stocks
