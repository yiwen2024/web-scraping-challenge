# web-scraping-challenge
# Background

A web-scraping and data analysis project was taken in this practice including identifying HTML elements on a page with their id and class attributes, and extracting information via both automated browsing with Splinter and HTML parsing with Beautiful Soup though which the core skills including collecting data, organizing and storing data, analyzing data, and then visually communicationg were stengthened.

# List of Content

There are two jupyter notebook files, one csv files, one json file, and a folder containing output images in this repository showing below: 

1. part_1_mars_news.ipynb
 Scrape titles and preview text from Mars news articles.

2. part_2_mars_weather.ipynb
Scrape and analyze Mars weather data, which exists in a table.

3. mars.data.csv
Output csv files exported from the DataFrame 

4. mars_news.json
Optional json file to store the scraping results

5. Output_image
Containing temp.png, sort_temp.png, pressure.png, and ter.png

# Instructions

Part 1: Scrape Titles and Preview Text from Mars News

Use automated browsing to visit the Mars news siteLinks 
url = 'https://static.bc-edx.com/data/web/mars_news/index.html'

Create a Beautiful Soup object

Extract the titles and preview text of the news articles being scraped. Store the scraping results in Python data structures as follows:

Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview. 

Print the list in the notebook.

Optionally, store the scraped data in a json file.

Part 2: Scrape and Analyze Mars Weather Data

Use automated browsing to visit the Mars Temperature Data SiteLinks  
URL = https://static.bc-edx.com/data/web/mars_facts/temperature.html.

Create a Beautiful Soup object 

Assemble the scraped data into a Pandas DataFrame. The columns have the same headings as the table on the website. The definition of the names of columns are shown below:

id: the identification number of a single transmission from the Curiosity rover
terrestrial_date: the date on Earth

sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars

ls: the solar longitude

month: the Martian month

min_temp: the minimum temperature, in Celsius, of a single Martian day (sol)

pressure: The atmospheric pressure at Curiosity's location

Examine the data types that are currently associated with each column. Cast the data to the appropriate data types.


The dataset was analyzed based on the questions shown below: 

1. How many months exist on Mars?

2. How many Martian (and not Earth) days worth of data exist in the scraped dataset?

3. What are the coldest and the warmest months on Mars (at the location of Curiosity)? 

4. Which months have the lowest and the highest atmospheric pressure on Mars? 

5. About how many terrestrial (Earth) days exist in a Martian year? 

All the questions have been anwered in the file of part_2_mars_weather.ipynb through data scraping, DataFrame, and plots. 