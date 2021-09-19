# School_District_Analysis

## Overview
Now that we have completed the School District Analysis, the school board suspect that there may have been some academic dishonesty from the 9th grade class at Thomas High School. With this in mind Maria has asked us to fix the data so that the potential 9th grade reading and math scores do not have a negative impact on the true averages for the district. To do this the school board has asked that I replace all the 9th grade reading and math scores while retaining all the other data associated intact.

## Results
With our School District Analysis modified to exclude the 9th grade reading and math scores from Thomas High School, we can see how if at all our results have changed.
- How is the district summary affected?
  - With the Thomas High School 9th grade reading and math scores removed from the data set there was a very small change in the averages downward.
  - The average math and reading score hardly changed: Math 79 to 78.9 and Reading 81.9 to 81.9.
  - The change was more pronounced in the Percent Passing in Math, Reading and the Overall Passing which all dropped one percentage point. Math 75 to 74, Reading 86 to 85, and Overall 65 to 64. 

![School Summary](https://github.com/PSWil/School_District_Analysis/blob/main/School_Summary.png)
![School Summary Clean](https://github.com/PSWil/School_District_Analysis/blob/main/School_Summary_clean.png)

- How is the school summary affected?
  - Thomas High School's summary took a large impact when we removed the 9th grades reading and math scores.
  - Before cleaning the data Thomas High School's overall passing percentage was 91%, after cleaning the data the passing percentage was only 65%.
  - While the average math and reading scores for Thomas did not changed substantially. 
  - The percent passing math dropped from 93.2 to 66.9, the percent passing reading dropped from 97 to 69.7, and the percent passing overall dropped from 90.6 to 65.1.
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  - Thomas High School ranking after removing the scores changed drastically with their district ranking droping from 2nd to 8th when we removed the 9th grade reading and math scores.
- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade? When we set the 9th grade reading and math scores to NaN this was equivalent to converting the scores to 0. The totals for Thomas High School percentage passing reading and math drop substantially seeing as the 9th grade scores are equal to 0.
  - Scores by school spending? Thomas High School sits in the $630-644 spending bracket and when we remove the 9th grade scores the percentages drop again. The percent passing math dropped from 73 to 67, the percent passing reading dropped from 84 to 77, and the percent passing overall dropped from 63 to 56.
  - Scores by school size? With 1635 students, Thomas High School is classified as a medium school in the district (1000 - 2000 students). Removing the 9th grade reading and math scores impacts the medium school percent passing averages negatively as well. Percent passing math dropped from 94 to 88, the percent passing reading dropped from 97 to 93, and the percent passing overall for medium size schools dropped from 91 to 85.
  - Scores by school type? Thomas High School is classified as a Charter school acording to the district. When we remove the 9th grade scores the percent passing averages drop, but not by as much when considering school spending and school size. The percent passing math dropped from 94 to 90, the percent passing reading dropped from 97 to 93, and the percent passing overall dropped from 90 to 87.

## Summary 
