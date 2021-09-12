# School_District_Analysis
## Overview of the school district analysis:
### The purpose of this analysis
Due to academic dishonesty for Thomas High School ninth graders, their grades need to be removed but still hold other grades scores. This will cause the whole school district's scores to be changed, the purpose of this analysis is to find how the change may affect school district, is that possible to cause different rank of school or higher or lower the overall passing scores.
## Results:
* We can see most score and passing rate have changed a little bit because we deleted ninth grade from Thomas High School, their grades can higher or lower the overall data due to ninth grade's performance, it doesn't change a lot because there are few students in ninth grade compare to overall district students.
<img width="922" alt="Screen Shot 2021-09-11 at 4 33 04 PM" src="https://user-images.githubusercontent.com/88211298/132965971-7b14ce47-c196-4923-b9de-1c7c911bea2d.png">
<img width="922" alt="Screen Shot 2021-09-11 at 4 30 50 PM" src="https://user-images.githubusercontent.com/88211298/132965934-76c1131c-f404-4711-a402-1ad225e37272.png">

* The only change in the school summary is Thomas High School, the percentage of passing rate boost a lot after deleting ninth grade.
<img width="1009" alt="Screen Shot 2021-09-11 at 4 40 36 PM" src="https://user-images.githubusercontent.com/88211298/132966153-c31c8b51-862f-4581-9672-878761e485c6.png">
<img width="1000" alt="Screen Shot 2021-09-11 at 4 41 06 PM" src="https://user-images.githubusercontent.com/88211298/132966154-0cd6d336-8f4a-4e01-8174-2aff71629ec5.png">

* However, this change will change the rank of school district and Thomas High School will be in the top 5.
* Ninth-grade scores doesn't affect math and reading scores by other grade because we use groupby() to differentiate. Of course, the ninth grade shows NaN.

* Scores by school spending affect the range [630-644] because Thomas High School in that range, Average Reading Score, % Passing Math, % Passing Reading, % Overall Passing are lower.
<img width="823" alt="Screen Shot 2021-09-11 at 5 30 29 PM" src="https://user-images.githubusercontent.com/88211298/132966781-9017e58b-5842-4f12-80fe-9c926a62d105.png">
<img width="775" alt="Screen Shot 2021-09-11 at 5 30 43 PM" src="https://user-images.githubusercontent.com/88211298/132966787-d07f9614-3acc-4565-988b-71d125454732.png">

* I use different range from PyCitySchools to determine the size,size_bins=[0,2000,3000,5000]  group_names=["Small (<2000)", "Medium (2000-3000)", "Large (3000-5000)"] This method splits schools more evenly than PyCitySchool, it also affect scores but I cannot compare this with PyCitySchool due to different measurement.
* Scores affect little by school type because there are only two types of school, and the amount of ninth grade in THS are relatively small in CHARTER compare to other CHARTER schools' student.
<img width="735" alt="Screen Shot 2021-09-11 at 5 35 18 PM" src="https://user-images.githubusercontent.com/88211298/132966880-bb540d54-4cbb-4e3b-8adc-3b73e207eab5.png">
<img width="755" alt="Screen Shot 2021-09-11 at 5 35 30 PM" src="https://user-images.githubusercontent.com/88211298/132966884-18c58c05-4793-4621-86a2-3e291aa912dc.png">

## Summary:
The rank of schools, scores by school type, scores by school size, scores by school spending are changed by % Passing Math, % Passing Reading, % Overall Passing because of ninth grade.
