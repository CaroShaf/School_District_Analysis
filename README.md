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

[Top Schools] (https://github.com/CaroShaf/School_District_Analysis/blob/main/Resources/topschools.png)
[Bottom Schools] (https://github.com/CaroShaf/School_District_Analysis/blob/main/Resources/bottomschools.png)

* % Passing Math Scores, % Passing Reading Scores, % Overall Passing - It should be noted by studying the tables of high (top) and low (bottom) performing schools that passing scores are less related to spending per student and overall budget than they are to school size and type of school.

* School Size - small and medium schools have by far higher achieving students.  The largest schools have the lowest passing rates and the largest budgets.
[School Size] (https://github.com/CaroShaf/School_District_Analysis/blob/main/Resources/schoolsize.png)

* Type of School - The type of school has a large effect on student performance, also.  The larger schools tend to be district schools while the charter schools are smaller.  
igh student performance is observed at charter schools with smaller student populations even when there is less spent per student.  This should not, of course, imply that larger
schools should have their budgets cut, but rather working towards splitting up larger schools into smaller charter schools could improve student success while not costing
significantly more in budgets.

[Type of School] (https://github.com/CaroShaf/School_District_Analysis/blob/main/Resources/charterdistrict.png)
* Performance by Grade Level


## Summary
In summary, removing the 9th grade Thomas High School students did not make a markable change in district wide analysis, as can be seen in the table below.  All indicators were
within 1% of their pre-filtered analysis. However, if looking at small numbers of students' grades there are some suspicious patterns among some of them.  There are
significantly more high 90s percentage scores in math than in the corresponding school's 10-12th grade classes.  There are also some students that have high 90s in reading and
math.  While this could be true, it is unlikely that they would differ so greatly from the upper grades.  Almost without variation, within schools, the percentage of passing in
reading, math and overall passing remains constant over all grades.  The academic dishonesty is likely not widespread and it is recommended to investigate this. THS is already a
top performing school, so there may be opportunity to make sure that students are not under greater pressure to perform and resorting to cheating to maintain the standards that
have been set.  My recommendation would be to focus on the low performing schools, both to make a plan to reduce the size of the schools as well as to look carefully at
standardized testing as the best way to evaluate student compentencies.

[District Wide Metrics](https://github.com/CaroShaf/School_District_Analysis/blob/main/Resources/District_overall.png)

There is a statement summarizing four major changes to the school district analysis after reading and math scores have been replaced
