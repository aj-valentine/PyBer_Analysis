# PyBer Ride Share Analysis
Analysis Using Jupyter Notebooks, Pandas, + Matplotlib

## Overview of the PyBer Ride Data Analysis :taxi:
This project was created for a CEO of a ride sharing app called PyBer. We were given two sets of data to work with and gather analysis. The first was a CSV file detailing the amount of drivers and type of region for each city that PyBer operates in. The three types of regions are Urban, Suburban, and Rural. The second CSV file contained information about all of the rides that PyBer had recorded for 2019. This detailed the city location, date and time, fare price, and ID number for each ride. We used Jupyter notebooks and Pandas to inspect datasets, write scripts to merge data into one dataframe for our analysis, and perform complex calculations. Then we used Matplotlib to create a line graph and provide a visual story from the data and represent our findings. 

## PyBer Ride Sharing Results 

Overall, we saw varying trends in ride share information between the three city type classifications: Urban, Suburban, and Rural. 
**Total Fares were ranked from highest to lowest: Urban $39,854 - Suburban $19,356 - Rural $4,327**

<img width="454" alt="summary_city_type_df" src="https://user-images.githubusercontent.com/67871338/90989614-25662780-e569-11ea-96ca-906cac98c513.PNG">

1. Urban cities had the highest number of total rides at 1,625 - compared to Suburban at 625 and Rural at 125. 
2. Urban cities also had the highest number of total drivers at 2,405 - compared to Suburban at 490 and Rural at 78. 
3. The average fare per ride was negatively correlated with ride and driver counts. The smaller the number of rides and drivers, the higher the average fare per ride and the average fare per driver. 
    - Rural had the highest average fare per ride at $34.62 - compared to Suburban at $30.97 and Urban at $24.53 per ride. 
    - Rural also had the highest average fare per driver at $55.49 - compared to Suburban at $39.50 and Urban at $16.57. 


When looking at the Total Fare by City Type by Week, we saw similar trends across the three city types. 

![Fig1](https://user-images.githubusercontent.com/67871338/90989595-ff408780-e568-11ea-834d-c5fa06bca5a2.png)

1. All three cities peaked in fare price in late February. 
2. There was an increase in fares for Urban and Rural city types in the beginning of April. 

## Summary of Analysis 

### Three Opportunites Based on the Analysis: 
1. Reduce the number of drivers in the Urban city type: this will increase the average fare per driver and give the drivers an opportunity to make more money for each ride. This will reduce the spend since there will be fewer drivers to provide equipment and resources for. Also, there were 2,405 drivers and 1,625 rides given in 2019 so some of the drivers did not even give one ride. There may be inactive drivers in this number, which would account for the zero rides per driver in some of these instances. Eliminating the inactive drivers would help show an increase in average fare per driver in the data. 

2. In order to increase Rural total fares, offer Rural riders a package deal or % off of their rides for shorter trips. This will incentivize riders to ride more frequently on shorter daily trips, instead of only far destinations like the airport or other longer rides. 

3. Hire drivers based on a seasonality perspective: employ more during the months of March and April and reduce numbers in early January and Februrary. 

