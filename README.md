# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this analysis is to show Louise how her play Kickstarter campaigns performed in relation to their launch dates and funding goals. We want to see if the launch date and the funding goal effected whether the campaign was successful, failed, or was canceled. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The Analysis of Outcomes Based on Launch Date was performed by creating a pivot table and using this pivot table to create a line chart to show whether the month of the launch date effected the outcome of the campaign. I organized the pivot table to show how many campaigns were successful, how many failed, and how many were canceled in relation to every calendar month. To do this I filtered by the parent category, "theater" and "years". I had to create a column for years in the Kickstarter tab using the =YEAR() function in excel. I put the "outcomes" in columns and the "date created conversion" in the rows of the pivot table. I had to group the rows to change the "date created conversion" to show only the applicable month. Please see my pivot table here: ![Pivot Table Screenshot](/Resources/Pivot_Table_Screenshot.png) 

Once I finished creating my pivot table, I inserted a line graph with the months of the year on the x-axis and the amount of successful campaigns on the y-axis. Please see my line chart here: ![Outcomes vs. Goals Line Chart](/Resources/Outcomes_vs_Goals.png)

### Analysis of Outcomes Based on Goals
The Analysis of Outcomes Based on Goals was performed by creating a table using the =COUNTIFS() function in excel. Please see my table here: ![Outcomes Based on Goals Table](/Resources/Outcomes_Based_On_Goals_Table.png). 

I used the =COUNTIFS() function because I wanted to only count the data that was applicable. For instance, I only wanted to count the data that was in the play subcategory. I also wanted to count the data according to the outcome and the funding goal. I then used the =SUM() function in excel to get the total amount of projects. Using all of this information, I was able to get the percentage of successful Kickstarter campaigns, the percentage of failed Kickstarter campaigns, and the percentage of canceled Kickstarter campaigns. I used the goal column, the percentage successful column, the percentage failed column, and the percentage canceled column to create a line graph. Please see my line graph here: ![Outcomes vs Goals Line Graph](/Resources/Outcomes_vs_Goals.png). 

### Challenges and Difficulties Encountered
Grouping the rows according to the month was the greatest challenge I faced when performing this analysis as this is a function that is new to me. I overcame this difficulty by performing research on how to group these items. I see how helpful this function is as it paints a better picture of how the launch date month effected the amount of successful or failed campaigns.

## Results

### Conclusions for Outcomes based on Launch Date
The pivot table and line graph that I created allow us to understand whether the launch date effects the outcome of the campaign. For instance, the line graph and pivot table show us that the campaigns with launch dates in May and June had the most successful outcomes. There were significantly more successful outcomes than failed outcomes in these months in relation to the other months in the calendar year. I can therefore draw the conclusion that May and June are the best months to launch a crowd-funding campaign for plays. The second conclusion that I can draw from this analysis is that December is the worst month to launch a kickstarter campaign. In December, there were about the same amount of failed Kickstarter campaigns as there were successful ones. This is the only month in the calendar year where these two outcomes are virtually the same. Therefore, I would advise Louise not to launch a Kickstarter campaign in the month of December. These two conclusions are very helpful to Louise because in the future she can launch her kickstarter campaigns during the more successful periods and avoid launching a campaign during December. 

### Conclusions for Outcomes based on Goals
The table and line graph I created show me that campaigns with a funding goal of over $45,000 are much more likely to fail. I can see this in the line graph as well as the table that I created. Therefore, I would advise Louse to keep her campaign goals under $45,000.

### Limitations of the Dataset
This dataset does not include information that could have had a large effect on the outcome of the campaign. A major factor that could have impacted the outcome of the campaign includes how this kickstarter was shared and how many people had visibility to this campaign. For instance, if Louise did a lot of marketing on her Kickstarter campaigns during the months of May and June, that could explain why those months had more successful outcomes. This limited data only shows a small picture of why these campaigns were successful or why they failed. Although it looks like the launch dates and the goals played a role in the success of these campaigns, other information would be important to validate this claim because we cannot assume that the campaigns were identical except for their launch dates and funding goals. 

### Other Graph Possibilities
One graph we could create is outcome based on number of backers. This would be interesting as we could see whether the amount of backers was positively correlated with the success of the campaign. If it was, then we could advise Louise to try to seek out a larger audience for her Kickstarter campaigns. A second graph we could create is average donation based on the Kickstarter goal. This would help us to understand if the goal effected the average amount of money donated. For instance, if the goal was small, would this cause people to donate less money? 
