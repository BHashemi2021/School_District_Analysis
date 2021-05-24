# School District Analysis

## Overview of the school district analysis 

The PyCitySchools analysis was performed on two separate datasets in csv format provided by School District authority, Maria. One of the datasets included data abut 15 schools of the city and the other was data on 39,170 students going to those schools. The first analysis was submitted upon completion but there is another call for a re-run of the analysis and exclusion of parts of the data as there has been concerns about academic misconduct regarding the 9th grade in Thomas High School. 
We have been tasked to do the analysis with three objectives: 
 •	Filter DataFrames using logical operators.
 •	Replace the incorrect values with NaN.
 •	Explain how PyCitySchools analysis changes after we exclude the incorrect data.
For the analysis we imported the datasets into Jupyter Notebook version 6.3.1 using Python Panadas. 

In a nutshell, the descriptive analysis of the study shows that the city has 15 schools (seven District type and 8 charter) and 39, 170 students and a total budget of $24, 649,428 (Figure 1 and 2).


## Results

The district summary stats were minimally affected given the large number of students in the dataset (figures 1 and 2)

**Figure 1. The results of descritive analysis**

-------
![1-Descriptive.png](https://github.com/BHashemi2021/School_District_Analysis/blob/main/Resources/1-Descriptive.png)

------

**Figure 2. The results of the first descriptive analysis **
-----------------
![1-b-Descriptive.png](https://github.com/BHashemi2021/School_District_Analysis/blob/main/Resources/1-b-Descriptive.png)
-----------------


On the other hand the performance of Thomas Hgh School was affected to a large degree, displacing its rank from the sencond (Figure 3) to the 13th (Figure 4).

**Figure 3. Position of Thomas High School after removing the 9th grade scores**
![3-Top-5-high-performing.png](https://github.com/BHashemi2021/School_District_Analysis/blob/main/Resources/3-Top-5-high-performing.png)
o	How is the school summary affected?

o	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?


o	How does replacing the ninth-grade scores affect the following:

  * Math and reading scores by grade
  * Scores by school spending
  * Scores by school size
  * Scores by school type

## Summary

Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
