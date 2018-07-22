# Predicting_NBA_Wins
Project Luther for Metis

## Files on this repo
The file "Scraping From Basketball Reference.ipynb" contains code that I used to scrape the data I needed from basketball-reference.com.

The data folder contains pickle files of the various tables I was scraping. These can be imported directly into python to avoid having to re-scrape from the website.

The file "NBA Winning Percentage Linear Model.ipynb" contains the code I used to create my linear model. It starts with importing the pickle files from the data folder and then combines them all into one dataframe. The code then proceeds to create the model. At the end of the file, there is also code that scrapes from a gambling website in order to see if my model would be useful in gambling.
