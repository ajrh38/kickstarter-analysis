# kickstarter-analysis
Repository to deliver 1st challenge - Data Analytics bootcamp. This is an analysis on outcome based kickstarted campains.


1.	Overview of Project
This analysis show a comphrenesive study on why Louise’s play “Fever” did not achieve fundraising goal. There is a belief that the time range was an important factor to come close but not enough to be funded.  This project will address using statistical analysis if louise’s guess is correct. 
2.	Purpose
Using the provided data set, analyze the relationship between launch dates and funding goals to determine the effect in achieving funding.
3.	Analysis and Challenges
•	Deliverable 1: Outcomes Based on Launch Date Chart
•	Deliverable 2: Outcomes Based on Goals Chart
•	Deliverable 3: A written analysis of the results (README.md)

4.	Analysis of Outcomes Based on Launch Date

Based on launch date.


Analysis in graph Theater_Outcomes_vs_Launch.png (https://github.com/ajrh38/kickstarter-analysis/blob/8ad26982d3fe48cf343688b09731b97514ca5591/Theater_Outcomes_vs_Launch.png) shows months in the year when there is a higher successful fundraiser. Looking at the data it shows that during April to May there was a higher number of successful campaigns vs fail. However “fever” took place in june which is still a high month in terms of fundraisers, this tell us the analysis in this graph is not enough to show that launch date is a CRITICAL factor to be successful in a campaign. Another conclusion is there is no significant difference on canceled projects depending on the month. 
Another important consideration is, graph would be better for this specific case as %. We look at it by the total numbers of kickstarters but there could be a potential variable in the total number of successful vs failed, an example of this is Oct, no projects were cancelled and there was an increased in failures.
Limitations of the data considered in the analysis might cause a incorrect analysis, it does not consider spotlights.


5.	Analysis of Outcomes Based on Goals

Analysis based on “Outcomes_vs_Goals.png” (https://github.com/ajrh38/kickstarter-analysis/blob/8ad26982d3fe48cf343688b09731b97514ca5591/Outcome_vs_Goals.png)  show a big increase of potential failure when increasing a goal over $1,000 dollars. Less than 1000 is close to 80% successful then it drops below 60%. This could explain why “fever” was very close to the goal but still fail.
A good conclusion is that a goal of +$45,000 has the highest potential of failure.

6.	Challenges and Difficulties Encountered
Formatting in actual  “dates” required in order to do an actual validation on years.
On countifs is very important to consider the lower and EQUAL otherwise you might loose or duplicate records. It is very important to do a double check. I did a filtering and quick count to verify my ranges were matching with the total of my countifs calculations.
7.	Conclusion
There are  limitations in the previous analysis. It will be very important to review if the data is normalized and if we require to remove certain data sets that are outside the boundaries of the quartiles.
Stacked line charts or Bar charts with 2 axis would help us to review relationship between more variables like including spotlight or even a graph that combine the relationship between goal and launch date.
