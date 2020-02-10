# School_District_Analysis

## Project Overview
PyCity Schools requested an analysis to be conducted to display passing math and reading scores per grade, school, and district.  With this information will also entail, how much money is spent on per student.  Thomas High School recently discovered that ninth graders at their school changed their scores, so the analysis includes all ninth-grade scores as "NaN."
 
## Resources
Data Source: schools_complete.csv, students_complete.csv
Software: Python 3.7, Jupyter

## Summary
The analysis of the School District summary are able to answer the questions:

1) How is the district summary affected?
Thomas High School is a charter school, the DataFrame shows that the average math score and average reading score were not effected whereas the percentage for passing math, reading, and overall were.  Passing percentage for math changed from 94% to 90%, reading changed from 97% to 93%, and overall changed from 90% to 87%.


2) How is the school summary affected?
Thomas High School went from being the second highest overall passing percentage(90.95%), to being a middle tier school(65.08%).  However, it is still not in the lowest school score's list.   

3) How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?
Thomas High student count: 1635

Replacing ninth-grade scores placed them on the bottom of the ranking list as their scores show "NaN." This affected Thomas High School's performance from having:1)  1525 students pass math to 1094 students, 2) 1591 students pass reading to 1139 students, 3) 1487 students pass both subjects overall to 1064 students.  Their placing from second highest school from all 15 schools, to the middle.

<u>Original School Summary</u>
<img width=“500” alt=“” src="https://github.com/estherhk/School_District_Analysis/blob/master/Images/Oschoolsum.png">

Changed School Summary
<img width=“500” alt=“” src="https://github.com/estherhk/School_District_Analysis/blob/master/Images/Cschoolsum.png">

4) How does replacing the ninth-grade scores affect the Math and Reading Scores by Grade, Scores by School Spending, Scores by School Size, and Scores by School Type? 

Replacing ninth-grade scores do not affect the math and reading scores per grade.  For scores by school spending(spending is $638/student), the average math and reading scores did not change, however the the percentage of passing each subject did change.  The percentage of passing math changed from 73% to 67%, percentage of passing reading changed from 84% to 77%, and the percentage of overall passing went from 65% to 56%. 

<u>Original School Spending</u>
<img width=“500” alt=“” src="https://github.com/estherhk/School_District_Analysis/blob/master/Images/Ostudentspend.png">

Changed School Spending
<img width=“500” alt=“” src="https://github.com/estherhk/School_District_Analysis/blob/master/Images/Cstudentspend.png">

Scores by school size (size is 1635), average math and reading scores did not change, however the percentage of each subject did.  Percentage of passing math changed from 94% to 88%, percentage of passing reading changed from 97% to 91%, and overall passing from 91% to 85%.  

Original School Size

<img width=“500” alt=“” src="https://github.com/estherhk/School_District_Analysis/blob/master/Images/Oschoolsize.png">

Changed School Size

<img width=“500” alt=“” src="https://github.com/estherhk/School_District_Analysis/blob/master/Images/Cschoolsize.png">

The average scores by school type(is a charter school) did not change, however the percentage of each subject did.  Percentage of passing math changed from 94% to 90%, percentage of passing reading changed from 97% to 93%, and overall passing changed from 90% to 87%. 
Original School Type

<img width=“500” alt=“” src="https://github.com/estherhk/School_District_Analysis/blob/master/Images/Oschooldistrict.png">

Changed School Type

<img width=“500” alt=“” src="https://github.com/estherhk/School_District_Analysis/blob/master/Images/Cschooldistrict.png">

## Challenge Overview
Using Jupyter, an analysis was completed to display the school districts summary of the average scores of math and reading.  This showed the original and the effects after changing Thomas High School ninth-grade scores to "NaN."  Percentages of scores decreased about 3-4% per any DataFrames they were assocaited with.

