# Web Scraping with BeautifulSoup
Web scraping allows you to extract data from web pages.

## Using BeautifulSoup:
You can use BeautifulSoup to parse HTML and extract information.

Example:
from bs4 import BeautifulSoup
import requests

url = 'https://example.com'
response = requests.get(url)
soup = BeautifulSoup(response.text, 'html.parser')

print(soup.title.string)  # Output: Title of the page

