# List Highest Grossing Films In US And Canada
# ![Python](https://img.shields.io/badge/python-blue?logo=python&logoColor=white) ![VS Code](https://img.shields.io/badge/VS%20Code-blue?logo=visual-studio-code&logoColor=white) ![Excel](https://img.shields.io/badge/Excel-217346?logo=Microsoft%20Excel&logoColor=white) ![Tableau](https://img.shields.io/badge/Tableau-005F99?logo=Tableau&logoColor=white)

### Overview!

### Step 1:
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

### Step 2:
### Data Cleaning and Analysis in Excel

Export the scraped data to Excel.
Clean the data by removing duplicates, handling missing values, and correcting any inconsistencies.
Perform preliminary analysis in Excel to understand the data better.

### Step 3:
### Creating Charts and Dashboard in Tableau

<div class='tableauPlaceholder' id='viz1723786438016' style='position: relative'><noscript><a href='#'><img alt='List of highest-grossing films in the United States and Canada ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Li&#47;Listofhighest-grossingfilmsintheUnitedStatesandCanadacomplete&#47;Dashboard4&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Listofhighest-grossingfilmsintheUnitedStatesandCanadacomplete&#47;Dashboard4' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Li&#47;Listofhighest-grossingfilmsintheUnitedStatesandCanadacomplete&#47;Dashboard4&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1723786438016');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.minWidth='420px';vizElement.style.maxWidth='1500px';vizElement.style.width='100%';vizElement.style.minHeight='587px';vizElement.style.maxHeight='1227px';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.minWidth='420px';vizElement.style.maxWidth='1500px';vizElement.style.width='100%';vizElement.style.minHeight='587px';vizElement.style.maxHeight='1227px';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='1577px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
Import the cleaned data from Excel into Tableau.
Create various charts to visualize key metrics such as the highest-grossing films by year, genre, and director.
Develop an interactive dashboard in Tableau to provide a comprehensive view of the data, allowing users to explore different aspects of the highest-grossing films.
