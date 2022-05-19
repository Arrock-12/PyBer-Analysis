# Pyber Ride Share Analysis
## Overview and Purpose
For this project, we analyzed how ride, fare, and driver data are impacted by city types: urban, suburban, and rural in order to provide the CEO of Pyber, V. Isualize, with suggestions on how to improve the efficiency of her company and make sure that she was allocating resources and support appropriately in order to maximize revenue and ensure that customers’ needs are met. In addition to analysis, we provided visualizations to V. Isualize to quickly portray the results and detect trends and correlations in the data. 
## Resources
-	Data source: city_data.csv, ride_data.csv
-	Software: Jupyter Notebooks, conda 4.12.0, Python 3.7.2
## Results 
In the Pyber Summary, we tallied the number of rides, the total drivers, the total fares, the average fare per ride, and the average fare per driver based on city type. The following chart summarizes the findings.

![Pyber_Summary](https://user-images.githubusercontent.com/101822948/169400531-005bcd62-26ec-4ce9-b6a7-ab67fdd601a9.png)

The results from the analysis were:
-	The majority of rides occurred in urban cities. There was nearly 13 times as many urban riders as there were rural riders. Nearly 68% of all rides were in urban areas compared with around 26% in suburban areas and 5% in rural. 
-	Most drivers operate in urban areas. Nearly 81% of Pyber’s drivers operate in urban cities compared with 16.5% in suburban areas and near 2.5% in rural. There were 30x more urban drivers than rural drivers.
-	Urban areas generated the most fares with totals just under $40,000 – 9x more than rural areas and 2x more than suburban cities. Urban fares constituted nearly 63% of the total fares generated.
-	However, average fares for rural riders were higher than both suburban and urban cities by around $5 and $10 respectively. 
-	Rural drivers average fare by driver was 3x more than urban drivers and 1.5x more than suburban. Rural drivers, on average, earned $55.49 per ride compared with Urban drivers, who earned $16.57 per ride.

In the analysis of Total Fare by City Type over the first four months of 2019, the results indicate that Urban areas consistently had higher fares, followed by Suburban cities and then Rural.

![Total_Fare_by_City_Type](https://user-images.githubusercontent.com/101822948/169400604-4bb0265f-585d-444f-8694-a51701860797.png)

-	The weekly total fares in Urban areas fluctuated within an $800 range during the time period studied, with fares at their lowest in January and at their highest around March. Mostly fares hovered between $2,000 and $2,500 during the time period studied.
-	The weekly total fares in Suburban areas fluctuated in a slightly narrower range of around $700. Fares were also at their lowest in January and peaked heading into March and then into May. Weekly fare totals mostly hovered around $1,000.
-	In Rural areas, prices hovered in a much narrower range with prices peaking in early April near $500 and their lows in January and February near or under $100. Prices never surpassed $500 during the time frame studied.  

## Summary 
After analyzing the data we were provided, we can make the following recommendations to V. Isualize and the Pyber board with the caveat that additional information (including any data that would indicate that demand isn’t being met for each city type such as canceled trips or long wait times) would allow for more detailed suggestions that would help Pyber meet its goal of providing service to underserved areas. 

-	Urban areas likely have fewer personal automobiles per household and so increasing drivers in this market would be idea. The revenues are the largest and the number of rides would warrant increased drivers, although current drivers might balk at having the average fare per driver decrease so some additional compensation measures might need to be implemented to keep drivers happy and riders' demand met.
-	Suburban city performance is healthy, but increased marketing resources could be put in this demographic for people traveling into urban areas for recreation or work, which would drive up the average per driver fares with minimal impact on average fares per ride. This seems like an area where revenues could improve.
-	The strongest recommendations we could make to V. Isualize and Pyber given that one of their stated goals is to improve service in underserved areas is to increase the drivers in rural areas. While the average fare per ride is higher than either Suburban or Urban areas, it’s within $10 and could reflect increased distances traveled to reach destinations. However, that the average fare per driver is notably higher than Urban and, to a slightly lesser extent, Suburban drivers indicates a shortage and that demand is not being met.  
