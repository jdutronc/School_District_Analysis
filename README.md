# School_District_Analysis

## Overview
The Chief Data Scientist for the City School District, Maria, has tasked us with looking into performance trends and patterns of over 39,000 students out of 15 district and charter schools to inform startegic decisions at the school district level.
We have created:
- a high-level snapshot of the district's key metrics, presented in a table format
- an overview of the key metrics for each school, presented in a table format
- tables presenting top 5 and bottom 5 performing schools, average math and reading scores per grade and per school, and school performance based on the budget per student, school size and type of school.
Now the School Board has notified Maria that the source data we bsed our analysis on shows evidence of academic dishonesty at Thomas High School. We have to replace math and reading grades for all ninth graders at THS with NaNs and run our analysis again.

## Results of the Updated Analysis

### District Summary

As shown in the table below, removing math and reading grades for all ninth graders at Thomas High School did have an impact at the school district level. The average math score across the district is down from 79.0 to 78.9, as well as the percentage of students passing math, passing reading and passing overall.

Original District Summary                |
:---------------------------------------:|
![](Resources/District_Summary_1.png)    |
Updated District Summary                 |
![](Resources/District_Summary_2.png)    |

<br>

### School Summary

As shown in the table below (and as expected), the results for Thomas High School are impacted by the change. Average scores in math and reading both remain the same, but the percentages of students passing math, passing reading and passing overall rose sharply from the 65%-70% range to over 90%.

Original School Summary                         |
:----------------------------------------------:|
![](Resources/Per_School_Summary_Tail_1.png)    |
Updated School Summary                          |
![](Resources/Per_School_Summary_Tail_2.png)    |

<br>

### THS performance Relative to Other Schools

<img align="right" src="Resources/THS_Ranking.png" width="400">
The table attached here on the right shows that the performance of Thomas High School students relative to other schools appreciated significantly after removing the grades of the ninth graders. The average math and reading scores remained the same (see above) and so does the ranking of the school relative to others, but we can see that Thomas High School is now one of the top schools in the district in terms of the proportion of students passing math (from 9th to 7th place), passing reading (from 15th to 3rd place) and passing overall both math and reading (from 8th to 2nd).


<br>

### Average Math and Reading Scores


### Scores by School Spending


### Scores by School Type


## Summary

1-
2- 
3- 
4- 
