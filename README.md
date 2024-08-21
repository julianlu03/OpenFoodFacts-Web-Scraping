# OpenFoodFacts Nutrition Data Scraper

This project automates the extraction of nutrition facts from the OpenFoodFacts food database using Python using libraries pandas, Selenium, and BeautifulSoup to significantly reduces manual data collection time and allows for scalable and efficient data retrieval.

**Features**
- Automated Web Scraping: Utilizes Selenium to navigate and retrieve data from the OpenFoodFacts website
- Data Parsing: Employs BeautifulSoup to parse the HTML and extract relevant nutrition facts
- Data Storage: Efficiently stores the extracted data into structured formats using Pandas for easy analysis
- Scalable: Easily adjustable to scrape data for a large number of products

**Installation**

Prerequisites:
Python 3.8 or higher
Google Chrome (or any Selenium-compatible browser)
ChromeDriver (compatible with your Chrome version)

**Required Python Packages**

- pandas
- selenium
- beautifulsoup4
- requests (for simple HTTP requests)

**Notes**:

- The scraper.py script can be easily adjusted to scrape multiple products by modifying the list of product URLs in the config.py file

- Once data is stored in a CSV file, you can use pandas to load and analyze the data 
