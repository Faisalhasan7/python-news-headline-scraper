# python-news-headline-scraper 📰

This simple Python script fetches the latest news headlines from a news website using web scraping techniques.

## 📌 Description

The program uses **`requests`** and **`BeautifulSoup`** to collect the top 20 unique news headlines from the BBC News homepage. It's designed as a basic lab task to demonstrate web scraping capabilities.

## 🔍 Features

- Retrieves the top 20 headlines (`<h1>`, `<h2>`, `<h3>` tags)
- Skips duplicate headlines
- Prints headlines in a numbered list format

## 📦 Requirements

- Python 3.x
- `requests` library
- `beautifulsoup4` library

You can install the required libraries using:

```bash
pip install requests beautifulsoup4
