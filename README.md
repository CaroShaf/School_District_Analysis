# School_District_Analysis

## Overview of the school district analysis:

Maria, chief data scientist of City School System, has asked for some assistance with preparing reports related to 15 schools and all students' standardized test scores in math
and reading for analysis on school performance, type of school and budgeting. Though analysis of mean scores across schools and grades is fairly routine, Maria asked for
assistance to compare 9th graders at the Thomas High School's data before and after including them in aggregate scores.  It had been reported that there may have been academic
dishonesty among this class.  The data cleaning process did take out several hundred "joke" titles, such as PhD, DDS and Dr. in order for student's names to match their scores
accurately.

With nearly 40, 000 students' data collected, Python, using the Pandas library, is considered the tool of choice for its ability to handle large data sets. Some quick visual
scanning of data was performed, too.
Resources utilized:  Python 3.7.9, Pandas library, Jupyter Notebook, Conda Python environment, Excel 365

## Results

Removing the 9th grade Thomas High School students did not make a markable change in district wide analysis.  All indicators were within 1% of their pre-filtered analysis.
However, if looking at grouping of students' grades there are some suspicious patterns among some of them.  There are significantly more high 90s percentage scores in math than in
the corresponding schools' 10-12th grade classes.  There are also some students that have high 90s in reading and math.  While this could be true, it is unlikely that they would
differ from the upper grades.  Almost without variation, within schools the percentage of passing in reading, math and overall passing remains constant.  This can be seen

* % Passing Math Scores
* % Passing Reading Scores
* % Overall Passing
* Spending per student
* School Size
* Type of School
* Performance by Grade Level


## Summary

There is a statement summarizing four major changes to the school district analysis after reading and math scores have been replaced
