# An Analysis of Kickstarter Campaigns

Performing analysis on Kickstarter data to uncover trends

:file_folder: [Kichstarter Excel File](/data-1-1-3-StarterBook.xlsx)

**Contents**

1. Kichstarter (Data)
2. Subcategory-Play (refer data)
3. Outcomes Based on Goals (use 2)(COUNTIFS)(challenge: play subcatgory)
4. Outcomes Based on Launch Date (challenge: theater category)
5. Outcomes Parent Category
6. Outcomes SubCategory
7. Failed U.S. Kickstarters (refer data)
8. Successful U.S. Kickstarters (refer data)
9. Descriptive Statistics (use 7 and 8) (AVERAGE,MEDIAN,STDEV.P,QUARTILE.EXC)
10. Edinburgh Research (VLOOKUP)

### Chalenge

1. Data analysis of the Category “Theater” based on date

Data Limition: The Data were included funding campaigns from countries around the world from 2009 to 2017. The successfull pledged campaigns was not distrubuted evenly among regions and years. If we just focus on May and June the most sucessfull plegded numbers, we can see all countries and years data are not evenly distributes. United States and Great Britain are two most countries have successful pledged outcome.

![Outcomes Based on Region](/SuccessfulPledgedByRegionAndYear.png)

![Outcomes Based on Launch Date](/OutcomesBasedOnLaunchDate.png)

Conclusion: If you plan to run the funding campaigns in the theater categrory and specially in Untited States and Great Britain, you should do the funding campaign between May and June. The worst time for funding were between November and December only 91 successful. The failed pledged numbers were the same for all months around 40 and 50. And also the canceled pledged numbers were 3 or 4 each month. The reason failed and canceled numbers may be asked high fundings or regions. Therefore, May and June are good months to do the theater category funding campaign.


2. Louise’s play Fever came close came close to its fundraising goal in a short amount of time. 
How many other Kickstarter campaigns were able to do this as well? In this challenge, 
you’ll conduct a data analysis to answer this question and determine whether the length of a campaign contributes to its ultimate success or failure.

Data Limitation: The data analysis were included plays around the world. If we know where it plays, then we can get country data to do analysis.

![OutcomesBasedonGoal SubCategory Play](/OutcomesBasedonGoal_SubCategory_Play.png)

![Color Condition Chart](/Support_Data.png)

![Donation Average Stat](/Average_Donation.png)

![Number Days of Successful Outcome Stat](/NumberDaysOfSuccessfulOutComes.png)

Conclusion:   Louise’s play Fever should do the funding campaign for $5,000 or less because the successful pledged or funded more 72%. The average days to run successful campaign is about 30 days based on the Number days of Successful OutComes. However, the duration may be longer than 30 days becuase there a lot of outliers over 40 days. The Average Donations of successful outcomes said that people are conformtable to pledge in this play subcatergory about $62. The chart aslo have a lot of outliers so it should be have some suprised to meet the goal earlier or funded more than the goal.
 

