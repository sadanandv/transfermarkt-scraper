# Transfermarkt Scraper

This Python-based web scraper is designed to extract detailed football transfer data from Transfermarkt using the Selenium framework. It efficiently captures player statistics, transfer fees, and market values, and outputs the data in a structured CSV format, ideal for further analysis or integration into sports analytics models.

## Project Features
- **Data Extraction**: Captures comprehensive transfer data including player names, ages, positions, nationalities, market values, clubs, leagues, and transfer details.
- **Cookie Management**: Automatically handles cookie consent popups to ensure seamless data scraping across multiple pages.
- **Pagination Handling**: Navigates through multiple pages to compile data across various transfer windows and leagues.
- **Output Format**: Data is neatly exported to a CSV file, making it easy to use in data analysis tools or sports analytics applications.

## Prerequisites
Before running the scraper, ensure you have the following installed:
- Python 3.6 or newer
- Selenium
- WebDriver Manager
- pandas

## Installation Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/sadanandv/transfermarkt-scraper.git
   ```
2. Change into the Project Directory:
   ```bash
   cd transfermarkt-scsrapper
   ```
3. Install the necessary Python Packages:
   ```bash
   pip install -r requirements.txt
   ```

## How to Use:
To run the Scraper:
1. Execute the script from the command line:
```bash
python transfermarkt_scrapper.py
```
2.  Follow the on-screen prompt to specify the year of the transfers you wish to scrape.
3.  Once the script completes, check the generated file names `transfermarkt_<year>.csv` in your project directory.

## License
Distributed under the MIT License. See LICENSE for more information.

## Support
If you encounter any problems or have any suggestions, please open an issue through the GitHub issue tracker. Feel free to reach out by creating a discussion in the repository if you have any questions or ideas about the project.
