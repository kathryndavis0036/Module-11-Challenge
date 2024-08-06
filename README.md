# Mars News and Weather Data Scraping

## Project Overview

This project is designed to scrape data from the NASA Mars news site and a Mars weather data site. The data includes news article titles and preview text as well as weather data like temperature and pressure on Mars. The project consists of two main parts:

1. **Scraping Mars News Articles**: Scraping titles and preview text from the NASA Mars news site.
2. **Scraping and Analyzing Mars Weather Data**: Scraping weather data from a table and analyzing it.

## Deliverables

1. **Deliverable 1**: Scrape titles and preview text from Mars news articles.
2. **Deliverable 2**: Scrape and analyze Mars weather data, which exists in a table.

## Technologies Used

- Python
- Jupyter Notebook
- Beautiful Soup
- Splinter
- Pandas
- Matplotlib

### Libraries

the following installed:

- Python 3.7 or later
- Jupyter Notebook
- ChromeDriver (compatible with your version of Chrome)
- Necessary Python libraries: `splinter`, `bs4`, `pandas`, `requests`, `matplotlib`, `webdriver_manager`

### Running the Notebooks

1. Start Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

2. Open and run the following notebooks:
    - `part_1_mars_news.ipynb` for Deliverable 1
    - `part_2_mars_weather.ipynb` for Deliverable 2

## Deliverables Details

### Deliverable 1: Scrape Titles and Preview Text from Mars News

The script:
- Uses Splinter to automate browsing and visit the Mars news site.
- Creates a Beautiful Soup object to parse the HTML.
- Extracts news titles and preview text.
- Stores the data in a list of dictionaries.

### Deliverable 2: Scrape and Analyze Mars Weather Data

The script:
- Uses requests to get the HTML content of the Mars weather data site.
- Creates a Beautiful Soup object to parse the HTML.
- Extracts the data from the HTML table and converts it to a Pandas DataFrame.
- Analyzes the data to find:
  - Number of months on Mars.
  - Number of Martian days in the dataset.
  - Coldest and warmest months on Mars.
  - Months with the lowest and highest atmospheric pressure.
  - Estimates the length of a Martian year in terrestrial days.
- Visualizes the results using Matplotlib.
- Exports the DataFrame to a CSV file.

## Analysis

There appears to be twenty-four months on Mars, given the seasonal paterns. For example, it takes about two years to reach the highest and lowest temperatures. The coldest days appear to get down to roughly -85 degrees celcius and the hottest days are roughly about -65 degrees celcius. The highest atmospheric month appears to be month 9. 
