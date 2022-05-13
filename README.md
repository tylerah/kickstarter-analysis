# An Analysis of Kickstarter Campaigns
## Overview of Project
### Purpose
The purpose of this project was to analyze Kickstarter campaigns in order to determine what characteristics were associated with successful and unsuccessful fundraising goals. The client, Louise, was interested in these characteristics as she utilized Kickstarter in order to raise funds for a play that she wrote. While the dataset included information regarding all types of campaigns, a particular emphasis was placed on the theater category in order to provide the most relevant information to Louise.
## Analysis and Challenges
### Method
The analysis was performed by compiling the data in Microsoft Excel and utilizing pivot tables and other functions in order to compare the outcome of each campaign to specific variables. For example, a pivot table was created in order to visualize campaign outcomes (successful/failed/canceled) based on when it was launched. Filters were applied in order to view this data based on category (theater or otherwise) as well as by month and year. Excel was then used to create a graph that easily visualizes this data. 

In addition to pivot tables, Excel was utilized to calculate the percentage of various outcomes (successful/failed/canceled) based on the financial goal set for the campaign. This was accomplished by using the “countif” function to separate campaigns into categories based on their target goal. Basic arithmetic was then used to calculate the percentages of successful or failed campaigns in each category. Excel was then used to create a graph that easily visualizes this data. 

The spreadsheet used for this analysis can be found here: [kickstarter-challenge.xlsx](https://github.com/tylerah/kickstarter-analysis/files/8684335/kickstarter-challenge.xlsx)

### Challenges and Difficulties Encountered
Very few challenges were encountered when preparing this analysis. The only difficulty encountered was that the dataset included information regarding “Live” campaigns. This data was not useful for the analysis at hand as their outcome is not yet apparent and it is not appropriate to make any assumptions about what their eventual outcome will be. However, this was easily addressed by using Excel to filter out all campaigns with a “Live” designation so that they did not have an impact on the overall analysis.
## Results
### Analysis of Outcomes Based on Launch Date
Two relevant observations can be made in regard to the outcome of a campaign based on its launch date. The first observation is an encouraging one. An analysis of the theater category reveals that for any given month more Kickstarter campaigns succeed than fail. On average, 70 campaigns are successful while only 41 are unsuccessful each month. However, while the odds are generally in favor for a successful campaign, it is clear that some months are better than others. May had the greatest number of successful campaigns out of any month with 111 that met their goal. December was the worst month with less than 40 campaigns that met their goal. It is likely that campaigns launched during November, December, and January are impacted by the holiday season. While more research is needed to determine why May is the best month to launch a campaign, it is recommended to launch Kickstarter campaigns during this month based on historical trends.

![theater_outcomes_vs_launch](https://user-images.githubusercontent.com/104606662/168218454-20aa6ed8-82d5-495d-8fc4-2ecf14cb686f.png)

### Analysis of Outcomes Based on Goals
The general trend regarding the success of a Kickstarter campaign compared to its initial goal is that lower goals tend to be more successful. Almost 75% of all campaigns that had a goal of $5,000 or less were fully funded. In contrast, only 20% of campaigns that had a goal for $25,000 were fully funded. 

Interestingly enough, there is a sudden spike of successful campaigns whose target goal was between $35,000 and $40,000. However, it is important to note that this is probably not representative of the average campaign as this category was made up of only 6 total projects. Additionally, by reviewing the blurbs of the 4 successful campaigns in this category one can observe that these particular campaigns were associated with individuals of some notoriety. For example, the play Verdigris featured Jim Beaver who stars in the popular television series Deadwood and Supernatural. It is not recommended that the average campaign set a goal this high.

![outcomes_vs_goals](https://user-images.githubusercontent.com/104606662/168218492-ab5e46a6-21ad-4a91-a2d6-52b4feddc56b.png)

### Potential Limitations of the Dataset
The greatest limitation of this dataset is that it provides very little information regarding marketing efforts. For example, how were the campaigns marketed to potential backers?  Was social media the primary means of advertisement? If so, which platforms were used and what strategy was used in regard to timing and amount of posts shared? Identifying and analyzing the relationship between outcomes and various marketing strategies could provide information that makes the difference between success and failure.  

Another potential limitation of the dataset is that it provides no information on the timing of the donations. Many campaigns were only open for roughly 30 days. Knowing when backers tend to donate could help campaign organizers make decisions regarding when to implement marketing strategies. For example, if a majority of backers tend to donate within the first few days of the campaign being open then marketing efforts should be greater during this time. It’s also possible that some failed campaigns may have succeeded if they had stayed open longer and data regarding when backers donated could provide some insight regarding how long a campaign manager should keep their campaign open.

Additional tables and graphs that could yield useful information are: outcomes based on average donation, outcomes based on backer count, and outcomes based on whether or not the campaign was a “staff pick” or “spotlighted” by Kickstarter. 
