# School_District_Analysis

## Overview of Project:

Analysis on school district performance using Jupyter Notebook with Python, Pandas Library and Numpy library.

The School Board would like to understand various performance metrics of the different school districts and schools. We will first work with Maria (our contact) provide the initial analysis based on data collected from many students and schools across the school district.

While the School Board is pleased with the insight that we have provided in our work with Maria, it has been identified that there appears to be some anomalies in the data, in particular in the math and reading scores of the grade nine students at Thomas High School. In order to ensure these results do not skew the analysis, the Boad has asked us to again work with Maria to remove the impact of these results by changing all the grade 9 Thomas High School math and reading scores to Nan (which is a null value).

The School Board will like to understand the impact of changing all the grade 9 math and reading scores at Thomas High School to Nan - we will now review how this change impacted various parts of the analysis relative to when it was ran including the Thomas High School grade 9 scores.

## Results:

How is the district summary affected?


How is the school summary affected?


How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?


How does replacing the ninth-grade scores affect the following:


Math and reading scores by grade


Scores by school spending


Scores by school size


Scores by school type

## Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

District Analysis - changes to all scores by less than 0.5 percentage points (or change by less than 0.5%) - no impact to school or student count.
Top School Ranking - no change to ranking, however Thomas High School scores did change, but by less than 1 percentage point (or changed by less than 1%) for each metric.
Scores by School Size - changes to Medium (1000-2000) grouping for all scores by less than 0.1 percentage points (or change by less than 0.1%).
Scores by School Type - chages to Charter type grouping for all scores by less than 0.1 percentage points (or change by less than 0.1%).

## Resources
Data Source: schools_complete.csv
Data Source: students_complete.csv
Sofware: Jupyter Notebook 6.4.8
Library: Pandas
Library: Numpy
Language: Python 3.6.7
