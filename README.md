# Membership Conversion Summer Marketing Campaign 
## R & Tableau


                                                         Introduction
                                                      



## **Background**: 
A bike share company is located in Chicago, Illinois. The company has a bike-share program that features over 5800 bicycles and 600 docking stations. The company also offers reclining bikes, hand tricycles, and cargo bikes, making bike-sharing more inclusive to people with disabilities and riders who are unable to use a standard two-wheeled bike.

The company's marketing strategy relies on building general awareness about the brand overall and appealing to broad consumer segments. The financial team has concluded that the annual members are more profitable compared to casual riders. The director of marketing believes that prioritizing maximizing the number of annual members will be the key to future growth. Instead of creating a marketing campaign to target all new customers, the director thinks that there is an great opportunity to focus on converting casual riders into annual members.





## **Goal**: 
The goal is to create a new marketing strategy that incorporates key metrics extracted from the company dataset to convert casual riders into annual members.


## **Business Task: What To Find Out**: 
How do annual members and casual riders use the company bikes? How


## **PREPARE**:
The dataset can be found here at https://divvy-tripdata.s3.amazonaws.com/index.html. The dataset is public and was made available by Motivate International Inc. under the Divvy Bikes License. 

The dataset contains the number of trips taken per month and per year by a casual rider or an annual member, the times and dates taken place, etc. Analyzing this information to get a breakdown of the differences between casual riders and member riders will help provide solid insights on answering the question of how the use of the bikes differ between both types of consumers. 



## **PROCESS**:
The data cleaning process was initially started in Microsoft Excel, but it was found that the files had issues loading, and was not performing optimally in SQL. I opted to use R, and while RStudio Cloud could not upload the data, I found that RStudio Desktop was able to without problems. My choice to utilize R came from seeing that the data had over 5 million points of data to work with, and to create an R Markdown worksheet to better map out my process of data cleaning with code step by step. 



The visualization and complete presentation was done on Tableau and can be viewed [here.](https://public.tableau.com/app/profile/visan2980/viz/DataAnalyticsProjectDashboard/Story1#1)

## Summary of Key Insights

### **Total Riders in 2021**
* Bike ridership data from January to December 2021 shows members made up approximately 55.4% of total riders, and casual riders made up approximately 44.6%
* These numbers were 2,539,802 for members and 2,048,302 for casual riders

### **Average Ride Lengths in 2021**
* Casual riders tend to on average have ride lengths that are approximately 19 minutes longer than members in 2021
* Average ride lengths were higher on Saturdays & Sundays for both members (15 min length approx.) and casual riders (36 min length approx.)

### **Number of Riders Per Day**
* Wednesday was the busiest day for members, reaching a total of 397,681 riders in 2021
* Saturaday was the busiest day for casual riders, reaching a total of 468,318 riders in 2021

### **Busiest Season for Riding**
* Amongst the four seasons, Summer was the busiest, accounting for approxiamtely 43% of the total rides in 2021
* Winter had the lowest amount of riders, accounting for just 6.6% of total rides in 2021
* Fall season accounted for 29.5% of total rides, Spring accounted for 20.8%

### **Amount of Riders By The Hour**
*
*
*

## Recommended Action Plan
*
*
*
