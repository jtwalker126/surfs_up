# Challenge Analysis
### Ojective
The goal of this analysis was to collect key statistical data on the weather in Oahu for different seasons. June and December were analyzed across all stations and all years to determine a representative dataset for summer and winter represectively.



### June
The statistical breakdown of recorded temperatures for the month of June from years 2010-2017 (the available years in the dataset) is as follows:
count	1700.000000;
mean	74.944118;
std	  3.257417;
min	  64.000000;
25%	  73.000000;
50%	  75.000000;
75%	  77.000000;
max 	85.000000.


### December
The statistical breakdown of recorded temperatures for the month of December from years 2010-2017 (the available years in the dataset) is below:
count	1517.000000;
mean	71.041529;
std	  3.745920;
min	  56.000000;
25%	  69.000000;
50%	  71.000000;
75%	  74.000000;
max	  83.000000.

### Analysis
Both datasets come from >1500 measurements over a range of 7 years and all observation stations and thus are likely good representative data of the weather in Oahu.  As expected, summer (June) is warmer than winter (December), but the difference is only about 3-4 degrees. The temperature appears to be slightly more predictable in the summer as the standard deviation is smaller (indicating less spread in the data). Analysis of the quartiles and the min/max suggests that the wider range in the winter is a result of a larger tail of cooler temperatures (vs. warmer temperatures). Thus, the business should know that there may be a few days in the winter that are substantially below the average temperature. However, even the minimum recorded temperature is still relatively warm and could still allow surfing and ice cream.

### Further Analysis
1. While this analysis looked at temperatures in Oahu and arlier analysis looked at precipitation levels here, a futher analysis could combine the two and look for correlations. Days that are both colder and usual and raining for example could interact to create even more unfavorable conditions for surfing and ice cream. 
2. Further analysis could also break down our seasonal analysis by the year. Since we are interested in projecting future earnings, trends in weather patterns (for example, if Oahu winters were getting warmer each year) would help us make informed decisions. 
3. Finally, we could break down our temperature tracking by observation station to determine if there is significant variability within Oahu on temperature (or precipitation). If so, this would be really helpful for us to know when picking our exact storefront location. We could also potentially exclude measurement stations if they were not helpful to us. For example, if there is a weather station on top of the nearby mountain. That weather data is very helpful in other contexts but could mislead investors about the temperature if it is significantly colder there than on the beach where the surfing and ice creaming will happen.
