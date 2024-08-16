# List Highest Grossing Films In US And Canada
# ![Python](https://img.shields.io/badge/python-blue?logo=python&logoColor=white) ![VS Code](https://img.shields.io/badge/VS%20Code-blue?logo=visual-studio-code&logoColor=white) ![Excel](https://img.shields.io/badge/Excel-217346?logo=Microsoft%20Excel&logoColor=white) ![Tableau](https://img.shields.io/badge/Tableau-005F99?logo=Tableau&logoColor=white)

### Overview!
This project involves scraping, cleaning, and analyzing data to identify the highest-grossing films in the United States and Canada. The final analysis and visualization are presented in a Tableau dashboard.

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

### Step 2:
### Data Cleaning and Analysis in Excel

Export the scraped data to Excel.
Clean the data by removing duplicates, handling missing values, and correcting any inconsistencies.
Perform preliminary analysis in Excel to understand the data better.

### Step 3:
### Created Charts and Dashboard in Tableau

[![Dashboard 4](https://github.com/user-attachments/assets/b861aa7a-13c1-4319-8e4a-fd4fec759c43)](https://public.tableau.com/views/Listofhighest-grossingfilmsintheUnitedStatesandCanadacomplete/Dashboard4?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
Click the image to view the dashboard in Tableau Public
