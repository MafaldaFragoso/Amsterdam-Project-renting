<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Short-term rentals in Amsterdam
*Alessandro Mazzoni, Katja Galyuk, Mafalda Fragoso*

*Ironhack, Amsterdam 6/03/2020*

## Content
- [Project Description](#project-description)
- [Questions & Hypotheses](#questions-hypotheses)
- [Dataset](#dataset)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)


## Project Description
This is a group project at Ironhack Amsterdam,  the project intends to find if there is any correlation between the price of Airbnb and the number of restaurants and nightlife facilities. Our team will find the data frame online and retrieve useful information in order to answer this question.

## Questions & Hypotheses
Our research question: "What is the impact of nearby bars and restaurants on the price of Airbnb in Amsterdam?". We do expect a correlation between the two, and to see that the more restaurants and bars surround an Airbnb the higher will be its price. WE also expect to find more restaurants and bars in the center of the city, which would be one of the factors that influence the higher price in the city center.

## Dataset
- Listings of Airbnb rental apartments: Data obtained from Inside Airbnb website; Data in CSV format with detailed listings data for Amsterdam including price per night, latitude, longitude, among others
http://insideairbnb.com/get-the-data.html
- Restaurants and nightlife venues: •Data obtained from Yelp Fusion API
https://www.yelp.com/developers/documentation/v3/get_started

## Workflow
DATA CLEANING
- Data set 1 : id, neighbourhood, latitude, longitude, room_type, price
- Data set 2 : id, acommodates
- Merge the two
- Checking missing values (0)
- Checking the number of duplicates (0)
- Rename the columns price to price_USD
- Creating the columns price_€ (price_USD * exchange rate(0.895667))
- Creating the columns price_€_accommodates (price_€ /accommodates)
- remove outlier (price between 30 and 900

DATA ANALYSIS
- checking for the statistics module values
- checking the Number of listings by neighbourhood
- mapping all the listings
- analysing the distribution number of accommodates
- analysing the distribution of price by neighbourhood

DATA MANIPULATION
- create a function to select all the facilities needed in a radius of 250m
- analyse a posible corrolation for price and facilities of each airbnb in the specific region
- repeat this process for more region


## Organization
In order to organize our work, we decide to create a planning on Trello. It helps us manage our work quantity and to avoid falling behind in the planning

## Links
Include links to your repository, slides and kanban board. Feel free to include any other links associated with your project.

[Repository] https://github.com/MafaldaFragoso/Amsterdam-Project-renting
[Slides] on github 
[Trello] https://trello.com/b/zT9SjBh4/housing-in-amsterdam
