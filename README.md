# School_District_Analysis</br>


## Overview of Project
Here is the list of deliverables for the analysis of the school district:</br>

A high-level snapshot of the district's key metrics, presented in a table format</br>
An overview of the key metrics for each school, presented in a table format</br>
Tables presenting each of the following metrics:</br>
Top 5 and bottom 5 performing schools, based on the overall passing rate</br>
The average math score received by students in each grade level at each school</br>
The average reading score received by students in each grade level at each school</br>
School performance based on the budget per student</br>
School performance based on the school size</br>
School performance based on the type of school </br>

## Resources
School District Analysis using Anaconda, Jupyter Notebook, Pandas & Python</br>
Data Source: PyCitySchools.ipynb file and rename it PyCitySchools_Challenge_testing.ipynb.</br>


## Background Analysis and Challenges
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.


# Deliverable 1: Replace Ninth-Grade Reading and Math Scores
Instructions: Using the Pandas loc method with conditional statements and comparison and logical operators, select the ninth-grade reading and math scores for Thomas High School. Then, use the Pandas NumPy module to change the reading and math scores to NaN.</br>

<img width="853" alt="Deliverable 1" src="https://user-images.githubusercontent.com/74282781/117086579-c6fd6580-ad01-11eb-8764-840ecb95384b.png">

## Deliverable 2: Repeat the School District Analysis
Instructions: Repeat the school district analysis you did in this module, and recreate the following metrics:</br>

<img width="794" alt="Deliverable 2" src="https://user-images.githubusercontent.com/74282781/117086599-ded4e980-ad01-11eb-941d-6c78d417d5c7.png"> </br>

https://github.com/spreeti12345/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb </br>


## Summary 

BEFORE DATA CLEANUP</br>

Average Math Score = 79.0</br>
Average Reading Score =81.9</br>
% Passing Math -75</br>
% Passing Reading- 86</br>
% Overall Passing -65</br>

AFTER DATA CLEANUP</br>

Average Math Score = 78.9</br>
Average Reading Score = 81.9</br>
% Passing Math- 74.8</br>
% Passing Reading- 85.7</br>
% Overall Passing-64.9</br>

A slight change in Math Score, including % Passing district averages, Comparing the two dataframes above, the average show the difference when the 9th grade student Math and Reading scores from Thomas High Schools were excluded from the District Summary.</br>

Thomas High School's % Overall Passing was 91, placing second. However after data cleanup Thomas High School's % Overall Passing was 65, placing eight with a significant dropin ranking. </br>


-Average math and reading scores stay consistent across grade level when grouped by school. There is no major improvement in scores from any school.</br>
-Math passing rates are always consistently lower across every metric, but the difference between math and reading passing rates is greater amoung lower performing schools,arge schools, and higher spending per student which all seem to correlate.</br>
-The top 5 schools are all charter schools while the bottom 5 all district schools.</br>
-In general (one exception), per student spending is higher in bottom performing schools than top performing.</br>
-Schools under 2000 students have much higher passing rates than those with student populations above 2000. A comparision of 95 to 75%. The same phenomenon is seen with high and low per student spending brackets and district versus charter schools.Summarize the Average Math & Reading scores, % Passing Math and Reading scores, Overall Passing marks changes, changes that are reflected in the funding for each student (Difference each students funding is ~ $200).</br>
-All that by the updated School_District_Analysis Reading and Math Scores from Thomas High School 9th Grade have been replaced with NaNs.</br>
