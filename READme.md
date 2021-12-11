# An Analysis of Kickstarter Campaigns using Excel

## Overview of Project
This project used an Excel database of Kickstarter entertainment funding programs to analyze trends and create visualizations of the data to assist a producer in decision making.

### Purpose
The goal of this project was to use Kickstarter data to determine future strategies for crowdfunding musical theater productions. Analysis of the data using Excel formulas and visualization tools allowed identification of trends and ulimately recommendations to be delivered to producer Louise.  

## Analysis and Challenges
The Kickstarter dataset is large and contains data related to crowdfunding campaigns in the areas of film & video, food, games, journalism, music, photography, publishing, technology and theater. This dataset looked at campaigns from 2009 to 2017. 


### Analysis of Outcomes Based on Launch Date
Musical theater productions typically run on a seasonal bases. Crowdfunding for successful musical theater productions also have a seasonal characteristic. The Outcomes Based on Launch Date chart shows the number of successful campaigns by the month in which they were launched. The highest number of successful theater production campaigns were launched in May and June.

![Outcomes Based on Launch Date](https://github.com/Bscheinin/Kickstarter-analysis/blob/main/Resources/Theater%20Outcomes%20Based%20on%20Launch%20Date.png) 
 

### Analysis of Outcomes Based on Goals
The Kickstarter dataset included funding goals and the sucess rate. As Louise was interested in musical theater plays, the  chart shows the funding ranges and the success rate of theater play campaigns. Fifty percent or more of funding campaigns were successful if the goal was leass than $20,000, the success rate rises as the goal decreased. There were also successful campaigns of 50% or more in the range of $35,000 to $45,000. Further analysis for Louise on these higher funded projects by number of donors and average donation would be helpful.

![Outcomes Based on Goal](https://github.com/Bscheinin/Kickstarter-analysis/blob/main/Resources/Outcomes%20Based%20on%20Goal.png)

### Challenges and Difficulties Encountered
The Kickstarter dataset is large. To make the data meaningful for Louise, data cleaning meant filtering data to reflect her area of interest along with formatting to allow for targeted analysis. For instance, the campaign dates were listed in Unix Timestamps and which were more readable if changed using this formula '=(((J2/60)/60)/24)+DATE(1970,1,1)'. In addition, of the 4,113 funding campaigns, only about 1,000 of those were for plays. Collecting additional data from another crowdfunding system specifically for plays may provide more data for Louise.

## Results
Several conclusions can be made from the Kickstarter dataset to help Louise determine the best parameters to use for her crowdfunding campaign.

From the analysis of the Theater Outcomes Based on Launch Date, one conclusion is that the most successful Kickstarter campaigns were launched in May or June. Additionally, this chart shows all theater productions and not just plays which are of interest to Louise. One of the challenges of this information is that this chart was created from the entire dataset (for all countries) rather than just in the countries where Louise is looking to open a musical theater production. Continuing to splice this data would be most helpful for Louise.

From the Outcomes Based on Goal information, we can conclude that successful Kickstarter campaigns may depend on the funding goal. This analysis shows that campaigns with goals of less than $20,000 where successful over 50% of the time. Additionally, there were successful campaigns with goals between $35,000 and $45,000 but knowing the average number of donors and average donation amounts would further inform Louise on her strategy with funding campaigns with higher goal amounts.

The timeframe of this dataset may be problematic for Louise. This data is pulled from crowdfunding projects conducted from 2009 to 2017. If Louise is looking to fund a theater production in 2022, she may want to obtain more recent trends to help determine if these historical trends apply to today's market environment. 

Finally, Louise initially expressed interest in opening theatrical productions in the United States as well as Great Britain. This current analysis could be refined to look at trends applicable to the Great Britain market especially in light of the nature of productions in the United Kingdom. 
