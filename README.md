# Oreilly-Scraper
Obtain product name, price and availability for a given O'reilly Store 
This script gathers product names, prices and availability information, and stores the data in a CSV file.

## Usage

1. **Preparing Data:**
   - Create a CSV file named `hrefs.csv` containing the URLs of the products you intend to extract data from.

2. **Configuration:**
   - Adjust the script's `headers` section to match the specific O'Reilly store you're targeting. Modify the `'cookie': 'selectedStoreId='` line with the appropriate `IdStore` value you need.

3. **Dependencies:**
   - This script relies on Beautiful Soup for HTML parsing and Pandas for data manipulation. Make sure these libraries are installed in your environment.

4. **Running the Script:**
   - The script processes a subset of the provided links. The variable `urls_test` is set to a sample of 1000 links for demonstration purposes. Modify it according to your needs.

## Important Notes

- It's recommended to periodically review the O'Reilly website's structure to ensure the script remains compatible with any changes.


In case Github doesn't display the Jupyter Notebook please enter here: https://nbviewer.org/github/acbouzas/Amazon-Scraper/blob/main/AmazonScraper.ipynb
This script is designed to extract product details from a given list of O'Reilly Auto Parts store links. 

![amazon_screenshot](https://github.com/acbouzas/Amazon-Scraper/blob/main/images/AmazonScreenshot.png)

![df_example](https://github.com/acbouzas/Amazon-Scraper/blob/main/images/dfscreenshot.png)

