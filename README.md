# Web Scraping Project — Dynamic Data Pipeline & Analysis

## Overview

This project demonstrates a scalable web scraping pipeline that extracts data from a paginated website, stores raw HTML for reproducibility, and performs structured data analysis with visualizations.

## Features
- Dynamic pagination handling (no hardcoded limits)
- Raw HTML storage for traceability
- Structured data extraction using BeautifulSoup
- Safe data parsing (handling missing values)
- Data transformation using Pandas
- Insightful visualizations using Matplotlib

## Tech Stack
- Python
- requests
- BeautifulSoup (bs4)
- pandas
- matplotlib

## Dataset
- Total records: 582

### Features
- Name
- Year
- Wins
- Losses
- Win %
- Goals For
- Goals Against
- Goal Difference (+/-)

## Pipeline Architecture

### Data Collection
- Iterates through paginated URLs
- Sends HTTP requests with headers
- Automatically stops when no data is found

### Raw Data Storage
- Stores HTML files for each page locally
- Enables reproducibility and debugging

### Data Parsing
- Extracts data using CSS selectors
- Converts values into appropriate data types
- Handles missing values safely

### Data Processing
- Combines all pages into a single DataFrame
- Performs sorting, grouping, and aggregation

## Visualizations

### Best Team Performance Over Time
Line plot showing yearly best teams based on win percentage.

### Top 10 Teams by Wins
Horizontal bar chart with value labels for readability.

### Wins vs Losses Distribution
Scatter plot with color encoding based on win percentage.

### Goal Difference Distribution
Histogram showing distribution of goal differences.

## Key Insights
- High win counts do not always correspond to the highest win percentage
- Teams with strong offensive stats do not always perform best overall
- Performance varies significantly across different years

## Output
- Clean dataset exported as CSV
- Raw HTML files stored for each page

## Future Work
- Implement search-based dynamic scraping
- Automate the pipeline
- Build an interactive dashboard using Streamlit
- Extend to an end-to-end machine learning pipeline

## Contributing
Suggestions and improvements are welcome.

## Contact
Open to opportunities in data science, machine learning, and data engineering.






