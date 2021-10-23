# Kickstarting with Excel

## Overview of Project

### Purpose
Louise, a playwright, has asked us to assist in her in analysis before she launches a crowd funding campaign for her play “Fever”. Her current estimated budget is over $10,000. We have data from a variety of Kickstarter campaigns to see trends in what is successful and what has failed. She is also interested in the data for future projects as well. 
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
In our analysis, we first needed to separate the subcategories from the parent categories so that we can look specifically at the category of theater that Louis is interested. We also needed to convert the Unix timestamp to a readable date. We did this by using: =(((J2/60)/60)/24)+DATE(1970,1,1). Once the data was in a useable form, we were able to create a Pivot table and line chart looking at the Outcomes of the Theater campaign based on the month the campaign was launched. As shown below. 

<img width="329" alt="Outcome_by_date_pivot" src="https://user-images.githubusercontent.com/90511014/138529945-068464cb-78fc-46af-8558-0c4ad25523ad.png">

![Theater_Outcome_vs_Launch](https://user-images.githubusercontent.com/90511014/138529928-c9706de5-fd30-4b93-b16f-4a8ebe3cebef.png)

### Analysis of Outcomes Based on Goals
As part of the analysis based on the goals, we determined the descriptive statistics of both the goal and pledged amounts for successful and failed US campaigns in the category of play. These statistics are below. Next, using the count function, we created a chart based on the number of each outcome in $5000 ranges. From this we determined the percentage of each outcome from each range.  We then created a line chart that visualizes the relationship between these outcomes and the goal range as shown below. 

<img width="238" alt="Descriptive_Statistics" src="https://user-images.githubusercontent.com/90511014/138532036-aabc8403-6b15-417a-a367-ab5526d4e56d.png">
<img width="714" alt="Goal_chart" src="https://user-images.githubusercontent.com/90511014/138540869-f2981a62-62cf-4086-b836-a56cc44051bb.png">


![Outcomes_vs_Goals](https://user-images.githubusercontent.com/90511014/138532041-6a3f8ce2-0b1e-4b2b-a3aa-2f5c3a074360.png)

### Challenges and Difficulties Encountered
The main challenge encountered is the possibility of other confounding variables that we are not currently accounting for. However, we drew conclusions based on the data provided and provided recommendations to reflect this knowing there may not be a causal relationship.  

## Results

### Results of Outcomes Based on Launch Date

Based on the data we can determine the best month to launch a successful Theater campaign is May. 
Although there are many failed theater campaigns that were launched in May, June, July, and October; May June and July still had a significant number of successful campaigns.  The worst month to launch a campaign in is December as there is the least number of successful campaigns while still maintaining an average number of failed campaigns. 
I would recommend that the next campaign is launched in in May if possible. I would also avoid Launching in October or December. 

### Results of Outcomes Based on Goals 
Based on the descriptive statistics there are large outliers that are skewing the data. This means that there were a few very large goals that varied significantly from the rest of the data. The most successful campaigns are those less than $5,000. Campaigns with a goal between $5,000 and $24,999 have a good likelihood of success ranging from 45% to 55% with a higher success at the lower goals. At $25,000 the success rate falls significantly. The percentage successful does increase again between $35,000 to $44,999 but this may be unrelated to the of the goal.
A Goal of $20,000 or less is recommended as at least have of Goals within this range were successful. 

### Limitations
For the Goal range of $35,000 to $44,999 there is an increase in the percentage successful from 20% and 27.3% for the previous two ranges of $25,000 to $29,999 and $30,000 to $34,999 respectively to 66.7%. From this I would conclude that the amount of the goal is not the only factor to consider and further research should be conducted to determine trends that could indicate why the $35,000 to $44,999 were successful and why the $25,000-$34,999 failed this data set does not specify what these trends can be. These factors could be the content of the play or even if the creator has had success before.  

### Considerations for future
Further analysis can be conducted with a graph that shows the relationship between whether the Kickstarter was a staff pick or a spotlight and the number of backers combined with the eventual outcome. It may also be interesting to determine if there is a relationship between number of backers and the amount pledged or to see if there was a difference in outcome based on the year launched. 









