# List of Highest Grossing Films In The United States And Canada
# ![Python](https://img.shields.io/badge/python-blue?logo=python&logoColor=white) ![VS Code](https://img.shields.io/badge/VS%20Code-blue?logo=visual-studio-code&logoColor=white) ![Excel](https://img.shields.io/badge/Excel-217346?logo=Microsoft%20Excel&logoColor=white) ![Tableau](https://img.shields.io/badge/Tableau-005F99?logo=Tableau&logoColor=white)

## Project Overview
This project explores the highest-grossing films in the United States and Canada, analyzing key metrics such as box office earnings, genre trends, and the impact of directors on box office success. The project involves web scraping to extract data, cleaning and preprocessing the data, and presenting the final insights through a comprehensive Tableau dashboard.

## Key Skills Demonstrated
- Data Scraping: Automated the extraction of data from a web source using Python.
- Data Cleaning: Refined and improved data quality by cleaning and organizing the dataset in Excel.
- Data Visualization: Created an interactive Tableau dashboard to highlight key insights in box office trends.

## Important Note
This analysis was based on data compiled in July 2024. As box office earnings and industry data evolve, the insights presented in this project may not reflect future updates or adjustments.

### Step 1: Data Scraping with Python
- Imported necessary libraries, including pandas for data manipulation and lxml for HTML parsing.
- Scraped data from a Wikipedia page on the highest-grossing films in the United States and Canada using pd.read_html.
- Extracted the relevant table and previewed the data for verification.
```
import pandas as pd
import lxml

# Define URL
url = "https://en.wikipedia.org/wiki/List_of_highest-grossing_films_in_the_United_States_and_Canada"

# Scrape and load tables
tables = pd.read_html(url)

# Select relevant table
highest_grossing_films = tables[0]
print(highest_grossing_films)
```

### Step 2: Data Cleaning and Analysis in Excel
* Export to Excel: Transferred the scraped data to Excel for further processing.
* Data Cleaning: Removed duplicates, handled missing values, and corrected inconsistencies to ensure data accuracy.
* Preliminary Analysis: Conducted initial analysis in Excel to explore trends and patterns.

### Step 3: Data Visualization and Dashboard Creation in Tableau
* Visualization Creation: Developed charts in Tableau to visualize key insights, such as box office trends, genre distribution, and director impact.
* Interactive Dashboard: Combined the charts into a cohesive Tableau dashboard to provide an interactive experience.

[![Dashboard 4](https://github.com/user-attachments/assets/b861aa7a-13c1-4319-8e4a-fd4fec759c43)](https://public.tableau.com/views/Listofhighest-grossingfilmsintheUnitedStatesandCanadacomplete/Dashboard4?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
Click the image to view the dashboard in Tableau Public

### Key Skills Demonstrated
* Data Scraping: Automated data extraction from web sources using Python.
* Data Cleaning: Improved data quality through meticulous cleaning in Excel.
* Data Visualization: Created a comprehensive Tableau dashboard showcasing the analysis.

### Conclusion
This project highlights my ability to handle end-to-end data analysis, from data extraction to visualization, using Python, Excel, and Tableau. The final Tableau dashboard provides actionable insights into the highest-grossing films in the US and Canada.
