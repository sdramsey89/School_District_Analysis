# School District Analysis
## Overview of Project

### Purpose
- The purpose of this project was to provide and updated analysis of student performance on Math and Reading assessments. The analysis breaks down student data by school, grade, funding, size, and type. Additionally, the analysis removes Thomas High School 9th (THS-9) grade test data to account for potential academic dishonesty.

## Analysis / Results
### Effects of Removing THS 9th Grade Data
![District All Data](Resources/top5.png) <br>
*District Level Summary (All Data)* <br>
![District Adjusted Data](Resources/top5_adjusted.png) <br>
*District Level Summary (THS-9 Removed) <br>
- Effects on district summary: We can see that removing THS-9 data brought the entire district down .2% in math, .1% in reading, and .3% overall.

![Top 5 All Data](Resources/top5.png) <br>
*School Level Summary - Top 5 Performing Schools (All Data)* <br>
![Top 5 Adjusted Data](Resources/top5_adjusted.png) <br>
*School Level Summary - Top 5 Performing Schools (THS-9 Removed)* <br>
- Effects on THS' school level data: Removing THS-9 lowered THS' passing math percentages from 93.3% to 93.2%, reading from 97.3% to 97.0%, and overall from 90.9% to 90.6%.
- Effects on top 5 schools: Despite these lowered scores, THS barely stayed in 2nd places. Before the adjustment, THS was beating Griffin HS by .3%, but after the adjustment the two schools are tied after rounding to the 10ths place.


![School Size All Data](Resources/school_sizes.png) <br>
*School Size (All Schools)* <br>
![School Size Adjusted Data](Resources/adjusted_size.png) <br>
*School Size (THS-9 Removed)* <br>
- Effects on school size data: THS is a medium sized school with 1635 students. Looking at the data before and after the conversion, it does not apper to have been affected by dropping the THS-9 data (the caveat here is that the data formatting requested by the district is rounding to nearest whole number which is hiding some of the effects).


![School Spending All Data](Resources/spending_ranges.png) <br>
*School Spending Per Student (All Schools)* <br>
![School Spending Adjusted Data](Resources/adjusted_spending.png) <br>
*School Spending per Student (THS-9 Removed)* <br>
- Effects on school budget data: THS spends $638 per student putting them in the second highest category. Once again the numbers are unchanged after removing the THS-9 data (as stated above, the caveat here is that the data formatting requested by the district is rounding to nearest whole number which is hiding some of the effects).


![School Type All Data](Resources/school_type.png) <br>
*School Type (All Schools)* <br>
![Shcool Type Adjusted Data](Resources/adjusted_type.png) <br>
*School Type (THS-9 Removed)* <br>
- Effects on schooltype data: THS is a charter school and the data shows no difference when rounded to the nearest whole number.

## Summary
The largest change caused by removing THS-9 data was on the school level summary. Since 9th graders make up 28% of the student body, removing their data had the greatest effect on the school. However, as we moved into larger groupings the effects were not as strong. When the data is not rounded to the nearest whole number the analysis shows that scores are also dropped in 3 other tables:
1. schools spending for $630 - 644
2. School type of Charter
3. School size of Medium (1000 - 2000) 
