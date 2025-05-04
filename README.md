# Amazon Web Scraping with Python

This project demonstrates how to scrape product data from Amazon using Python. The script retrieves the product title, price, and date of scraping, storing the collected data in a CSV file. Additionally, it includes a feature to send an email alert if the price of a product drops below a specified threshold.

## Overview

The **Amazon Web Scraping** project is a Python-based solution that allows you to:
- Scrape product information (title, price) from Amazon product pages.
- Save the scraped data in a structured CSV file.
- Set up a price monitoring system that sends an email notification when a product's price falls below a predefined value.
- Periodically check product prices at regular intervals (every 12 hours).

## Key Features

- **Web Scraping**: Uses **BeautifulSoup** to parse the HTML of Amazon product pages and extract details such as product title and price.
- **CSV Storage**: Stores the scraped product data (title, price, and date) in a **CSV file**.
- **Price Monitoring**: Periodically checks product prices and sends an email if the price drops below a set threshold.
- **Scheduled Scraping**: The script runs at regular intervals (every 12 hours) to check for price changes.

## Requirements

To get started, ensure you have the following Python libraries installed:

```bash
pip install requests
pip install beautifulsoup4
pip install smtplib
pip install pandas
