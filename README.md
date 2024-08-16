# List Highest Grossing Films In US And Canada
# ![Python](https://img.shields.io/badge/python-blue?logo=python&logoColor=white) ![VS Code](https://img.shields.io/badge/VS%20Code-blue?logo=visual-studio-code&logoColor=white) ![Excel](https://img.shields.io/badge/Excel-217346?logo=Microsoft%20Excel&logoColor=white) ![Tableau](https://img.shields.io/badge/Tableau-005F99?logo=Tableau&logoColor=white)

## Overview!
This project involves scraping, cleaning, and analyzing data to identify the highest-grossing films in the United States and Canada. The final analysis and visualization are presented in a Tableau dashboard. This project analyzes the highest-grossing films in the United States and Canada, focusing on various factors such as box office earnings, genre trends, and director impact. The dataset used was compiled in July 2024.

### Important Note
Please note that the data used in this project was compiled in July 2024. The information presented reflects the state of the data at that time, and there may have been updates or changes to the dataset since then. Future analysis should consider using the most up-to-date data available.

### Step 1: Data Scraping with Python
* Importing Libraries: Utilized pandas for data manipulation and lxml for HTML parsing.
* URL Definition: Specified the target Wikipedia page URL.
* HTML Table Extraction: Used pd.read_html(url) to scrape tables from the Wikipedia page.
* Table Selection: Extracted and stored the relevant table containing the highest-grossing films data.
* Data Preview: Printed the DataFrame to verify the scraped data.
```
import pandas as pd  # Importing pandas for data manipulation and analysis
import lxml          # Importing lxml for HTML parsing

url = "https://en.wikipedia.org/wiki/List_of_highest-grossing_films_in_the_United_States_and_Canada"
tables = pd.read_html(url)
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
