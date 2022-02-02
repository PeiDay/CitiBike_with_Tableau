# Citi Bike with Tableau
![Citi-Bikes](https://github.com/PeiDay/CitiBike_with_Tableau/blob/main/images/908px-Citi_Bike_logo.png)

## Background

  Since 2013, the Citi Bike Program has implemented a robust infrastructure for collecting data on the program's utilization. Through the team's efforts, each month bike data is collected, organized, and made public on the [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage.

  * Tableau public: https://public.tableau.com/app/profile/peichi.hockaday/viz/CitiBike_Analysis_16437614999410/CitiBikeAnalysis?publish=yes


## Extract and Clean Data
1. Extract the data from [Citi Bike Data](https://www.citibikenyc.com/system-data) by pandas and python. Combined the logs for 2020 into one file. 
2. Clean the data so that any missing data or errors can be omitted for better results. Considering the facts of NYC traffic and assumptions based on those facts, the following data have been removed: 
  * Trip Duration > 24 Hours
  * Unknown Gender
  * User Age > 90 

3. Separate the Stations information and saved to another file. 
4. Removed the Stations information, only keep Station ID for join, from all data in order to reduce the data size.

    ** All the process of extracting is described along with the code in the __extract_CitiBike.ipynb__ of this repo.**

## Analyzing and Visualization 
  Upon analyzing the Citi Bike data for 2020, several phenomena were uncovered. Through this analysis, some insights have been discovered that will help to inform business decisions moving forward.

:bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike:

  * There were 16,740,962 rides during 2020, September had the highest rides.  April had the least rieds, which might be affected by the NYC lockdown due to COVID19 outbreak.  68.11% of the riders are male.  85.05% of the riders are Subscribers, and 14.95% are passholders or signle trip riders. 
  * While most of the riders are male subscribers, it would be the company's best interests to conduct further research on users identifying as male could provide answers as to why so many do choose to ride the bikes, and develop marketing campaigns geared toward individuals who identify as female to increase interest of Citi Bike in New York City. 

  ![Dashboard1](https://github.com/PeiDay/CitiBike_with_Tableau/blob/main/images/Dashboard1.png)
  

:bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike:


  * The busiest month was September during 2020. The whole month of April was on lockdown due to the COVID19 outbreak, therefore, the total rides in April was significant lower. The peak riding hours are between 5pm to 6pm on weekdays, it could be to avoid the crowd in the subway when a lot people are rushing to get back home from work. For the weekend, the peak hour is between 12pm to 4pm, though the peak times throughout week are relatively steady.
  * On a larger scale, the peak times for each month grouped by different seasons were analyzed. As suspected, there is an increase throughout the summer and fall months, most likely due to the warmer weather and the increase in daylight hours. 

  ![Dashboard2](https://github.com/PeiDay/CitiBike_with_Tableau/blob/main/images/Dashboard2.png)
  

:bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike:

  * The top 10 most popular stations to start and end a ride are in the middle of the city which provides a central and convenient location for riders. These places are close to some of the busiest area in the city.

  ![Dashboard3](https://github.com/PeiDay/CitiBike_with_Tableau/blob/main/images/Dashboard3.png)
  ![Dashboard4](https://github.com/PeiDay/CitiBike_with_Tableau/blob/main/images/Dashboard4.png)
  

