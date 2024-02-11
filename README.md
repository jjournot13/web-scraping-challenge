# web-scraping-challenge
## Overview
The purpose of this project is to implement the skills learned and tools introduced in Module 11 to perform full web-scraping and data analysis - collecting data, organizing and storing data, analyzing data, and then visually communicating insights.

## Tools
- BeautifulSoup
- Jupyter Notebook
- Matplotlib
- Pandas
- Python
- Splinter

## Project Structure
### Part 1: Scrape Titles and Preview Text from Mars News
1. Use automated browsing to visit the Mars news site.
1. Create a Beautiful Soup object to extract text elements from the website.
1. Extract the titles and preview text of the news articles scraped and store the results in Python dictionaries.
1. Store all the dictionaries in a Python list.
1. Print the list in notebook.
1. (Optional) Export the scraped data to a JSON file.


### Part 2: Scrape and Analyze Mars Weather Data
1. Use automated browsing to visit the Mars Temperature Data site.
1. Create a Beautiful Soup object and use it to scrape the data in the HTML table.
1. Using the same column headings as the website table, assemble the scraped data into a Pandas Dataframe.
1. Examine the data types associated with each columns and convert the data types where appropriate.
1. Analyze the dataset using Pandas functions to answer the following questions:
	- How many months exist on Mars?
	- How many Martian (and not Earth) days worth of data exist in the scraped dataset?
	- What are the coldest and the warmest months on Mars (at the location of Curiosity)? 
	- Which months have the lowest and the highest atmospheric pressure on Mars? T
	- About how many terrestrial (Earth) days exist in a Martian year?
1. Export the DataFrame to a CSV file.

----
## Sources
In addition to referencing several class actvities and applicable documentation, I used the following references to complete this challenge:
	- Step 3: https://scrapfly.io/blog/how-to-scrape-tables-with-beautifulsoup/
	- Convert data types: https://www.geeksforgeeks.org/change-data-type-for-one-or-more-columns-in-pandas-dataframe/