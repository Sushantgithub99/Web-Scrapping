**Web Scraping Script for Product Data Extraction**

This Python script utilizes the BeautifulSoup library to scrape product data from HTML files. The HTML files contain information about different products listed on an e-commerce platform.

**Key Features:**

**Importing Libraries:** The script imports necessary libraries including BeautifulSoup for HTML parsing and pandas for data manipulation.

**HTML File Paths:** The script expects a list of file paths where each file contains HTML content of a product listing.

**Data Extraction:** It iterates over each HTML file, parses the content, and extracts relevant information such as product name, price, image URL, product details, seller name, star rating, and whether the seller is trusted or not.

**DataFrame Creation:** Extracted data is stored in a list of dictionaries and then converted into a pandas DataFrame for easy manipulation and analysis.

**CSV Export:** The extracted data is saved to a CSV file named "extracted_data.csv" for further use or analysis.

**Reading CSV Data:** Additionally, the script reads the saved CSV file back into a DataFrame named df1 for further processing if needed.
