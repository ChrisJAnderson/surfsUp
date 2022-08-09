# surfsUp
## Overview
This analysis uses an SQLite database read through python's SQLalchemy plugin to generate and draw conclusions from summary statistics.
We analyze two datasets of temperatures from June and December recorded in Oahu over several years to produce these statistics.
The purpose of this analysis is to establish the viablility of a year-round surf shop and ice cream business in Hawaii.
## Results
![December's summary stats](https://github.com/ChrisJAnderson/surfsUp/blob/main/images/dectempSummaryStats.png)  
![June's summary stats](https://github.com/ChrisJAnderson/surfsUp/blob/main/images/junetempSummaryStats.png)  
*The first difference we can see between December and June's summary statistics is a that december is slightly colder overall, with lower numbers in the 25%, 50%, and 75% quartile measures.  
*There is also a difference in our average temperature, but it's slight- december still boasts an average temperature of 71 degrees versus june's 75 degrees.  
*Finally, we can see a difference in the consistency of the temperatures from day-to-day in December versus in June. The std dev is higher for december, and our data encompasses a slightly wider ranger between the quartile measures- a difference of five degrees in december versus four degrees in june. The range of temperatures in December is also wider- a difference of 27 degrees between the max and min temperatures in december versus 21 degrees in june.  
## Summary
Overall the data shows us that a year-round surf shop/ice cream shop in Oahu is likely feasible. Although December tends to be colder and more unpredictable overall, we still see an average temperature of over 70 degrees, and can see that the majority of our temperatures fall between 69 to 74 degrees throughout the month- still fine weather for surfing and icecream. 
Two more queries I would like to perform to gather more data about the feasibility of a year-round surf shop are summary statistics for precipitation in december, our coldest month (and also near the beginning of Hawaii's rainy seasons) as well as a query to obtain precipitation data from march, the end of the rainy season and one of the wettest months of the year, to see if it's likely that extensive rain will pose a danger for the operation of our surf shop during the rainy season. 
