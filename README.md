# **PyBer Analysis**

## Overview of the analysis

In this module, we are are expected to use our knowledge of Pandas and Matplotlib and Python skills to produce the following deliverables:
* Create a summary DataFrame of the ride-sharing data by city type
* Create a a multiple line graph that shows the total weekly fares for each city type
 
For this, we have been provided with two files namely city_data.csv and ride_data.csv, which have been stored in the resource folder. 
~~~python 
pyber_data_df = pd.merge(ride_data_df, city_data_df, how="left", on=["city", "city"])
~~~
Using the code above, the two files were merged annd analysis was carried out to understand the variations and similiarties between the data provided for Rural, Suburban and Urban communities. 

## Results
Based on the detailed analysis the following results were obtained:

![Summary DataFrame](https://github.com/Manishthapa2022/PyBer_analysis/blob/main/analysis/PyBer_Summary.png)
---
With reference to the above table, it can be seen that there was overwhelming high number of drivers in Urban areas (2405) as compared to Suburban (490) and Rural areas (78). Correspondingly, this resulted in high total fares for Urban areas ($ 39,854.38) which is approx 9.21 times as compared to Rural areas ($ 4,327.93) and approx 2 times when compared to Suburban areas ($ 19,356.33)
When the average fare per ride and average fare per driver is taken into account there is major contrast as the Rural drivers make more money per ride and as per Driver when compared to both Urban annd Suburban drivers. 

![Multiple city chart](https://github.com/Manishthapa2022/PyBer_analysis/blob/main/analysis/PyBer_fare_summary.png)
---
A Data frame was further created from from 1st Jan 2019 to 28th April 2019 and this was furrther divided into weekly bin to show sum of fares for each week based on city types. A Multiple-line chart provided the following insights:
* The lowest total weekly fare for both Urban ($ 1,661.68) and Suburban ($ 721.60) cities can be seen in the month of Jan 2019. 
* For Urban cities, the peak weeks are in Feb and March when the tatal fares have gone to approx. $ 2500, whereas for the Suburban areas, it can be seen that the highest weekly total fare was achieved for the month of Feb at approx. $ 1,400. 
* Overall, it can been seen that the overall weekly fares were the highest for the Urban cities as compared to Suburban and Rural areas. For Rural areas, the business was not able to gathr muc pace and total weekly fares were marginal riding along the $ 200 to $ 300 weekly mark. 

## Summary
 Based on the above analysis the following recommendations can be made:
 * The Rural areas did not fair that well as compared to Urban and SubUrban areas. This could be beacuse of the several reasons such as the lack of knowledge, and less number of cars which resulted in low total weekly fares and high fare per ride and also per driver. More advertising campaigns can be launched to make the Rural residents aware of the Ride sharing app and the benefits that can be achieved from it. 
 * Wth respect to Rural areas the high fare per ride and per driver could also be attributed to long travel distances as generally, the population is more spread out. Information regarding the average ditance travelled and the total distance travlled per ride could help bridge the gap and help provide better analysis. Incase if the diistances are more, then providing discounts.coupons on completing a certain amount of rides or teaming up with local supermarkets or shops to provide better offers could help increase the revenue.
 * We are not aware whether the cities (Urban, Suburban and Rural) that have been selected in the survey are within the same or differennt province. It could be that the fuel prices could vary resulting in high fare per ride or per driver. If this is the case, then collaborating with some fuel stations to provide discounted rates for the Ride share drivers could help and reduce the overall fuel costs.  
 * Pirticularly inccase of urban areas, the demand is vry high and further incentives could be offered to both the customers and drivers to use the app, thereby creating more revenue options. 

