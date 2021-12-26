# Kickstarting with Excel

## Overview of Project
This kickstarter data provides outcomes based on the various types of programs being funded.  We are specifically looking an analysis of Theater funding outcomes by launch date and the outcomes based on the goal amount.
### Purpose
The kickstarter data will help Louise understand if there are months that are more successful than others for certain kickstarters, specifically for Theater, in this example.  We will also have a better understanding of what the sweet spot would be for a goal amount and what will be the most successful estimate to try and obtain.  Louise can use the data to determine how aggressive to be with goal setting by seeing which goal amounts are most likely to end in success.
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
There appears to be evidence that there are a higher number of successful outcomes that string together in the months of April through August.  This could indicate that theater is more likely to be successful in warmer months.  It's also noted in the data that the number of failed outcomes tends to stay fairly constent with a slight uptick as more kickstarters take place in the warmer months, however, the number of successful outcomes still outpaces the failures.
### Analysis of Outcomes Based on Goals
The vast majority of kickstarters had a goal range of less than $100, $1000 to $4999, and $5000 to $9999.  Of those three ranges, there was more success the lower the goal amount, with 76% successful in the less than $1000 bucket, and 73% successful in the $1000 to $4999 bucket.  It is also noted that there was a high failure rate in the top two buckets with 100% of outcomes failing in the $45000 to $49999 bucket, and 83% failure in the greater than 50000 bucket.  It's worth noting that no project was canceled.
### Challenges and Difficulties Encountered
In the theater outcomes by month, it's tough to understand where the theater might be taking place.  The assumption is that theater is more successful in warmer months, but if the geographical location is in the southern states where the climate is warm all year round, it makes it tough to consider what the driving factor is for the 5 month stretch that is most successful.

In the outcomes based on goals, there is a very small amount of kickstarter that had goals of greater than $25000, which is not a good sample size to work with to make any strong statements of what could be causing the issues.  Also, no kickstarters were canceled, so it's worth asking why we would analyze that data only to see there is nothing to review.
## Results
![This is an image](https://github.com/barrettben/Kickstarter-Analysis/blob/11169e78003e98476cc12d4a611c9105e272085d/Theater_Outcomes_vs_Launch.png)
- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. It is better to do a kickstarter in the months of April through August to have the most likelyhood of being successful
2. There is a small chance that the kickstarter will get canceled
![This is an image](https://github.com/barrettben/Kickstarter-Analysis/blob/11169e78003e98476cc12d4a611c9105e272085d/Outcomes_vs_Goals.png)
- What can you conclude about the Outcomes based on Goals?
1. There is not enough data for goal ranges above $25000 to provide confidence in the success rate.
2. The ranges of less than $1000 and $1000 to $4999 seem to be the best ranges to assure a highest probability of success
- What are some limitations of this dataset?
1. Region of data is unknown to understand is any data is seasonal based.  The data shows country, but we do know know climate based on the region of those countries.
2. Marketing budget is unknown
3. Marketing methods are unknown
4. Number of staff dedicated to each kickstarter is unknown
- What are some other possible tables and/or graphs that we could create?
1. Comparison by country would be helpful to know if the kickstarters were providing different outcomes by countrys when compared side by side
2. Average duration of each kickstarter to help understand if there is a sweet spot for how long a kickstarter should be by goal range
