# Module 5 - PyBer Analysis

## Overview of PyBer Analysis

#### This PyBer Analysis had two deliverables.

#### In Deliverable 1 we were to create a Data Summary that broke down each city type (Rural, Suburban, Urban) displaying Total Rides, Total Drivers, Total Fair, Avg Fare/Ride, Avg Far/Driver. This consisted largely of using the groupby function to create DataFrames, then creating a summary DataFrame that was formatted to show dollar amounts for certain columns

#### In Deliverable 2 we worked to create a final line chart that displayed the Total city fare by city type per week. To do this we needed to group data the with groupby function with multiple incies. This allowed us to report on each city type for each date. Then we displayed that data for a specific time line and turned it into a pivot. Finally taking that data and create a line chart through object-oriented interface method

## PyBer Analysis Results

### Deliverable 1
#### From the DataFrame summary we were that Urban has the most business in term of rides and drivers, followed by Suburban and Rural. Average Fare per Ride and Driver showed the opposite. With Rural having the most expensive rides and the largest fare per driver. Likely duo to simple economics as there is less supply for the rural cities, so they can charge a higher rate. 
#
![stacked_launch_outcomes](https://github.com/charlieburd/PyBer_Analysis/blob/main/analysis/pyber_summary_df.png)
#

### Deliverable 2
#### From the Total Fare by City Type we can confirm the analysis from Deliverable 1, Urban does bring in the largest Fare Totals week over week, followed by Suburban and Rural. But we can also analyze how those shares change each week. For example, in the 3rd week of Feb we see a big spike is fare totals among all city types, spikes like these can sometimes be attributed to holidays or current events. But also in the 2nd week of Jan we see Urban fare total dip, while Suburban and Rural fare totals increased. Overall, fare total remained quite consistent over the timeline analyzed, there were not a major seasonal trend, if we looked at a larger timeline we may see something like this. 
#
![stacked_launch_outcomes](https://github.com/charlieburd/PyBer_Analysis/blob/main/analysis/weekly_fare_df.png)
#


## PyBer Analysis Summary:
#### In the last reported week, almost the last week in May we see Suburban will a very large increase in fare total. Both Urban and Rural have decrease in fare total. This is odd because Suburban usually mimics either two or one other city type. I would guess this is because there are similarities between Suburban and Urban as well as Suburban and Rural, there is less similarities between Urban and Rural. This would be a point to watch. This week wouldn't be considered an outlier, it could be that PyBer is investing in their Suburban cities, but it is unusual.

#### It seems a bit odd there would be such a large difference in Avg Fare per Driver between Rural and Urban. Drivers make much more in rural cities. It could be worth it for PyBer to recommend to drivers that more rural cities could result in them making more money if they are willing to drive over to them.

#### Considering there are 1.27 rides per driver in Suburban and only 0.67 rides per driver in Urban cities I would consider riders luckily to only 20% more per a ride. If PyBer wanted to increase their profit they could charge more per a ride in that city type.
