# Computer game industry analysis
This is the first integrated project of the Practicum DA/DS course, combining Data Preprocessing, EDA and SDA sprints.

## Description
Here we have a small dataset of various data on video games collected from open sources. We want to identify patterns that determine whether a game succeeds or not. They would allow us to spot potential big winners and plan advertising campaigns.

First, we should do some data preprocessing: fill in the missing values, clean spelling errors, and change data types. Also, we need to add some new columns to help our analysis. After doing so, we could explore our data and test hypotheses. 

## Conclusion
After preprocessing, I calculate each game's total sales across all regions.

For the first step of the analysis, I looked at the game number and total_sales for the platforms across time. We could see that consoles have a limited lifespan, so we should consider only the eighth generation of consoles (PS4, XOne, 3DS, PC, WiiU, and PSV) and PC to be potentially profitable. And, of course, do not forget about the Nintendo Switch that will be released in 2017.

We don't see any apparent correlation between Users' or Critics' scores and game sales.

The most profitable genres are Action, Shooter, Sports, and Role-Playing.

Comparing different regions, we could see that North America and European Union users behave similarly, while Japan market is different in most profitable platforms, genres and ratings.

And finally, I tested two hypotheses and found that average user scores for Xbox One and PC are equal. At the same time, there is a statistically significant difference in average user scores for the Action and Sports genres. 
