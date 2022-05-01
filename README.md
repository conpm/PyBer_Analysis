# PyBer_Analysis
---
## Overview of PyBer Analysis
The purpose of this analysis was to compare ride-sharing data between three different types of cities which were defined as "Rural", "Suburban", and "Urban".  The specific ride-sharing data points used in order to compare these three city type were; total number of rides, total number of drivers, and total fares earned.  Additionally, once these data points were found there were used to calculated 'average fare per ride' as well as 'average fare per driver'.  By comparing the three city types through these criteria it is possible to see which city type is most profitable in both absolute terms, as well as relative to the number of drivers and the number of rides taken in an area.
## Results
![PyBer_Summary_DF](https://github.com/conpm/PyBer_Analysis/blob/main/analysis/PyBer_Summary_DF.PNG)

The dataframe above is broken down into the three city types and it is clear that Urban city types have substantially more rides, drivers, and total fares than the opther two city types.  However, the Average fares per ride and per drive are both highest in the Rural city type.

![PyBer_fare_summary](https://github.com/conpm/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

When viewing this line graph showing the data between Jan 6 2019 and April 28 2019 we can see that there is not any overlap between the city types, meaning there is no point in this timefram where there is any change to ranking based on total fares.  Also this multi-line graph shows that there is some consistancy in when total fares increase across all city types, as can be seen clearly in the rise in fares just before the month of March.

## Summary
Based on the analysis performed here, I have come to several reccomendations to address disparities between the city types.  
- The first reccomendation I would make would be to decrease the number of drivers in urban cities, this is because, while there is the largest number of rides in urban cities, the average fare per driver is substantially lower in urban cities due to the very high number of drivers.
- The next reccomendation I would make would be to adjust the pricing of fares depending on the city type, more expensive fares in urban cities and less exensive fares in rural cities could result in more similar averages for fare earned per ride.
- The last reccomendation I would make would be to gather data about fares relative to distance traveled, as well as gas prices in the city types.  By adding these data points into our analysis it would be possible to further understand the costs and benefits of different types of cities.
