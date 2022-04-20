# PyBer_Ride_Analysis

## Overview of the Analysis
V. Isualize, the CEO of a ride-sharing app PyBer, was seeking an analysis to disover various information about the rides at PyBer.  This analysis includes:
 - A summary of the ride-sharing data by city type
 - A graph to show the total weekly fares for city type

## Resources 
 - Data Source: city_data.csv, ride_data.csv
 - Software: Python 3.10, Anaconda Navigator 4.10, Jupyter Notebook 6.4.5
 
## Results
![pyber_summary_df](https://user-images.githubusercontent.com/100173822/164245846-b9cec18c-62c8-4659-99bb-65657aee4944.png)

Rides are most common in Urban areas, which account for 68.4% of all rides.  In this area, there were more total drivers (2,405) than rides given (1,625).  This caused the average fare per driver in Urban areas to be less than half of the other two city types.  Average fares per ride were highest ($34.62) in rural areas, meaning that more distance was traveled in this area.   

![PyBer_fare_summary](https://user-images.githubusercontent.com/100173822/164247655-03dde0ff-5335-4e82-92e0-abcd5e4ecd70.png)

The beginning of January saw the lowest total fares across Urban and Suburban areas.  There was a spike in total fares across all city types nearing the end of February before all types dipped at the beginning of March.  There was a rise in total fares at the beginning of April for Rural and Urban areas, while Suburban areas dropped. 

## Summary
Business Recommendations:

1.  Decrease the amount of total drivers by half in Urban areas.  By doing this the rides per driver will be relatively consistent across all types:

    - Urban (1,625 rides, 1,202 drivers) = 1.35 rides per driver
    - Suburban (625 rides, 490 drivers) = 1.28 rides per driver
    - Rural (125 rides, 78 drivers) = 1.60 rides per driver

2.  Determine what caused a spike in total fares in late February and use that information to create more revenue.  Seeing as this is not a time for holidays, what caused the fares to spike across all types?  Advertising?   

3.  Determine a way to increase the amount of total rides for Rural areas.  These rides get the most bang for the buck.  
