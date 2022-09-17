# Py-City-Schools
## Overview
This purpose of this analysis was to clean and organize student data from a variety of schools. The information for each school was then grouped and analyzed for a variety of factors: school spending, school size, and school type (district or charter). An analysis was performed to determine the top 5 and bottom 5 performing schools based on overall passing rate of the students. Average math and reading scores from each school at each grade level were analyzed, along with analyzing the differnce made in passing percentages for Thomas High School once 9th grade test scores had been removed from the data (this was done due to evidence of academic dishonesty in this grade level). Overall, this analysis was completed to provide accurate testing results from a school district while providing several metrics to look into to determine future budgeting.
### Results After Replacing THS 9th Grade Scores
- District Summary 
By nullifying the math and reading scores for 9th graders at THS, there is a slight decrease in all metrics other than Average Reading Score compared to previous results.

![District_summary](https://user-images.githubusercontent.com/111502918/190870927-d3009791-125e-4dc9-ab1b-a433f0e99828.PNG)

- School Summary & THS Performance Compared to Other Schools

The new school summary DataFrame displays a decrease in overall passing percentage of THS. When compared to other schools in the disctrict, such as Bailey High School and Shelton High School, THS is still out-performing these schools but with a narrower margin.

![per_school_summary](https://user-images.githubusercontent.com/111502918/190870944-75112e4c-68d3-4568-a44a-37ed62ec378e.PNG)

  - Math Scores by Grade
  
  Nullifying the math scores for the 9th graders at THS had no effect on the other grades at THS, or the other scores from 9th graders at other schools; however, removing these grades could show a lower average for all 9th graders in the district.
  
 ![math_scores_by_grade](https://user-images.githubusercontent.com/111502918/190870981-e2807b0b-2868-4cae-b08b-0d8ae548be86.PNG)
 
  - Reading Scores by Grade
    
    Nullifying the reading scores for the 9th graders at THS had no effect on the other grades at THS, or the other scores from 9th graders at other schools; however, removing these grades could show a lower average for all 9th graders in the district.
    
 ![reading_scores_by_grade](https://user-images.githubusercontent.com/111502918/190871021-deb3ce6f-5801-4cfc-95a9-6e5e2acf64fd.PNG)
 
  - Scores by Spending 
  
  Removing scores from the 9th graders at THS appears to have a minimal impact on average scores in the $631-645 spending range, which THS falls under. The lack of this information caused changes to the degree of tenths of a percent.
  
 ![scores_by_spending](https://user-images.githubusercontent.com/111502918/190871045-5a89844b-01d7-4b67-8905-5af5f01439e4.PNG)
 
  - Scores by Size
  
  The changes made to the data caused minimal impact on average scores for the 1000-1999 school size category, which THS falls under. This category of schools is still the best performing size in all metrics except for Average Math Score.
  
 ![scores_by_size](https://user-images.githubusercontent.com/111502918/190871072-03ed611b-1f32-47c4-9d43-c0c2ffcff414.PNG)
 
  - Scores by Type
  
  After removing the 9th grade scores from THS, Charter Schools in the district are still out-performing District Schools by large margins in every category.
  
 ![scores_by_type](https://user-images.githubusercontent.com/111502918/190871090-36b0bc7e-7299-41c9-9da3-94c2202a720a.PNG)

#### Summary
Replacing the reading and math scores for ninth graders at Thomas High School with a value of NaN appeared to have minimal changes to many metrics. The largest change was of course to the scores by grade DataFrame as the 9th grade section for THS had NaN as a value compared to all other schools. There was a slight decrease in overall passing for THS and for the District, potentially due to a decrease in sample size with a large portion of the data being nullified. Additionally, the removal of scores for 9th graders at THS likely had an effect on 9th grade scores for the district as a whole. Overall, removing grades suspect of academic dishonesy allows for a more accurate school and district analysis, thus allowing for a more accurate distribution of funds accross the district.
