# Module 4: PyCitySchools with Pandas
## An Introduction to Pandas and Jupyter Notebook
- - -
## Overview of the Project
In this module activity we were introduced to Jupyter notebook and the pandas library for python.  To practice with these new tools we helped "Maria" extrapolate and analyze data about funding and standardized test scores collected from all of the schools in a school district.  From this data analysis, the school board should be able to make decisions about future budgeting.  To prepare the data, we had to first check each of our data sets for any missing or inaccurate information.  Once complete, we merged the data about the students and schools into one complete dataset.  Finally, we were able to run some statistical measures to evaluate if there was any correlation between standardized test scores and school size, spending per student, and/or type of school (district vs charter).  However, After we completed our module we became aware of a potential issue with scholastic dishonesty within one of the schools.  So, we were asked to remove the potentially compromised data and rerun our analysis.
- - -
## Results and Summary
[See source code](https://github.com/murphyk2021/School_District_Analysis/blob/7c4da0d17664b5e62b9b9d07894b5f2e05ea3843/School_District_Analysis/PyCitySchools_Challenge_testing.ipynb)

- **How is the district summary affected?** After we removed the 461 students in the 9th grade attending Thomas High School, the district summary did not change significantly as seen in the data below.  The totaly number of schools, students, and budget all remained the same, of course, while the standardized test scores were only minimally influenced.
![image showing district summary](https://github.com/murphyk2021/School_District_Analysis/blob/3a8ad1fb13a91250c5d48cf39b1b3f35328d35cd/School_District_Analysis/Resources/District%20summary.PNG)

- **How is the school summary affected?**  The statistics for Thomas High School as a whole also did not change very significantly.  Even though we removed 461 students, there was still a high percentage that passed the standardized exams.  It was important, however, to adjust our perentage calculations to account for the nullified grades as we can see in the data table below.  In the first two rows our percentage of students passing math, reading, and both math and reading was based off of the total students attending the school.  The last row calculated the percent passing based on the number of students who had grades for the math and reading exams.

![image showing school summary](https://github.com/murphyk2021/School_District_Analysis/blob/3a8ad1fb13a91250c5d48cf39b1b3f35328d35cd/School_District_Analysis/Resources/school%20summary.PNG)

- **How does replacing the 9th graders' math and reading scores affect Thomas High School's performance relative to the other schools?** With the adjusted calculations, Thomas High School still placed second in terms of overall performance when compared to the other schools in the school district.

- **In addition, the removal of the 9th Grade scores From Thomas High School did not appear to change the correlations between standardized test scores and school spending, size, or type.**

- - -


