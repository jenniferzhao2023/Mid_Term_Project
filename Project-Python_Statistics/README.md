# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
Pull data from 3 API's, merge them then model them to look for any statistical relationships to demonstrate [Python Statistical](https://github.com/Jagunmolu-dev/LIGHTHOUSELABS/blob/main/Project-Python_Statistics/assignment.md) assignment.

## Process
Grab live data from CityBikes API
Specifically generated a list of ebike stations in limerick, Ireland (23 stations found)
Python code in notebook [city_bikes.ipyb](https://github.com/Jagunmolu-dev/LIGHTHOUSELABS/blob/main/Project-Python_Statistics/notebooks/city_bikes.ipynb)

![image](https://github.com/Jagunmolu-dev/LIGHTHOUSELABS/assets/67484584/e36d3413-72de-42ad-87d6-cf41b7d51964)

                  `All ebike Stations in Limerick, Ireland as of June 3, 2023`


# Step 2: FourSquare and YELP API's
used API's to find Points of Interest (POI's) near each of the stations
specifically looked within 1000m for "Bars and resturants" 
Python code in notebook [yelp_foursquare_EDA.ipynb](https://github.com/Jagunmolu-dev/LIGHTHOUSELABS/blob/main/Project-Python_Statistics/notebooks/yelp_foursquare_EDA.ipynb)

## Results
## Quality of APIs
Result generated from Yelp POI results produced more valuable result compared to the FourSquare which may be because of the category selected of "Bars and Restaurants"

## Exploraty Data Analysis (EDA)
During EDA, various visualization techniques were applied to explore the data and extract meaningful information
Python code in notebook [joining_data.ipynb](https://github.com/Jagunmolu-dev/LIGHTHOUSELABS/blob/main/Project-Python_Statistics/notebooks/joining_data.ipynb)
![image](https://github.com/Jagunmolu-dev/LIGHTHOUSELABS/assets/67484584/6e017eed-20a8-4730-8c9b-215c6dff17cd)
                          
                                             `  Histogram of all features`

![image](https://github.com/Jagunmolu-dev/LIGHTHOUSELABS/assets/67484584/32207823-57b4-4fd2-8640-2f92415a20ec)
                              Heatmap Diagram 

## Challenges 
- Getting all POIs and performing analysis on all the stations of the cit bikes due to time constraint
- Unclear questions on how to proceed in joining/ merging  all the data together
- Poor API Documentation
- Inconsistent naming of columns gotten from the api, i had to rename columms before merging data

## Future Goals
- Get all data from the POI close to each station to be able to better make predictions 
- Document functions and my code for future reference and reusability
- 
