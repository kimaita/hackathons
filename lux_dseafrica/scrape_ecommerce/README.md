# Scrape e-commerce discounts

## Project Brief

Scrape data from Amazon, Jumia, or any other e-commerce website to create a list of all products currently offered at a discount.

**Tools:**
Python, Beautiful Soup, Selenium, Scrapy, Pandas, Numpy.

## Implementation

### [Amazon](www.amazon.com)

Using a scraper directly on Amazon results in blocking so an additional service was used to bypass this - [scraperapi](https://www.scraperapi.com/).
Create an account and add your API Key to a .env file in this directory's root.

[This notebook](./notebooks/amazon_bs4.ipynb) contains the workflow for getting deals on amazon products. Provide a search term and discounts will be fetched for that search term.