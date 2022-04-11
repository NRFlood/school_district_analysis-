# School District Analysis using Pandas

## Overview of School District Analysis

The purpose of this project was to assist Maria in auditing the math and reading scores for all of the schools within the district.  After learning of potential academic dishonesty at Thomas High School we leveraged the Pandas library in combination with the Jupyter Notebook to clean up the data, and set all 9th grade reading and math scores to NaN at Thomas High School.  With that data corrected we were then able to rerun the school district analysis to determine how the overall results were impacted.

## School District Analysis Results

By using Pandas I was able to generate a new data frame that would allow me to rerun the math and reading scores for Thomas High School, without the 9th grade scores included. This in turn impacted the average math and reading scores for the district overall as well as the scores for the various categories that Thomas High School is apart of (School type, School size, School spending). 

**How is the district summary affected?**

*The percentage of students passing math within the district declined by 22 basis points (74.98% to 74.76%), and the percentage of students passing reading declined by 15 basis points (85.81% to 85.66%) after removing the Thomas High School ninth graders'.  As a result the percentage of students passing both math and reading declined by 31 basis points (65.17% to 64.86%) overall.  In addition the average math score in the district declined by 6 basis points(78.99% to 78.93%) and the average reading score declined by 2 basis points (81.88% to 81.86%) after making the same adjustments.*   
    
**How is the school summary affected?**

*The percentage of students passing math at Thomas High School declined by 8 basis points (93.27% to 93.19%), and the percentage of students passing reading declined by 29 basis points (97.31% to 97.02%) after removing the scores from the ninth grade class.  As a result the percentage of students passing both math and reading at Thomas High School declined 32 basis points (90.95% to 90.63%). In addition the average math score at Thomas High School declined by 7 basis points (83.42% to 83.35%), and the average reading score improved by 5 basis points (83.85% to 83.90%) after making the same adjustments.* 

**How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

*Relatvie to other schools Thomas High School still remains at #2 overall, however the decline in the percentage of students passing math and reading, as well as the decline in the average math scores now puts them only 3 basis points above Griffin High School overall, whereas before they had been 35 basis points ahead of Griffin High School.*

**How does replacing the ninth-grade scores affect the following:**

   * **Math and reading scores by grade**
   
       *The math and reading scores at other schools are not impacted in anyway by the corrections that were made to the ninth grade data at Thomas High School, nor were the scores of the 10th, 11th, and 12th graders at Thomas High School.  When slicing the data by grade the district level scores at the ninth grade level are the only ones that should be impacted by the change at Thomas High School.* 
   
   * **Scores by school spending**
       
       *Thomas High School is part of the per student spending range of $631-645, so this is the only range impacted by the change in data.  The images below showcase the changes in that spending range.

![BEFORE](https://github.com/NRFlood/school_district_analysis-/blob/main/Spending%20Range%20(Before).png)

![AFTER](https://github.com/NRFlood/school_district_analysis-/blob/main/Spending%20Range%20(After).png)

   * **Scores by school size**

   * **Scores by school type**

 
