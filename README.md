# Kickstarting with Excel
## Overview of Project
Louise, an up-and-coming playwright, came to us because she wanted to start a crowdfunding campaign to help fund her play, *Fever*. She estimated a budget of over $10,000 and was understandably hesitant about jumping into her first fundraising campaign. Now Louise’s play Fever came close to its fundraising goal in a short amount of time, and she wants to know how different campaigns fared in relation to their launch dates and their funding goals.

Our purpose is to provide Louise a report with our analysis that explains how the outcome of campaigns could influence them based on their launch date and funding goals according to our dataset. The report will be explained with the support of charts to facilitate the visualization of the data.
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
To answer the question of how different campaigns fared in relation to their launch dates, we went to our dataset and used a pivot table to filter the theater campaigns, by the date we have as launch date, then filtered by the outcome, either successful, failed or canceled, and displayed the information by the month of launch.

Now with the pivot table, we created a chart for better visualization of the data that we can see below. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/113747210/193135797-5406600c-5abc-4c18-a65e-3e0bc5578175.png)
In the chart we can see a line for each outcome, yellow for canceled campaigns, a red line for the failed and a blue line for the successful campaigns. Every line has a marker according to the month in which the campaign was launched. 

Also, we can see with the numbers on the left side of our chart the approximate number of campaigns that were successful, canceled or failed in relation to their launch month, that is, the higher the score of a blue line is, means that there were more successful campaigns and at the bottom of the chart we can see which month it corresponds to. For example, May is the month of launch with the most successful campaigns.

We can also read from the chart that the month of launch with the most failed campaigns is between May and October and the less failed campaigns started on November, September, and January; but at the same time these last-mentioned months have a low percentage of success.

### Analysis of Outcomes Based on Goals

Now, regarding the question of how different campaigns fared in relation to their funding goals we created a chart to visualize the percentage of successful, failed, and canceled plays based on the funding goal amount. We defined dollar-amount ranges so projects can be grouped based on their goal amount. The ranges were as follows:

![Amount ranges](https://user-images.githubusercontent.com/113747210/193138088-ed2e3fcc-70f3-458a-a513-1b8b7afb69b6.png)

We calculated the number of campaigns that succeeded, failed, and were canceled according to the range of funding goal amount. Then, we calculated the percentage of successful, failed, and canceled projects also according to each range of funding goal we defined.

To visualize the data described above, we created the next chart:

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/113747210/193138316-1a602503-da30-4e8f-a39b-9cd57aac3f28.png)

The blue line of our chart represents percentage of the successful campaigns and the orange one the failed campaigns. What we can observe is that between 70-80 percent of campaigns with a funding goal amount up to 4,999 were successful, and as we saw the ones with goals from 5,000 to 29,999 the percentage goes down. 

Then we have an increase on successful campaigns that goes from 27% to 67% with funding goals between 30,000 to 44,999; and then again goes down to 13%.

The most successful campaigns are the ones with a funding goal below 4,999 and the ones between 35,000 and 44,999. But we have to take into account that the majority of the projects have a funding goal between 1 and 4,999 with 720 projects, and more than 70 percent were successful. While the campaigns that has a funding goal between 35,000 and 44,999 also have a 67 percent rate of success, but there were only 6 projects.

<img width="389" alt="Pivot_table_Screen_Shot" src="https://user-images.githubusercontent.com/113747210/193138929-d2c8b734-e8d6-464e-a0da-893b2d91a075.png">

Later we will draw our conclusion of what the data described above can tell us about Louise’s questions. 

### Challenges and Difficulties Encountered

For now, I would like to mention some challenges that we may encounter when analyzing the data or how we must prepare the data set in such a way that we can visualize and obtain what we are looking for. 

For example, this data set provides us with campaign launch dates in a format that we cannot read, therefore it is necessary to convert it to a format that we know how to read and that excel allows us to use it in our formulas. 

Also, it is necessary to check that the formats of the columns are properly assigned, for instance that quantities are not read as text. 

## Results

-	**Theater Outcomes by Launch Date**

The largest number of successful campaigns were started in the months of May, June, and July and those with the highest percentage of failed campaigns were started in October, and in the months of May, June and July, which is where the bulk of launched campaigns are. 
The months with the highest number of launched campaigns are also May, June, July, which have a good percentage of successful campaigns, above 80%, although it is important to note that they have a high number of failed campaigns. Therefore, we could say the best month to start a campaign would be June, with a better balance between those that were successful and those that were not.

Also, during the months of November, December and January are the least recommended to start a campaign since they have the lowest percentages of success and high number of failed campaigns.

-	**Outcomes based on Goals**

If our goal is around 5,000 dollars or less, we have greater chances of success, because above 70% of the campaigns have succeeded. Also, in this range of funding goal amount are most of the campaigns, we have 720 projects in which 73 percent were successful. Therefore, the amount recommended as funding goal could be between 1,000 and 4,999 dollars.

-	**Limitations of this dataset**

The limitations could be the sample size, we're not sure it's enough or if it's the one that's available given the nature of what we're looking at. Likewise, the information could be more specific in terms of backers, in order to identify if there is any trend there or if it only depends on the country where it is carried out, because according to the culture of each country the preferences will vary and therefore what type of campaigns will be more successful.

-	**Possible tables and/or graphs that we could create**

I would create a graph that shows the total number of projects started per month in two bars that differentiate the successful and failed projects to appreciate the difference, and also with the projects according to the target amount to be raised. The reference data here would be how many campaigns were launched (differentiating by colors) and by the outcome (successful or failed).

