# School_District_Analysis
## Overview of the Project
### Purpose
The purpose of this project is to report state math and reading test scores for 9th-12th graders at 15 specific high schools in a school district. An initial analysis was conducted, then, under suspicion of academic dishonesty, all scores for 9th grade students at one high school, Thomas High School, were replaced with NaNs and the analysis was re-run. This report reviews the effects of replacing the scores with NaNs on the school district as a whole, as well as the schools individually, particularly Thomas High School, and scores by grade, by school spending, school size, and school type. 

### Results
- Effects to school district summary
  - After re-running the analysis, it appears that for the school district as a whole, average reading and math scores, as well as passing percentages, were not significantly impacted by removing the 9th grade scores from Thomas High School. At most, scores changed by .3%. 

Screenshot 1
Screenshot 2

- Effects to school summary
  - Re-running the analysis only impacted Thomas High School's metrics particularly to the passiing percentages, defined by receving 70% or higher, as shown in the DataFrames below. Prior to replacing the scores with NaNs Thomas High School had performed relatively well.
 
 2 dataframes
 
 - Thomas High School's performance compared to other schools 
    - By replacing the 9th grade scores with NaNs, Thomas High School's overall passing percentage is second highest in the district, with competitively high scores math and reading.

ths top 2

- Effects to math and reading scores by grade
  - As expected, in comparing each school by grade, replacing Thomas High School's 9th grade scores only affected that grade at Thomas High; all other scores remained the same.  

- Effects to math and reading scores by school spending
  - Also as expected, each school spent the same amount of money per student regardless of test scores.
 
- Effects to math and reading scores by school size

- Effects to math and reading scores by school type

  jdfa;ldjfls
