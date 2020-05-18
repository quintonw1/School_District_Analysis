# School_District_Analysis_Challenge
This analysis consisted of comparing the results for the students within the school districts. The comparison included metrics such as math, and reading scores. It also included a percentage pass analysis where the percentage of each high school's students that passed math, reading and both were compared to eachother. 

Additional Analysis was performed to compare the impact that school budget on a per capita basis, school size and finally, type had on the success of it's students. 

A change was made after the grades for the 9th grader students attending Thomas High School were deemed incorrect. Code used to modify analysis can be found in sections 11 to 15 in the PyCitySchools_Challenge file. 

The following differences were observed:

1a. How is the district summary affected? 
The districts average math score decreased by 0.1%, and the % passing math rate decreased by 1%

1b. How is the school summary affected? 
Thomas High School's average math and reading score changed from 83.42 to 83.35, and 83.85 to 83.90 respectively. The passing rates for math and reading changed from 93.27% to 66.91%, and 97.3% to 69.66% respectively. The overall passing rate for both math and reading decreased from 90.95% to 65.08%.

2. How does replacing the ninth graders' math and reading scores affect Thomas High School's performance, relative to the other schools? 
The changes made dropped Thomas High School' ranking from 2nd to 8th place when comparing % Overall Passing. 

3. How does replacing the ninth-grade scores affect the following when using the scores by grade, school spending, school size, and school type metrics?  
3a. Math and reading scores by grade:
Grade 9 scores are now NaN, and therefore there can be no useful comparison betwee the two cases. All other grades still possess the same scores for each course. 

3b. Scores by School spending:
Since Thomas High school falls within the $630 - $644 bucket, the statistics for this bucket are altered as the scores were lower. 
% Overall Passing decreased from 63% to 56%. 

3c. Scores by School size: 
Since Thomas High school falls within the Medium school category the values for this row have changed. The % overall passing decreased from 91% to 85%. 

3d. Scores by School type: 
Since Thomas High School falls under the Charter school type, the results for this comparison have changed. The % overall passing decreased from 90% to 87% for Charter school types as a result of this change

The results seen above can be attributed to the incorrect modifcation of the data. If the marks were to be zeroed, then the students should be removed from the analysis. By simply substituting a NaN value into the marks for math and reading, the averages still consider the student to exist in the system, however with a 0% grade in both of the subjects, hence why the passing percentages dropped. 
