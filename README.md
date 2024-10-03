# Google Trends Scraper

This Python script allows you to scrape Google Trends data for a given country, extract information such as trending topics, their approximate traffic, and publication date, and save the data in JSON format. The script uses country codes as input and outputs a formatted JSON file containing the trends for the specified country.

## Features

- Fetches Google Trends data for various countries.
- Extracts key information including:
  - **Title** (Trending topic)
  - **Approximate Traffic**
  - **Publication Date**
- Saves data to a JSON file named after the country.
- Outputs trends data to the console for quick access.
- Simple and lightweight, utilizing Python's built-in libraries and `requests`.

## Requirements

Before you can run the script, ensure you have the following:

- Python 3.x installed on your system.
- The following Python libraries:
  - `requests`
  - `xml.etree.ElementTree` (standard library)
