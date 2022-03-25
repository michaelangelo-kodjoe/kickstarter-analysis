# Kickstarting with Excel

## Overview of Project
An analysis to show how fundraiser campaign events correlate to various targets set by the dates they were lauched and their funding goals. 

### Purpose
The purpose of this analysis is to have an informed understanding on how to help Louise know how various plays in theater have fared based on the times they were were launched and how how those plays fared based on the the amount of funding acquired.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
After analysing the kickstarter dataset, there was a slight uptick in both successful and failed outcomes in February. Between February to March, both outcomes also took a slight dip. From March all the way through to May, both outcomes grew higher in percentage but there successful outcomes grew exponentially higher. From May, all the outcomes took a dip with the success rate falling very steeply. More successess came for a tad bit in a month between September and October but eventually fell for the rest of the year.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/85206793/155828352-558cb18e-4f38-412f-bc0c-3517b66053d7.png)

### Analysis on Outcomes Based On Goals
Analysing the Kickstarter dataset, we can clearly see that there is an inverse correlation between the percentage of plays that were successfuk to those that failed. Plays that had goals between $O to $29,999 have had their succession rate fall steadily while the inverse happened for plays that failed with the same threshold . There is a little bit of an uptick between the $29,999 to $39,999 goals increasing their success rate. The opposite can be said for failed plays within the same range. Success rate plateaus between $39,999 to $44,999. There is an immediate fall in success rate from $44,999 to $49,999. 
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/85206793/155828687-393fb90f-aaeb-47fd-aa97-2bc5d2a79b07.png)

### Challenges and Difficulties Encountered
A challenge someone will likely encounter is the the creation of the months labels in Excel. Creating the labels is a combination of skills that one must practice. In order to create the motnths label in the launch date analysis, inserting both the "dates created" and "dates ended" will give you the more than one label in the pivot tble created tor the analysis. Just removing the other unused labels in the row section of the pivot table gives you the row label.

## Results
Two conclusions that can be be made from the outcomes by launch date are:
1.Plays are less successful between May and August meaning there is a problem about plays being successful during the summer.
2. Fall and Spring usually see a rise in plays meaning people like to watch plays when the temperature outside is neither too hot or cold.

One conclusion about the outcome by goals is:
1.Plays that have a goal ratio between $44,999 to $49,999 are very unsuccessful and should not be looked.

Limitations On the Data Set.
1. The sample size is limited. The data set does not clearly represent all the outcomes based on the goals and their launch dates.There could be a different sample size which shows in a different sense that the seasons might actually be an indicator of whether someon would want to watch a play or not.

What are some other possible tables and/or graphs that we could create?
Some other tables that can be created are:

1. Tables which show the amount pledged vs the outcome to see if there is a direct link between the actual money onbtained for the play versus the goal intended for the play.
2. Which years had a more succesful rate in plays and which subcategories were more successful. There you can find if people preferred to watch a particular genre of show and at which time period that is.  
