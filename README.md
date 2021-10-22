# Kickstarting with Excel

## Overview of Project

### Purpose
Louise, a playwright, has asked us to assist in her in analysis before she launches a crowd funding campaign for her play “Fever”. Her current estimated budget is over 10000. We have data from a variety of Kickstarter campaigns to see trends in what is successful and what has failed. She is also interested in the data for future projects as well. 
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
In our analysis, we first needed to separate the subcategories from the parent categories so that we can look specifically at the category of theater that Louis is interested. We also needed to convert the Unix timestamp to a readable date. We did this by using: =(((J2/60)/60)/24)+DATE(1970,1,1). Once the data was in a useable form, we were able to create a Pivot table and line chart looking at the Outcomes of the Theater campaign based on the month the campaign was launched. As shown below. 

<img width="329" alt="Outcome_by_date_pivot" src="https://user-images.githubusercontent.com/90511014/138529945-068464cb-78fc-46af-8558-0c4ad25523ad.png">

![Theater_Outcome_vs_Launch](https://user-images.githubusercontent.com/90511014/138529928-c9706de5-fd30-4b93-b16f-4a8ebe3cebef.png)

### Analysis of Outcomes Based on Goals
As part of the analysis based on the goals, we determined the descriptive statistics of both the goal and pledged amounts for successful and failed US campaigns in the category of play. These statistics are below. Next, using the count function, we created a chart based on the number of each outcome in $5000 ranges. From this we determined the percentage of each outcome from each range.  We then created a line chart that visualizes the relationship between these outcomes and the goal range as shown below. 

<img width="238" alt="Descriptive_Statistics" src="https://user-images.githubusercontent.com/90511014/138532036-aabc8403-6b15-417a-a367-ab5526d4e56d.png">

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/90511014/138532041-6a3f8ce2-0b1e-4b2b-a3aa-2f5c3a074360.png)

### Challenges and Difficulties Encountered
The main challenge encountered is the possibility of other confounding variables that we are not currently accounting for. However, we drew conclusions based on the data provided and provided recommendations to reflect this knowing there may not be a causal relationship.  





