# Mid-Term Project-

## Project/Goals
> This project is aim to analyze the bike buyer dataset that includes individuals' demographic attributes (marital status, gender, age, and children), financial status (income and home ownership), education, occupation, number of cars, commute distance, region, and whether they purchased a bike or not.

our project goal is to find whether is there any column or all columns that have a connection or causation to the “Purchased bike” column. Make valuable insights for companies in the bike industry to better understand their customers and improve their marketing and product strategies.


## Process
### Got the data from [Kaggle](https://www.kaggle.com/datasets/heeraldedhia/bike-buyers?select=bike_buyers.csv)


1. Got the data from Kaggle and explored data to understand what the dataset is all about

2. Performed Data Cleaning: During the dataset exploration, I noticed that this dataset is already looking clean but still some null values can be observed. I utilized Jupyter Notebook to inspect the presence of null values.  Upon investigation, I discovered that the "Price" column did not contain any null values. However, I did identify null values in the "Review Score Rating" and "Host Since" columns. In this case, I made the decision to keep the null values rather than removing them.

3.	Data visualization and make insights: Throughout the project, I created different visualizations to gain insights into thelistings dataset. 



### Compared each of the variables to know which demography is more likely to purchase a bike 

## Results

We conducted an analysis to determine the relationship between each column and the likelihood of purchasing more bikes.

By targeting specific demographics and adapting to market trends, bike retailers and marketers can enhance their ability to attract and retain customers in a competitive market. Recommendations for bike retailers or marketers based on the insights are as follows:

1.Target Specific Demographic Groups: Focus marketing efforts on middle-aged individuals who have fewer children and less cars, as they may have more time and disposable income for leisure activities like biking.

2.Consider targeting individuals with higher levels of education, as they may value the health and environmental benefits of cycling.

3.Emphasize Professional Occupations: Tailor marketing messages and campaigns towards individuals with professional occupations, as they may have higher purchasing power and be more inclined to invest in quality bikes and accessories.

4.Highlight Commute-Friendly Features: Promote bikes that are suitable for shorter commutes, emphasizing their convenience, eco-friendliness, and potential cost savings compared to other modes of transportation.




> Comparing all factors to show demographics of who is likely to purchase a bike
![output 1](https://github.com/Jagunmolu-dev/LIGHTHOUSELABS/assets/67484584/be4b8839-f7ac-4845-8ffe-9c852142b4ec)

> From the output above we can see that those with a lesser commute time are more likely to purchase a bike than those with a longer commute time which is clearly shown in the image below
![image](https://github.com/Jagunmolu-dev/LIGHTHOUSELABS/assets/67484584/b8cc23fc-9d03-425e-bac8-e6b1e4dd7212)

> Compared the count of those who purchased a bike by the income
![image](https://github.com/Jagunmolu-dev/LIGHTHOUSELABS/assets/67484584/a86677df-a9f1-4948-a578-9a2c67a9d843)
From the chart provided above we can see that those whose income is between 40,000 and 70,000 are most likely to purchase a bike and we see that as income increases the probability of purchasing a bike reduces as seen in the boxplot below which shows some rare occurrences of those with higher income purchasing a bike
![image](https://github.com/Jagunmolu-dev/LIGHTHOUSELABS/assets/67484584/f52b4028-31be-479f-98c6-c78040400b12)

> A moderate positive linear relationship between the ages of those who purchased a bike and the number of children

> We can see that gender does not have a considerable effect on whether a bike is purchased or not
![image](https://github.com/Jagunmolu-dev/LIGHTHOUSELABS/assets/67484584/27b0df93-1707-4f33-b66c-128a9d32e3bb)

> Finally a dashboard that shows insight to which demographics is likely to purchase a bike
![image](https://github.com/Jagunmolu-dev/LIGHTHOUSELABS/assets/67484584/90ce0f0b-9e3d-4b8e-a5b8-c42153e7ca14)


## Challenges 
1.Limited numeric variables to use for comparisons to make more accurate insights.

2. This dataset differed from previous ones we had worked with. One significant issue was the limited amount of information available for analysis, as we only had data pertaining to the specific column - purchased bike. As a result, all the charts produced seemed to exhibit a similar and unimpressive appearance.


## Future Goals
If we have more time, our future goal is to focus on developing and refining models that can accurately predict which demographic is more likely to purchase a bike. 
