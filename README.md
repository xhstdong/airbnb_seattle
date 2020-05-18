# airbnb_seattle
Analysis of airbnb's Seattle Kaggle dataset for an Udacity class

# Introduction
The Seattle airBnB dataset on Kaggle (https://www.kaggle.com/airbnb/seattle) provides details on the type of listings available in 2016, as well as the prices of the listing throughout the year. This dataset is analyzed to provide a few insights for people interested in using AirBnB while visiting Seattle

# Files
This project includes two files

The first is the data in a zip file. It contains 3 separate csv

-listings.csv contains details on each property available

-review.csv contains reviews provided by guests

-calendar.csv contains the pricing and availability data during the 1 year period of this dataset

The second is the analysis python code, presented in a jupyter notebook. 

Note: The data read-in procedure (using pd.read_csv) in the python notebook will have to be changed depending on the location you save the data. 

# Dependencies
The analysis code uses the following libraries
os

numpy

pandas

matplotlib

sklearn

all are available for install using pip

# Results of analysis
Conclusions of the analysis are:

-cheapest time to get an AirBnB in Seattle is the last week of January

-cheapest area to stay is Delridge, but a number of areas are almost as affordable

-a predictive model with R2 better than 0.97 can be constructed

# Acknowledgment
Inspired by the work done here: https://www.kaggle.com/aleksandradeis/airbnb-seattle-reservation-prices-analysis
