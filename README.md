# Oreilly-Scraper
Obtain product name, price and availability for a given O'reilly Store 
This script gathers data form a given 10.000 link list of a single store. Product name, price and availability are tored in a CSV file once the scraping was finished. 
To scrape other products, please first create your 'hrefs.csv' file containing the url's products you want to extract. Then, on 'headers' please change the 'cookie': 'selectedStoreId=' to the specific IdStore you are trying to scrape the data from. 

The project utilizes Beautiful Soup for HTML parsing, and Pandas for data manipulation.

In case Github doesn't display the Jupyter Notebook please enter here: https://nbviewer.org/github/acbouzas/Amazon-Scraper/blob/main/AmazonScraper.ipynb

![amazon_screenshot](https://github.com/acbouzas/Amazon-Scraper/blob/main/images/AmazonScreenshot.png)

![df_example](https://github.com/acbouzas/Amazon-Scraper/blob/main/images/dfscreenshot.png)
