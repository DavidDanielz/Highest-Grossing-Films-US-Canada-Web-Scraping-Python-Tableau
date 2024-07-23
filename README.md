# List Highest Grossing Films In US And Canada
# ![Python](https://img.shields.io/badge/python-blue?logo=python&logoColor=white) ![VS Code](https://img.shields.io/badge/VS%20Code-blue?logo=visual-studio-code&logoColor=white) ![Excel](https://img.shields.io/badge/Excel-217346?logo=Microsoft%20Excel&logoColor=white) ![Tableau](https://img.shields.io/badge/Tableau-005F99?logo=Tableau&logoColor=white)

### Overview!
This project aims to scrape and analyze data from Wikipedia to identify the highest-grossing films in the United States and Canada.

1. Import Libraries: 'pandas' for data manipulation and 'lxml' for HTML parsing. 
```
import pandas as pd  # Importing pandas for data manipulation and analysis
import lxml          # Importing lxml for HTML parsing
```
2. Define URL: Specify the URL of the Wikipedia page with the highest-grossing films data.
```
url = "https://en.wikipedia.org/wiki/List_of_highest-grossing_films_in_the_United_States_and_Canada"
```
3. Read HTML Tables: Use pd.read_html(url) to extract HTML tables from the specified URL. This function returns a list of DataFrames representing each table found on the page.
```
tables = pd.read_html(url)
```
4. Select Relevant Table: Assuming the first table (tables[0]) contains the highest-grossing films data, assign it to a variable.
```
highest_grossing_films = tables[0]
```
5. Display Results: Print the DataFrame to view the scraped data.
```
print(highest_grossing_films)
```

### Next Steps
### Data Cleaning and Analysis in Excel

Export the scraped data to Excel.
Clean the data by removing duplicates, handling missing values, and correcting any inconsistencies.
Perform preliminary analysis in Excel to understand the data better.

### Creating Charts and Dashboard in Tableau

Import the cleaned data from Excel into Tableau.
Create various charts to visualize key metrics such as the highest-grossing films by year, genre, and director.
Develop an interactive dashboard in Tableau to provide a comprehensive view of the data, allowing users to explore different aspects of the highest-grossing films.
