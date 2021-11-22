# School_District_Analysis
## Overview
	The purpose of this analysis is to look at standardized test scores for schools in a district and use the metrics for reporting and investigating performance of students in schools ultimately helping the school board make decisions about funding. Our analysis will give insight into the relationship of school spending, school size and school type with student performance. After processing the original data, we will remove the reading and math scores of 9th grade students at Thomas High School suspected of academic dishonesty to analyze how this change affects the overall analysis. 
### Results 
•	Scores by School spending
-	Overall passing percentage is highest in schools spending less than $584 per student and least in those spending more than $645. 
-	Bottom five schools in this category have a little over half of their students passing both subjects.
•	Scores by School size
-	Large schools (student population of 2000-5000) have the lowest overall passing percentage at 58%
-	 whereas medium and small schools (<2000 students) have a comparable and high overall passing ratio of roughly 90 and 92% respectively. 
•	Scores by School type
-	Overall, charter schools have a much higher overall passing rate of 91% compared.
-	District schools only have 54% of their students passing both math and reading. 
•	District Summary
Overall passing in the district dropped from 80%  to 65% as seen in the tables below. 
 ![image](https://user-images.githubusercontent.com/92958091/142797690-66444085-459b-496e-8d5f-6b179b909a53.png)
  ![image](https://user-images.githubusercontent.com/92958091/142797723-5ad1966c-15ff-4965-aa3d-c54be7a1b366.png)

The results listed above are essentially true for the analyses before and after the removal of 9th grade Thomas High School math and reading scores. 
#### Summary: 
-	Thomas High School’s overall performance significantly drops from 91% to 65% after math and reading scores for 9th grade were excided out (NaN). There were not significant changes in the performance of other schools in the district – only minute changes usually less than 0.2%. 

-	The overall passing percentage of charter schools increased after the scores were removed.

-	Before
-![image](https://user-images.githubusercontent.com/92958091/142797747-2dab6608-e0d8-44ac-8631-815c342771b1.png)

-	After
 ![image](https://user-images.githubusercontent.com/92958091/142797762-f49acdcb-19ea-4e07-8099-6637534d939e.png)

-	before 
![image](https://user-images.githubusercontent.com/92958091/142797778-157f2415-d6bc-46aa-b0d0-ab3d3021bd89.png)

-	after 
![image](https://user-images.githubusercontent.com/92958091/142797795-3c53b3c9-c24d-4d5e-9596-cc6799611227.png)

 	As can be seen most values are the same, however it is important to note the minor difference in overall passing percentage of the medium size school category of which Thomas High School is a member. The difference is in the hundredths place and can be considered trivial but shows the change in value as a result of removal of values.  
	An imperative observation that can be made from this analysis is how the overall passing percentage dropped from 80% to 65% after we removed the math and reading scores. Although the district might not have solid evidence for academic dishonesty, our analysis shows that 9th grade data from Thomas High School (only 461 out of 39,170 students) resulted in a 15% drop in the district overall performance. 
	In summary, the data processed for the school district shows key metrics pertaining to disparities in student performance based on spending, school size and type. This would serve as a great tool for future budget allocation and issues that need to be addressed to improve standardized test performance among high school students. The analysis can also be replicated for other districts who wish to investigate similar topics. 

