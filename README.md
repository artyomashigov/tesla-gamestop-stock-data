# Tesla and GameStop Stock Data

Notebook project for extracting and visualizing Tesla and GameStop stock and revenue data.

## Project Overview

This assignment practices two common data-collection methods: using an API-style package for stock-price history and web scraping for revenue tables. The notebook then visualizes each company's stock price alongside revenue information.

## Analysis Questions

- How can stock-price history be extracted with `yfinance`?
- How can company revenue tables be scraped from web pages?
- What cleaning is needed before scraped revenue data can be plotted?
- How do Tesla and GameStop stock and revenue trends compare visually?

## Notebook Structure

- Define a reusable graphing function
- Extract Tesla stock data with `yfinance`
- Scrape Tesla revenue data
- Extract GameStop stock data with `yfinance`
- Scrape GameStop revenue data
- Clean dates and revenue values
- Plot Tesla stock and revenue
- Plot GameStop stock and revenue

## Files

- `TeslaGamestop.ipynb` - full notebook with extraction, cleaning, and visualizations.

## Tools

Python, pandas, yfinance, requests, BeautifulSoup, plotly, and Jupyter Notebook.

## Notes

This is a compact example of combining structured financial data with scraped web tables, then presenting the result in clear time-series charts.
