Annette Blackburn


# PyCity School District Analysis

## Overview of School District Analysis

The purpose of this school district analysis is to analyze students’ standardized test scores (math and reading) relative to school funding (overall budget, funding per student), size, and type (District or Charter). Due to possible academic dishonesty, both math and reading standardized test scores from ninth graders at Thomas High School were replaced with non-numeric values for the analysis.

## Results

### How the District Summary is Affected

- The district summary with all students’ scores included had an average math score of 79.0 with 75% of students passing math and an average reading score of 81.9 with 86% passing reading. 
- The district summary with Thomas High School’s ninth grade score replaced with non-numeric values had an average math score of 78.9 with 74.8% passing math and an average reading score of 81.9 with 85.7% passing reading. 
- The main differences between the district summaries with and without Thomas High School’s ninth graders are a lower average math score, a lower percent passing math, and a lower percent passing reading. 

### How the School Summary is Affected

- The school summary is only affected for Thomas High School (THS). 
- Including the possible academic dishonesty, the average math score was 83.35 with 90.6% passing math and the average reading score was 83.89 with 90.6% passing reading. 
- Excluding the possible academic dishonesty, the average math score was 83.35 with 93.18% passing math and the average reading score was 83.89 with 90.6% passing reading. 
- Excluding the ninth graders at THS affected the summary by increasing the percent of students who are passing math.

! [School Summary Including THS Ninth Grade Scores](school_summary_including_9th_THS.png)
! [School Summary Excluding THS Ninth Grade Scores](school_summary_excluding_9th_THS.png)

### How Replacing the Ninth Graders' Math and Reading Score Affect Thomas High School's Performance 

- Since only 461 students’ scores were not included in a sample of over 37,000, replacing ninth graders’ math and reading scores did not drastically affect THS’s performance relative to the other schools (i.e., the percent passing reading is 90.6% including and excluding the ninth graders).

#### Replacing Ninth Graders' THS Scores Affect Relative to Other Schools

- Replacing the ninth grade scores changed the average scores for THS ninth graders to “NaN” and did not change the scores for the tenth, eleventh, and twelfth graders.


#### Replacing Ninth Graders' THS Scores Affect Math and Reading Scores by Grade

- THS has a per student budget of $637.00, which is in the $631-$645 bin. 
- Before replacing the scores, schools in this spending range had an average math score of 78.5 and average reading score of 81.6. 
- After replacing the scores, schools in this per student spending range had an average math score of 81.89 and average reading score of 75.65. 
- Overall, replacing THS ninth grade scores increased the average math score by roughly 3 points and decreased the average reading score by nearly 5 points.  

#### Replacing Ninth Graders' THS Scores Affect Math and Reading Scores by School Spending Per Students

- THS is a medium sized school (with between 1000 and 1999 students).
- Before replacing the scores, medium schools had an average math score of 83.37 and an average reading score of 83.86. 
- After replacing the scores, medium schools have an average math score of 83.36 and an average reading score of 83.87.
- Overall, replacing THS ninth grade scores decreased the average math score by 0.01 and increased the average reading score by 0.01. 

! [School Spending Summary Including THS Ninth Grade Scores](school_spending_including_9th_THS.png)
! [School Spending Summary Excluding THS Ninth Grade Scores](school_spending_excluding_9th_THS.png)

#### Replacing Ninth Graders' THS Scores Affect Math and Reading Scores by School Size 

- THS is a Charter school. 
- Before replacing the scores, Charter schools had an average math score of 83.46 and reading score of 83.90. 
- After replacing the scores, Charter schools have an average math score of 83.46 and reading score of 83.90. 
- Overall, replacing THS ninth grade scores the average math resulted in no change in math or reading scores.

#### Replacing Ninth Graders' THS Scores Affect Math and Reading Scores by School Type

- After reading and math scores for the ninth grade at THS have been replaced, the scores by school size were marginally affected, the scores by school type were not affected, the overall school summary is not affected; however, the math and reading scores by school spending change dramatically: average math scores increased by roughly 3 points and average reading scores decreased by roughly 5 points.
