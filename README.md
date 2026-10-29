Welcome to my Python Data Analysis & Web Scraping Portfolio! This repository brings together a collection of projects focused on web scraping, data cleaning, automated data pipelines, and exploratory data analysis (EDA) using core Python libraries like Pandas, BeautifulSoup, Requests, and Seaborn.

## 🛠️ Tech Stack & Prerequisites

* Languages: Python 3.x

* Libraries: `pandas`, `beautifulsoup4`, `requests`, `matplotlib`, `seaborn`, `openpyxl`

* Core Concepts: Web Scraping, API Automation, Data Cleaning, Data Aggregation, Exploratory Data Analysis (EDA)

## 📁 Repository Overview

  |Project|                               |Main Tools |                                   |Key Highlights | 

[Amazon Price Tracker]                | BeautifulSoup, Requests, `smtplib`            | HTML parsing, price monitoring, automated email alerts | 
[CoinMarketCap API Pipeline]          | Requests, Pandas, Seaborn                     |API data ingestion, data normalization, time-series visualization | 
[Hockey Data Scraper]                 | BeautifulSoup, Pandas                         | Multi-page pagination scraping, tabular data extraction | 
[BMI Calculator]                      | Python Standard Library                       | User input validation, logic flow, conditional categorization | 
[Customer Call List Cleaning]         | Pandas                                        | Regex string manipulation, phone number formatting, null handling | 
[World Population EDA]                |Pandas, Seaborn, Matplotlib                    | Descriptive statistics, grouping/aggregation, distribution analysis | 

## 🚀 Projects

1. Amazon Price Tracker

Directory: `./01-amazon-price-tracker/`

Description: Scrapes product pages to track price changes over time and sends automated email alerts via SMTP when prices drop below a specified threshold.

2. CoinMarketCap API Pipeline

Directory: `./02-crypto-api-pipeline/`

Description: Connects to the CoinMarketCap API to periodically ingest real-time cryptocurrency price data, appends it to a structured dataset, and visualizes market trends.

3. Hockey Data Scraper

Directory: `./03-hockey-data-scraper/`

Description: Demonstrates web scraping techniques by iterating across paginated HTML tables from the *Scrape This Site* sandbox to gather and structure hockey team statistics.

4. BMI Calculator

Directory:`./04-bmi-calculator/`

Description: A lightweight interactive Python script that processes user input (weight and height) to calculate Body Mass Index and outputs custom status classifications.

5. Customer Call List Cleaning

Directory: `./05-customer-call-list-cleaning/`

Description: Addresses real-world data quality issues by cleaning messy call lists—standardizing phone numbers, splitting addresses, removing duplicates, and handling missing entries.

6. World Population EDA

Directory: `./06-world-population-eda/`

Description: Performs Exploratory Data Analysis on historical world population data, featuring correlation analysis, group aggregations, and data visualization.

💻 How to Run

1. Clone the repository:

   ```
   git clone https://github.com/your-username/python-data-scraping-portfolio.git
   cd python-data-scraping-portfolio
   
   ```

2. Install dependencies:

   ```
   pip install -r requirements.txt
   
   ```

3. Run any script:

   ```
   python 01-amazon-price-tracker/price_tracker.py
   
   ```
