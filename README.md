# School_District_Analysis

## Overview of Analysis

### Purpose
The purpose of this analysis was to provide a variety of breakdowns of reading and math scores for ~15 schools while excluding the potentially questionable scores of Thomas High School's 9th grade class.

### Results
A number of the summary dataframes generated were affected:
 - **District**: Because Thomas High School 9th graders were a relatively small percentage of the overall population, the district scores did not change much. Average math scores descreased slightly and all three passing percentages declined by 0.1 - 0.2 percentage points.
#### _With Thomas 9th Graders_
   ![With Thomas 9th Graders](/district_summary_with_thomas_9th_graders.png)
#### _Without Thomas 9th Graders_
   ![Without Thomas 9th Graders](/district_summary_without_thomas_9th_graders.png)

 - **School**: Outside of Thomas High School, the school summary was unaffected. THS saw its scores and passing percentages in math and reading decrease; however, that drop was less than a single percentage point.
#### _With Thomas 9th Graders_
   ![With Thomas 9th Graders](/school_summary_with_thomas_9th_graders_2.png)
#### _Without Thomas 9th Graders_
   ![Without Thomas 9th Graders](/school_summary_without_thomas_9th_graders.png)

 - **Relative Performance**: Before the scores were adjusted, THS' overall 90.9% passing rate was second among all schools (trailing only Cabrera High School). After removing Thomas High's 9th grade scores, the overall passing percentage dropped to 90.6% - still good for second overall but much closer to Griffin, Wilson, and Pena.

 - **Impact of 9th Grade Score Replacement on**: 
     * _Math and reading scores by grade_
        - Thomas High School's 9th grade class averaged 83.7 in reading and 83.6 in math. Those reading scores would have ranked in the top half of all schools while their math performance would have been among the top 3 (and the best for any grade at THS).
     * _Scores by school spending_
        - This is another case where the sample size was too small to make a significant impact. Considering THS 9th graders made up just four percent of the $631-$645 spending cohort, the math and reading scores changed by less than a percentage point.
     * _Scores by school size_
        - Similar to school spending, the change in data on school size was negligible.
     * _Scores by school type_
        - More good news - Thomas High's 9th graders (461) were such a small percentage of the entire Charter school population (12,194) that the overall figures were not affected.

### Summary
Overall, the impact of academic dishonesty among THS 9th graders was relatively small. District-wide scores and passing percentages declined slightly (less than a full point); the biggest change was in Thomas' metrics themselves, but the difference was comparable to the district-level change. Performance by school size and type were relatively unaffected as well, meaning that the bulk of the original analysis should still be useful to the school board.
