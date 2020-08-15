# pyber_analysis
Analyze all the rideshare data from January to early May of 2019 for PyBer, a ride-sharing app company.

DELETE REFERENCES
![PyBer Fare Summary chart](https://github.com/timbannock/pyber_analysis/blob/master/analysis/PyBer_fare_summary.png)
![PyBer Summary By Type table](https://github.com/timbannock/pyber_analysis/blob/master/analysis/PyBer_Summary_by_Type.PNG)


Use your repository README file to write your analysis of how to address any disparities in the ride-sharing data among the city types.

The analysis should contain the following:

Overview of the analysis: Explain the purpose of the new analysis.
Results: Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.
Summary: Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.
END REFERENCES

## Overview
Summarize PyBer data by city type (rural, suburban, and urban) and then summarize how those differences can be used by PyBer going forward.

## Results
The line chart shows us that the demand for PyBer seems to follow similar trends throughout time, as rural, suburban, and urban fares all see the same general spikes over time, with only minor variation.

![PyBer Fare Summary chart](https://github.com/timbannock/pyber_analysis/blob/master/analysis/PyBer_fare_summary.png)

However, the total fares clearly (and logically) favor more populous areas by a significant amount: there's a big difference from rural to suburban total fares, and again (and even more so) from suburban to urban cities.

When we look at the summary table, we see how these numbers play out across several other factors, including the numbers of rides, drivers, as well as averages for fares per ride and fares per driver. There are significantly more rides and thus income from fares in urban environments (by over 20x from rural to urban cities!), but the fares per ride dip and the fare per driver sees a significant decrease (urban drivers make barely 20% of what rural drivers make per fare).

![PyBer Summary By Type table](https://github.com/timbannock/pyber_analysis/blob/master/analysis/PyBer_Summary_by_Type.PNG)

## Summary
Three business recommendations for addressing any disparities among city types might include:

1. Urban cities experience slightly more volatility in early March than rural and suburban cities do. Additionally, suburban cities saw a larger upward trend in April while both urban and rural cities dropped. Both of these situations seem worthy of further analysis to understand the full context of what's happening during these time periods.

2. Urban areas represent a great opportunity to experiment with changing how drivers are hired and paid. One example might include restricting hiring more, so there are less drivers, but still enough to meet demand, so that divers earn more fare per ride, and fares per driver increase.

3. Rural fares per ride are high enough that efforts to increase the total rides might have significant impacts even if the increases are incremental. 