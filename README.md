# School_District_Analysis
## Overview
The purpose of this project is to analyze the math and reading grades of Thomas High School students because of potential academic dishonesty. Within the student grades dataset, it appears the academic dishonesty is in the ninth grade. To identify altered grades, NaNs, or not a number, will be applied to math and reading scores for Thomas High School ninth grade. The goal is to see how much the overall analysis will change. If drastic changes occur academic dishonesty is highly likely. 


## Results:
- How is the district summary affected?
  - The district summary changes:
    -Average math scroe decreased 0.1%
    -Percent of students who passed math decreased 0.2%
    -Average reading score remained the same
    -Percent of students who passed reading decreased 0.3%
    -Overal percent of students who passed only decreased 0.1%


- How is the school summary affected?
  - The school summary changes only occurred in Thomas High School:
    -Students who passed math dropped from 93.272171% to 66.911315%
    -Students who passed reading dropped from 97.308869% to 69.663609%


- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  - The overall students passing score changed from 90.94801% down to 65.07645%, which would drop them from second highest to eighth lowest in the district.

- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade:
	  - When the scores were replaced to show NaN within the dataset, both math and reading scores dropped for the ninth grade. 
  - Scores by school spending:
	  - The spending stayed the same within the range of $630 - $644 per student. But, the overall passing dropped from 79% to 63% for this range.
![/Resources/School_Spending_Comparison.png](/Resources/School_Spending_Comparison.png)
  - Scores by school size:
	  - Thomas High School falls within the 1000-2000 bracket. The reading and math scores remained the same but the percentage of students passing reading and math dropped by 6% for this bracket.
![/Resources/Scores_By_School_Size_Comparison.png](/Resources/Scores_By_School_Size_Comparison.png)
  - Scores by school type:
		- Charter schools still performed better than District schools. The only impact was the district overall passing percentage dropped by 20%.
![/Resources/Scores_By_School_Type_Comparison.png](/Resources/Scores_By_School_Type_Comparison.png)

## Summary
Four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
1. NaN is an effective way to find inconsistencies within a dataset without messing up the rest of the data. 
2. Charter schools performed better than district schools 
3. School spending does not impact the grades of either subject
4. school size has an impact on the variance in testing scores. With more students, the higher chance there is for low outliers that bring down averages.
