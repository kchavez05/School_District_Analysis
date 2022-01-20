# School District Analysis

## Overview
This analysis serves to compare schools within a district based on math and reading scores, as well as relating the success of their respective students to school size, school type, and spending per capita.  After the original analysis, it was found that there were reporting discrepancies for a single grade at a single school, so the analysis was re-run with cleaner data.

## Results
### District Analysis
After removing the scores for the 9th graders at Thomas High School, the overall passing percentage for the district went down only 0.1%.

#### Old
![District Analysis Old](Resources/district_analysis_old.PNG)
#### New
![District Anaylsis New](Resources/district_analysis_new.PNG)

### School Summary
In the revised analysis, Thomas High School's scores are affected significantly.  The % Passing Math score dropped from 97.3% to 93.2% and the % Passing Reading Score rose to 97.0% from 90.6%.  The Overall Passing % remained relatively stable - moving only three basis points from 90.9% to 90.6%

#### Old
![School Summary Old](Resources/per_school_old.PNG)
#### New
![School Summary New](Resources/per_school_new.PNG)

### Top 5 Schools
Though the new analysis changed Thomas High School's metrics, it maintains the second highest Overall Passing % in the district.

#### Old
![School Performance Old](Resources/top_schools_old.PNG)
#### New
![School Performance New](Resources/top_schools_new.PNG)

### Scores By Grade
When displaying reading and math scores by grade, we can see that the data for the 9th grade at Thomas High School is NaN - removed from the analysis.

#### Reading Scores by Grade
##### Old
![Reading by Grade Old](Resources/reading_by_grade_old.PNG)
##### New
![Reading by Grade New](Resources/reading_by_grade_new.PNG)

#### Math Scores By Grade
##### Old
![Math by Grade Old](Resources/math_by_grade_old.PNG)
##### New
![Math by Grade New](Resources/math_by_grade_new.PNG)

### Scores by Per Student Spending
Interestingly, spending per student has an inverse effect on overall passing percentage.  The schools at the lowest end of the spending per student range in both analyses were the most successful.

#### Old
![Scores by Spending Old](Resources/scores_by_spending_old.PNG)
#### New
![Scores by Spending New](Resources/scores_by_spending_new.PNG)

### Scores by Size
In both analyses, the Medium sized schools had the highest % Overall Passing.
#### Old
![Scores by Size Old](Resources/scores_by_size_old.PNG)
#### New
![Scores by Size New](Resources/scores_by_size_new.PNG)

### Scores by Type
Charter schools in both analyses are significantly more successful than District schools - they maintain a 90% Overall Passing in both analyses compared to the District Schools' 54%

#### Old
![Scores by Type Old](Resources/scores_by_type_old.PNG)
#### New
![Scores by Type New](Resources/scores_by_type_new.PNG)


## Summary
Though there was a slight change in scores and percentages for Thomas High School, it does not have a significant effect on the district-wide analysis.  Average scores went down, but only by tenths of percentage points.  The overall analysis, however, does seem to indicate a striking disparity between student success at Charter vs District schools which warrants further research.  Additionally, follow up is needed at Thomas High School to ensure that future reporting is honest and accurate.
