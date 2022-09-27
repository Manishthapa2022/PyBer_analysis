# **PyBer Analysis**

## Overview of the analysis

In this module, we are are expected to use our knowledge of Pandas and Matplotlib and Python skills to produce the following deliverables:
* Create a summary DataFrame of the ride-sharing data by city type
* Create a a multiple line graph that shows the total weekly fares for each type city type
 
For this, we have been provided with two files namely city_data.csv and ride_data.csv, which have been stored in the resource folder. 
~~~python 
pyber_data_df = pd.merge(ride_data_df, city_data_df, how="left", on=["city", "city"])
~~~
Using the code above, the two files were merged annd analysis was carried out to understand the variations and similiarties between the data provided for Rural, Suburban and Urban communities. 

## Results
Based on the detailed analysis the following results were obtained:
---
![Summary DataFrame](https://github.com/Manishthapa2022/PyBer_analysis/blob/main/analysis/PyBer_Summary.png)
---
With reference to the above table, it can be seen that there was overwhelming high number of drivers in Urban areas (2405) as compared to Suburban (490) and Rural areas (78). Correspondingly, this resulted in high total fares for Urban areas ($ 39,854.38) which is approx 9.21 times as compared to Rural areas ($ 4,327.93) and approx 2 times when compared to Suburban areas ($ 19,356.33).
When the average fare per ride and average fare per driver is taken into account there is major contrast as the Rural drivers make more money per ride and as per Driver when compared to both Urban annd Suburban drivers. 
---
![](https://github.com/Manishthapa2022/PyBer_analysis/blob/main/analysis/PyBer_fare_summary.png)
---
Further analysis of the Multiple-line chart for city type on a weekly basis provides th following results:
* The lowest total fare for both Urban ($ 1,661.68) and Suburban ($ 721.60) cities can be seen for the month of Jan 2019. 
* For Urban cities, the peak months are Feb and March when the tatal fares have gone to approx. $ 2500. 


## Summary

