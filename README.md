# **School_District_Analysis**


## **Overview of the school district analysis**

### The purpose of this analysis was to audit the results of the state-wide testing for reading and math. The school board claimed that there was acamedic dishonesty commmited during the testing. Specifically, Maria was tasked to look into the reading and math grades for Thomas High School, based on the evidence presented to her. The goal was to replace the reading and math scores of Thomas High School with "NaNs" while keeping the rest of the data intact. Then, repeat the analysis and write a description of how the changes affected the overall analysis.

## **Results**

### After careful analysis, the following results were shown:
    
  - **District Summary**
    - The changes in math and reading scores of Thomas High School did not significantly affect the overall district test performance summary. The difference is too small to declare that there was a massive extent of academic dishonesty that occured during testing. It is also important to note the average reading remained the same.

 *Before audit district summary*
<img width="933" alt="district_summary_before" src="https://user-images.githubusercontent.com/96095956/151729576-92cd25e6-d24b-40c6-aa87-457f3154f708.PNG">
*After audit district summary*
<img width="933" alt="district_summary_after" src="https://user-images.githubusercontent.com/96095956/151729577-deaf37d3-247a-4c7a-8ecc-07562ddf0819.PNG">

  - **School Summary and Thomas High School's Performance**
    - Changes in the reading and math scores of 9th grade students of Thomas High School did not substantially affect it's overall performance. Despite replacing 9th grade scores with "NaNs", Thomas High School remained in the top five performing schools. Other schools' data remained the same.
   
  *Before*
<img width="992" alt="top_performing_before" src="https://user-images.githubusercontent.com/96095956/151732932-215d355f-84e1-4865-9004-fb4c9a0232c1.png">
  *After*
 <img width="998" alt="top_performing_after" src="https://user-images.githubusercontent.com/96095956/151733546-f09e60a6-dcd3-4b7f-8d1e-4b73f7738d3d.PNG">
 
 - **Effect of changing 9th grade scores**
  - Changing 9th grade scores in math and reading did not have any distinguishable effect on reading and math scores of other grade levels. Since only Thomas High School had the change, the rest of the data or result remained the same. The same can be said for school spending data frame, school size data frame, and school type data frame.
 
*Math Scores*
 
 <img width="313" alt="math_scores_by_grade" src="https://user-images.githubusercontent.com/96095956/151735988-2fb1ae18-b6e7-4d1e-b774-40c9d572ed86.PNG">

*Reading Scores*

<img width="311" alt="reading_scores_by_grade" src="https://user-images.githubusercontent.com/96095956/151735991-6a178870-815a-4167-893a-2f3c6d069e67.PNG">

 *School Spending*
 
  <img width="840" alt="spending_range" src="https://user-images.githubusercontent.com/96095956/151736692-a363174f-cd0b-4c30-a194-f63c679cf782.PNG">

  *School Size*
  
   <img width="714" alt="school_type" src="https://user-images.githubusercontent.com/96095956/151736680-35d24e34-2134-4200-a8b5-0952b51b1eb2.PNG">

  *School Type*
  
  <img width="714" alt="school_type" src="https://user-images.githubusercontent.com/96095956/151736707-b19cc939-fbc1-4d85-ac73-80969a666cbe.PNG">

## **Summary**

### After careful analysis, the data shows that there is not a substantial effect when the 9th grade scores for math and reading of Thomas High School were replaced with "NaNs". This is because the district summary remained virtually the same before and after the implementation of the saide change. The same can be said for the school summary. Thomas High School's performance in comparison with other schools remained the same as it stayed in the top five performing schools. The math and reading scores were replaced with "NaNs" but the rest of the data remained intact. This would mean that school size, school spending, and school types data frames did not substantially change, if there was a change at all. 
