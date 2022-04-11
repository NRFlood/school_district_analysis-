# School District Analysis using Pandas

## Overview of School District Analysis

The purpose of this project was to assist Maria in auditing the math and reading scores for all of the schools within the district.  After learning of potential academic dishonesty at Thomas High School we leveraged the Pandas library in combination with the Jupyter Notebook to clean up the data, and set all 9th grade reading and math scores to NaN at Thomas High School.  With that data corrected we were then able to rerun the school district analysis to determine how the overall results were impacted.

## School District Analysis Results

By using Pandas I was able to generate a new data frame that would allow me to rerun the math and reading scores for Thomas High School, without the 9th grade scores included. This in turn impacted the average math and reading scores for the district overall as well as the scores for the various categories that Thomas High School is apart of (School type, School size, School spending). 

**How is the district summary affected?**

*The percentage of students passing math within the district declined by 22 basis points (74.98% to 74.76%), and the percentage of students passing reading declined by 15 basis points (85.81% to 85.66%) after removing the Thomas High School ninth graders'.  The average math score in the district declined by 6 basis points(78.99% to 78.93%) and the average reading score declined by 2 basis points (81.88% to 81.86%) after making the same adjustments.*   
    
**How is the school summary affected?**

*The percentage of students passing math at Thomas High School declined by 8 basis points (93.27% to 93.19%), and the percentage of students passing reading declined by 29 basis points after removing the scores from the ninth grade class.  The average math score at Thomas High School declined by 7 basis points (83.42% to 83.35%), and the average reading score improved by 5 basis points (83.85% to 83.90%) after making the same adjustment.* 

**How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

* Relatvie to other schools Thomas High School still remains at #2 overall, however the decline in math scores no puts them below Griffin High School 



*How does replacing the ninth-grade scores affect the following:*

   -Math and reading scores by grade*

   -Scores by school spending*

   -Scores by school size*

   -Scores by school type*

 
