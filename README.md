#  Web Crawling, WARC & PySpark

## Project Overview

This project demonstrates a basic web crawling and web archiving workflow using Wget, WARC, Python, BeautifulSoup, and PySpark.

## Tools Used

- Wget - Web crawling
- WARC / Warcio - Web archiving
- Python - Data extraction and processing
- BeautifulSoup - HTML parsing
- Apache Spark / PySpark - Data analysis

## Project Contents

- `WARC (1).ipynb` - Jupyter Notebook containing the implementation and analysis.
- `quotes.warc` - WARC archive generated from the web crawl.
- `task1B.pdf` - PDF version of pyspark notebook.

## Main Tasks

1. Perform a small web crawl using Wget.
2. Create a WARC archive from the crawled web pages.
3. Read archived pages using Python and Warcio.
4. Extract page titles using BeautifulSoup.
5. Extract quotes, authors, and tags from the archived pages.
6. Analyze the extracted data using PySpark.

## Dataset

The project uses the "Quotes to Scrape" website as the crawling target.

## Results

The WARC archive contains archived web pages from the crawl.  
The extracted quote data was analyzed using PySpark to calculate quote counts by author and the most frequent tags.
