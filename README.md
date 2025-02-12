# Stock Price and Revenue Analysis for Tesla and GameStop (Up to June 2021)

This project is  a **Data Science Project for IBM** and is dedicated to performing an analysis of **stock prices** and **quarterly revenue** for two companies: **Tesla** and **GameStop**, up to **June 2021**. The project focuses on the use of **web scraping techniques** to collect data from various sources and analyze it to extract meaningful insights.

## Overview

This project consists of two main components:
1. **Stock Price Analysis**: Collecting historical stock price data for Tesla and GameStop.
2. **Revenue Analysis**: Scraping quarterly revenue data from external websites using web scraping techniques.

The goal is to understand trends in the stock prices and revenue of these two companies, comparing them up to June 2021. 

## Tools and Technologies Used

- **Python**: The primary programming language for data scraping, analysis, and visualization.
- **Libraries**:
  - `requests`: To make HTTP requests and retrieve web data.
  - `BeautifulSoup`: For parsing and scraping HTML content from webpages.
  - `pandas`: For handling, processing, and analyzing the data.
  - `yfinance`: For downloading stock price data directly from Yahoo Finance.
  - `Plotly`: For creating interactive plots and visualizations.
  
## Web Scraping

Web scraping was used to collect **quarterly revenue data** from external web pages. The data was extracted from tables and cleaned for further analysis. Specifically, the **`pd.read_html()`** and **`BeautifulSoup`** libraries were used to scrape the data efficiently.

## Key Steps in the Project

1. **Stock Data Collection**:
   - Used **yfinance** to download Tesla and GameStop stock prices.
   - Cleaned the data, specifically filtering it up to **June 2021** for further analysis.
   
2. **Revenue Data Scraping**:
   - Scraped quarterly revenue data for Tesla and GameStop using **web scraping** techniques.
   - Cleaned the scraped data by removing unwanted characters like commas and dollar signs, ensuring the revenue figures are in numeric format.
   
3. **Data Visualization**:
   - Visualized the **historical stock prices** and **quarterly revenue** data using **Plotly**.
   - Created interactive plots for a clear comparison of the stock prices and revenue trend

## Conclusion

By the end of this project, we were able to extract meaningful insights into the stock prices and revenue trends of Tesla and GameStop up to June 2021. Through web scraping and data analysis, this project provides valuable comparisons and visualizations to better understand the financial growth of these companies.
