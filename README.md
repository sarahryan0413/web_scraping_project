# 🚀 Exploring Mars with Web Scraping & Data Analysis
For this week's challenge, we are heading to Mars! 🪐 I tackled a full web-scraping and data analysis project, refining my skills in automated browsing, HTML parsing, and data visualization. Using Splinter and Beautiful Soup, I extracted information from HTML elements—including tables and recurring elements—before organizing, analyzing, and visually communicating my insights.

## 🔍 Part 1: Scraping Titles and Preview Text from Mars News
To start, I used automated browsing to visit the [Mars News website](https://redplanetscience.com/), where I inspected the page and identified the elements to scrape. Using Beautiful Soup, I extracted the titles and preview text from the news articles and stored them in Python dictionaries with title and preview keys. These dictionaries were then collected into a list and printed in my notebook. I exported the scraped data to a JSON file for easy sharing! 📂

## 🌡️ Part 2: Scraping & Analyzing Mars Weather Data
For this task, I worked in Jupyter Notebook (part_2_mars_weather.ipynb) to scrape and analyze Mars weather data from the [Mars Temperature Data Site](https://static.bc-edx.com/data/web/mars_facts/temperature.html). Using Beautiful Soup, I extracted table data and organized it into a Pandas DataFrame, ensuring data types were appropriate for analysis.
###🔎 Key Questions & Insights:
- How many months exist on Mars? → 12 months
- How many Martian days' worth of data are in the dataset? → 1867 days
- What are the coldest and warmest months on Mars? → Coldest: March 🌨️, Warmest: August ☀️
- Which months have the lowest and highest atmospheric pressure? → Lowest: June, Highest: September
- How many terrestrial (Earth) days exist in a Martian year? → 687 days 🌎
### 📊 Data Visualization:
To gain deeper insights, I plotted bar charts to visualize temperature fluctuations and atmospheric pressure trends. One particularly interesting takeaway? Mars’ seasons impact its temperature and pressure in distinct ways, just like on Earth—but with much more extreme variations!
#### 📌 Final Step: I exported my cleaned and analyzed dataset to a CSV file for further exploration and sharing. ✅

## 🚀 Final Thoughts
This challenge reinforced my ability to scrape, clean, analyze, and visualize data. Web scraping is a powerful tool for extracting valuable insights from online data sources, and combining it with Pandas and Matplotlib made it even more rewarding. I’d love to take this further by automating data updates and expanding my analysis!  

📊 Data provided by edX Boot Camps LLC for educational purposes.
