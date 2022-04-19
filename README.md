School District Analysis
## Overview of the Project
### Purpose
The purpose of this project is to report state testing scores in math and reading for 9th-12th graders at 15 specific high schools in a school district. An initial analysis was conducted, then under suspicion of academic dishonesty, all scores for 9th grade students at one school - Thomas High School - were replaced with NaNs and the analysis was re-run. This report reviews the effects of replacing the scores with NaNs on the school district as a whole, as well as the schools individually, particularly Thomas High School, and scores by grade, by school spending, school size, and school type. 

### Results
- Effects to school district summary
  - After re-running the analysis, it appears that for the school district as a whole, average reading and math scores, as well as passing percentages, were not significantly impacted by removing the 9th grade scores from Thomas High School. At most, scores changed by .3%. 

Initial Analysis with Thomas High School's 9th Grade Scores
![School_District_with_THS](https://github.com/nikkiheaston/School_District_Analysis/blob/main/Resources/District_Summary_with_THS9th.PNG)


Re-run Analysis with Thomas High School's Scores Replaced with NaNs
![School_District_without_THS](https://github.com/nikkiheaston/School_District_Analysis/blob/main/Resources/District_Summary_without_THS9th.PNG)

- Effects to school summary
  - Re-running the analysis only impacted Thomas High School's metrics particularly to the passing percentages (defined by receving 70% or higher), as shown in the DataFrames below. Prior to replacing the scores with NaNs Thomas High School had performed relatively well, with passing percentages at 93% for math and 97% for reading. Then, replacing the 9th grade scores with NaNs caused the percentages to drop significantly - to 67% and 70% respectively. Finally, re-running the data using only scores for 10th-12th graders brought the percentages back up - to 93% and 97% as before.
 
 Initial Analysis with Thomas High School's 9th Grade Scores
 ![THS_with_9th_scores](https://github.com/nikkiheaston/School_District_Analysis/blob/main/Resources/Per_school_summary_THS_included.PNG)
 
 Replacing Thomas High School's 9th Grade Scores with NaNs
 ![THS_replace_NaNs](https://github.com/nikkiheaston/School_District_Analysis/blob/main/Resources/Per_school_summary_THS_excluded.PNG)
 
 Re-Run Analysis Using Only Thomas High School's 10th to 12th Grade Scores
 ![THS_10th_to_12th](https://github.com/nikkiheaston/School_District_Analysis/blob/main/Resources/Per_school_summary_final.png)
 
 - Thomas High School's performance compared to other schools 
    - By replacing the 9th grade scores with NaNs, Thomas High School's overall passing percentage kept the school in second place in the district, with overall passing percentage of 90.6%.

- Effects to math and reading scores by grade
  - As expected, in comparing each school by grade, replacing Thomas High School's 9th grade scores did not affect any other school or grade's performance.

- Effects to math and reading scores by school spending
  - Replacing Thomas High School's 9th grade scores did not affect the scores by school spending analysis. Thomas High spent $638 per student, and it's 10-12th grade scores were not significantly different enough to adjust the data.  
 
- Effects to math and reading scores by school size
  - Thomas High School's total student count falls into the Medium bin (1000-1999 students) and remains the same. Again, the 10-12th grade scores were not significantly different enough to change this analysis. 
 
- Effects to math and reading scores by school type
  - No changes were made to the scores by school type. 

### Results
In summary, the changes made to the school district analysis after replacing Thomas High School's 9th grade scores with NaNs were minor: the school district as a whole saw a .3% decrease in the overall passing percentage; Thomas High School also saw a .3% decrease in overall passing percentage; its percent passing math and reading scores decreased by .1% and .3% respectively, and it's average reading and math scores saw less than .1 change. 
