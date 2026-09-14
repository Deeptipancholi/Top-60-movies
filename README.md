# Top 60 Movies Web Scraping Project

## 📌 Project Overview

This project is a Python web scraping project that extracts movie information from Rotten Tomatoes' Top 60 Movies page.

The scraped data includes movie titles, release years, Tomatometer scores, directors, cast, critics' consensus, and movie synopses.

The collected data is stored in a CSV file for further analysis and use.

## 🛠️ Technologies Used

- Python
- Requests
- BeautifulSoup
- CSV
- Jupyter Notebook

## 📊 Data Collected

The project extracts the following information:

- Movie Title
- Release Year
- Tomatometer Score
- Directed By
- Star Cast
- Critics Consensus
- Synopsis

## 🔍 Web Scraping Process

1. Send a request to the Rotten Tomatoes webpage.
2. Parse the HTML content using BeautifulSoup.
3. Identify movie cards from the webpage.
4. Extract movie details using HTML tags and CSS classes.
5. Follow individual movie links to collect the full synopsis.
6. Store the extracted data in a CSV file.

## 📁 Project Files

- `Top-60-movies.ipynb` — Jupyter Notebook containing the web scraping code.
- `movies.csv` — CSV file containing the scraped movie data.

## 🎯 Purpose

The purpose of this project is to practice Python web scraping, HTML parsing, data extraction, and CSV file handling.

## 🚀 Future Improvements

- Scrape additional movie details.
- Perform data cleaning and analysis using Pandas.
- Create visualizations from the collected movie data.
