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
 [SUMMARY DATAFRAME]()








# Summary

Based on the above analysis and results, the three business recommendations to address any disparities among the city types are as follows:

