# School District Analysis: Using Python and Jupyter Notebook to Examine School District Data

## Overview
This project draws on academic data taken from a sample school district in order to better organize it for identifying key information and evaluating patterns. On being alerted to suspicions of academic dishonesty, the analysis focuses on reading and math scores for Thomas High School ninth graders, while keeping the rest of the data intact. By replacing the suspected scores with NaN values, the aim is to explore how this change affects the overall scores for the district.

## Results
* The district summary shows a drop in passing percentage after replacing grades from the suspect population with NaN values.
![Screen Shot 2022-03-14 at 3 46 34 PM](https://user-images.githubusercontent.com/91562577/158249300-2cb5aa05-2be7-44b7-b799-7f9bc54c05ca.png)

* The school summary shows a marked effect of this change, as the overall passing score for Thomas High School dropped to 65%.
![Screen Shot 2022-03-14 at 3 47 41 PM](https://user-images.githubusercontent.com/91562577/158249466-48018d9e-e146-4e6b-97ad-25c83dde63c9.png)
Thomas High School is no longer included in the top five schools.
![Screen Shot 2022-03-14 at 4 24 49 PM](https://user-images.githubusercontent.com/91562577/158255230-ebac78d7-026e-4c85-bbd6-7ae74301154f.png)

The bottom five schools remain the same.
![Screen Shot 2022-03-14 at 3 49 52 PM](https://user-images.githubusercontent.com/91562577/158249805-7c596eb8-4161-4bd9-bda4-f8ab61f4d5ed.png)

* Math scores by grade were kept intact across the district, save for Thomas High School ninth graders.
![Screen Shot 2022-03-14 at 4 23 32 PM](https://user-images.githubusercontent.com/91562577/158255013-181731fa-fbc3-4820-8fe7-e94c70e5263e.png)

* Reading scores by grade were also kept intact across the district, save for Thomas High School ninth graders.
![Screen Shot 2022-03-14 at 3 56 15 PM](https://user-images.githubusercontent.com/91562577/158250809-fa637426-70a3-4b0b-a19d-8bcfe4ceee9f.png)

* Scores by school spending remained the same for all of the spending ranges except for $630-644, the range that included Thomas High School. This range saw a 6% drop in passing math, 7% drop in passing reading, and 6% drop in overall passing percentage.

![Screen Shot 2022-03-14 at 4 22 46 PM](https://user-images.githubusercontent.com/91562577/158254923-3b274988-68ee-468c-a6a1-f2b7d686aec4.png)

* Scores by school size followed the same pattern as scores by school spending--only the medium-sized range that included Thomas High School saw a change. This group, with 1000-2000 students, dropped 6% in each of passing math, passing reading, and overall passing percentage.
![Screen Shot 2022-03-14 at 3 58 25 PM](https://user-images.githubusercontent.com/91562577/158251175-6d29c2ad-0a46-4fbc-aba7-b12aa0407d8e.png)

* Scores by school type shows that the Charter schools group, which included Thomas High School, saw a drop in each of math, reading, and overall passing percentage. However, these lower scores did fully narrow the gap in the passing rates of Charter schools compared to the lower rates for District schools.
![Screen Shot 2022-03-14 at 3 59 08 PM](https://user-images.githubusercontent.com/91562577/158251289-29cc568a-7b92-4cb6-a103-cba5f9bba838.png)

## Summary
Replacing the scores for ninth graders at Thomas High School results in lower passing rates in several metrics, particularly obvious when grouping schools based on spending, size, or school type. Because the entire ninth grade cohort at Thomas High School was omitted in the analysis, it remains unclear what type of academic dishonesty may have occurred, and which individuals may have been involved. At a population level however, separating this group shows a clear pattern in the drops in overall passing percentage, passing math percentage, and passing reading percentage. The ranking of Thomas High School in the district also dropped, as without the inflated scores of the ninth grade class the school was no longer in the top five. 
