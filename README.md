# Kickstarting with Excel

## Overview of Project

This project used Excel to analyze the success/fail rates of kickstarter campaigns for plays in order to compare to Louise's play *Fever*.  

### Purpose
The purpose of this project is to review the success / fail rates of kickstarter campigns in an attempt to identify the best time of year to launch and the most successful fundraising goals.   To achieve this analysis, we narrowed the data to theater outcomes according to launch date and outcomes according to the funding goal.  See the graphs below.
![Outcomes Based on Launch Date] (https://github.com/LauraZJ/Kickstarter-Analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

![Outcomes based on Goals] (https://github.com/LauraZJ/Kickstarter-Analysis/blob/main/Resources/Outcomes_vs_Goals.png)

## Analysis and Challenges


### Analysis of Outcomes Based on Launch Date

Review of the outcomes based on launch date identifies May - July as the most successful months to launch.  

### Analysis of Outcomes Based on Goals

When reviewing the outcomes based on goals, we see that the percentage of projects that are successful trends downward as the project goals increase.  


### Challenges and Difficulties Encountered
When calculating the outcomes based on goal, I was concerned that the formula I used to calculate the number canceled returned a zero value for all goals.  To verify that zero was the correct answer, I went to the main worksheet and filtered by each criteria and verified that zero was the correct result.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. December has the highest failure to success ratio at nearly one to one.  There is a higher failure risk in Decmeber and I would be cautious about launching in December.
2. The success to failure rate is highest in May, June and July.   

- What can you conclude about the Outcomes based on Goals?
1. The projects with smaller goals are more successful at achieving the goal.

- What are some limitations of this dataset?
1. This dataset does not provide socioeconomic data of the backers such as age, education, and income.     
2.  The huge limitation in the outcomes vs. goal analysis is that it does not include the number of projects reflected in the data.  The graph doesn't show that we are comparing more than 300 projects in the lower goal range whereas the highest goal data points represent less than 5 projects. 

- What are some other possible tables and/or graphs that we could create?
1. I would add the number of projects to the outcomes based on goals graph.  This would give a clearer picture knowing that 100% failure rate is only one or 2 projects.  
2. Consider comparing the deadline vs. launch date as it relates to success.  It would be good to see if the some of the failures are due to a short fundraising timeline.   
3. Comparing subcategories would also be give a clearer picture when viewing theater outcomes.  
