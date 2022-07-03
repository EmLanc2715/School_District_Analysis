# School_District_Analysis
Anaconda, Jupyter, Python

## Overview 

Student funding information and standarized math and reading test results from 15 high schools were analyzed to help better understand perfromance trends and patterns.

### Purpose

The purpose of this analysis was to give information to the School Board and Superintendent, so that they could make decisions concerning school budgets and priorities. During this analysis, it was brought to my attention that there was evidence of academic dishonesty in the data. Specifically, Thomas High Schools ninth grade readiang and math scores. My colleague Maria and I were tasked to replace all of the Thomas High Schools ninth grade reading and math scores with NaNs, and then repeat the analysis to detect if there were an changes that affected the overall analysis.

## Results

### How is the district summary affected?

Overall the district summary was marginally affected by excluding data from Thomas High Schools ninth grade class. The overall passing percentage dropped from 65.2% to 64.9%, a negligble difference.

![School_district_summaries](https://user-images.githubusercontent.com/101427781/177053938-42794bea-4ea1-4674-aa1e-b7cab40150c1.png)

### How is the school summary affected?

The school summary was greatly affected by the change of scores. The Thomas High School percentage passing math went from a 90.9% down to 66.9%. Consequently, the percentage passing reading was also affected and dropped from a 97.3% to a 69.7%. The overally passing percentage however, as mentioned above, were close to equal.

![School_summary_comparision](https://user-images.githubusercontent.com/101427781/177053923-b9300fd6-b008-4fbc-b97f-ea79ba3cf4a4.png)

### How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?

Thomas High Schools's performance relative to other schools changed dramatically. They have fallen from being ranked the 3rd school to the 13th in performance after the changes had been made.

![School_rank](https://user-images.githubusercontent.com/101427781/177054423-19f479bc-7a4e-4b66-9449-e5a59dec68dd.png)

### How does replacing the ninth-grade scores affect the following?

  #### Math and reading scores by grade
  
  There was no change to the math and reading scores by grade because in the new analysis the 9th grade scores for Thomas High School is Nan, as shown in the image.
  
  ![Ninth_grade_scores](https://user-images.githubusercontent.com/101427781/177054603-d65f16ff-7558-4c30-8a92-aacd8f1c6e34.png)

  #### Scores by school spending
  
  The scores by school spending were unaffected. THere was a slight change in the % passing reading column for the $631-$645 range. In the original analysis the       percentage was 84% and in the revised analysis the percentage is 83%
 
 ![Spending](https://user-images.githubusercontent.com/101427781/177054837-e539698d-bac7-4061-bc6f-f978d3119199.png)

  #### Scores by school size
  
  There is no difference betweem scores by school size, as shown in the image.
  
  ![Scores_vs_Size](https://user-images.githubusercontent.com/101427781/177055053-70f38db3-a411-4229-b47e-81abe7acddae.png)

  #### Scores by school type
  
  There was a 1% change in the scores by school type in the % passing reading column, as shown in the image below.
  
  ![Scores_vs_Type](https://user-images.githubusercontent.com/101427781/177055125-b634eaf5-6c31-481a-9052-8fb87c5b8893.png)

## Summary

There were varied changes to the data after replacing the Thomas High's ninth grade reading and math scores with NaNs. There were metrics left unchanged, for example; scores by school size amd scores by school spending.

Unfortunately, due to the academic dishonesty in Thomas High's ninth grade class, other metrics of the analysis were indeed impacted.
  1. The overall passing percentage for Thomas High fell considerably from 91% to 65%.
  2. Thomas High Schools overall ranking between the 15 districts fell from 3rd to 13th.
  3. The district summary changed from an overall passing percentage of 65.2% to 64.9%.
  4. The math and reading scores for the ninth grade class at Thomas High School were changed from 83.6% for math and from 83.7% for reading to NaNs, which reflects        poorly on the high school.
