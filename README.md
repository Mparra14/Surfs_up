# Surfs_up
## Overview 
In this project, we were tasked by an investor in Oahu, that would like more information on the weather for his investment decision. The investment is a surf shop that will also serve ice cream, but he is afraid that weather will affect the sales. He asked for a weather analysis for the months of June and December before he invests in the shop. We were given a Sqlite file to query over using SQLAlchemy and using Pandas methods to create a data frame and get statistical analysis for each month. 

## Results
Looking at the statistical data from both months the following can be seen:
For the month of June:
 * We see that the average temperature is 74.94 F°.
 * The highest temperature during this month is 85 F°.
 * The lowest temperature for this is month was 64 F°. These can be seen in the table below.
 
 ![Jun_temp](https://github.com/Mparra14/Surfs_up/blob/main/June_temp.png)
 
 For the month of December:
 * It's seen that the average temperature is 71 F°.
 * The highest temperature for this month is 83 F°.
 * The lowest temperature for this month is 56 F°. These results can be seen below. 
 
 ![Dec_temp](https://github.com/Mparra14/Surfs_up/blob/main/December_temp.png)
 
## Summary 
 With the statistics for each month, for both months’ temperatures only differ slightly, as the average temperature for December drops about 3 degrees when compared to the average temperature in June. It seems that the island has a relatively standard temperature year-round, considering we only looked at two months out of the whole year, but these results are based on seven years of data of the island. Therefore, if customers are willing to buy ice cream or surf in June, there shouldn't be a reason why they wouldn't on an average day in December. Even though temperature should be considered when looking at weather, there is another factor that also weighs in it, and that is rain. Even if the temperature is adequate for surfing or ice cream, that does not mean that rain will not affect sales. If it does rain, there will not be much surfing, so we should look at the precipitation statistics for both months. 

To look at the precipitation for each month, I decided to refactor the query to specify the precipitation column instead of the temperature. While using these new queries, the average precipitation in inches for the month of June is 0.136 while the precipitation for December is 0.216. Even though it does rain during these months, it is not significantly higher than normal. Considering the results, rain during these months shouldn't affect sales as much, while there are outliers in the data, those days will just have lesser sales. The statistics for the precipitation for both months can be seen below.

![Prec_june](https://github.com/Mparra14/Surfs_up/blob/main/precipitation_june.png)
![prec_dec](https://github.com/Mparra14/Surfs_up/blob/main/precipitation_dec.png)

