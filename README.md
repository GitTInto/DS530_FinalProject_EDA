# Exploratory Data Analysis on Factors Affecting Students Performance.

## Statistical Question/Hypothesis :


1. Does gender of the student affect the performance of the student in the exams?
2. Does race/ethnicity of the student effect the performance of the student in the exams?
3. How does the parent’s education level effect the performance of student?
4. Does the availability of a subsidized lunch have any effect on the performance of a student?
5. Does taking the test preparation course have any effect on the performance of student in the exam?

## Summary of Regression analysis: 

### For regression analysis math_score as a function of test_preparation_course
 
we saw that can see the slope and the intercept are statistically significant, which means that they were unlikely to occur by chance, but the R2 value for this model is small. which means that "test preparation course" doesn’t account for a substantial part of the variation in math score.
 
### For math_score as a function of lunch
 
we saw that the slope and the intercept are statistically significant, which means that they were unlikely to occur by chance, and we see the R2 value for this model also significant. which means that "lunch” accounts for a 12% of the variation in math score.
 
### For math_score as a function of test_preparation_course+race_ethnicity+lunch+parental_level_of_education+gender
 
we saw that test_preparation_course+race_ethnicity+lunch+parental_level_of_education+gender accounts for 25% (R2 0.255) of the variation in math score
 
### For writing_score as a function of test_preparation_course+race_ethnicity+lunch+parental_level_of_education+gender
 
test_preparation_course+race_ethnicity+lunch+parental_level_of_education+gender accounts for 33.4% of the variation in writing score
 
 
### For reading_score as a function of test_preparation_course+race_ethnicity+lunch+parental_level_of_education+gender
 
test_preparation_course+race_ethnicity+lunch+parental_level_of_education+gender accounts for 22.7% of the variation in reading score
