
# Web Scraping Project

This project is a web scraping project that extracts financial data and comments from Yahoo Finance for a list of stocks.

## Installation and Usage

To run this project, you will need Python 3 and the following libraries:

- yfinance: A Python library that allows you to access financial data from Yahoo Finance. You can install it using pip: `pip install yfinance`
- requests: A Python library that allows you to send HTTP requests and handle responses. You can install it using pip: `pip install requests`
- BeautifulSoup: A Python library that allows you to parse and extract data from HTML and XML documents. You can install it using pip: `pip install beautifulsoup4`
- json: A Python library that allows you to encode and decode data in JSON format. It is included in the standard library, so you don't need to install it.

To use this project, you can follow these steps:

1. Clone or download this repository to your local machine.
2. Open a terminal or command prompt and navigate to the project folder.
3. Run the main.py script using Python: `python main.py`
4. The script will download the financial data for the stocks in the stock_list variable, and print the last five rows of each data frame.
5. The script will also extract the top 10 comments for each stock from the Yahoo Finance community page, and print them to the console.

## Dependencies and Requirements

This project depends on the following data sources:

- Yahoo Finance: A website that provides financial news, data, and analysis for various markets and instruments. The website URL is: [2](https://finance.yahoo.com/)
- Spot.IM: A platform that provides social engagement and community tools for websites. The API URL is: [3](https://api-2-0.spot.im/v1.0.0/conversation/read)

This project requires the following Python version and libraries:

- Python 3.8 or higher
- yfinance 0.1.63 or higher
- requests 2.26.0 or higher
- BeautifulSoup 4.9.3 or higher
- json

## Features and Functionalities

This project has the following features and functionalities:

- It can download financial data for a list of stocks from Yahoo Finance using the yfinance library. It can download data for different periods and intervals, such as daily, weekly, monthly, or quarterly.
- It can extract comments for a list of stocks from the Yahoo Finance community page using the requests, BeautifulSoup, and json libraries.
