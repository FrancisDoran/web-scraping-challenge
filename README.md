# Mars Weather Data Analysis

Uncover insights into Martian weather through web scraping, data extraction, and analysis.

## Overview:

### 1. Mars News Scraping:

- **Tools:** Automated browsing with Splinter, HTML parsing with Beautiful Soup
- **Process:** Visited Mars news site, extracted news articles’ titles and preview text.
- **Output:** Data stored in a Python list of dictionaries.

### 2. Mars Weather Data Analysis:

- **Tools:** Beautiful Soup for HTML table extraction, Pandas for data manipulation
- **Process:** 
  - Scraped Mars weather data from an HTML table into a DataFrame.
  - Ensured proper column headers and data types.
  - Analyzed Mars' weather patterns answering questions like the number of months and Martian days' worth of data present.
  - Conducted analysis like identifying months with extreme temperature and atmospheric pressure variations.
  - Computed the relationship between Earth days and a Martian year.

### 3. Data Export:

- **Process:** The processed DataFrame was saved as a CSV file, facilitating any future use or detailed external analysis.
