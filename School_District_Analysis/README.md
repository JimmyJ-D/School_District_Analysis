# School_District_Analysis Module 4 Challenge


# PyCitySchools
Data Analysis Bootcamp
Module 4 Python - Data

## Project Overview
Using the districted supplied data in csv format we are asked to analyze common school district statistics such as:
- Budget
- Reading Scores
- Math Scores
- Total number of students 
- Averages and mean for a specific high school "Thomas High School"
- Best performing schools in the district 
- Lower performing schools in the district
- Budget spent per student at top .head() and lower .tail() performing schools. 

- As an additional constraint, we simulated receiving data sets with missing or malformed data. 
When data is missing, as an analysis we can drop, fillin, or replace the missing information. For this exercise we will exclude Thomas High School 9th grade data because of missing cell. There are 461 student in the 9th grade. The math and reading scores were replaced with "NaN". 

## Results

- How is the district summary affected?
The distrist summary between the challenge data set and the homework data set appears to be unchange based on the averages. Removing the 9th graders of Thomas High School did not reflex a difference in the district summary. 

- How is the school summary affect?
Removing the 9th graders from the calculation at Thomas High School resulted in a less than a percent point change in overall passing rate. 

- How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?
We are not including the data in our calculation but base on the school performance as we assumed that the percentage would not deviate. 

- How does relacing the ninth-grade scores affect the following: 
--Math and reading scores by grade
The Thomas High School's 9th graders are excluded from all data, aveage, and percentage calculation. We can assume with a per student budget of $638 and being a charter school that the 9th graders would score on par with school 10th - 11th grade averages. 

- Scores by school size
Thomas High School student count has it as medium (1000-2000) student size in the district. Medium size schools ranked higher than large schools with (2000-5000) student count.  

- Scores by school type
According to the data charter schools ranked in the top 5 in Overall Passing scores. Schools that were classified as district schools ranked in the bottom 5 of Overall Passing scores.  

## Summary
Removing the missing data did lower the overall Thomas High School. As a charter school, and medium size school in the district removing 9th graders average did not cause the Thomas High School to rank lower than a district school. While 461 student seems like a lot it is less than 1% of the district total student count.  
