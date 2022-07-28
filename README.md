# School_District_Analysis

## Overview
### Purpose
The goal is to find any academic dishonesty by replacing the 9th Grader grades for Math and Reading with NaNs and observing how this with affect the overall Averages for the entire School Board. 

## Results
* How is the district summary affected?
  * Pre-cleaned Data to Post-cleaned Data: Average Math Score 79% to 78.9% (Decrease), Average Reading Score 81.9% to 81.9% (Same), % Passing Math 75% to 74.8% (Decrease), % Passing Reading 85.8% to 85.7% (Decrease), % Overall Passing 65.2% to 64.9% (Decrease)
 
![district_post](https://user-images.githubusercontent.com/108701073/181388953-89bb73a6-02da-4077-816a-0388b36e0883.png)

* How is the school summary affected?
  * Pre-cleaned Data to Post-cleaned Data: Average Math Score 83.35% to 83.35% (Same), Average Reading Score 83.89% to 83.89% (Same), % Passing Math 66.91% to 93.19% (Increase), % Passing Reading 69.66% to 97.02% to (Increase), % Overall Passing 65.08% to 90.63% (Increase)

Pre Clean
![School_summary_pre](https://user-images.githubusercontent.com/108701073/181388886-00af1f5e-d7de-4dd9-8847-35f2430f11d1.png)


Post Clean
![School_summary_post](https://user-images.githubusercontent.com/108701073/181388907-0bdbe745-0345-41b6-91b8-0097855bbb5c.png)
  
* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  * Thomas High School still shows that it is still second place after the Clean up
 
Pre Clean
![Top_5_pre](https://user-images.githubusercontent.com/108701073/181392427-b3b95261-5e44-4ca9-b024-4e95879d0bf1.png)


Post Clean
![Top_5_post](https://user-images.githubusercontent.com/108701073/181392450-43d653c8-cae8-420e-8c60-189b7bd32197.png)


* How does replacing the ninth-grade scores affect the following:
  * Math and reading scores by grade
  Results have stayed the same except the results for Grade 9 at Thomas High School shows "nan"
  
Pre Clean
Math
![Results_by_grade_pre](https://user-images.githubusercontent.com/108701073/181392918-1321bb96-26d2-4898-a763-dc888f41ccfc.png)


Read
![Results_by_grade_pre_read](https://user-images.githubusercontent.com/108701073/181393454-79a477ea-66cd-4a07-9060-40094e0bb32c.png)


Post Clean
Math
![Results_by_grade_post](https://user-images.githubusercontent.com/108701073/181392943-7f7479a5-cf7b-4b1e-a276-adf0033b5a38.png)
 
 
Read
![Results_by_grade_post_read](https://user-images.githubusercontent.com/108701073/181393288-9dec48be-295c-4067-b9f6-ca8eea8f17a9.png)


  * Scores by school spending
The results have not changed

Pre Clean
![spending_pre](https://user-images.githubusercontent.com/108701073/181393499-b69a4467-018f-4608-860e-a91cea508658.png)


Post Clean
![Top_5_post](https://user-images.githubusercontent.com/108701073/181393725-e9494571-cf49-44e0-b1fc-8eff3e2c151c.png)


  * Scores by school size
The results have not changed

Pre Clean
![size_pre](https://user-images.githubusercontent.com/108701073/181394351-dc5dee91-a98e-46e7-a443-7f80bf730116.png)


Post Clean
![size_post](https://user-images.githubusercontent.com/108701073/181394370-67c1faa4-4bb7-4c73-9c02-55c359a2bb18.png)


  * Scores by school type
The results have not changed

Pre Clean
![type_pre](https://user-images.githubusercontent.com/108701073/181394771-d377b94b-6487-4379-aca0-5de1130e8bd5.png)


Post Clean
![type_post](https://user-images.githubusercontent.com/108701073/181394799-57560ff3-6776-43bd-900c-01d1da1ad044.png)


## Summary
In conclusion by replacing the math and reading test scores for the grade 9 at Thomas High School it has caused their results to slighlty change or the results were the same before we removed the 9th Grader Scores. So we can assume that there wasn't much academic dishonesty at Thomas High School.
