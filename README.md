# Python-Project-for-Data-Science
Data Extraction and Visualization for Stock Analysis
This project, developed as part of a Data Science, AI, and Development course, focuses on extracting and visualizing financial data for popular stocks. The primary goal is to simulate the role of a Data Scientist / Data Analyst at a new startup investment firm, providing insights into historical share prices and quarterly revenue reports to aid investment decisions.

Table of Contents
Project Overview

Stocks Analyzed

Features

Technologies Used

Setup and Installation

Usage

Dashboard Analytics

Acknowledgements

License

Project Overview
The core of this project involves using Python libraries to obtain financial data (historical share prices and quarterly revenue) from various online sources, primarily through web scraping and the yfinance API. Once collected, this data is processed and visualized in interactive dashboards using Plotly to identify patterns and trends.

Stocks Analyzed
The project specifically focuses on the following popular stocks:

Tesla (TSLA)

Amazon (AMZN)

AMD (Advanced Micro Devices)

GameStop (GME)

Features
Historical Stock Price Extraction: Utilizes yfinance to download historical daily stock prices.

Quarterly Revenue Data Extraction: Employs web scraping with requests and BeautifulSoup to extract quarterly revenue information from specified web pages.

Data Cleaning and Preparation: Processes raw extracted data, including handling string manipulation (e.g., removing commas and dollar signs) and data type conversions (e.g., to datetime objects and floats).

Interactive Data Visualization: Generates dynamic and informative graphs using Plotly to display historical share prices and revenue trends.

Dashboard Generation: Creates a visual dashboard to present key financial indicators.

Technologies Used
Python: The primary programming language used.

pandas: For data manipulation and analysis, especially with DataFrames.

requests: For making HTTP requests to download web page content.

BeautifulSoup4 (bs4): For parsing HTML and XML documents to extract specific data from web pages.

yfinance: A Python library to download historical market data from Yahoo Finance.

plotly: For creating interactive data visualizations and dashboards.

html5lib / lxml: Parsers used by BeautifulSoup.

Setup and Installation
To run this notebook, you need to have Python installed. It's recommended to use a virtual environment.

Clone the Repository (if applicable) or download the Final Assignment.ipynb file.

Create and activate a virtual environment (optional but recommended):

Bash

python -m venv venv
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate
Install the required libraries:
Open your terminal or command prompt and run:

Bash

pip install pandas requests beautifulsoup4 yfinance plotly html5lib lxml
Launch Jupyter Notebook:

Bash

jupyter notebook
Open the Notebook:
Navigate to Final Assignment.ipynb in your Jupyter environment and open it.

Usage
Once the Jupyter Notebook is open:

Run all cells sequentially: Execute each code cell from top to bottom.

Kernel -> Restart & Run All

Alternatively, you can run cells one by one to observe the output at each step.

Observe the output: The notebook will display extracted dataframes (.head() and .tail() outputs) and generate interactive Plotly graphs for Tesla and GameStop, illustrating their historical share prices and revenues.

Review the questions: The notebook contains specific questions related to the extracted data, which you can answer by inspecting the DataFrame outputs.

Dashboard Analytics
The project demonstrates how to visualize:

Historical Share Price: Line plots showing stock price trends over time.

Historical Revenue: Line plots illustrating quarterly revenue trends.

These visualizations are combined into a single dashboard view for each stock, allowing for easy comparison and trend identification.

Acknowledgements
This project is part of the "Python for Data Science, AI & Development" course by IBM Developer Skills Network.

Authors: Joseph Santarcangelo, Azim Hirjani, Akansha Yadav

License
This project is for educational purposes as part of an IBM course. Specific licensing information, if any, would be provided by the course instructors.
