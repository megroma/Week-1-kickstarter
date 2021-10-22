# Kickstarting with Excel

## Overview of Project

### Purpose
Louise, a playwright, has asked us to assist in her in analysis before she launches a crowd funding campaign for her play “Fever”. Her current estimated budget is over 10000. We have data from a variety of Kickstarter campaigns to see trends in what is successful and what has failed. She is also interested in the data for future projects as well. 
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
In our analysis, we first needed to separate the subcategories from the parent categories so that we can look specifically at the category of theater that Louis is interested. We also needed to convert the Unix timestamp to a readable date. We did this by using: =(((J2/60)/60)/24)+DATE(1970,1,1). Once the data was in a useable form, we were able to create a Pivot table and line chart looking at the Outcomes of the Theater campaign based on the month the campaign was launched. As shown below. 

<img width="329" alt="Outcome_by_date_pivot" src="https://user-images.githubusercontent.com/90511014/138529945-068464cb-78fc-46af-8558-0c4ad25523ad.png">

![Theater_Outcome_vs_Launch](https://user-images.githubusercontent.com/90511014/138529928-c9706de5-fd30-4b93-b16f-4a8ebe3cebef.png)


# An Analysis of Kickstarter Campaigns
This analysis attempts to detemine the relationship between Sucecessful and failed kickstarter campaign and determining factors such as category and goal of the campaign.
Music and Theater are the most sucessful campaigns.
![KickstarterParentCategoryOutcomes](https://user-images.githubusercontent.com/90511014/137641455-e54f5669-d953-4489-9c30-91b3cacffb84.png)
Through this anaysis the recomendation for a sucessful theater campaign is to have a goal of 4000 or less.
![BoxandWhisker](https://user-images.githubusercontent.com/90511014/137641415-af7ba979-0e9a-4d69-8ba7-9e242c28a97b.png)
Also May is the best month to start a sucessful campaign.
![KickStarterLine graph](https://user-images.githubusercontent.com/90511014/137641461-bdea7874-9519-4bfc-87f9-da418045cacc.png)
