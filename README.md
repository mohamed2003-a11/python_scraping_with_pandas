Welcome to my Python Data Analysis & Web Scraping Portfolio! This repository brings together a collection of projects focused on web scraping, data cleaning, automated data pipelines, and exploratory data analysis (EDA) using core Python libraries like Pandas, BeautifulSoup, Requests, and Seaborn.

## 🛠️ Tech Stack & Prerequisites

* Languages: Python 3.x

* Libraries: `pandas`, `beautifulsoup4`, `requests`, `matplotlib`, `seaborn`, `openpyxl`

* Core Concepts: Web Scraping, API Automation, Data Cleaning, Data Aggregation, Exploratory Data Analysis (EDA)

Repositories Overview

--

1. Amazon Price Tracker 
Directory: 01-amazon-price-tracker/ 
Description: Tracks product prices on Amazon and automatically sends an email notification whenever the price drops below a designated target threshold.
Main Tools: BeautifulSoup, Requests, smtplib 
Key Highlights: HTML parsing, price monitoring, automated email alerts 

--

2. CoinMarketCap API Pipeline 
Directory: 02-crypto-api-pipeline/ 
Description: Automates real-time cryptocurrency data ingestion using the CoinMarketCap API, cleans the JSON response into DataFrames, and plots price trends.
Main Tools: Requests, Pandas, Seaborn 
Key Highlights: API data ingestion, data normalization, time-series visualization 

--

3. Hockey Data Scraper 
Directory: 03-hockey-data-scraping/ 
Description: Navigates through paginated web pages to scrape hockey team statistics across multiple pages and converts the raw data into structured tables.
Main Tools: BeautifulSoup, Pandas 
Key Highlights: Multi-page pagination scraping, tabular data extraction 

--

4. BMI Calculator 
Directory: 04-bmi-calculator/ 
Description: An interactive tool that takes user physical metrics, validates input values, and calculates the precise Body Mass Index category using custom logic.
Main Tools: Python Standard Library 
Key Highlights: User input validation, logic flow, conditional categorization 

--

5. Customer Call List Cleaning 
Directory: 05-customer-call-list-cleaning/ 
Description: Cleans messy client contact records by removing duplicate entries, standardizing phone number formats, and handling missing values with Pandas.
Main Tools: Pandas 🛠️
Key Highlights: Regex string manipulation, phone number formatting, null handling 

--

6. World Population EDA 
Directory: 06-world-population-eda/ 
Description: Analyzes global demographic historical trends using descriptive statistics, group aggregation, and informative distribution charts.
Main Tools: Pandas, Seaborn, Matplotlib 
Key Highlights: Descriptive statistics, grouping/aggregation, distribution analysis 

--

🛠️ Requirements & Setup

To run any of the scripts locally, install all necessary dependencies using:

pip install -r requirements.txt
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
