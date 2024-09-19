# Stock Scraping Script

## Description
This Python script scrapes stock information (such as price, percentage change, and volume) for various companies from the Groww website. It gathers data from a list of URLs and stores the extracted information in an Excel file (`stocks.xlsx`).

The script uses the `requests` library to retrieve HTML pages, `BeautifulSoup` from `bs4` to parse the HTML, and `pandas` to organize and export the data. It includes a mechanism to avoid rate limiting by pausing for 10 seconds between requests.

### Features
- Extracts stock price, daily change, and volume for multiple companies.
- Data is saved in an Excel file (`stocks.xlsx`).

## Dependencies

To run this script, you need to have the following Python libraries installed:
- `requests`
- `beautifulsoup4`
- `pandas`
- `openpyxl` (for exporting to Excel)

You can install these dependencies by running the following command:

```bash
pip install requests beautifulsoup4 pandas openpyxl

