# Webscrape tutorial

A short tutorial on how to scrape multiple webpages on the same URL using Python 3 and BeautifulSoup in order to collect data for projects. In this example I save the 2nd and 3rd instances of text data on every webpage.

webscrapetutorial.ipynb is the generic scraper.

webscrapetutorial_if_else_statements.ipynb is the scraper with an added feature for skipping scraping pages that fill a certain defined critera.

NOTICE: Check the webpages robot.txt file and their ToS or Licenses before use.

In this tutorial I use Jupyter notebooks. The scraper will be uploaded as a .ipynb

1) Start by importing the needed libraries. 

2) Set ut the columns we want to save the data to.

3) Set up a for loop for our requests.

4) We use a sleep and random integer function to not overload the server.

5) Save Pandas dataframe to csv


