# An Analysis of Kickstarter Campaign
Toni Hewin
## Overview
The purpose of this report is to analyze how plays and theater prospered according to their launch dates and funding goals.
## Analysis and Challenges
### Outcomes based on Launch Date
For the first analysis “Outcomes based on Launch Date”, I took the Kickstarter table in Excel; which shows a range of different categories for plays, theater and musicals in multiple Countries. I created a column to formulate the year by extracting information from the date created conversion column on the table. From there, the table was filtered based on successful, failed, and canceled theater based on the launch date. Next, a pivot table was done, and a line graph was created to show the relationship between outcomes and launch month.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/101079743/160292155-6873464b-f158-43b5-a23f-e5917cd0b782.png)

### Outcome based on Goal
For the second analysis “Outcomes Based on Goals”, the same Kickstarter table was used. First, to calculate the goals range for successful, failed, and cancelled plays the “Countifs() function in Excel was used. Next, the sum formula in excel was used to get the total percentage of the outcome. Lastly, a line chart was created to show the difference between the goal amount ranges, and percentages of the successful, failed, and canceled plays on an x and y-axis. One of the formulas used for one of the outcomes were:=COUNTIFS(Kickstarter!$F:$F, "succesful". Kickstarter$D:$D, ">=1000", Kickstarter!$D:$D,"<=4999", Kickstarter!$R:$R,"plays"). The Countifs were much easier to understand after revisiting.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/101079743/160292242-48b6b87b-af7f-4ee0-8bea-b610d66aab36.png)

### Challenges and Difficulties Encountered
In reviewing again, I found Countifs to be slightly easier to understand, and no error messages were presented, and no difficulties encountered were using the “Countifs() function, it took a few hours playing with the formula to get it to line up properly.

### Results
In the Outcomes based on Launch Date analysis, I found that there are more successful theater campaigns, than failed, and cancellations were minimum. In addition, theater is more successful during the warmer months. 
In the Outcomes based on Goals I found that plays with a goal range of under $5000 has a better success rate of 73 percent or higher. 
The limitations found in this dataset were theater based on launch date, and plays based on range goals. Other possible tables we could’ve considered were the States, or adding other campaigns such as musicals.
### Conclusion
In conclusion, it’s best to launch theater campaigns during the Summer due to the success rate, and a more reasonable goal range under $5000 provided more sucess than the others ranges. 
### Resources
www.youtube.com 
www.slack.com
www.google.com
