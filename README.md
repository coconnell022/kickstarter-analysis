# Kickstarting with Excel
An analysis of a Kickstarter fundraising campaign based on outcomes with respect to launch dates and goals set. 

## Overview of Project and Purpose
This project takes a look at a data set composed of thousands of Kickstarter fundraising campaigns across the world containing data regarding all aspects of the campaigns and their successes. Initially, Louise, an amateur play writer, wanted to know the best options for planning her Kickstarter campaign for her play *Fever* and if her budget and timeframe would set her up for success. Now the project will take a deeper look into different trends within the data. The purpose of this project is to analyze a dataset containing over 4000 past fundraising campaigns to discover needed insight for future campaigns; specifically, in relation to their fundraising time frame and initial goals. 

## Analysis and Challenges

In this project, an analysis was performed on a large data set to determine trends across different types of fundraising campaigns. The analysis was performed using excel and its data analysis tools like pivot tables, charts, filtering, and formulas. 
The following functions were used from excel to aid in the analysis.
- YEAR () 
- COUNTIFS ()
- SUM ()

### Analysis of Outcomes Based on Launch Date

For the first analysis, a pivot table was used to determine the different outcomes possible based on month of the year. A formula was generated prior to the pivot table to determine the year for the start date of each campaign. The year function and column in excel allowed the pivot table to sort the data by months in order to get a concise snapshot of all years of data consolidated into one table. After the pivot table was filtered for the theater category and the outcome of the campaign, the pivot line chart was able to be generated. This chart is based on the pivot table and shows a visual representation of all theater fundraising campaigns outcomes based on their launch date. See attached for tables and charts referenced. 

![alt text](https://github.com/coconnell022/kickstarter-analysis/blob/master/Analysis%202.png?raw=true)
![alt text](https://github.com/coconnell022/kickstarter-analysis/blob/master/Theater_Outcomes_vs_Launch.png?raw=true)

### Analysis of Outcomes Based on Goals

The second analysis used different excel functions generated into a simple table to determine the outcomes for plays based on goals. The "countifs" formula in excel was used to populate the number of successful, failed, and canceled campaigns for plays based on the set ranges. After determining the number of outcomes based on goals, I found a percentage out of the total for that specific goal range. This table was then able to be used to generate a simple line chart that shows the outcomes for the play based on the various goals. See attached for tables and charts referenced. 

![alt text](https://github.com/coconnell022/kickstarter-analysis/blob/master/Analysis%201.png?raw=true)
![alt text](https://github.com/coconnell022/kickstarter-analysis/blob/master/Outcomes_vs_Goals.png?raw=true)

### Challenges and Difficulties Encountered

Various possible challenges could have occurred while performing this analysis. Since the data set is so large and contains upwards of 4000 files, there is a large room for error if a piece of data were to be labeled wrong, accidentally deleted, not calculated correctly, etc. I found that while performing this analysis there were a few small issues that I ran into that I was easily able to overcome after double checking my work. The first issue I encountered was when I was converting the start date and end date columns from timestamps to actual dates. I realized that in my initial calculations I missed over 1000 rows of data and left part of the date conversion columns blank. As I was generating the pivot table, I noticed that several categories had the years listed as 1900 which is excels default for a blank year function entry. I was then able to go back and correct my error and making sure that no columns were left blank in the initial Kickstarter worksheet. The second minor issue I ran into was accidentally deleting the plays filter for the formula in the "# of failed" column for the table in the 2nd analysis. I had noticed that the numbers were much larger than the other 2 columns and quickly fixed my error by editing the formula. 

## Results

1.	What are two conclusions you can draw about the Outcomes based on Launch Date?

One conclusion that can be drawn about the Outcomes based on Launch Date Analysis is that theater fundraising campaigns have a much higher rate of success during the months of April, May and June due to the significant peak on the line graph. Another conclusion that can be drawn from this data analysis is that during the month of October, there appears to be an almost equal number of successful and failed campaigns as well as no canceled campaigns. The number of failed campaigns also spiked during October compared to the surrounding months. It can be concluded that this is a less popular time of year for people to be interested in pledging donations for theater fundraising campaigns. A fundraiser that started at this time of the year would have about a 50% chance of meeting its goal, therefore compared to other months this would not be an optimal month to fundraise.  

2.	What can you conclude about the Outcomes based on Goals?

Based on the outcomes versus goals analysis, it would appear that as the fundraising goal increases, the less likely it will be successful. This could be for a few different reasons, one of which being that if a fundraising goal is smaller it would simply take less money for it to be met. It would also seem that there is a significant number of play fundraising campaigns with a goal of less than $5000 compared to those with goals above. Based on the analysis, most plays can operate within a budget of $5000 and have a better success rate for meeting that goal. 

3.	What are some limitations of this dataset?

One limitation of this dataset is the lack of specifics in each subcategory. I think there could be different results for a subcategory like plays, depending on the genre, popularity, timeframe, etc. Another limitation is not knowing the specific location within countries. Within the United States there are several major cities that all have different types of theater that would significantly impact the outcomes for successful plays. Additionally, another limitation on this dataset is the timeframe in which the data was recorded. The current dataset only looks at Kickstarter campaigns from 2009 to 2017 and while this provides helpful insight, it would be more accurate if there was a longer time period for the scope of data. 


4.	What are some other possible tables and/or graphs that we could create?

I think it could also be helpful to look into the average donation for specific fundraising campaigns to get better insight into how individual successful plays were funded.  This sort of insight could help determine what type of people and demographic should be targeted in order to have an extremely successful campaign. 
