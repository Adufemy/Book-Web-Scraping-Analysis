# Books Web Scraping and Data Analysis

## Project Overview
This project uses Python to scrape and analyze book catalogue data from Books to Scrape.

## Project Objectives
- Collect book information from a website.
- Clean and validate the scraped dataset.
- Analyze book prices and star ratings.
- Create visualizations to communicate findings.

## Data Source
Website: https://books.toscrape.com/

The dataset contains 1,000 book records collected from the demonstration website Books to Scrape.

## Tools and Technologies
- Python
- Jupyter Notebook
- Requests
- Beautiful Soup
- Pandas
- Matplotlib

## Dataset Columns
- Title
- Price
- Rating
- Availability
- Book_URL
- Rating_Number

## Methodology
1. Connected to the website using Requests.
2. Extracted book information using Beautiful Soup.
3. Collected records across 50 catalogue pages.
4. Cleaned book prices and converted ratings to numerical values.
5. Checked missing values, duplicate rows, and invalid prices.
6. Performed exploratory data analysis.
7. Created seven visualizations.

## Key Findings
- Total records: 1,000.
- Average book price: approximately £35.07.
- Median book price: approximately £35.98.
- Lowest price: £10.00.
- Highest price: £59.99.
- The one-star rating group contains 226 books.
- Four-star books have the highest average price, approximately £36.09.
- All collected records were marked as in stock.

These findings describe this demonstration catalogue and should not be generalized to the entire book industry.

## Visualizations
The book_visualizations folder contains seven charts:
1. Book price distribution.
2. Number of books by rating.
3. Average price by rating.
4. Price distribution by rating.
5. Ten most expensive books.
6. Ten cheapest books.
7. Price versus rating.

## How to Run the Project
1. Download the project files.
2. Install the required libraries.
3. Open the Jupyter Notebook.
4. Run the notebook cells in order.

Install the libraries with:
pip install requests beautifulsoup4 pandas matplotlib

An internet connection is required to rerun the scraping steps.

## Limitations
- The source is a demonstration website.
- All books were marked as in stock in the collected data.
- The analysis describes patterns and does not establish causation.

## Conclusion
This project demonstrates a practical workflow for web scraping, data cleaning, exploratory data analysis, and visualization using Python.

## Author
Add your name and professional links here.
