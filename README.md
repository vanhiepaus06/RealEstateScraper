# Real Estate Scraper

This project scrapes real estate data from a website and saves it to CSV files. 

## Setup

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/RealEstateScraper.git
    cd RealEstateScraper
    ```

2. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

3. Make sure you have [ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/) installed and it's in your PATH.

## Usage

1. Run the scraping script:
    ```sh
    python scrape_real_estate.py
    ```

2. After scraping, merge the CSV files:
    ```sh
    python merge_csv_files.py
    ```

## Files

- `scrape_real_estate.py`: Script to scrape data and save to individual CSV files.
- `merge_csv_files.py`: Script to merge all individual CSV files into one.

## Notes

- Ensure your internet connection is stable during scraping.
- Modify the `postcodes` list in `scrape_real_estate.py` as needed.
- It will take around 20 hours scrape the data from the website