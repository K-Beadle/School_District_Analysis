# School_District_Analysis

## Analysis Overview
To Analyze data gathered from 15 different schools and tell a story with the data.

### Purpose

The purpose of this analysis was to analyze the data that was collected from schools in a certain area and provide a high-level snapshot of the disctrict's key metrics, and key metrics for each school both in table format. The key metrics were to include the top 5 and bottom 5 performing schools based on overall passing rate; average math scores; average reading scores; school performance based on budget per student, school size, and type of school.

## Reviewing Results

**1. How is the district summary affected?**
![District_Summary_df](https://user-images.githubusercontent.com/78178900/113541528-4418ac00-9597-11eb-8078-853553cef967.png)
![District_Summary_df New](https://user-images.githubusercontent.com/78178900/113541543-4975f680-9597-11eb-8d05-38bcd4dc7658.png)
  - Average Math Score decreased by 0.1%
  - % Passing Math decreased by 0.2%
  - % Passing Reading decreased by 0.3%
  - % Overall Passing decreased by 0.1%

**2. How is the school summary affected?**
![Per_School_Summary_df(1)](https://user-images.githubusercontent.com/78178900/113541552-509d0480-9597-11eb-9549-d1d7d67e501d.png)
![Per_School_Summary_df(2)](https://user-images.githubusercontent.com/78178900/113541559-5692e580-9597-11eb-9b49-f3a22e2a54a1.png)
![Per_School_Summary_df New](https://user-images.githubusercontent.com/78178900/113543656-ab385f80-959b-11eb-9297-58f6db50d988.png)
*please note that the first two screenshots are include all the information from the dataframe that was before the exclusion of 9th grade data*

  - % Passing Math went from 93%-67%
  - % Passing Reading went from 97%-70%
  - % Overall Passing went from 91%-65%


**3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

There were three different categories that were affected for the per_school_summary_df data frame under the row for Thomas High School: Percent Passing Math, Percent Passing Reading, Percent Overall Passing. All three sections suffered large percentage decreases of 26%, 27% and 26%. This caused them to go from the 90th percentile to the 65th-70th percentile in all three of those sections.

**4. How does replacing the ninth-grade scores affect the following:**

**4a. Math and reading scores by grade**

![Math_Scores_by_Grade](https://user-images.githubusercontent.com/78178900/113541604-6f9b9680-9597-11eb-98ea-9d457e6a1b21.png)
![Avg_Math_Score_df](https://user-images.githubusercontent.com/78178900/113541611-732f1d80-9597-11eb-8b18-b71400d057fa.png)

  - The only way that it affects the data frame for scores by grade is that it changes the math score from an integer value to "nan" since there is no value. So, we don't have an average score metric for Math in the 9th grade class at Thomas High School

![Reading_Scores_by_Grade_df](https://user-images.githubusercontent.com/78178900/113541620-7924fe80-9597-11eb-813f-73600358a0dc.png)
![Avg_Reading_Scores_df](https://user-images.githubusercontent.com/78178900/113541628-7c1fef00-9597-11eb-8e0a-e4fd185a8a81.png)

  - The affect on the Reading score by grade is the same result as the affect on the Math score by grade: we don't have an average score metric for Reading in the 9th grade class at Thomas High School so the value is "nan".

**4b. Scores by school spending**
![Spending_Summary_df](https://user-images.githubusercontent.com/78178900/113541643-80e4a300-9597-11eb-988a-e105dee0bf80.png)
![Spending_Summary_df New](https://user-images.githubusercontent.com/78178900/113541652-84782a00-9597-11eb-9e34-0c7a2c96395f.png)

  - $$$  < $584 Average Reading score went down by 0.1% and % Passing Math wend down by 1.0%
  - $585 - $629 % Overall Passing percentage dropped by 1% and average Math score dropped by 0.1%
  - $630 - $644 Average Reading score went down by 0.2%
  - $645 - $675 There was no noticable change in this range of spending

**4c. Scores by school size**

![Size_Summary_df](https://user-images.githubusercontent.com/78178900/113541656-87731a80-9597-11eb-902c-0c8599da9259.png)
![Size_summary_df New](https://user-images.githubusercontent.com/78178900/113541665-8b06a180-9597-11eb-9dd7-626195421823.png)

  - Small (<1,000): Average Math score decreased by 0.2% and Average Reading score decreased by 0.1%
  - Medium(1,000-2,000): Average Math score increased by 0.2% and Average Reading score decreased by 0.1% and % Passing Math increased by 1.0%
  - Large(2,000-5,000): Average Math score decreased by 0.1% and Average Reading score decreased by 0.1%

**4d. Scores by school type**

![Type_Summary_df](https://user-images.githubusercontent.com/78178900/113541674-8e019200-9597-11eb-83f7-2439570b8c04.png)
![Type_Summary_df New](https://user-images.githubusercontent.com/78178900/113541676-8fcb5580-9597-11eb-9993-e78d90311948.png)

  - Charter Average Math Score increased by 0.1% and Average Reading score decreased by 0.1%
  - District There was no change in percentage outcomes for this school type.

## Summary: 
#### Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

The four major changes that occured to the school disctrict analysis were a decrease in four different areas. Although the decrease in percentages was not a tremendous decrease in percentage value, it is still noteworthy becuase it caused a decline in four different metrics that are used to evaluate success criteria. The four changes were addressed above under the "1." section of "Reviewing Results" and are as follows:

  - Average Math Score decreased by 0.1%
  - % Passing Math decreased by 0.2%
  - % Passing Reading decreased by 0.3%
  - % Overall Passing decreased by 0.1%
