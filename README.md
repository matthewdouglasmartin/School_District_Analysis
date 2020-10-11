# School_District_Analysis

## Overview of the school district analysis: Explain the purpose of this analysis.

A local school board has requested the compilation of school performance within its school district.  The performance of the school district by math and reading scores was categorized by school, math and reading scores by grade, school size, school spending and school type.  Initially analysis was performed on a data set provided by the school district, but this original data set had incorrect scores for the 9th grade students from Thomas High School.  An updated analysis that does not include the performance of 9th graders from Thomas High School was requested by the school district.  Once updated and with further analysis, the below conclusions regarding the comparison of these two school district performance summaries were drawn. 

## Results: Using bulleted lists and images of DataFrames as support, address the following questions.

* Impact on the the district summary:
  * Original District Summary
    * ![Original_District_Summary](https://github.com/matthewdouglasmartin/School_District_Analysis/blob/master/Resources/Original%20Analysis%20Screenshots/Original%20District%20Summary.png)
  * Updated District Summary
    * ![Updated_District_Summary](https://github.com/matthewdouglasmartin/School_District_Analysis/blob/master/Resources/Updated%20Analysis%20Screenshots/Updated%20District%20Summary.png)
  * The average math score drops from 79.0 to 78.9.
  * The percentage of students passing math drops from 75% to 74.8%.
  * The percentage of students passing reading drops from 86% to 85.7%.
  * The percentage of students that are passing math and reading drops from 65% to 64.9%.
* Impact on the school summary:
  * Original School Summary
    * ![Original School Summary](https://github.com/matthewdouglasmartin/School_District_Analysis/blob/master/Resources/Original%20Analysis%20Screenshots/Original%20School%20Summary.png)
  * Updated School Summary
    * ![Updated School Summary](https://github.com/matthewdouglasmartin/School_District_Analysis/blob/master/Resources/Updated%20Analysis%20Screenshots/Updated%20School%20Summary.png)
  * Thomas High School maintains its rank in performance, second top performing school in the district.
    * Updated Top 5 Performing Schools
      * ![Updated Top Performing Schools](https://github.com/matthewdouglasmartin/School_District_Analysis/blob/master/Resources/Updated%20Analysis%20Screenshots/Updated%20Top%20Performing%20Schools.png)
  * Replacing Thomas High School's 9th graders' math and reading scores, negatively impacts math scores and positively impacts reading scores for the entire school.
    * Average math score decreases from 83.418 to 83.351.
    * Average reading score increases from 83.849 to 83.896
  * The percentage of students passing both math and reading drops from 90.948% to 90.630%.
  * Originally, Thomas High School had 97.309% of its students passing reading and Griffin High School had 97.139% of its students passing reading.  After removing the 9th graders' grades from Thomas High School, 97.019% of its students are passing reading- which is now below that of Griffin High School.
* Replacing the ninth-grade scores affects the following:
    * Math and reading scores by grade
      * Updated Math Scores by Grade
        * ![Updated Math Scores by Grade](https://github.com/matthewdouglasmartin/School_District_Analysis/blob/master/Resources/Updated%20Analysis%20Screenshots/Updated%20Math%20Scores%20by%20Grade.png)
      * Updated Reading Scores by Grade
        * ![Updated Reading Scores by Grade](https://github.com/matthewdouglasmartin/School_District_Analysis/blob/master/Resources/Updated%20Analysis%20Screenshots/Updated%20Reading%20Scores%20by%20Grade.png)
      * When the 9th graders' scores are replaced, they are no longer visible for both the Math Scores by Grade and Reading Scores by Grade summaries.
    * Scores by school spending are unchanged.
      * Original Scores by School Spending
        * ![Original Scores by School Spending](https://github.com/matthewdouglasmartin/School_District_Analysis/blob/master/Resources/Original%20Analysis%20Screenshots/Original%20Scores%20by%20School%20Spending.png)
      * Updated Scores by School Spending
        * ![Updated Scores by School Spending] (https://github.com/matthewdouglasmartin/School_District_Analysis/blob/master/Resources/Updated%20Analysis%20Screenshots/Updated%20Scores%20by%20Spending.png)
    * Scores by school size are unchanged.
      * Original Scores by School Size
        * ![Original Scores by School Size](https://github.com/matthewdouglasmartin/School_District_Analysis/blob/master/Resources/Original%20Analysis%20Screenshots/Original%20Scores%20by%20School%20Size.png)
      * Updated Scores by School Size
        * ![Updated Scores by School Size](https://github.com/matthewdouglasmartin/School_District_Analysis/blob/master/Resources/Updated%20Analysis%20Screenshots/Updated%20Scores%20by%20Size.png)
    * Scores by school type are unchanged.
      * Original Scores by School Type
        * ![Original Scores by School Type](https://github.com/matthewdouglasmartin/School_District_Analysis/blob/master/Resources/Original%20Analysis%20Screenshots/Original%20Scores%20by%20School%20Type.png)
      * Updated Scores by School Type
        * ![Updated Scores by School Type](https://github.com/matthewdouglasmartin/School_District_Analysis/blob/master/Resources/Updated%20Analysis%20Screenshots/Updated%20Scores%20by%20%20School%20Type.png)

## Summary:

When the grades of the 9th graders at Thomas High School are replaced with "nan," the following major changes occur.  At the district level: the average math score, percentage of students passing math, percentage of students passing reading, and the percentage of students passing math and reading all decrease.  As a school, Thomas High School's averaged math score, average reading score, and the percentage of students passing both math and reading decereases.  When compared to Griffin High School, Thomas High School's percentage of students passing reading is now lower than that of Griffin High School.  Finally, when viewing average grades for math and reading by grade, Thomas High School no longer has values present for its 9th graders.  The most concerning of these changes that arise the fact that the entire distirct's performance decreases across all measurables.  