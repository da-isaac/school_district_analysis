# School District Analysis

## Overview of Project

### Purpose
The client needed an analysis of testing and funding data within their school district to help the school board determine where they should allocate resources.

## Results

* How is the district summary affected?
<br />*District Summary - Module DataFrame*
![module_district_summary](/Resources/district_summary_df_module.PNG)

<br />*District Summary - Adjusted DataFrame*
![adjusted_district_summary](/Resources/district_summary_df_adjusted.PNG)
<br />Ultimately, the district summary didn't see that much of an impact. There was a slight decrease in averages scores for math and reading, and in the percentage of students who passed, but because the students that were removed from the data were such a small piece of the dataset, its impact on a general level was small.
<br /><br />
* How is the school summary affected?
<br />*School Summary - Module DataFrame*
![module_per_school_summary](/Resources/per_school_summary_df_module.PNG)

<br />*School Summary - Adjusted DataFrame*
![adjusted_per_school_summary](/Resources/per_school_summary_df_adjusted.PNG)
<br/>Slight decrease in math score, slight increase in reading score, decrease in passing math, decrease in passing reading, decrease in passing overall
<br /><br />
* How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?
<br />*Top Schools - Module DataFrame*
![module_top_schools](/Resources/top_schools_module.PNG)

<br />*Top Schools - Adjusted DataFrame*
![adjusted_top-schools](/Resources/top_schools_adjusted.PNG)
While there was a slight decrease in Thomas High School's overall performance, it was not significant enough to change its ranking when viewing all other schools.
<br /><br />
* How does replacing the ninth-grade scores affect the following:
    * Math and Reading scores by grade
    <br />*Math Scores by Grade - Module DataFrame*<br />
    ![module_math_scores_grade](/Resources/math_scores_by_grade_module.PNG)
    <br />*Math Scores by Grade - Adjusted DataFrame*<br />
    ![adjusted_math_scores_grade](/Resources/math_scores_by_grade_adjusted.PNG)
    <br />*Reading Scores by Grade - Module DataFrame*<br />
    ![module_reading_scores_grade](/Resources/reading_scores_by_grade_module.PNG)
    <br />*Reading Scores by Grade - Adjusted DataFrame*<br />
    ![module_reading_scores_grade](/Resources/reading_scores_by_grade_adjusted.PNG)
    <br />Because only one summary value was affected by the change in math and reading scores, it did not have an impact on any other 9th grade data or other high school data.<br /><br />
    * Scores by school spending
    <br />*Scores by School Spending - Module DataFrame*<br />
    ![module_scores_by_spending](/Resources/scores_by_spending_module.PNG)
    <br />*Scores by School Spending - Adjusted DataFrame*<br />
    ![adjusted_scores_by_spending](/Resources/scores_by_spending_adjusted.PNG)
    <br />No significant change occurred when comparing the scores based on school funding after values were nullified.
    <br /><br />
    * Scores by school size
    <br />*Scores by School Size - Module DataFrame*<br />
    ![module_scores_by_size](/Resources/scores_by_size_module.PNG)
    <br />*Scores by School Size - Adjusted DataFrame*<br />
    ![adjusted_scores_by_size](Resources/scores_by_size_adjusted.PNG)
    <br />No significant change occurred when comparing the scores based on school size after values were nullified.
    <br /><br />
    * Scores by school type
    <br />*Scores by School Type - Module DataFrame*<br />
    ![module_scores_by_type](/Resources/scores_by_type_module.PNG)
    <br />*Scores by School Type - Adjusted DataFrame*<br />
    ![adjusted_scores_by_type](/Resources/scores_by_type_adjusted.PNG)
    <br />No significant change occurred when comparing the scores based on school type after values were nullified.
    <br />
    
## Summary
While the 9th grade data from Thomas High School needed to be nullified, the impact of these changes were surprisingly small. On a district level, the average math and reading score saw a slight decrease, as did the overall percentage of students passing both reading and math. On a school level, the same overall percentage also saw a decrease.