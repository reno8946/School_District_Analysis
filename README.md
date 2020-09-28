# School_District_Analysis

## Overview of School District Analysis
The students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards. For this challenge, we are to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact and then repeat the school district analysis that we did in the module and write up a report to describe how these changes affected the overall analysis.

## Resources
-Data Source: schools_complete.csv
              students_complete.csv

-Software: Python 3.7.8 (Anaconda), Jupyter Notebook

## School District Analysis Results

-How is the district summary affected?
  
  - When running the district_summary_df in the module, this was the result:
  
  ![image](https://user-images.githubusercontent.com/70483866/94389178-be620280-0114-11eb-8b60-79e54390907a.png)
  
  - When running, the district_summary_df in the challenge, this was the result: 
  
  ![image](https://user-images.githubusercontent.com/70483866/94389316-26184d80-0115-11eb-9f95-dc79500f52eb.png)

    -Although negligible, there was a slight decrease for the percent passing math, reading, and overall passing.
    
-How is the school summary affected?

   - When running the per_school_summary_df in the module, this was the result as you can see Thomas High School in the bottom row of the table:
   
   
![image](https://user-images.githubusercontent.com/70483866/94389756-498fc800-0116-11eb-8f9e-dbc102c6970a.png)

   - When runniing the per_school_summary_df in the challenge with passing math, passing reading, and overall passing percentages updated after removing 9th graders for Thomas       High School, here is the result:
   
 ![image](https://user-images.githubusercontent.com/70483866/94389975-f79b7200-0116-11eb-93a6-686ab300680a.png)
 
-How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
 
      -The passing math, passing reading, and overall passing percentages skyrocketed once replacing the math and reading scores of 9th graders with NaN by nearly 30% among the three categories and brought Thomas High School within the top 5 best performing schools.

-How does replacing the ninth-grade scores affect the following:

  - Math and reading scores by grade:
  
  - Scores by school spending:
  
  - Scores by school size:
  
  - Scores by school type:
  
      -Overall, there were no differences found between math and reading scores by grade, scores by school spending, scores by school size, and scores by school type when replacing the 9th grade scores. While it did affect specifically Thomas High School's rank, it did not have an effect on the overall big picture between when it was ran in the module versus in the challenge. See charts below to notice the lack of difference in outputs from what was ran in the module exercise.
      
![image](https://user-images.githubusercontent.com/70483866/94391056-223afa00-011a-11eb-9cce-b3ae432100d6.png)

![image](https://user-images.githubusercontent.com/70483866/94391095-3f6fc880-011a-11eb-956a-7780fd77d3ca.png)

![image](https://user-images.githubusercontent.com/70483866/94391127-557d8900-011a-11eb-8ac0-d08196176f20.png)

      
## School District Analysis Summary

Overall, after replacing the 9th grade reading and math scores at Thomas High School with NaN, the overall big picture didn't change a whole lot. However, Thomas High School did see a drastic increase in their:

  - Math passing percentage (66.915 -> 93.18%)
  
  - Reading passing percentage (69.66% -> 97.01%)
  
  - Overall passing percentage (65.07% -> 90.63%)  
  
  - This propelled them from one of the lower tier performing schools to within the top five best performing schools in the district at second place overall, right behind Cabrera High School

![image](https://user-images.githubusercontent.com/70483866/94391529-46e3a180-011b-11eb-99c3-bc738c74fad8.png)


