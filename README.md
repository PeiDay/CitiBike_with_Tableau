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
  
  ### The first dashbord shows the demographic of total reidership broken down by **User Type**, **Gender**, and **Age**. 
    

:bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike:


  * What are the peak hours in which bikes are used in different seasons?

  ![Dashboard2](https://github.com/PeiDay/CitiBike_with_Tableau/blob/main/images/Dashboard2.png)
  
  ### The peak month and hour

:bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike::bike:

  * What are the top 10 stations in the city for starting a journey?
  * What are the top 10 stations in the city for ending a journey?

  ![Dashboard3](https://github.com/PeiDay/CitiBike_with_Tableau/blob/main/images/Dashboard3.png)
  ![Dashboard4](https://github.com/PeiDay/CitiBike_with_Tableau/blob/main/images/Dashboard4.png)
  
  ### Popular bike stations

