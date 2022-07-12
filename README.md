# School District Analysis

## Overview of Project:

School District Analysis on grade performance using Jupyter Notebook with Python, Pandas Library, and Numpy library.

This repository contains an analysis about grade performance. We are working with our client Maria is responsible for preparing data for insights into performance trends. 

The school board will like to analyze test scores to help ensure better financial decisions.

We will now review the data below and see the results.

## Results:

**School District Summary**

![This is an image](https://github.com/ABorden23/School_District_Analysis/blob/main/Resources/Resources/District%20Summary%20df.png)

When examining the district summary there was very small effects to removing the 9th grade data of Thomas High School.

* Average Math Scores: moved from 79 to 78.9 (.1 point) as a result of this change.
* Average Reading Scores did not change
* % Passing Math moved from 75% to 74% (delta: 1 percentage point)
* % Passing Reading moved from 86% to 85% (1 percentage point)
* % Overall Passing moved from 65% to 64% (1 percentage point

**School Summary**

![This is an image](https://github.com/ABorden23/School_District_Analysis/blob/main/Resources/Resources/School%20Summary%20df.png)

The school summary, there were some minor adjustments to the data as well.

Summary below:

* Average math at Thomas decreased from 83.42 to 83.35
* Average reading at Thomas slightly increased from 83.84 to 83.89 (less than .1 point)
* Average percent passing Math at Thomas greatly decreased from 93.3% to 66.9% (26.7 percentage points)
* Percent passing Reading at Thomas decreases from 97.3% to 69.7% (27.6 percentage points)
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

As a result of the removal of suspect scores, Thomas High was no longer in the top 5 schools by performance, thus, we have further evidence of score inflation at the 9th grade level within Thomas High.

How does replacing the ninth-grade scores affect the following:

Scores by school size :

Scores by school type :

Math and reading scores by grade :

Scores by school spending :

## Summary: 

* Top School Ranking- Thomas High School that was ranked 2nd and dropped out of the top 5 schools to 8.
* The percentage passing students for math, reading and overall was also significantly affected at school and grade level for Thomas High School after the   change. 
* Scores by School Size - changes to Medium (1000-2000) grouping for all scores by less than 0.1 percentage points (or change by less than 0.1%).
* Scores by School Type - changes to Charter type grouping for all scores by less than 0.1 percentage points (or change by less than 0.1%).

## Resources
Data Source: schools_complete.csv
Data Source: students_complete.csv
Sofware: Jupyter Notebook 6.4.8
Library: Pandas
Library: Numpy
Language: Python 3.6.7
