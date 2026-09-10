# CodeAlpha Web Scraping Project

## Project Overview

This project demonstrates web scraping using Python.

The project extracts book information from a public webpage and stores the collected information in a CSV dataset.

## Objective

The main objective of this project is to collect useful information from a public webpage using Python web scraping techniques and create a structured dataset for further analysis.

## Website Used
Books to Scrape

https://books.toscrape.com/

## Technologies Used

- Python 3.14
- Requests
- BeautifulSoup
- Pandas
- Visual Studio Code

## Data Collected

The following information was extracted:

- Book Title
- Price
- Availability

## Methodology

1. Send a request to the webpage using the Requests library.
2. Receive the HTML content of the webpage.
3. Parse the HTML using BeautifulSoup.
4. Locate the book information from the HTML structure.
5. Extract the book title, price, and availability.
6. Store the extracted information in a Python list.
7. Convert the collected data into a Pandas DataFrame.
8. Save the final dataset as `books.csv`.

## Project Files

```text
CodeAlpha_Web_Scraping/
│
├── screenshots/
│   └── web_scraping_output.png
│
├── books.csv
├── web_scraping.py
└── README.md