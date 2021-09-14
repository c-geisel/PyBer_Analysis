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

## Summary
Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.
j
