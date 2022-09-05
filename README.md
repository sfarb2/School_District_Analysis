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
 - **School**: Outside of Thomas High School, the school summary was unaffected. That said, Thomas High School's passing percentages went through the roof. By excluding the 9th graders, Thomas High School's math, reading, and overall passing percentages jumped from the 60s into the 90s and it went from a middle-of-the-road performer (relative to the other schools) to one of the best.
#### _With Thomas 9th Graders_
   ![With Thomas 9th Graders](/school_summary_with_thomas_9th_graders.png)
#### _Without Thomas 9th Graders_
   ![Without Thomas 9th Graders](/school_summary_without_thomas_9th_graders.png)
