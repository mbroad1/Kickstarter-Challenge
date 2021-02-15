# Kickstarting with Excel
---
## Overview of Project
---
- Louise is a creative interested in meeting her fundraising goal for her play Fever. In order to do so, she wants to analyze different fundraising campaigns for plays based on their launch dates and funding goals using a Kickstarter dataset to assess the factors that make for a successful campaign.
---
### Purpose
---
- The purpose of this analysis is to find trends in the Kickstarter dataset related to plays that will ultimately aid Louise in planning her campaign to make it as successful as possible (aka, raise the most amount of money).
---
## Analysis and Challenges
---
- In order to plan a successful fundraising campaign for Louise's play, there are two important factors that can help: launch date and fundraising goal. By analyzing the trends in launch dates of successful, failed, and canceled campaigns, we can determine which month is the best month to launch a fundraising campaign. Likewise, there may be a difference in goal amount among successful, failed, and canceled campaigns, so knowing the most successful goal amount of money may help Louise in creating a practical (and successful) fundraising goal.
---
### Analysis of Outcomes Based on Launch Date
---
![Theater_Outcomes_vs_Launch](https://github.com/mbroad1/Kickstarter-Challenge/blob/main/Theater_Outcomes_vs_Launch.png)
---
- Looking at the Outcomes vs Launch Date - Theater Kickstarter graph, we can see that the most successful campaigns launch in May. Following May, in terms of success, are the months of June and July. Similarly, the greatest number of failed campaigns started in May (second greatest number is from October). However, the number of successful campaigns in May is double that of the number of failed campaigns in May, which leads me to believe that there are other factors that weigh more significantly in the failure than the launch date, but launch date is a significant factor in the success of a campaign.
---
- In terms of canceled campaigns, the number of canceled campaigns per month is relatively the same (January had the most with 7), so we can conclude that the launch date of a campaign does not determine whether it is canceled or not.
---
### Analysis of Outcomes Based on Goals
---
![Outcomes_vs_Goals](https://github.com/mbroad1/Kickstarter-Challenge/blob/main/Outcomes_vs_Goals.png)
---
- The percentage of successful campaigns and the percentage of failed campaigns based on fundraising goals are exactly opposite of each other; this makes sense considering there are no canceled campaigns that contribute to the total projects and thus do not influence the percentage calculations featured in the graph.
---
- The percentage of successful campaigns is greater than that of failed campaigns until $15000 to $19999 where they equal to one another.
---
- Campaigns greater than the $15000 to $19999 range and roughly less than the $35000 to $39999 range were mostly failed vs. successful (~70-80% of campaigns in that range failed vs ~20-30% of those campaigns succeeded in meeting their goals).
---
- Interestingly about 60-70% of campaigns that had a goal from $35000 to $39999 and $40000 to $44999 were successful.
---
- However, after $44999, 90-100% of campaigns fail to meet their fundraising goals.
---
### Challenges and Difficulties Encountered
---
- In terms of the challenges of this assignment, I was able to do all of the tasks easily. One problem that may occur is selecting the elements wanted for a pivot table – if one is unaware of the ability to filter what is wanted for the rows and columns of a pivot table, they may have more elements in the chart than needed.
---
- Another issue that may occur is with the COUNTIFS() function. Potentially, one could include the 1000 value in both the "less than 1000" and "1000-4999" so that plays that had a goal of 1000 would be included in both rows and thus would count plays who meet the criteria of both rows twice when summed for the total.
---
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
---
- Firstly, I can conclude that launch date does help in determining a successful campaign and that the majority of successful campaigns had a launch date in May. Secondly, launch date does not determine if a campaign fails as there are no clear trends as to which month has the most amount of failed campaigns; therefore, there must be other factors that determine if a campaign fails.
---
- What can you conclude about the Outcomes based on Goals?
---
- Campaigns with a fundraising goal of anywhere from less than $1000 to a range of $15000 to $19999, have a good likelihood of succeeding based on the fact that the majority of campaigns that had those fundraising goals were successful campaigns. Likewise, majority of campaigns with a fundraising goal from $35000 to $44999 were successful. However, campaigns that either had a goal from $20000 to $35000 or greater than $44999 typically failed which means that those fundraising goals are less likely to be met.
---
- What are some limitations of this dataset?
---
- This dataset does not have the fundraising information for every play ever made (it draws from a subset of that population), so the trends that we are analyzing in this dataset only reflect a subset of data and thus may not give the best picture of the data. Likewise, it may be more helpful to look at only plays that are in the same genre as Louise's Fever so that the fundraising campaign can be tailored to that specific type of play (e.g. raising money for a comedy show would be different than raising money for a tragedy).
---
- What are some other possible tables and/or graphs that we could create?
---
- We could redo the graphs featured in this assignment to only pertain to plays in the US if Louise plans to premiere and only perform her play in the US. We could also look to see the success of a fundraising campaign based on both the length of the campaign and the date it ended to see whether there is an ideal amount of time for a campaign.
