# Election_Analysis
# An Analysis of Kickstarter Campaigns
## Overview of Project
### Performing analysis on Kickstarter data to uncover trends bringing some insights, for the playwright of the play "Fever", about the relationship between the launch date of a play and its outcomes, and the funding goals set for a campaign and its outcomes. 
---
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Dates

![Outcomes_Based_on_Launch_Date](https://github.com/Connectime4ever/kickstarter-analysis/blob/main/resources/Theater%20Outcomes%20Based%20on%20Launch%20Date.png)

### Analysis of Outcomes Based on Goals

![Outcomes_ Based_ on_ Goals](https://github.com/Connectime4ever/kickstarter-analysis/blob/main/resources/Outcomes%20Based%20on%20Goal.png)

### Challenges and Difficulties Encountered
- In the instruction number 4 of Deliverable 2 a pivot table was used to simplify the filtering needed to apply function COUNTIFS.  (Please see "Sheet Notes" in Kickstater Challenge for reference) (https://view.officeapps.live.com/op/view.aspx?src=https%3A%2F%2Fraw.githubusercontent.com%2FConnectime4ever%2Fkickstarter-analysis%2Fmain%2FKickstarter_Challenge.xlsx&wdOrigin=BROWSELINK)
- Trying to comeup with an insight based on Graph Outcomes Based on Goals. It is visually difficult to read the story and could be confussing.

## Results
- It is recommended the play launch date is picked from May to July preferably. These months show the highest numbers of successful plays  (**above 80%**), and also the highest ratios successful/failed.
- Launches in February, April and August tend to have the same successfull rate around mid 70%. They might be options to consider.
- In the event the play has to be launched in the last quarter of the year, October seems to be the preferable month to pick. However, this month also shows the second worst ratio successful/failed after December,so it is risky.
- It is advised to **avoid** launch dates from November to January following year. 
- Campaigns with goals less than $1000 shows higher percentage of success while campaigns with goals set higher than $45000 tend to be the least successful.               
### Limitations of this dataset
- As this dataset is only for one year it is not sure if it is showing a reliable seasonality pattern of success based on launch dates. It might need necessary to look into the trend of other years to be sure that the seasonality is consistent, and if there are any extraordinary situations affecting the monthly performance. 
- It would be interesting to know what is the rate of pledges actually collected in plays subcategory. This migth be helpful to tune a play campaign goal.
### Other possible tables and/or graph that we could create. 
- The pivot table above referenced in "Challenges and Difficulties Encountered" could be helpful to ease the process and assure accuracy.
- This table with some statistics about goals of successful plays could lead the playwrigth when trying to set a goal for the play.

![Statistics_of_ Successful_Plays_Goals](https://github.com/Connectime4ever/kickstarter-analysis/blob/main/resources/Statistics%20of%20Successful%20Plays.png)
- This Clustered Column Graph below could be useful for the analysis of Outcomes Based on Goals. It is easier to read and bring additional insights at a glance.
![Outcomes_Based_on_Goals_Suggested](https://github.com/Connectime4ever/kickstarter-analysis/blob/main/resources/Outcomes%20Based%20on%20Goals%20Suggested.png)