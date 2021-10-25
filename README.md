# PyBer_Analysis
## Overview of the Analysis
A set of visualizations have been prepared from PyBer's 2019 ride-share data to help their executive team make decisions on where resources and support are needed.  The PyBer dataset is a combination of two .csv files (city_data and ride_data) and provides information for a number of key metrics. The analysis primarily focuses on fare price, city type, and driver count. The data captures the total number of drivers for every city and each city is assigned a type, such as urban, suburban, and rural. This analysis will look at the total average fare, total rides, and total drivers in each city type to identify ways for Pyber to improve their business.

In addition to the visualizations, PyBer's CEO would like to have a chart of the analysis with the total rides, total drivers, total fares, average fare per ride, and average fare per driver in a chart for each city type. The CEO also wants a multiple-line chart of total fares for each city type.


## Results

Below is a chart of PyBer Ride-Sharing Data for 2019. The bubble chart shows the average fare (in dollars) versus the total number of rides per city. The data is sorted by city type, as indicated in the chart legend, and the bubble sizes corregate with the number of drivers per city. 

![Bubble Chart from Initial Analysis](https://github.com/jp3tty/PyBer_Analysis/blob/main/analysis/Fig1.png)

It's clear from the chart that:
* More rides occur in an urban setting than in a rural setting.
* Urban average fares are, in general, lower than suburban and rural average fares.
* Rural settings have the lowest driver counts.

The below box plots show the statistical distribution of drivers for every setting. 

![Driver Count Stats](https://github.com/jp3tty/PyBer_Analysis/blob/main/analysis/Fig2.png)

Urban and rural locations show normal distributions but the suburban setting have a negative skewed which will lets us know that some of these drivers are gathering less fares than other drivers.

Another set of box plots below show the statistical distribution of ride counts for every city type.

![Ride Count Stats]()

As seen above, the rural type strongly shows a positive skew in the data, and the urban and suburban setting generally show a normal distribution.

Chart showing average fare distribution per location.

![% of Fare by City](https://github.com/jp3tty/PyBer_Analysis/blob/main/analysis/Fig5.png)


Chart showing ride distribution per location.

![% of Rides by City](https://github.com/jp3tty/PyBer_Analysis/blob/main/analysis/Fig6.png)


Chart showing driver distribution per loction.

![% of Drivers by City](https://github.com/jp3tty/PyBer_Analysis/blob/main/analysis/Fig7.png)


"There is a description of the differences in ride-sharing data among the different city types. Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type."

![PyBer Summary](https://github.com/jp3tty/PyBer_Analysis/blob/main/analysis/PyBer_Summary.PNG)

![PyBer_Fare_Plot](https://github.com/jp3tty/PyBer_Analysis/blob/main/analysis/PyBer_Challenge_Fare.png)



## Summary
"There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types."
Based on the resulting analysis, my recommendation to address disparity amonng city types...the PyBer CEO 
