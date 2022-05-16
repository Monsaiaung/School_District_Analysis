# School_District_Analysis

## Overview of the analysis

The purpose of the analysis is remove school data that have some evidences of academic disonesty. The grades that have been altered were math and reading scores of ninth graders in Thomas High School. In order to upload state-testing standards, the math and reading scores of ninth graders in Thomas High School will be replaced with NaNs while keeping the rest of the data. Then a report will be written to show how the clean-up affected the overall analysis. 

## Deliverables

- Deliverable 1: Replace ninth-grade reading and math scores
- Deliverable 2: Repeat the school district analysis
- Deliverable 3: A written report for the school district analysis (README.md)

## Results

- How is the district summary affected?

Before removing Thomas High School ninth graders out of the dataset.
![Beforedistrictsummary](https://github.com/Monsaiaung/School_District_Analysis/blob/8e9e600a87b660b7beee188b607039f1f44b6ae6/Resources/BeforeDistrictSummary.png)
Afer removing Thomas High School ninth graders out ouf the dataset.
![Districtsummary](https://github.com/Monsaiaung/School_District_Analysis/blob/8e9e600a87b660b7beee188b607039f1f44b6ae6/Resources/DistrictSummary.png)

As seen in the images above, Average Math Score, % Passing Math, % Passing Reading, and % Overall Passing all decreased by some decimal points after taking Thomas High School ninth graders out of the dataset. However, Average Reading Score doesn't seem to be affected.



- How is the school summary affected?
![BeforeSchoolSummary](https://github.com/Monsaiaung/School_District_Analysis/blob/7987a794ca4bbb4a324e7872af8abe000f178289/Resources/AfterSchoolSummary.png)

![AfterSchoolSummary](https://github.com/Monsaiaung/School_District_Analysis/blob/7987a794ca4bbb4a324e7872af8abe000f178289/Resources/BeforeSchoolSummary.png)

After the clean-up of Thomas School School data, % Passing Math decreased from 93% to 67%, % Passing Reading decreased from 97% to 70% and % Overall Passing decreased from 91% to 65%.


- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

 After replacing ninth graders’ math and reading scores of Thomas High School’s performance, its ranking went down from 2nd place to 8th place relative to the other schools.
 
 
 
### How does replacing the ninth-grade scores affect the following:
- Math and reading scores by grade

Math and Reading Scores from Thomas High School 9th Grade were replaced and set to "nan". After cleaning the data, the student count of Thomas High School decreased from 1635 to 1174.The average math and reading scores of other grades only increased slighty by decimal points after replacing the ninth-grade scores.

- Scores by school spending

Thomas High School Spending bracket falls into $630-644. There weren't big affect in school spending by replacing ninth-grade scores.
![SchoolSpending](https://github.com/Monsaiaung/School_District_Analysis/blob/d90653daf7e0b603a9d33056ba917837efc2df05/Resources/BeforeSchoolSpending.png)

- Scores by school size
Scores by school size didn't have any affect by replacing ninth-grade scores.
![SchoolSpending](https://github.com/Monsaiaung/School_District_Analysis/blob/d90653daf7e0b603a9d33056ba917837efc2df05/Resources/BeforeSchoolSpending.png)
- Scores by school type
- 
Scores by school type didn't have any affect by replacing ninth-grade scores.
![SchoolSpending](https://github.com/Monsaiaung/School_District_Analysis/blob/d90653daf7e0b603a9d33056ba917837efc2df05/Resources/BeforeSchoolSpending.png)
