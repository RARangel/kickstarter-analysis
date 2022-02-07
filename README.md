# Module 1: Kickstarting with Excel

## Overview of Project
### Purpose

The purpose of this exercise was to use the Kickstarter dataset to analyze how plays fared 
in relation to their launch dates and their funding goals. 

[Dataset] (Kickstarter_Challenge.zip)

## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date

Using the pivot tables and pivot charts, the data is filtered by theatre campaigns only. Data is then calculated by month
as well as the number counts of successful, failed and canceled campaigns for each month. Then the data is graphed
on a line chart to display the number of outcomes for each month. 

![Chart] (Theatre_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals

This analysis made use of the COUNTIFS statements in excel to separate the Goals into dollar ranges (rows)  and then 
counting the number of successful, failed, and canceled plays for each dollar range. Then the total number
of  projects in each range were summed and percentages were calculated for each outcome. The results were displayed on a line
graph, with the percentages on the Y-axis and the goals dollar ranges represented on the X-axis. 

![Chart] (Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

Most of the content in the module was very well written and documented.  The biggest challenge I faced was getting
the COUNTIFS formulas to work.  I kept inadvertently changing the columns which reulted in code errors.  I also did not
filter by "greater than AND equal to"  which kept throwing off my counts.  


## Results

- The most successful months for launch date are May and June.  Overall, the number of successful outcomes peak in the summer and
steadily fall towards the winter.

- Having a lower dollar amount as a goal  (for example, less than $15,000)  has a higher chance of becoming a successful 
campaign. Overall, most of the plays had campaign goal amounts less than $20,000,  so the percentage of sucessful-to-failed 
results are not well represented. 

- Limitations of this dataset include no canceled outcomes.  Also there were not enough campaings that had high dollar amounts.  Everything
 above $20,000 could have been grouped together. 

- Other possible tables and/or graphs that we could create:
Average donation over time  for any subcategory;
Category vs. goal in dollar amounts or percentage funded
