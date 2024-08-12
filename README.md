# Project: Zomato Data Analysis
## Overview
### This project involves analyzing restaurant transaction data using two datasets:
1. <b>zomato.csv</b>: Contains transaction details of restaurants.
2. <b>country.xlsx</b>: Maps country codes to country names.

### Datasets
a] zomato.csv

    This CSV file contains detailed information about restaurants. The columns in this dataset include: 
    
    Restaurant ID: Unique identifier for each restaurant.
    Restaurant Name: Name of the restaurant.
    Country Code: Code representing the country where the restaurant is located.
    City: City where the restaurant is located.
    Address: Address of the restaurant.
    Locality: Locality within the city.
    Locality Verbose: Detailed locality information.
    Longitude: Longitude coordinate of the restaurant.
    Latitude: Latitude coordinate of the restaurant.
    Cuisines: Types of cuisine offered.
    Currency: Currency used for transactions.
    Has Table Booking: Indicator if the restaurant offers table booking (Yes/No).
    Has Online Delivery: Indicator if the restaurant offers online delivery (Yes/No).
    Is Delivering Now: Indicator if the restaurant is currently delivering (Yes/No).
    Switch to Order Menu: Indicator if the restaurant has a switch to order menu (Yes/No).
    Price Range: Price range for dining.
    Aggregate Rating: Overall rating of the restaurant.
    Rating Color: Color code representing the rating.
    Rating Text: Textual representation of the rating.
    Votes: Number of votes received.

b] country.xlsx

    This Excel file maps country codes to country names. The columns in this dataset include:
    
    Country Code: Code representing the country.
    Country: Name of the country.
    
### Usage
Data Merging: Combine zomato.csv with country.xlsx using the Country Code to enrich the restaurant data with country names.
Analysis: Perform various analyses, such as rating distribution, geographic distribution of restaurants, or cuisine popularity.
