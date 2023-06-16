# Final-Project-Tableau

## Project/Goals

This project aims to explore and analyze a dataset containing 30,478 Airbnb listing in New York city with Tableau. By analyzing this dataset, our goal is to gain a comprehensive understanding of various aspects of the listing and uncover meaning patterns, trends, and valuable insights. These insights will provide a valuable knowledge of Airbnb market in New York city, benefiting both Airbnb hosts and potential guests.

## Process
1.	Data Connection and Exploration: After connecting the data, I thoroughly explored the tables and detected the datatypes of columns. From my observations, it is evident that the dataset provides valuable information about the hosts, geographical details, and various metrics such as price, number of reviews, and other related fields.
2.	Data Cleaning: During the dataset exploration, I noticed that this dataset is already looking clean but still some null values can be observed. I utilized Jupyter Notebook to inspect the presence of null values.  Upon investigation, I discovered that the "Price" column did not contain any null values. However, I did identify null values in the "Review Score Rating" and "Host Since" columns. In this case, I made the decision to keep the null values rather than removing them.
3.	Data visualization and make insights: Throughout the project, I created different visualizations to gain insights into the Airbnb listings dataset. 


## Results
(Fill in which Option you chose, either 1 or 2. List the dataset you selected for the project if you selected Option 2. Also, discuss the visualizations you created, and why. For Option 2, also identify what your data question was, and how you went through the prompts.)

I chose option 2 Airbnb dataset for this project.

During this analyze and visualization process, each visualization was designed to address a particular data question or explore a specific aspect of the data.

1.	Map Visualization of Airbnb Listings by Neighborhood with Scatter Plot: 
By utilizing a map visualization with a scatter plot, we can gain a comprehensive understanding of the geographical distribution of Airbnb listings across different neighborhoods. Additionally, by using interactive features, we can dynamically display additional information such as the listing name, price, room type, and other relevant details.

2.	Which are the popular neighborhoods, and what’s the number of different room type of listings?
From Beds availability for each room type bar chart, we can see the most listings are in Manhattan and Brooklyn. Queens comes in the third most listing but are not close to the number of listings in Manhattan and Brooklyn. Bronx and Staten Island have very few listings compared to the other 3 regions.

3.	Which neighbourhood has highest rating and review?
By review and average ratings of each neighbourhood bar chart, we can observe the total number of reviews and average review ratings. All regions have and average rating greater than 90%, with Brooklyn receiving the highest rating of 92.36.

4.	How is the pricing varying with location and property type?
From those Average price by Neighbourhoods and by room type, we observed that Manhattan area has the highest price average ($198.5) with Bronx having the lowest ($94.7). Interestingly, when it comes to entire homes and apartments, Staten Island takes the lead with and average price of 295.7. 

5.	What are the correlations between average price and average rating score?
 I utilized plotting the average price of listings against the average review score they received. Basically, this cluster scatter plot effectively illustrates the positive correlation between average price and average review score. As the price increases, there is a corresponding increase in the review score.

6.	What’s the trend of the average price per year for each neighbourhood?
By average price per year and trends lines, we can observe the average price for each year and the corresponding trend line for each neighborhood. In the case of Brooklyn and Manhattan indicate a reliable forecast of the trend.

7.	What are the trends of Airbnb hosts number in different neighbourhoods?
Utilizing a line chart, I analyzed the growth of hosts joining Airbnb from 2008 to 2015. In Manhattan and Brooklyn, there was a remarkable increase in the number of hosts between 2008 and 2014, followed by a decline in 2015. On the other hand, the remaining three regions displayed a consistent upward trend in host numbers throughout the entire period. These trends forecast a growth for all for all regions in the next three years.




## Challenges 

One of the challenges I encountered during this project was improving the details within a limited timeframe. 
I also have a question about the data cleaning. For this dataset, my approach involved excluding null values. However, for datasets requiring extensive cleaning, we will perform initial cleaning using Python to make it ready for the visualization. I wondered if there were any tools available that would enable me to perform additional cleaning tasks without the need to convert the data back to CSV format after connecting it to Tableau.


## Future Goals

If I have more time, I will dedicate it to enhancing the dashboard with attention to detail, such as refining the color palette, selecting appropriate fonts, and adjusting the positioning of legends and other elements. Additionally, I will create additional dashboards with separate worksheets to present a comprehensive Tableau story, providing a more comprehensive visualization experience.