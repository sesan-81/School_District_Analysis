  
 
School_District_Analysis

(1)  PROJECT OVERVIEW

                      The purpose of the Analysis
                      
The school board has notified Maria and her supervisor that the student_complete.csv file shows evidence of academic dishonesty; specifically, reading and math
grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they 
want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

This project was completed for a school district to analyze student test scores on a certain metrics


Maria is the chief data scientist for a city school district. She has requested an analysis of school spending and standardized test scores.
The following materials were used:
•	Software: Python 3.7.6; Anaconda Navigator 4.12.0; Jupyter Notebook 6.4.5
•	Data Source: schools_complete.csv, students_complete.csv
•	Code: pyCitySchool_Challenge_starter_code

(2) RESULT

(A) HOW THE DISTRICT SUMMARY WAS AFFECTED

The average reading score remained the same while the average math score decreased by 0.1 points. The percentage of students passing math decreased by 1% as did the percentage of students passing reading. The overall passing percentage also decreased by 1%.

(B) HOW THE SCHOOL SUMMARY WAS AFFECTED

There is change in data is with the Thomas High School only and there is also decrease in overall math and reading passing numbers.

(C) HOW REPLACING THE NINTH GRADERS’ MATH AND READING SCORES AFFECT THOMAS HIGH SCHOOL’S PERFORMANCE, RELATIVE TO THE OTHER SCHOOLS

Thomas High School moved from 2nd place overall with a passing % of ~92% down to last place with a passing % of ~68%.

(D) HOW DOES REPLACING THE NINTH GRADE SCORES AFFECT THE FOLLOWING

I.	Math And Reading Scores By Grade

nothing is affected by this, although Thomas High School has no math and reading scores.

II.	Scores by School Spending

The $630-644 bin saw a decrease in the passing percentages since Thomas High School was in that spending range. Though, interestingly the average math and reading scores for that range remained the same.

III.	Scores by School Size

There is decrease in the Medium (1000-2000) bin passing percentages. Thomas High School while the average math and reading scores in the range was unaffected.

IV.	Scores by School Type

The Charter schools saw a decrease in the passing percentages since Thomas High School was in that school type. Though, interestingly the average math and reading scores for that range was unaffected.

(3)  SUMMARY

FOUR CHANGES IN THE UPDATED SCHOOL DISTRICT ANALYSIS AFTER READING AND MATH SCORES FOR THE NINTH GRADE AT THOMAS HIGH SCHOOL HAVE BEEN REPLACED WITH NANS. 

a.	There is an increase in the average reading grade.

b.	The average math score decreased by 0.1% for the data set assigning Thomas High School ninth grade scores to NaN.

c.	There is decrease in % Passing reading by 0.1% for the data set assigning Thomas High School ninth grade scores to NaN.

d.	There is decrease in % Overall Passing by 0.3% from 65.2% to 64.9% after assigning Thomas High School ninth grade scores to NaN.




