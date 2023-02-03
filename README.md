# Mission-to-Mars-Webscrape-Challenge

This challenge involved scraping date from the Mars NASA news site (https://redplanetscience.com) and the Mars Temperature Data Site (https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html) using BeautifulSoup. The scraped data was either exported to a JSON file or inserted into a MongoDB database. This data was then analysed and visualised using Pandas and Matplotlib. Finally, the data was saved into a CSV file for future reference.

## Analysis
The following research questions were examined through an analysis of the scraped data:
- How many months exist on Mars?
- How many Martian (and not Earth) days worth of data exist in the scraped dataset?
- What are the coldest and the warmest months on Mars (at the location of Curiosity)?
- Which months have the lowest and the highest atmospheric pressure on Mars?
- About how many terrestrial (Earth) days exist in a Martian year?

Refer to part_2_mars_weather.ipynb for further details.

## Technologies used
- Splinter
- BeautifulSoup
- Pandas
- Matplotlib
- Webdriver Manager for Chrome
- MongoDB
- pymongo