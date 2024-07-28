# Vijay Sales Web Scraping

This repository contains a Python script for scraping product data from the Vijay Sales website. The script collects product details such as titles, offer prices, discount details, availability of offers, and no-cost EMI information for various mobile phones and tablets.

## Overview

The script fetches product data from the Vijay Sales website and processes it into a structured format. It extracts:

- Product Titles
- Offer Prices
- Offer Discounts
- Offer Availability
- No-Cost EMI Information

The data is then saved into a CSV file for further analysis.

## Table of Contents

- [Requirements](#requirements)
- [Usage](#usage)
- [Data Structure](#data-structure)
- [Example Data](#example-data)

## Requirements

Ensure you have Python installed on your system. The script requires the following Python packages:

- `requests`
- `beautifulsoup4`
- `pandas`

You can install these packages using pip:

```bash
pip install requests beautifulsoup4 pandas
```
## Usage

This script performs the following tasks:

- `Fetches the HTML content from the Vijay Sales website.`
- `Parses the HTML to extract relevant data.`
- `Saves the HTML content to a file named testHTML.html.`
- `Extracts product details and stores them in a DataFrame.`
- `Saves the DataFrame to a CSV file named VijaySales.csv.`

After running the script, you will find the extracted data in the VijaySales.csv file. You can open this file with any spreadsheet application or analyze it using data analysis tools like Pandas.

## Data Structure
The CSV file VijaySales.csv contains the following columns:

- `title: The name of the product.`
- `offer_price: The current offer price of the product.`
- `offer_discount: The discount percentage offered.`
- `offer_avail: Whether the offer is available or not.`
- `no_cost_emi: Information about no-cost EMI and standard EMI  options.`

## Example Data
![image](https://github.com/user-attachments/assets/c41812c3-d0fd-4ba7-b8ce-734221ee1c7a)

