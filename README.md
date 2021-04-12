# School District Analysis
Module 4: PyCitySchools with Panda

## Overview of Project
### Purpose
In our analysis, we will be helping Maria the chief data scientist for a school district, analyze student funding and standardize test scores. The data that has been provided includes the student’s math and reading test scores, the schools they attend in the district and their budget. By evaluating the data, we will display trends in school’s performance. Our findings will dictate the distribution of school budget that must be determined by the school board. 
The calculations will be done through Jupyter Notebook, and the raw data that has been provided are the *students_complete.csv* and the *students_complete.csv”. The student’s csv file contains, the following information for the students: “Student ID”, Student Name”, “Gender”, “Grade”, “School Name”, “Reading Score” and “Math Score. The provided schools csv file, contains the following material on the schools: “School ID”, School Name”, “Type”, “Size” and “Budget”.  The given data will help give an insight to the student’s accomplishments from grade 9th to 12th, the overall rank of each school, and how this relates to their given budget. 

## Results
### How is the district summary affected?
The district summary tells us a story of 7 district schools which have significant diverse budgets and overall school performances. For example, the school with the highest budget is Bailey High School at $3,124,928 and the one with the lowest budget is Ford High School at $1,763,916. However, BHS budget per student is $628, versus FHS $644. The discrepancies can be due to school size, but when we create bundles for school size we see that both schools have are within the “Large (2000-5000) group. Let’s look at the overall passing performance student’s math and reading test score is very close, BHS at 55% and FHS at 54%. When we look at the overall performance of all district schools, we find the overall passing grade is 54%. It seems that the distribution of budget is not adequate and should be re-evaluated based on the student’s performance. 

![District Summary](https://github.com/cynmmarin/School_District_Analysis/blob/3ddb71bb92c0d955baefeabf381b0f5162dbf29c/District_Summary.png)

![District Summary per School](https://github.com/cynmmarin/School_District_Analysis/blob/3ddb71bb92c0d955baefeabf381b0f5162dbf29c/District_Summary_Per_School.png)

## How is the school summary affected?
The complete school summary includes 15 schools, with an overall passing grade of 65%. This summary includes the charter schools, which adds up to a total of 39,170 students and a budget of $24,649,428. The charter schools are included in this summary and we can see the distribution of budget and performance differentiate from the one from the district non charter schools. Even though the average score for math is 78.98 and for reading is 81.87, unfortunately, the overall passing score is low. Specially, when we considering the large budget. 

![School Summary](https://github.com/cynmmarin/School_District_Analysis/blob/3ddb71bb92c0d955baefeabf381b0f5162dbf29c/School%20Summary%20Affected.png)

## How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
### Math and Reading Scores by Grade
We have taken away the Thomas High School’s grades for the 9th grader, given to a believe in fraudulent grading process. Once this score is taken away we see a few changes. The math and reading scores changed, they dramatically, the reading scores decrease to 69.66 from 90.94. Thirds the passing math grade dropped to 66.91 from 97.30. For now we can start to see that there may have been a fraudulent action that has taken place, and but doesn’t not have a large impact on the overall passing grades of the district.   

![Math and Reading Scores](https://github.com/cynmmarin/School_District_Analysis/blob/3ddb71bb92c0d955baefeabf381b0f5162dbf29c/Math%20and%20Reading%20Scores.png)

### Scores by School Spending
When it comes to school spending we see Scores by school spending show that the overall passing average for school with the highest spending range is the one with the lowest over all passing grade. In the other hand the school with the lowest spending range is the one with the highest overall passing grade. 

![School Spending](https://github.com/cynmmarin/School_District_Analysis/blob/3ddb71bb92c0d955baefeabf381b0f5162dbf29c/Scores%20by%20School%20Spending.png)

### Scores by school size 
The schools with the largest population between 2,000 and 5,000, are the ones with the lowest overall passing grade at 58%. The schools with the medium range of 1,000 and 2,000 are the honest with the highest passing grade at 91%. Meanwhile the schools with the smallest size has a medium passing grade of 90%. Therefore, the schools that have a medium size offers the ability to focus on their students and allow them to have a successful academic performance.

![Scores by School Size](https://github.com/cynmmarin/School_District_Analysis/blob/3ddb71bb92c0d955baefeabf381b0f5162dbf29c/Scores%20by%20school%20size%20.png)

### Scores by school type
The school type has the most significant difference out of all the scores distribution. We see that charter schools have an overall passing performance of 91%, in comparison to the district schools that only obtained a 54% of overall passing grades. We can conclude that the charter schools has the ability to provide a higher education and a better distribution of the budget to go into student development.

![Scores by School Type](https://github.com/cynmmarin/School_District_Analysis/blob/3ddb71bb92c0d955baefeabf381b0f5162dbf29c/Scores%20by%20school%20type.png)

## Summary
The four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs were that the overall passing grade decreased from 90% to 65%. The second is that the passing reading grade dropped to 69.66 from 90.94. Third, the passing math grade dropped to 66.91 from 97.30. Lastly, we cannot see significant change in the average of math and reading. Therefore, we can conclude that the THS may possibly be manipulating the math and reading scores on students. However, that may not have a significant impact on the district overall passing scores. 
