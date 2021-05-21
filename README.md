# PyBer with Matplotlib

## Overview of Analysis
In this scenario, we are working as a data analyst for PyBer, a Python-based ride-share company/app. We are tasked with performing an exploratory analysis on ride data to discover the relationship between different cities, the number of riders, the number of drivers, and provide various summary statistics based on the type of city. Our goal is to help improve access to ride share services and improve affordability of rides in underserved neighborhoods. With this new analysis, we created a summary DataFrame including ride-sharing data by city type. Using this information, we created a visualization to show the total weekly fares for each city type.  

## Results
### Summary of Data by City Type
![Image of Summary Data by City Type](https://github.com/jpb12002/PyBer_Analysis/blob/main/Analysis/Summary_Data_By_City_Type.png)
- The total number of rides is significantly higher in Urban cities than any other type, with 1,000 more rides than the next highest city type which is Suburban. Rural type cities had the fewest number of total rides. 
- The total number of drivers is significantly higher in Urban cities than any other type, with almost 2,000 more drivers than the next highest city type which is Suburban. Rural type cities had the fewest number of total drivers.  
- The total amount of fares collected is significantly higher in Urban cities than any other type, with $20,000.00 more collected than the next highest city type which is suburban. Rural type cities had the lowest amount of total fares collected. 
- There is an inverse relationship between the number of rides in a city type and the average fare per ride. Rural type cities have the fewest number of rides, but the average fare per ride is the highest compared to the other types of cities.  
- There is an inverse relationship between the number of drivers in a city type and the average fare per driver. Rural type cities have the fewest number of drivers, but the average fare per driver is significantly higher compared to the other types of cities. 

### Weekly Summary of Fares by City Type
![Image of Total Fare by City Type](https://github.com/jpb12002/PyBer_Analysis/blob/main/Analysis/PyBer_Fare_Summary.png)
- The total fares collected on a weekly basis is highest in Urban city types, with these cities collecting between $2000-$2500 per week. Suburban city types had the second highest total fares collected on a weekly basis, with these cities collecting between $1000-$1500 per week. Rural city types had the lowest total fares collected on a weekly basis, with these cities collecting between <$100-$500 per week. 
- The amount of fares collected in each city type is fairly consistent from week to week, with no significant deviations in the trend lines. Interestingly, all three city types had a spike in fares collected in the last week of February. 

## Summary
We recommend the following to address the disparities between Urban and Rural community usage of PyBer:
1. Investigate our advertisements in Rural communities and determine if the low total number of rides is truly from fewer residents in these communities or if there is a lack of knowledge about PyBer and our business offerings. Word-of-mouth about PyBer may not be enough to increase customer usage in these Rural areas and we may need to consider increasing our advertising budget within these areas. Because of the inverse relationship between the number of rides in an area and the average fare per ride, the cost of the rides in Rural communities should decrease if we can persuade more customers to use PyBer.
2. Investigate why there are so few drivers in Rural communities compared to Suburban and Urban communities. The small number of drivers is likely related to the smaller number of workers in these communities. We may need to consider offering incentives for Urban and Suburban drivers who are closer to these Rural areas to accept more rides from Rural communities. Since the average fare per driver is much higher in Rural communities, drivers from Suburban and Urban areas are in a position to increase their earnings if they are able to drive out to these Rural areas. 
3. Consider readjusting the fare prices in Urban versus Rural communities. Since the usage of PyBer is so high in Urban areas, the fare calculations could be slightly increased for these customers. This could then offset a more significant price decrease in Rural communities. Since the high cost per ride could be a deterrent for new customers in Rural communities, any price decrease might bring in additional customers and increase PyBer usage. 
