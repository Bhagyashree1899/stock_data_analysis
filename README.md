# stock_data_analysis

As part of my journey in learning Data Science, I built this project to apply real-world data extraction and visualization techniques. In this project, I took on the role of a Data Scientist working for a startup investment firm, where my task was to extract, clean, and visualize financial data to help clients make informed investment decisions.

What I Did - 
I extracted historical stock prices and quarterly revenue data for Tesla, GameStop, Amazon, and AMD using two different techniques:
- yfinance library — to pull live historical stock price data directly from Yahoo Finance
- Web Scraping — using requests and BeautifulSoup to extract revenue tables from HTML web pages
I then cleaned the data, handled missing values, and built a visual dashboard using matplotlib to display both stock price and revenue trends side by side.

Tools and Libraries Used
- yfinance — Extracted historical stock prices
- requests — Downloaded HTML web pages
- BeautifulSoup — Scraped and parsed revenue tables
- pandas — Cleaned and organized data
- matplotlib — Built visualization dashboard

Stocks Analyzed
- Tesla (TSLA)
- GameStop (GME)
- Amazon (AMZN)
- AMD (Advanced Micro Devices)

What I Learned
How to use the yfinance library to extract real financial data with just a few lines of Python.
How web scraping works — downloading a webpage, parsing HTML, and extracting specific table data.
How to clean messy real-world data by removing dollar signs, commas, and null values.
How to build a multi-panel dashboard with matplotlib.

Key Challenges I Overcame
Debugged multiple parser errors with BeautifulSoup by switching between html.parser and html5lib,
Identified the correct HTML table index by iterating through all tbody elements,
Fixed DataFrame issues like typos in method names and case-sensitivity errors in variable names.

This project was completed as part of the IBM Data Science Professional Certificate on Coursera — Course: Python Project for Data Science.
