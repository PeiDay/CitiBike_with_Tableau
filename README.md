# Citi Bike with Tableau
![Citi-Bikes](https://github.com/PeiDay/CitiBike_with_Tableau/blob/main/images/908px-Citi_Bike_logo.png)

## Background

  Since 2013, the Citi Bike Program has implemented a robust infrastructure for collecting data on the program's utilization. Through the team's efforts, each month bike data is collected, organized, and made public on the [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage.

  * Tableau public: https://public.tableau.com/app/profile/peichi.hockaday/viz/CitiBike_Analysis_16437614999410/CitiBikeAnalysis?publish=yes


## Extract and Clean Data
1. Extract data from [Citi Bike Data](https://www.citibikenyc.com/system-data)

2. Remove the following rows: 
  * Trip Duration > 24 Hours
  * Unknown Gender
  * Age > 90 

3. Separate the Station to another table in order to reduce the data size.

## Analyzing and Visualization 
  Upon analyzing the Citi Bike data for 2020, several phenomena were uncovered. Through this analysis, some insights have been discovered that will help to inform business decisions moving forward.

  * How many trips have been recorded total during 2020?
  * What is the gender breakdown of active participants (Male v.s Female)?
  * What are the user types of active participants (Subscriber v.s. Customer)?

  ![Dashboard1](https://github.com/PeiDay/CitiBike_with_Tableau/blob/main/images/Dashboard1.png)

#### The first dashbord shows the demographic of total reidership broken down by **User Type**, **Gender**, and **Age**.  
    

  * What are the peak hours in which bikes are used in different seasons?

  ![Dashboard2](https://github.com/PeiDay/CitiBike_with_Tableau/blob/main/images/Dashboard2.png)


  * What are the top 10 stations in the city for starting a journey?
  * What are the top 10 stations in the city for ending a journey?

  ![Dashboard3](https://github.com/PeiDay/CitiBike_with_Tableau/blob/main/images/Dashboard3.png)
  ![Dashboard4](https://github.com/PeiDay/CitiBike_with_Tableau/blob/main/images/Dashboard4.png)

