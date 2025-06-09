# Web Scraping of Maruti Car Listings from Cars24

A Python-based project that automates the process of extracting car listings (e.g., Maruti cars in Mumbai) from [Cars24](https://www.cars24.com/), and exports the results in a structured CSV format for analysis.

## Table of Contents
- [Project Overview](#project-overview)
- [Tools & Technologies](#tools--technologies)
- [Methodology](#methodology)
- [Output](#output)
- [Conclusion](#conclusion)
- [Author](#author)

## Project Overview

**Goal:**  
To extract and save relevant details of used cars from Cars24 into a CSV file.

**Objectives:**
- Scrape details like model, price, fuel type, and more
- Automate extraction using Python
- Store data in tabular CSV format

  
## Tools & Technologies
- Python
- requests
- BeautifulSoup (bs4)
- pandas
- Google Colab / Jupyter Notebook

  ## Methodology

1. **Send HTTP Request:**  
   Use `requests` to fetch the HTML page from Cars24.

2. **Parse HTML Content:**  
   Use `BeautifulSoup` to extract relevant car data blocks (car cards).

3. **Extract Data:**  
   For each car, extract:
   - Car Make and Model
   - Kilometers Driven
   - Fuel Type
   - Transmission
   - Price
   - Location

4. **Store in Lists:**  
   Save the data in Python lists.

5. **Create a DataFrame:**  
   Use `pandas` to organize the data into a table.

6. **Export to CSV:**  
   Save the table to `cars24_Maruti_Mumbai_9.csv`.

## Output

**File Generated:** `cars24_Maruti_Mumbai_9.csv`  
**Contains:** Data of 9 used Maruti cars listed in Mumbai with relevant details in tabular format.

## Conclusion

This project showcases how web scraping can collect structured data from real-world sources like Cars24. The data can assist in analyzing car prices, trends, and availability in a specific city.

