# NFLX_DATA_ANALYSIS
This repository contains analyses and instructions for answering questions about Netflix streaming platform titles and reports on their positioning against competitors.

These are the questions and their answers:

### 1. In the ‘Films (English)’ category, which film has the most appearances in our data set (NFLX Top 10 tab of the Sheet)? What were its average weekly hours viewed? 
Title : Sonic the Hedgehog 
Average Weekly Hours Viewed: Average 7.481.250 weekly hours viewed 

![question 1: query](.\images\query_question1.png)
![question 1: result/output](images\output_question1.png)
<img src=".\images\query_question1.png" alt="question 1: query">
<img src="images\output_question1.png" alt="question 1: result/output">


### 2. In the 'Films (English)' category, which film has the lowest IMDb rating? What were its average weekly hours viewed? 
Title: 365 Days: This Day 
Average Weekly Hours Viewed : Average 29.022.500 weekly hours viewed

![question 2: query](images\query_question2.png)
![question 2: result/output](images\output_question2.png)
<img src=".\images\query_question2.png" alt="question 2: query">
<img src="images\output_question2.png" alt="question 2: result/output">

### 3. In the 'Films (Non-English)' category, which film has spent the most weeks in the top 10? To estimate the number of users who watched this film, what assumptions would you make and what risks are involved?
he film Through My Window has spent the most weeks in the top 10. Based on calculations 
from the runtime dataset, this film has been watched 775,862 times. Assuming it was watched 
once by every single user, it had 775,862 users.

![question 3.a: query](images\query_question3.png)
![question 3.a: result/output](images\output_question3.png)
<img src=".\images\query_question3.png" alt="question 3: query">
<img src="images\output_question3.png" alt="question 3: result/output">

![question 3.b: query](\images\query_question3_b.png)
![question 3.b: query](\images\output_question3_b.png)
<img src="\images\query_question3_b.png" alt="question 3.b: query">
<img src="\images\output_question3_b.png" alt="question 3.b: query]">

### 4. What are the risks of ignoring the data from the week of May 22nd when calculating the metrics from the previous questions?
The week of May 22nd was removed due to the issue with the weekly_hours_viewed field. 
This removal could affect the analysis if a film during this week was on the list of most
watched films, or if a film from this week had more weeks in the top 10.

### 5. While we've indicated that the 'weekly_hours_viewed' data for the week of May 22nd cannot be used in our estimates, we may want to fill in this missing information for other analyses. As a Data Specialist, what methodology would you propose to estimate the 'weekly_hours_viewed' for this missing week?
One of the first approaches would be to examine the behavior of the weekly_hours_viewed 
data before and after the missing week. Using the mean or median of adjacent weeks, I could 
generate an estimate for the week of May 22nd. If there is a linear behavior, it could be filled with a linear regression prediction. 

### 6. Do you think the information presented in this report is positive or negative for  NFLX as a company? Why? 
Positive, as NFLX has the most loyal subscribers, who have subscription priority with its 
platform. Furthermore, the data shows that there is historically a good acquisition of former
subscribers who were churners in the past. Recently, the rate of NFLX churners joining competing services reached its lowest level, which means that it is still the absolute leader in the competition. 

### 7. List 3 questions our clients may have after reading the report. 
What is the average time a subscriber stays on NFLX before churning? 
What is the churn rate from NFLX to Paramount+, considering the recent subscriber growth 
experienced by Paramount+?. 
What is the correlation between title launches and the churn rate? Which titles have the 
highest churn rate after launch?

### 8. Please clarify the level of proficiency in any coding skills that you have. (Note: coding skills are not a prerequisite for the position. If you do not possess any coding skills, please write "NA")
Data Analysis
    Python – 10/10 
    SQL – 9/10
    Statistics - 9/10
Data Viz
    Power BI: 10/10
    Tableau: 8/10


