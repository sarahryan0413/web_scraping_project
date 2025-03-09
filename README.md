---
# Module 11 Challenge
---
For this week's challenge, we are going to Mars! I am tackling a full web-scraping and data analysis project. I will use Splinter and Beautiful Soup to extract information from HTML elements, including tables and recurring elements, while refining my skills in collecting, organizing, analyzing, and communicating data insights.

## Part 1: Scrape Titles and Preview Text from Mars News

In this part, I scraped the Mars News website by using automated browsing to visit the site, inspected the page, and identified the elements to scrape. I used Beautiful Soup to extract the titles and preview text of the news articles, storing them in dictionaries with "title" and "preview" keys. These dictionaries will be collected in a list, which I printed in the notebook. Lastly, I exported the scraped data to a JSON file for easier sharing.

## Part 2: Scrape and Analyze Mars Weather Data

In this task, I worked through the Jupyter Notebook part_2_mars_weather.ipynb to scrape and analyze Mars weather data. I started by using automated browsing to visit the Mars Temperature Data Site, inspected the HTML page, and scraped the data with Beautiful Soup. I then assembled the data into a Pandas DataFrame, with columns matching the table headings: id, terrestrial_date, sol, ls, month, min_temp, and pressure. I ensured the data types were appropriate for analysis.

The dataset was analyzed using Pandas to answer the following questions:
- How many months exist on Mars? __12 months__
- How many Martian days' worth of data are in the dataset? __1867 days__
- What are the coldest and warmest months on Mars? __Coldest: March; Warmest: August__
- Which months have the lowest and highest atmospheric pressure? __Lowest: June; Highest: September__
- How many terrestrial days exist in a Martian year? __687 terrestrial days__

I visualized the data with bar charts, estimated the number of Earth days in a Martian year, and finally exported the DataFrame to a CSV file for sharing.
