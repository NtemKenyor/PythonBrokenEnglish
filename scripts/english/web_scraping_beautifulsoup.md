# Web Scraping with BeautifulSoup
Web scraping allows you to extract data from websites.

## Using BeautifulSoup:
You can use the BeautifulSoup library to parse HTML and XML documents.

Example:
from bs4 import BeautifulSoup
import requests

response = requests.get('https://example.com')
soup = BeautifulSoup(response.text, 'html.parser')
title = soup.title.string
print(title)  # Output: Title of the webpage

