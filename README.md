# kickstarter-analysis
Performing analysis on kickstarter data to uncover trends

## Overview of the Project
In this project we are given data on different campaigns and their fundraising goals.

### Purpose
The purpose of this project is to see how different campaings in the theater/play category fared according to their fundraising goals and their launch dates in order to give Louise a better understanding of how her play "Fever" did compared to other campaings in the same category.

## Analysis and Challenges
For this project we were given the data in an excel file and had to use excel tools in order to get our results.

### Analysis of Outcomes Based on Launch Date
In the first part of the challenge we were asked to create a visual that shows campaign outcomes ("Successful", "failed" or "cancelled") based on their launch date. For this activity I used a pivot table in order to extract information I needed in order to get the visual required. For the fields in the pivot table i used the following: 

Filters                 Columns            Rows             Value
- Parent Category       - Outcomes       - Date Created     - Count of Outcomes
- Years

### Analysis of Outcomes Based on Goals
In the second part of the challange we were asked to create a visual to show the percentage of successful, failed and cancelled plays based on their funding amount goal. For this activity I created a table: in the first column I created a range of goal amounts in oncreases of $5000. Then for the other columns I used a COUNTIFS() function in excel to populate the cells. 

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. May was the most successful month with 66% of the projects launched in May were successful
2. The average Success rate was 60%

- What can you conclude about the Outcomes based on Goals?
Any project with a funding goal amount of less than a $1000 had a 76% chance to succeed.


- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
