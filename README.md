# School District Analysis

## Overview of Project:

This project was performed to anaylze grade dishonesty performance using an array of Data Analytics softwares, Jupyter Notebook with Python, Pandas Library, and Numpy library.

We are working with our client Maria is responsible for preparing data for insights into performance trends. We have replaced math and reading schores for Thomas High School with NAN while keeping the original data intact. The school board will like to analyze test scores to help ensure better financial decisions.

We will now review the data below and see the results from our Jupyter Notebook.

## Results:

**School District Summary**

![This is an image](https://github.com/ABorden23/School_District_Analysis/blob/main/Resources/Resources/District%20Summary%20df.png)

When examining the district summary there was minor effects when removing the 9th grade data of Thomas High School.

* Average Math Scores: moved from 79% to 78.9% (.1 point) as a result of this change.
* Average Reading Scores did not change
* Percentage of Passing Math moved from 75% to 74% (1 percentage point)
* Percentage of Reading moved from 86% to 85% (1 percentage point)
* Percentage of Passing moved from 65% to 64% (1 percentage point)

**School Summary**

![This is an image](https://github.com/ABorden23/School_District_Analysis/blob/main/Resources/Resources/School%20Summary%20df.png)

The school summary, there were some minor adjustments to the data as well.

Summary below:

* Average math score at Thomas High School decreased from 83.42% to 83.35% (less than .1 point)
* Average reading score at Thomas High School increased from 83.84% to 83.89% (less than .1 point)
* Average percent passing math at Thomas greatly decreased from 93.3% to 66.9% (26.7 percentage points)
* Percent passing reading at Thomas decreases from 97.3% to 69.7% (27.6 percentage points)
* Average percent overall passing both Math and Reading decreased from 90.9% to 65.1% (25.8 percentage points)

**Top Five Performing Schools**

![This is an image](https://github.com/ABorden23/School_District_Analysis/blob/main/Resources/Resources/Top%205%20Schools%20df.png)

**Bottom Five Performing Schools**

![This is an image](https://github.com/ABorden23/School_District_Analysis/blob/main/Resources/Resources/Bottom%205%20Schools%20df.png)

**Average Math Scores by Grade and School**

![This is an image](https://github.com/ABorden23/School_District_Analysis/blob/main/Resources/Resources/Average%20Math%20Scores%20df.png)

**Average Reading Scores by Grade and School**

![This is an image](https://github.com/ABorden23/School_District_Analysis/blob/main/Resources/Resources/Average%20Reading%20Scores%20df.png)

**School Spending Summary**

![This is an image](https://github.com/ABorden23/School_District_Analysis/blob/main/Resources/Resources/School%20Spending%20Summary%20df.png)

**School Size Summary**

![This is an image](https://github.com/ABorden23/School_District_Analysis/blob/main/Resources/Resources/School%20Type%20Summary%20df.png)

**School Type Summary**

![This is an image](https://github.com/ABorden23/School_District_Analysis/blob/main/Resources/Resources/School%20Type%20Summary%20df.png)


## How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Replacing the ninth graders' math and reading scores with NaN resulted in the following changes for Thomas High School:

The overall passing percentage for Thomas High School fell to 65%
The overall passing percentage for the entire district fell to 64.9%
Thomas High School was no longer included on the list of top five schools.

## Summary: 

* Top School Ranking- Thomas High School that was ranked 2nd and dropped out of the top 5 schools to 8.
* When replacing the 9th graders math and reading scores with NAN. The percentage of passing students for math, reading, and overall was significantly affected at school and grade level for Thomas High School after the change. 
* Based on performance of the budget per student, it will impact the decision on whether school boards decide to provide funding schools based on there averages/passing percentages.
* At the final result of this project, it we may see an uptick in district school developments over charter schools in the future.


## Resources
Data Source: schools_complete.csv
Data Source: students_complete.csv
Sofware: Jupyter Notebook 6.4.8
Library: Pandas
Library: Numpy
Language: Python 3.6.7
