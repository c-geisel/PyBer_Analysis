# PyBer Analysis

## Overview of the analysis
The following project analyzes the company PyBer's data on ride sharing. In this analysis the goal is to create a multiple-line graph that compares the Fare prices of various types of cities depending on the time of the year. In past assignments for this company, analyses have been completed on the data between ride counts, driver counts, and average fare prices based on the type of city. This assignment varies in the aspect that we are incorporating the data across a time period. In order to complete this assignment, a summart dataframe is created using pandas and then a the graph is created using matplotlib. This analysis will assist decision makers address disparities among rural, suburban, and urban cities. 

## Results
Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.
- talk about the dataframe and then insert an imafe
- talk abou the creation of the fraph and then insert an image

To begin this analysis, a dataframe is created to obtain the total number of rides, total drivers, total fares, average fare per ride, and the average fare per driver based on the city type. To do this, columns were pulled from the pyber_data_df and then either counted using .count() or added together using .sum(). After this, averaged were found and the values were added and formatted to the pyber_summary_df. 

The following dataframe shows that urban cities had the highest number of total rides, drivers, and fares. Suburban cities had the second most of these categories and rural cities had the least amount of thes categories. However, the highest average fares per ride and per driver were the highest in rural cities with second most still being at suburban and the lowest being in urban cities. This can be explained by the fact that there are less rides and less drivers so in order for them to make a better wage they charge more per ride. In addition to this, rural drivers are most likely driving farther distances and thus charging more per ride. On the opposite end of this spectrum, urban cities are able to charge less per ride as they are driving shorter distances in a city and they have more customers and drivers so prices are kept lower. 
![PyBer_summary_df.png](analysis/PyBer_summary_df.png)

Following the dataframe creation, a line graph was created as an additional analysis tool. The goal of the graph was to show the comparison of the fare prices at different months of the year for the various city types. To accomplish this goal, our pyber_data_df was grouped by type and date and the sum of the fare column was found. A pivot table was created with the fare values based on date for city types and then we resampled this data to group by week. From here a line graph was created. 

In the completed line graph below it can be seen that on average, urban cities have the highest total fare, suburban cities have the second highest, and rural cities have the lowest total fare at about 4 times lower than the average for urban cities. All three lines have quite a bit of variablility from January to April, but the highet fare prices for all city types is at the end of February, while the lowest total fare prices are around January. The fact that urban cities have such a high total fare as compared to other types of cities can be explained by what was stated about that urban cities have more rider traffic and shorter rides leading to a higher total amount of money made. Also, urban cities are more densly populated with less people owning cars leading to more money spent in urban cities. The information that the highest fare was in february can be explained by the fact that this is the coldest time of the year leading more people to want a ride as opposed to walking, while January may be low being that this is the holiday season where many people are staying home and spending time with family and friends. 
![PyBer_fare_summary.png](analysis/PyBer_fare_summary.png)

## Summary
Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.
j
