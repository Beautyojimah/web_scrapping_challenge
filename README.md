# web_scrapping_challenge
This repository contains a web scrapping project that involves scrapping mars news articles and mars weather data.

## Description
This repository contains the solutions to a webscrapping challenge. Within the repository are two jupyter notebooks (part_1_mars_solution.ipynb and part_2_mars_weather_solution.ipynb) and csv file (mars_data.csv). part_1_mars_solution contains codes for retrieving the title and preview from Mars news website using automated browsing. part_2_mars_weather_solution contains code for the extraction, manipulation and visualisation of tables from Mars temperature data website. The scrapped data from part_2_mars_weather_solution is saved in  the mars_data.csv file. 

For part_2_mars_solution, pandas was leveraged to assemble the scraped data into a dataframe, as well as for analysis to answer the following questions:
- How many months exist on Mars?
- How many Martian (and not Earth) days worth of data exist in the scraped dataset?
- What are the coldest and the warmest months on Mars (at the location of Curiosity)?
- Which months have the lowest and the highest atmospheric pressure on Mars?
- About how many terrestrial (Earth) days exist in a Martian year


## Installation
splinter
bs4
selenium
matplotlib
pandas
