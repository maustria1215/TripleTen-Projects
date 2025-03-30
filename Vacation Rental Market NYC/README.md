# Vacation Rental Market NYC

The Google Sheets file can be viewed here: 
https://docs.google.com/spreadsheets/d/1lEBiuIQ_vgnCWyR8tkwlWOYmTuz7yY9UlkiJlfDqAlI/edit?usp=sharing

This project was created to help a client analyze the vacation rental market in the Manhattan borough of New York City. The client was interested in investing in several properties but would like some guidance on what types of properties they should be targeting. My role was to analyze data collected on current Airbnb listings to identify useful insights.

# Data
The data was one Google spreadsheet file provided by TripleTen:

'nyc_airbnb_data.csv': each row corresponds to one listing on AirBnB in September 2022
'data_dictionary': summary of field titles seen in file and it's data type
'listings': uniquely listings available with all available data
'calendar': listings with upcoming availabilities and date type data

# Description:
This project is a 17 page spreadsheet that includes raw data, processed data, data analysis, pivot tables, and a bar chart. The purpose was to determine what types of properties should be targeted for the vacation rental market, in the Manhattan borough of New York City based on available AirBnB data.

# Assumptions:
* This data was scraped from Airbnb.com and only includes listings located within Manhattan
* The number of reviews a property had in the last 12 months was used as the best estimate of how often a listing was rented
* This analysis only considered very actively rented listings which were determined to have 48 or more reviews in the last 12 months
* This analysis only considered listings that were above $99 and less than $401
* This analysis only considered short-term rentals which were defined as having a minimum night stay of 7 days or less

# Process
* I explored, filtered, and cleaned the data
* Then I created aggregations and pivot tables to determine the type of properties that should be targeted
* I performed calculations, pivot tables and charts to determine occupancy and estimated revenue
* I then performed analysis to determine what attributes are important for a vacation rental
* Lastly I formatted the document for the client's readability


# Findings/Executive Summary:

The following analysis is to determine what property type should be targeted within Manhattan, NYC for purchase with the intention of renting via Airbnb for investment purposes. Based on the data, the best property to target would be a one-bedroom property in the Lower East Side neighborhood. This type of property is estimated to bring in $66,349 in revenue per year. However, finding the right property is not the only consideration.

To maximize revenue, it is important to have your property available for bookings on Fridays & Saturdays, to become (and maintain the status) an Airbnb Superhost, and have your property instantly bookable as properties with these features have higher occupancy rates and market value. If a property is located within a larger building it should have a doorman as these properties have slightly higher review scores for check-in.

Finally, beware of price hiking when great reviews roll in. Higher review scores by themself do not necessarily warrant higher prices. In fact, higher review scores also don't directly affect occupancy rate either. However, ratings are very important to earn and maintain status as a Superhost (must maintain a 4.8 review score), which will in turn warrant charging higher prices.
