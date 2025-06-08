
# Module 11 Challenge

## Mars News and Weather Data Scraping & Analysis

### Project Overview

This project focuses on web scraping and data analysis to extract and study Mars news and weather data. It uses Splinter for browser automation and BeautifulSoup for HTML parsing. Extracted data is structured with Pandas and visualized using Matplotlib.

### Technologies Used

- Python  
- Splinter (browser automation)  
- BeautifulSoup (HTML parsing)  
- Pandas (data processing)  
- Matplotlib (data visualization)  
- Jupyter Notebook  

### Deliverables

#### Mars News Scraper

- Automated browsing of the [Mars News Site](https://static.bc-edx.com/data/web/mars_facts/temperature.html)
- Extracted news titles and preview text:
    ```python
    {
      'title': "NASA's MAVEN Observes Martian Light Show Caused by Major Solar Storm",
      'preview': "For the first time in its eight years orbiting Mars, NASA’s MAVEN mission witnessed two different types of ultraviolet aurorae simultaneously..."
    }
    ```
- Stored multiple articles in a list; optionally exported to JSON.

#### Mars Weather Data Scraper

- Accessed [Mars Temperature Data](https://static.bc-edx.com/data/web/mars_facts/temperature.html)
- Scraped weather details including:
  - Transmission ID
  - Earth date
  - Sol (Martian day)
  - Solar longitude (ls)
  - Martian month
  - Minimum daily temperature (°C)
  - Atmospheric pressure (Pa)

### Data Processing & Analysis

- Converted relevant fields to appropriate data types.
- Performed the following analyses:
  - Identified number of Martian months and total Sols in the dataset
  - Found coldest and warmest months using average minimum temperature  
  - Determined months with lowest and highest atmospheric pressure  
  - Estimated the length of a Martian year (~687 Earth days) using temperature cycles
- Exported final DataFrame to CSV

### Instructions

#### Part 1: Scrape Mars News
1. Open `mars_news_1.ipynb` in Jupyter Notebook.
2. Run the script to:
   - Visit the Mars News site
   - Extract and store titles and previews
   - Save the data as JSON

#### Part 2: Scrape and Analyze Mars Weather
1. Open `mars_weather_2.ipynb` in Jupyter Notebook.
2. Run the script to:
   - Scrape and process the temperature data
   - Convert the data into a Pandas DataFrame
   - Analyze seasonal trends
   - Estimate the Martian year’s length
   - Export results to CSV

### Results & Insights

- Mars experiences 12 months with distinct temperature and pressure patterns.
- Identified the coldest and warmest months by averaging minimum temperatures.
- Atmospheric pressure fluctuates seasonally, shown through bar charts.
- By plotting temperature cycles, we estimated a Martian year to be ~687 Earth days.

### Conclusion

This project strengthens skills in web scraping, data processing, and visualization while offering insights into Martian seasonal patterns. Understanding these trends is vital for planning future missions to Mars.

### Assistance
- DU Xpert AI Learning Assistant  
- ChatGPT