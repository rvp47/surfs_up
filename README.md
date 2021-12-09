# surfs_up

## Overview of the analysis

This analysis explores temperatures trends in Oahu to help determine if the surf and ice cream shop business would be sustainable year-round. It looks at the differences in weather between June and December using Python, Pandas functions and methods, and SQLAlchemy. The analysis involves retrieving temperature data, converting them to lists, creating DataFrames, and generating summary statistics for the months of June and December. At the end of this analysis, recommendations will be provided for further analysis.

## Results 

- The first immediate difference was in the number of times the temperature was taken during each month. June had 183 more counts, which may impact the accuracy of the summary statistics for the month. 
- The lower temperatures showed the biggest diffience as June had a low of 64°F and December had a low of 56°F. 
- There was slightly higher variability (based on standard deviation) in the month of December. 

#### June Summary Statistics

![june summary statistics](https://user-images.githubusercontent.com/90656004/145335246-922cc337-b83d-48ed-9878-be35de7b4783.PNG)

#### December Summary Statistics

![december summary statistics](https://user-images.githubusercontent.com/90656004/145335240-5d6902e7-d540-4397-8e69-fd4e372d1eba.PNG)


## Summary
Overall, there is not a substantial difference between the weather in June and December. The highest, lowest, and average temperatures are similar enough to be able to assume that the surf and ice cream shop would be successful no matter the season in Oahu.

Further analysis can involve looking at other weather conditions like precipitation and humidity in June and December. Both weather conditions can have an impact on whether potential customers will want to venture out and then patronize this shop. It would be interesting to see which month has higher humidity, which has more precipitation and then compare that to the temperature. Perhaps these additional queries would get more insight about how weather may affect the surf and ice cream shop's sustainabiltiy and success.
