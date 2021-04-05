# PyBer Analysis


## Overview of PyBer Analysis
As a data analyst for PyBer, a python-based ride-sharing app company, we have been asked to perform exploratory analysis on a .csv file containing information on the rideshares occurring across different cities. This file includes information on:
- the city name
- the date of the rideshare
- the total fare
- the number of drivers
- the type of city (Urban, Suburban or Rural)

We have been tasked with producing visualizations to help PyBer improve access to ride-sharing services and determine affordability for underserved neighbourhoods. The current project involves creating a summary of the ride-sharing data based on city-type. These findings will then be visualized in a multi-line graph that shows the total weekly fares for each city type from January - April 2019.  A report will be presented based on these findings to inform the decision-makers at PyBer.


## PyBer Analysis Results

Upon grouping the ride-share data by city type, it becomes apparent that each market's usage and needs differ greatly. Below, you can see a summary of the data on rides, fares and drivers between each city type:
 
 ![Analysis Summary](/Analysis/Analysis_summary.PNG)
 
 The first thing to note is that engagement with the service overall is much lower in rural communities, with rural rides making up a mere 5% of total rides. Meanwhile, usage in urban communities makes up 68%. 
  
  The difference in the number of total drivers falls in line with usage in that there are much fewer drivers in rural cities (2.6%) while the majority of drivers are active in urban areas(81%). This correlational data cannot determine causation. It may indicate that the lack of demand for rides (as shown by the smaller number of total rides) has led to fewer drivers. Alternatively, the lack of available drivers may have caused the lower engagement through a lack of available services. 
 
 ![Rides by city](/Analysis/Rides_by_city)
 ![Drivers by city](/Analysis/drivers_by_citytype)
 
As expected, based on the trend in total rides and drivers across city types, the total of fares accumulated in rural cities was much lower (6.8%), and the majority of fares were earned in urban cities (63%).

 ![Fares by city](/Analysis/Fares_by_citytype)

While the trend across city types remains consistent, the difference between types shrunk when measuring total fares; this is explained by the increased average fare per ride and per driver that we see in rural cities. In the case of these measures, average fares in urban cities come out at the bottom, and suburban fares fall easily in the middle.
 
These findings suggest that overall engagement in rural communities is lower, and the rides that do occur come at a higher cost to the user. This increased fare could come as a result of the smaller number of drivers and subsequently reduced competition. It may also come as a result of the greater distances typically traversed in rural areas. 
 
 After breaking down each factor across city types, a subset of the data consisting of rides taken between January 1, 2019, and April 29, 2019, was compared, by date, across city type to look for trends across time. Below, you  can see the total fares earned within rural, suburban and urban cities each week:
 
  ![Week by Week Visualization](/Analysis/PyBer_Analysis.PNG)

From this, it is apparent that the usage amongst each city type has remained relatively stable on a week-to-week basis with the exception of a slow, steady increase in urban fares. Suburban and rural total fares show no clear increase or time-based fluctuations.


## PyBer Analysis Summary

Based on the analysis above, I have three recommendations for addressing the disparities among city types. 
1. Carry out an additional analysis into the average length of rides within each of the three types of cities. The average cost per kilometre should be assessed alongside the average price of gas to determine if the increased average fare per ride results from longer rides, increased expenses for drivers, or reduced competition amongst fewer drivers in rural and suburban areas. 
2. Should a greater cost (as indicated by increased gas prices, longer average drives) be seen to present a barrier to entry for drivers in urban and suburban areas, pilot studies within each category may be used to test the implementation of fuel subsidies for drivers or increased shares of fares. These small pilot studies could be used to assess whether these subsidies can increase market engagement large enough to justify the expense.
3. If gas prices and ride length are similar to rides in each city type or even lower in rural and suburban cities than in urban cities, reduced competition amongst fewer drivers may be playing a role in the increased cost to the consumer (as previously indicated by larger average fares). Should this be the case, it is recommended that PyBer implement limits on the fares drivers are permitted to charge and allocate funding towards marketing in these underserved areas to inform the markets of these increasingly affordable rates and hopefully stimulate engagement from consumers. This increase in consumers may, in turn, produce an increased demand for rides that will encourage more rural drivers to join our program. This course of action presents a risk of upsetting current drivers within areas of higher fares; however, the thriving market amongst urban cities suggests that greater numbers of rides and reduced average fares as positively related. 