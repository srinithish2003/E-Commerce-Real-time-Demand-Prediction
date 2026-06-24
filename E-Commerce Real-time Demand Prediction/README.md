E-Commerce Real-Time Demand Prediction
A data pipeline and analysis notebook that scrapes live product listings from major e-commerce platforms (Amazon, eBay, Flipkart, Walmart, Alibaba) using ScraperAPI, stores the results in Google Sheets, and performs demand signal analysis through feature engineering and exploratory data analysis (EDA).
Features

Multi-platform web scraping via ScraperAPI across 5 major e-commerce sites
Google Sheets integration for real-time data storage and retrieval
Data cleaning: missing value handling, IQR-based outlier removal, currency normalization (multi-currency to INR)
Custom Demand Score metric derived from search count, ordered quantity, and price
Min-max normalization for feature comparability
EDA visualizations: top searched products bar chart, price distribution, boxplots, scatter plots, pair plots, and correlation heatmap

Tech Stack
Python · BeautifulSoup · ScraperAPI · gspread · Google Sheets API · pandas · matplotlib · seaborn
Use Case
Useful for market researchers, sellers, and analysts who want to monitor product demand trends across platforms in near real-time without access to proprietary marketplace APIs.