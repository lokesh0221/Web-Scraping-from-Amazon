# Amazon Web Scraping: Top 50 Authors & Ratings from Teaching & Education Category

This project demonstrates how to scrape Amazon's Best Sellers page in the Teaching & Education category to collect data about the top 50 authors and their ratings using Python.

## Prerequisites

Before starting, ensure the following Python libraries are installed in your environment:

- `requests`: For sending HTTP requests and retrieving web pages.
- `BeautifulSoup`: For parsing and extracting information from HTML content.
- `pandas`: For organizing and saving the extracted data into a tabular format (CSV).

If you're using Google Colab or Jupyter Notebook, `pandas` and `requests` are pre-installed. You will need to install `BeautifulSoup` using the following command:

```bash
!pip install beautifulsoup4
