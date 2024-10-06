# Data-Analytics-Project


                                                         Introduction
                                                      



## **Background**: 
A bike share company located in Chicago, Illinois. The bike-share program features more than 5800 bicycles and 600 docking stations. The company also offers reclining bikes, hand tricycles and cargo bikes, making bike-share more inclusive to people with disabilities and riders who can’t use a standard two-wheeled bike.

The company's marketing strategy relies on building general awareness and appealing to broad consumer segments. The financial team has concluded that annual members are more profitable compared to casual riders. The director of marketing believes that maximizing the number of annual members will be the key to future growth. Instead of creating a marketing campaign to target all new customers, the director thinks there is an opportunity to convert casual riders into annual members.




## **ROLE**: 
As a data analyst working in the marketing analyst team, the team wants to understand how casual riders and annual members use bikes differently. Then, we will use these insights to come up with marketing strategies to help with our business task.



## **Goal**: 
The overall goal is to design a new marketing strategy targeting factors extracted from data insights aimed to convert casual riders into annual members.


## **Business Task**: 
How do annual members and casual riders use bikes differently?


## **PREPARE**:
The dataset can be found here https://divvy-tripdata.s3.amazonaws.com/index.html. The dataset is public and made available by Motivate International Inc. under the Divvy Bikes License. 

The data contains trips about the number of trips taken per month in a year, by a casual rider or an annual member, the times and dates, etc. Analyzing this information to get a breakdown of the differences between casual riders and member riders will help provide us solid information on answering our question of how the use of bikes differ between both types of consumers. 



## **PROCESS**:
I started the data cleaning process in Excel, but quickly found that the files were far too big for Excel, and very large for SQL. I opted to use R, and while RStudio Cloud could not upload the data I found that RStudio Desktop was able to seamlessly. My choice to utilize R came from seeing that the data had over 5 million points of data to work with, and to be able to create an R Markdown worksheet to better map out my process of data cleaning with code step by step. 



The visualization and presentation was done on Tableau and can be viewed [here.](https://public.tableau.com/app/profile/visan2980/viz/DataAnalyticsProjectDashboard/Story1#1)

## Insights Summmary

### **Total Riders in 2021**
* Bike ride data from January to December 2021 shows members made up about 55.4% of total riders, and casual riders made up 44.6%
* These numbers were 2,539,802 for members and 2,048,302 for casual riders

### **Average Ride Lengths in 2021**
* Casual riders tend to on average have ride lengths 19 minutes longer than members in 2021
* Average ride lengths were higher on Saturdays and Sundays for members (15 min length approx.) and casual riders (36 min length approx.)

### **Number of Riders Per Day**
* Wednesday was the busiest day for members, reaching a total of 397,681 riders in 2021
* Saturaday was the busiest day for casual riders, reaching a total of 468,318 riders in 2021

### **Busiest Season for Riding**
* Across the four seasons, Summer was the busiest account for 43% of the total rides in 2021
* Winter had the lowest amount of riders, accounting for just 6.6% of total rides in 2021
* Fall had been analyzed to account for 29.5% of total rides, Spring accounted for 20.8%

### **Amount of Riders By The Hour**
*

## Recommendations

