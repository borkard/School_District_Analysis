# School_District_Analysis

## Overview of Project
### Purpose
WELL DEFINED PURPOSE GOES HERE OF THE SCHOOL DISTRICT ANALYSIS.

## Results

* **How is the district summary affected?**

By replacing the Thomas High School ninth graders’ math and reading scores with NaNs, the district summary is affected slightly in that the “Average Math Score” is 0.1 point lower than in the initial analysis district summary, which also brings the “% Passing Math” down by 0.2%. The “% Passing Reading” is also down by 0.3% and the “% Overall Passing” is down by 0.1%. Images of the district summaries before and after replacing the ninth graders’ math and reading scores are below.

*Original School_District_Analysis with Thomas High School ninth graders' math & reading scores:
![District_Summary_PyCitySchools](https://github.com/borkard/School_District_Analysis/blob/main/Resources/District_Summary_PyCitySchools.PNG)

*Repeated School_District_Analysis without Thomas High School ninth graders' math & reading scores:
![District_Summary_PyCitySchools_Challenge](https://github.com/borkard/School_District_Analysis/blob/main/Resources/District_Summary_PyCitySchools_Challenge.PNG)


* **How is the school summary affected?**

By replacing the Thomas High School ninth graders’ math and reading scores with NaNs, the school summary is affected for THS in particular in that the points and percentages for “Average Math Score”, “Average Reading Score”, “% Passing Math”, “% Passing Reading”, and “% Overall Passing” all decreased by less than a point or percent. Images of the school summaries before and after replacing the ninth graders’ math and reading scores are below.

*Original School_District_Analysis with Thomas High School ninth graders' math & reading scores:
![school_summary_PyCitySchools](https://github.com/borkard/School_District_Analysis/blob/main/Resources/school_summary_PyCitySchools.PNG)

*Repeated School_District_Analysis without Thomas High School ninth graders' math & reading scores:
![school_summary_PyCitySchools_Challenge](https://github.com/borkard/School_District_Analysis/blob/main/Resources/school_summary_PyCitySchools_Challenge.PNG)


* **How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?**

Relative to the other schools, with or without replacing the ninth graders’ math and reading scores, Thomas High School’s performance ranks as second best in the district. Although the average math and reading scores dropped slightly causing the “% Overall Passing” to drop slightly, Thomas High School still maintains the 2nd highest “% Overall Passing” rate relative to the other schools. Images of the top five schools before and after replacing the ninth graders’ math and reading scores are below.

*Original School_District_Analysis with Thomas High School ninth graders' math & reading scores:
![top_5_schools_PyCitySchools](https://github.com/borkard/School_District_Analysis/blob/main/Resources/top_5_schools_PyCitySchools.PNG)

*Repeated School_District_Analysis without Thomas High School ninth graders' math & reading scores:
![top_5_schools_PyCitySchools_Challenge](https://github.com/borkard/School_District_Analysis/blob/main/Resources/top_5_schools_PyCitySchools_Challenge.PNG)


* **How does replacing the ninth-grade scores affect the following:**

  * **Math and reading scores by grade**
  
  After replacing the Thomas High School ninth graders’ math and reading scores with NaNs, the math and reading scores by grade changed with the obvious substitution of NaN for   both 9th grade math and reading scores where they were previously 83.6 and 83.7 respectively. The average math and reading scores for 10th-12th grade did not change after the   analysis in which the ninth graders’ scores were removed. Images of the math and reading scores by grade before and after replacing the ninth graders’ scores are below.
  
     *Original School_District_Analysis with Thomas High School ninth graders' math & reading scores - Math:
     ![math_scores_by_grade_PyCitySchools](https://github.com/borkard/School_District_Analysis/blob/main/Resources/math_scores_by_grade_PyCitySchools.PNG)

     *Repeated School_District_Analysis without Thomas High School ninth graders' math & reading scores - Math:
     ![math_scores_by_grade_PyCitySchools_Challenge](https://github.com/borkard/School_District_Analysis/blob/main/Resources/math_scores_by_grade_PyCitySchools_Challenge.PNG)

     *Original School_District_Analysis with Thomas High School ninth graders' math & reading scores - Reading:
     ![reading_scores_by_grade_PyCitySchools](https://github.com/borkard/School_District_Analysis/blob/main/Resources/reading_scores_by_grade_PyCitySchools.PNG)

     *Repeated School_District_Analysis without Thomas High School ninth graders' math & reading scores - Reading:
     ![reading_scores_by_grade_PyCitySchools_Challenge](https://github.com/borkard/School_District_Analysis/blob/main/Resources/reading_scores_by_grade_PyCitySchools_Challenge.PNG)


  * **Scores by school spending**
  
  Replacing the Thomas High School ninth graders’ math and reading scores with NaNs had no effect on the scores by school spending. The scores and percentages for “Average Math   Score”, “Average Reading Score”, “% Passing Math”, “% Passing Reading”, and “% Overall Passing” remained the same per spending bin before and after replacing the scores.         Images of the scores by school spending before and after replacing the ninth graders’ scores are below.
  
     *Original School_District_Analysis with Thomas High School ninth graders' math & reading scores:
     ![scores_by_school_spending_PyCitySchools](https://github.com/borkard/School_District_Analysis/blob/main/Resources/scores_by_school_spending_PyCitySchools.PNG)

     *Repeated School_District_Analysis without Thomas High School ninth graders' math & reading scores:
     ![scores_by_school_spending_PyCitySchools_Challenge](https://github.com/borkard/School_District_Analysis/blob/main/Resources/scores_by_school_spending_PyCitySchools_Challenge.PNG)
  
  
  * **Scores by school size**
  
  Replacing the Thomas High School ninth graders’ math and reading scores with NaNs had no effect on the scores by school size. The scores and percentages for “Average Math       Score”, “Average Reading Score”, “% Passing Math”, “% Passing Reading”, and “% Overall Passing” remained the same per school size bin before and after replacing the scores.     Images of the scores by school size before and after replacing the ninth graders’ scores are below.
  
     *Original School_District_Analysis with Thomas High School ninth graders' math & reading scores:
     ![scores_by_school_size_PyCitySchools](https://github.com/borkard/School_District_Analysis/blob/main/Resources/scores_by_school_size_PyCitySchools.PNG)

     *Repeated School_District_Analysis without Thomas High School ninth graders' math & reading scores:
     ![scores_by_school_size_PyCitySchools_Challenge](https://github.com/borkard/School_District_Analysis/blob/main/Resources/scores_by_school_size_PyCitySchools_Challenge.PNG)
     
  
  * **Scores by school type**
  
  Replacing the Thomas High School ninth graders’ math and reading scores with NaNs had no effect on the scores by school type. The scores and percentages for “Average Math       Score”, “Average Reading Score”, “% Passing Math”, “% Passing Reading”, and “% Overall Passing” remained the same per school type bin before and after replacing the scores.     Images of the scores by school type before and after replacing the ninth graders’ scores are below.
  
     *Original School_District_Analysis with Thomas High School ninth graders' math & reading scores:
     ![scores_by_school_type_PyCitySchools](https://github.com/borkard/School_District_Analysis/blob/main/Resources/scores_by_school_type_PyCitySchools.PNG)

     *Repeated School_District_Analysis without Thomas High School ninth graders' math & reading scores:
     ![scores_by_school_type_PyCitySchools_Challenge](https://github.com/borkard/School_District_Analysis/blob/main/Resources/scores_by_school_type_PyCitySchools_Challenge.PNG)


## Summary
Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
