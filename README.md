# School_District_Analysis
Using Pandas and Jupyter Notebook with Python

## Overview of the school district analysis:
The school board has contacted Maria to help with some analysis on the school and student data so they could make plans for their upcoming academic year. Maria seeked our help to complete the school district analysis where we combined two datasets, cleaned the data and did a bunch of calculations such as;
- Average Math Score
- Average Reading Score
- Average % Passing Math
- Average % Passing Reading
- Average % Overall Passing

After our initial analysis, the school board notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. 

We are here to help Maria replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once we replaced the math and reading scores, we repeated the school district analysis to see how these changes affected the overall analysis.

## Results of the School District Analysis

### How is the district summary affected?

We can compare the two images below that shows the old District summary in comparison to the new one to see that the Average Math Score, % Passing Math, % Passing Reading, and % Overall Passing were slightly affected and went down when we removed the data for 9th graders of Thomas High School. 

#### Old District Summary

<p align="left">
  <img src="/Images/Old District Summary.png">
  </p>


#### New District Summary


<p align="left">
  <img src="/Images/New District Summary.png">
  </p>


## How is the school summary affected?

We can compare the two images below to see that other than Thomas High School(THS), all the other schools remained uneffected. After removing the math and reading scores for the 9th graders at THS, the % passing math, reading and overall went up quite a bit. 

#### Old School Summary

<p align="left">
  <img src="/Images/Old School Summary.png">
  </p>


#### New School Summary


<p align="left">
  <img src="/Images/New School Summary.png">
  </p>

## How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

While comparing the images below, we can see that even though the overall passing percentage for Thomas High School went down from 90.95 to 90.63, that slight reduction did not change the relative performance for THS in comparison to other schools and they still remained at 2nd place.

#### Old Top School

<p align="left">
  <img src="/Images/Old_top_schools.png">
  </p>


#### New Top School


<p align="left">
  <img src="/Images/New_top_schools.png">
  </p>


## How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade
- when looking at math and reading score by grade, all the schools remained unaffected except THS ninth grade scores returned a NaN value.

Scores by school spending
Scores by school size
Scores by school type
