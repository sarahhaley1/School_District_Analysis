# School_District_Analysis

## Overview of school district analysis
### Background
The school board has claimed that the scores in the students_complete.csv file look as though they have been altered. 
#### Purpose
The purpose of this analysis was is to verify any academic integrity. We can look at the data in a single dataframe with pandas built in package in python. This allows for the comparison of the math & reading scores from Thomas High School with the other High Schools in the dataset to find if there was academic dishonesty with the scores reported from Thomas High School for the ninth graders. The reason to find this is to uphold the state testing standards. 
We were able to obtain the values of test scores for each grade in each school to see the result difference when Thomas High School 9th graders' math and reading scores were negated from the data set. This will help us verify the academic dihonesty that is suspected.

## Results

#### District Summary 
  - When removing the ninth grade scores from Thomas High School we can see that our district summary data frame does change. The total number of students goes down, and the overall passing rate also decreases. However, the total budget, average Math score, average reading score, percent passing math, and percent passing reading stay the same. The affects on the students and passing rates go down with the removal of the ninth grade students from Thomas High School, because the dishonesty in the ninth grader scores shifts the data of overall passing rate to be lower since their scores were falsified, and data was removed. 


#### School Summary
  - When removing the ninth grade scores from Thomas High School we can see that our school summary data frame changes for Thomas High School only. It significantly decreases their overall passing score because we no longer include the false scores of the ninth grade students. Since the scores were so positively affected by the ninth graders' scores, we can see that there was an issue with the scores reported for that class at Thomas High School.
  
#### Replacing Ninth Graders' math and reading scores relative affect
  - When we replace the ninth grade scores NaN and only account for the 10th - 12th graders at Thomas High School, we see that the overall passing for Thomas High School in comparison to other schools we see that there is a very high passing rate compared to other schools in the data set. When we replace the scores, we see that Thomas High School is apart of the top 5 as number 2 statistics wise. Thus we see that Thomas High School is a high performing school, even with the ninth grade scores taken out. However, we aren't able to compare the ninth grade class at Thomas High School to other schools, which takes out data, making Thomas High School look like they are performing better. The passing rate increases immensely when we remove 9th grade from Thomas High School data. 
  
#### Math and reading scores by grade
  - When replacing ninth grade scores at Thomas High School, we see that it negates the scores for 9th graders at Thomas High School but everything else stays relatively the same. 
  
#### Scores by school spending
  - When replacing the ninth grade scores at Thomas High School with NaN, we see that the scores based on school spending does not change the dataframe. The average reading and math scores, as well as the percentage rates do not change. 
  
 #### Scores by school size
  - When replacing the ninth grade scores at Thomas High School with NaN, we see that the scores based on school size does not change the data frame. The average reading and math scores, as well we the percentage rates do not change with the negation of ninth graders' at Thomas High School.
  
 #### Scores by school type
  - When replacing the ninth grade scores at Thomas High School with NaN, we see that the scores based on school size does not change the data frame. The average reading and math scores, as well we the percentage rates do not change with the negation of ninth graders' at Thomas High School.
  
 ## Summary 
 There are four major changes to the school district summary analysis due to the negation of ninth graders' scores at Thomas High School. The first change is the overall passing rate column in the school district summary data frame. When we removed the 9th grade scores, we see a dramatic decrease in the overall passing rate for the district summary since the ninth grade scores were so high. The inccorrect data gave the validation for the unchanged dataset including academic dishonesty. The second major change was the total number of students. Taking out the 9th graders reduces the total number of students. The third major change was in the school summary data frame. When removing the 9th graders' scores, we see a dramatic increase in the school overall passing rate for Thomas High school because we took out the 9th grade data and compared the passing rate wiht only the 10th-12th graders at Thomas High School. The fourth major change was that when removing the 9th graders and only accounting for the 10th - 12th graders at Thomas High School, we see that their school summary changes in the percent overall passing column due to the reduces student population. The studnets at Thomas High School were individually compared to a smaller number of students, making them rank higher in the school summary because we removed data. 
 
 
