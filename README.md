# School District Analysis

## Overview of the school district analysis 

The PyCitySchools analysis was performed on two separate datasets in csv format provided by School District authority, Maria. One of the datasets included data abut 15 schools of the city and the other was data on 39,170 students. The first analysis was submitted upon completion but there is another call for a re-run of the analysis and exclusion of parts of the data as there has been concerns about academic misconduct regarding the 9th grade in Thomas High School. 

We have been tasked to do the analysis with three objectives: 

 *	Filter DataFrames using logical operators.
 *	Replace the incorrect values with NaN.
 *	Explain how PyCitySchools analysis changes after we exclude the incorrect data.
 
 
For the analysis we imported the datasets into Jupyter Notebook version 6.3.1 using Python Panadas. 

## Results

#### District Summary before and after data clean up

The descriptive analysis of the study shows that the city has 15 schools (seven District type and 8 charter) and 39, 170 students and a total budget of $24, 649,428. The district summary stats were *minimally* affected upon removing the 9th graders' scores for math and reading from Thomas High School, given the large volume of students in the dataset (Figures 1 and 2).

**Figure 1. District Summary after data clean up**

-------
![1-(district summary) Descriptive.png](https://github.com/BHashemi2021/School_District_Analysis/blob/main/Resources/1-(district%20summary)%20Descriptive.png)

------



**Figure 2: District Summary before data clean up**

------------------
![2-(district summary) Descriptive](https://github.com/BHashemi2021/School_District_Analysis/blob/main/Resources/2-(district%20summary)%20Descriptive.png)

------------------

#### School summary before and after data clean up

While the district summary underwent very small changes due to the large number of students in the dataset, the effects of removing 9th greaders' scores from the dtaset, changed the schools standing alongside t=lowring its passing scores for both subjects, their percentages and the overall passing score percentage.


#### The overall Effects of replacing the ninth graders’ math and reading scores on Thomas High School’s performance vs other schools

Replacing the ninth graders’ math and reading scores with NaN (managed missing data), affected Thomas High School’s performance relative to the other schools, displacing its rank from second to eighth as its overall passing score decreased from 91% to 65% (Figure 3).  


** Figure 3: Comparing Thomas High School's rank before and after data clean up.

--------------------
![3-comparative-school-summary-(percentage).png](https://github.com/BHashemi2021/School_District_Analysis/blob/main/Resources/3-comparative-school-summary-(percentage).png)

--------------------


### Effects of replacing the ninth-grade scores in more details

##### Math and reading scores by grade

By replacing the Thomas High Schools' 9th grade with NaN (managing them as missing data) we notice that:
Although the average scores for both reading and math underwent minor changes but passing scores for both went below 70 or the pass mark.  

##### Scores by school spending

Thomas High School is in $630-645 spending bucket, and budget per student have not undergone any changes but passing math and reading scores are evidently different (Figure 4)

**Figure 4: Spending per student and school budget

-----------------
![4-spendingbudget.png](https://github.com/BHashemi2021/School_District_Analysis/blob/main/Resources/4-spendingbudget.png) 

-----------------

##### Scores by school size

Thomas High School is categorized is in the 1000 to 2000 students educational facility.
By removing the 9th grade scores for math and reading, there was a reduction in those scores, and the overall passing scores but the budget remined the same. Not counting the students in the tally, we need to subtract the number of students at 9th grade (461) from the former total of 1635 leaves the count with 1174 students.   

##### Scores by school type

The Thomas High School is in the medium-sized (1000-2000) educational facility bin. Removing the 9th grade students from the count does not change the bucket or bin the school is in but math and reading scores did change the passing scores or math and reading, their percentages, as well as the overall passing percentage.


## Summary

Replacing the scores of the 9th graders from Thomas High School, minimally changed district summary results.

Replacing the scores of 9th graders changed the standing of the Thomas High School from second to eighth. 

Removing the math and reading scores of 9th graders of Thomas High School, changed the passing mark for those two subjects.

Removing the math and reading scores of 9th graders of the school changed the percentage of passing marks for the two subjects.


