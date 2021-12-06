# Module_9-surfs_up

# Overview

The purpose of this analysis is to evaluate the year round sustainability of a surf/ice cream shop in Oahu by comparing temperatures during both June and December over the course of multiple years.

# Results

The major point to be taken from the results of this analysis is that, at least judging by temperature, the surf shop in Oahu seems to be a viable year round business. Over multiple years, the average June temperature (74.94) barely differs from the average December temperature (71.04) in Oahu. As expected, June temperatures tend to be a bit higher, but overall the two months are far more similar than I would have expected.

There is a quite a wide range of recorded temperatures reported within each month, indicating that there may be some noteworthy fluctuations in temperature within a given month from day to day, week to week, or even year to year. This phenomena is a bit more prominent in December, where the standard deviation is 3.74 as opposed to 3.25 in June, both of which seem a bit large, though perhaps not for weather data, which may have frequent outliers. 

As one would expect, June on average is slightly warmer than December, although both months are quite warm. 50% of June temperatures fall between 73 and 77 degrees, while 50% of December temperatures fall between 69 and 74 degrees.

Below are the June and December summaries, respectively:

![Screenshot (92)](https://user-images.githubusercontent.com/91569387/144791528-a4908a2a-879e-428a-9949-977ed6a8ed5e.png)
![Screenshot (93)](https://user-images.githubusercontent.com/91569387/144791540-c8405b93-0d71-4f91-ad39-06ab32686759.png)

# Summary

Overall, the surf shop seems like a viable year round business given the warm temperatures in both June and December. Though the results of this query are likely representative of the whole, they may not provide enough information to fully determine the year round viability of the business. 

One further step I would take to develop a fuller understanding of the data would be to create either a bar or line graph to chart the average temperature of June and December of each year over the course of multiple years. This chart would aid in visualizing longer term temperature trends to answer such questions as "Is Oahu generally getting warmer or getting cooler?" and "How much variation is there in temperature from one year to the next?". Breaking down the summary statistics by year will help to determine the long term viability of the business by revleaing long term temperature trends, as opposed to the seasonal differences between June and December.

We could query additional meteorological factors for June and Decemeber in addition to temperature in order to develop a more comprehensive understanding of how the months and seasons compare to each other. These other factors could include precpiation, wind, and any other factors available in the SQLite file. We could also run this analysis on other months to fill in gaps and project which months may be more or less profitable.
