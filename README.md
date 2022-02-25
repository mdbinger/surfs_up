# Surf's Up Challenge
### Module 9 of Data Analytics Bootcamp

## Overview
We are hoping to start a new business in Hawaii that rents and sells surf equipment and ice cream. We have been in contact with a potential investor, W. Avy, and he is ready to invest! However, W. Avy needs to get his investment team onboard with the investment as well. We have been asked to provide W. Avy with summary statistics about the weather in Hawaii. Specifically, W. Avy would like summary statistics on the temperatures in Hawaii for the months of June and December. We used a combination of python (with a variety of dependencies imported) and sqlite to complete this analysis.



## Results
#### Provide a bulleted list with three major points from the two analysis deliverables. Use images as support where needed

- The mean temperature in June is about 75 degrees, while the mean temperature in December is about 71 degrees. This suggests that the temperature in Hawaii is consistent throughout the year, which is great news for our potential shop!
- The maximum temperatures from the June and December data are 85 degrees and 83 degrees, respectively. This is also great news for our potential shop, as again this suggests that the typical high temperature in Hawaii is going to be around the mid-80s all year.
- The minimum temperatures from the June and December data are 64 degrees and 56 degrees, respectively. Although this is not a huge concern, this is the first somewhat considerable difference we have noticed in temperature data. 56 degrees is noticeably colder than 64 degrees, but still not cold enough for us to believe our shop will not be successful, especially considering minimum temperatures are typically reached in the early morning. 

/Users/michaelbinger/Documents/Bootcamp/Module_9/Challenge/June_Summary_Stats.png
/Users/michaelbinger/Documents/Bootcamp/Module_9/Challenge/December_Summary_Stats.png

## Summary
#### Provide a high-level summary of the results 

There isn't much to be concerned about in regard to opening our surf and ice cream shop based upon the temperature data in Hawaii for June and December. As stated in our results section, the weather in Hawaii appears to be consistent all year. This is demonstrated by June and December temperature summary statistics being relatively close to each other. The maximum temperature from our June data was only two degrees higher than December, which is effectively the same. 

Similarly, the average temperature in June is only four degrees warmer than December, which may be a noticeable difference, but not much. The only considerable difference was the minimum temperatures in December was eight degrees cooler than June. While eight degrees is typically a noticeable difference, this temperature was likely recorded during a time that our shop would not be open. 

Lastly, it is worth noting that our minimum temperature discrepancy between June and December may be the result of an outlier. We would need to perform more advanced statistical analyses to know for sure, but you can see from our summary statistics that our mean, 25th percentile, 50th percentile, and 75th percentile numbers for June and December all have a difference of about four degrees. All those summary statistics are dependent on the entire set of data, whereas the minimums are only one data point in each month. Therefore, it is likely there was just an untraditionally cold night sometime in the range of dates our data is from. 

#### Additional Analysis
and two additional queries that you would perform to gather more weather data for June and December

There could be some additional data we can analyze to feel even more comfortable with our decision to open a shop in Hawaii. It is great that our temperatures seem consistent all year, but below are two additional ideas we should consider before making a final decision.
- Precipitation averages: Rain has a big impact on surfing, and likely impacts people's desire to eat ice cream as well. I believe it would be beneficial to consider the average amount of rain that falls in June compared to December.
- Wind speeds: Wind can have a huge impact on the actual "feel" of temperature. A windy day can make a hot day feel nice, but it can also make a comfortable or cold day feel annoyingly cold. This isn't even mentioning wind's impact on surfing. It would be a good idea (if the data is available) to consider how windy Hawaii can get in the months of June and December in order to determine how often we truly will have great surfing and ice cream weather! My suggestion would be to look at average wind speeds and maximum wind speeds to get a feel for what we can expect.






