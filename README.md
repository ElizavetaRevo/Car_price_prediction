# Car_price_prediction



## Description 



Buying a car is never an easy task, especially when it comes to purchasing a used one. There are many factors to consider, and in some regions, used car options are limited and prices can be high. To explore this issue, I conducted a survey using a dataset of used car listings scraped from Craigslist.

For this project, I performed essential data cleaning steps, which you can review in the analysis.ipynb file:

a) Identified and handled missing values in various columns.

b) Merged and standardized column values to reduce outliers.

c) Removed inconclusive columns.

d) Detected and corrected data entry errors.

Additionally, I analyzed the geographical distribution of used cars and their characteristics in Tableau. You can view the interactive dashboard here:
https://public.tableau.com/app/profile/elizaveta.sokolova/viz/Usedcarsproject/Dashboard1.

## Import Data

The data for this project is obtained from kaggle datasets, it consists over 450000 entries and it's a listing on craigslist from October to December of 2020 used cars for sale.
The data is available on kaggle- https://www.kaggle.com/austinreese/craigslist-carstrucks-data?

This data is originally scraped by Austin Reese, it contains most relevant information that Craigslist provides on car sales including columns like price, condition, manufacturer, latitude/longitude, and 18 other categories.

Our dataset contains over 450000 used vehicle sales entries from Craigslist.org

The columns are as follows:

id - Unique identification number

url - Listing URL

region - Craigslist region

region - Region listing URL

price - Listing price

year - Year of manufacturing

manufacturer - Manufacturing company

model - Model of vehicle

condition - Condition of vehicle

cylinders - Number of cylinders

fuel - String - Type of fuel required

odometer - Miles traveled

title_status - Vehicle title status/existence

transmission - Transmission of vehicle

drive - Drive of vehicle

size - Size of vehicle

type - Type of vehicle

paint_color - Color of vehicle

image_url - Image URL

description - Description about the sale

state - 2 letter state abbreviation

latitude - Latitude of listing

longitude - Integer - Longitude of listing

posting_date - Posting Date of the sale




