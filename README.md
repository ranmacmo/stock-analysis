# VBA Refactoring 

## Overview of Project

### Purpose
Utilize existing data on kickstarter projects to provide Louise feedback regarding what has been successful and/or not based on launch dates and funding goals. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
- The launch month of May showed the most successful outcomes. 
- The launch months of January, March, September and November had the least favorable outcomes. 
![Original Code](Resources/VBA_Challenge_2018.png)

### Analysis of Outcomes Based on Goals

- Funding goals in the range from $1000 to $4999 dollars the largest number of and percentage of successes. 
- Failure rate for funding goals from $5000 to $14,999 ranged from 45% to 46%. - as opposed to 24% to 27% for the ranges under $5000. 

![Refactored Code](Resources/VBA_Challenge_2018_Refactored.png)

### Challenges and Difficulties Encountered
The overall purpose would need additional refinement by asking  additional clarifying questions throughout the analysis process. 

## Summary
- The best launch date for a successful outcome historically has been May. 
- Successful outcomes drop at a downward rate from May to September. 
- A goal of $5000 or less has a stronger chance of being successful. 
- There were some large goals that could skew the data; these outliers could affect the data depending on the analysis being done. 
- Another chart based on project count could be useful to illustrated the large number of projects in the less than $5000 goal range that make up a large number of the overall successful projects. Other percentages could be misleading due to the smaller number of projects in the larger goals ranges. 

