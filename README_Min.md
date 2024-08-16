Used the Kaggle Olympic_Games_Medal_Tally for the medal totals and then World Bank Group csv for GDP (https://data.worldbank.org/indicator/NY.GDP.MKTP.CD)
and Population (https://data.worldbank.org/indicator/SP.POP.TOTL).

You will see the steps in Jupyter Notebook where I had to fix multiple values with Russia.
In 1960 and 1980 Russian Federation was the Soviet Union.
In 2022 Russian Federation was banned from competing and had its athlehtes under the ROC.
1980 Olympics had East Germany which I changed to Germany.
There was no GDP data for Russian Federation for 1960 and 1980.
I used google searches fro the Soviet Union GDP for those years and added them in.  

Originally I plotted the GDP per capita/medals for 2022 Olympics.
I noticed the highest GDP per capita had a few medals and cross referenced to find out it was Bermuda.
I think not think GDP per capita was a good variable to used and switched to total GDP.  

I plotted the GDP data/medals for 2020, 2016, 2012, 2008, 2004 and found the data to be very similar.
There about 50-60 counteries near the bottom left corner of the plot.   
In those years, only 2 countries out of like 300 were above 20 medals.
I did not think this provide an interesting data points so I changed my analysis to 2020, 2000, 1980, and 1960.

I used the Xpert Learning Assitant to review the .isin feature to grab the data from 1960, 1980, 2000, 2020.

I left the 1980 Olympic Dataset to look at because its interesting but should be thrown out for analysis.
1980 Olympic was dominated by Russia because 65 countries (including USA and China) boycotted the Olympics.

I used the Xpert Learnign Assitant to review the nlargest/nsmallest function

I stated the limitations in the presentation
-assume all the data is correct, the 2000 Russia GDP looks like it could be wrong based on the data trends
-only looking at the countries who won medals
-not factoring athlethes who made it to the finals (only athlethes who won a medal)
-not factoring in countries who are cheating (drugs, corruption) or favortism.  

I believe GDP and population are both positve variables to the total medal count.  I believe GDP is a bigger
positive factor than Population from the Data.   There are companies who can win a medium - medium high level of medals
at an Olympic but the only the elite medal winners were top GDP countries and top population.   India was outlier to this
data but India is known to underfund their Olympics sports.   
