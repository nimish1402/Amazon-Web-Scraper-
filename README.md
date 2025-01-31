# Amazon Product Scraper

### Overview

This script allows you to scrape product details from Amazon search results using Python. It fetches details like product name, price, and URL, and saves them in a CSV file.

### Features

1.Scrapes product details from Amazon search results.

2.Extracts product name, price, and URL.

3. Supports multiple pages.

4. Saves data in CSV format.

### Requirements
Ensure you have the following Python libraries installed:

```python
pip install requests beautifulsoup4 pandas
```

### Usage 

1. Run the Script
```python
python amazon_scraper.py
```
2. Enter the product name you want to search for (e.g., laptop).

3. Enter the number of pages to scrape.

4. The script will save the data in amazon_products.csv.

### how it works

1. The script sends requests to Amazon search pages.

2. Parses the HTML response using BeautifulSoup.

3. Extracts product details like name, price, and URL.

4. Saves the data into a CSV file.

