**Project Name**: **Amazon Product Scraper with Data Export**

**Project Description**:  
This project is a web scraping tool that extracts product details from Amazon product pages and saves the information into a CSV file. Using Python's `requests` and `BeautifulSoup` libraries, the scraper fetches data from the product page, including the title, price, description, image link, rating, and number of reviews. The collected data is then written into a CSV file for further analysis or use.

The scraping logic handles missing values gracefully by providing default messages when a particular element (like price or description) is not found. The data is exported to `product_data.csv` and can easily be used for market research, product analysis, or comparison purposes.

The tool also includes additional functionality for scraping a list of products from a specific category on Amazon, and it supports API-based data retrieval with HasData API for enhanced functionality.

**Features**:
- Extracts product title, price, description, image link, rating, and number of reviews.
- Handles missing values and elements gracefully.
- Exports scraped data to CSV for further use.
- Scrapes multiple products using pagination and integrates with external APIs for additional data sources.
- Provides insights into product information like price and rating for decision-making.

This tool is useful for automating the process of gathering product details, conducting market analysis, and building a database of e-commerce products.
