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
Instructions: Using the Pandas loc method with conditional statements and comparison and logical operators, select the ninth-grade reading and math scores for Thomas High School. Then, use the Pandas NumPy module to change the reading and math scores to NaN.

Deliverable 1 Requirements:
You will earn a perfect score for Deliverable 1 by completing all requirements below:

The loc method is used to select all the reading and math scores from the ninth grade at Thomas High School. Inside the loc method, the following are completed:

A comparison operator is used to retrieve all the rows with Thomas High School in the "school_name" column of the student_data_df.
A comparison operator is used to retrieve all the rows with the ninth grade in the "grade" column of the student_data_df.
Logical and comparison operators are used to retrieve all the rows with the "reading_score" column for Thomas High School ninth graders from the student_data_df.
Logical and comparison operators are used to retrieve all the rows with the "math_score" column for Thomas High School ninth graders from the student_data_df.
The reading and math scores for the ninth graders in Thomas High school are replaced with NaNs.
Deliverable 1 Results with detail analysis:
1. A comparison operator is used to retrieve all the rows with Thomas High School in the "school_name" column of the student_data_df.

Image with Python, Jupyter Notebook and Pandas Code below.

Code and Image

name-of-you-image

2. A comparison operator is used to retrieve all the rows with the ninth grade in the "grade" column of the student_data_df.

Image with Python, Jupyter Notebook and Pandas Code below.

Code and Image

name-of-you-image

3. Logical and comparison operators are used to retrieve all the rows with the "reading_score" column for Thomas High School ninth graders from the student_data_df.

Image with Python, Jupyter Notebook and Pandas Code below.

Code and Image

name-of-you-image

4. Logical and comparison operators are used to retrieve all the rows with the "math_score" column for Thomas High School ninth graders from the student_data_df.

Image with Python, Jupyter Notebook and Pandas Code below.

Code and Image

name-of-you-image

5. The reading and math scores for the ninth graders in Thomas High school are replaced with NaNs.

Image with Python, Jupyter Notebook and Pandas Code below.

Code and Image for Reading

name-of-you-image

Code and Image for Reading

name-of-you-image

ALL CODE - Deliverable 1

name-of-you-image

Deliverable 2: Repeat the School District Analysis
Instructions: Repeat the school district analysis you did in this module, and recreate the following metrics:

The district summary
The school summary
The top 5 and bottom 5 performing schools, based on the overall passing rate
The average math score for each grade level from each school
The average reading score for each grade level from each school
The scores by school spending per student, by school size, and by school type
Deliverable 2 Requirements:
You will earn a perfect score for Deliverable 2 by repeating the school district analysis and updating the following required metrics in the PyCitySchools_Challenge.ipynb file:

The district summary DataFrame.
The school summary DataFrame.
The top 5 performing schools, based on the overall passing rate.
The bottom 5 performing schools, based on the overall passing rate.
The average math score for each grade level from each school.
The average reading score for each grade level from each school.
The scores by school spending per student.
The scores by school size.
The scores by school type.
Deliverable 2 Results with detail analysis:
1. The district summary DataFrame.

Image with Python, Jupyter Notebook and Pandas Code below.

Code and Image

name-of-you-image

2. The school summary DataFrame.

Image with Python, Jupyter Notebook and Pandas Code below.

Code and Image

name-of-you-image

3. The top 5 performing schools, based on the overall passing rate.

Image with Python, Jupyter Notebook and Pandas Code below.

Code and Image

name-of-you-image

4. The bottom 5 performing schools, based on the overall passing rate.

Image with Python, Jupyter Notebook and Pandas Code below.

Code and Image

name-of-you-image

5. The average math score for each grade level from each school.

Image with Python, Jupyter Notebook and Pandas Code below.

Code and Image

name-of-you-image

6. The average reading score for each grade level from each school.

Image with Python, Jupyter Notebook and Pandas Code below.

Code and Image

name-of-you-image

7. The scores by school spending per student.

Image with Python, Jupyter Notebook and Pandas Code below.

Code and Image

name-of-you-image

8. The scores by school size.

Image with Python, Jupyter Notebook and Pandas Code below.

Code and Image

name-of-you-image

9. The scores by school type.

Image with Python, Jupyter Notebook and Pandas Code below.

Code and Image

name-of-you-image

Deliverable 3: A Written Report for the School District Analysis
Instructions: For this part of the Challenge, write a report that summarizes your updated analysis and compares it with the results from the module.

The analysis should contain the following:

Overview of the school district analysis: Explain the purpose of this analysis.

Results: Using bulleted lists and images of DataFrames as support, address the following questions.

How is the district summary affected?
Below the analysis.

BEFORE DATA CLEANUP

Average Math Score = 79.0
Average Reading Score = 81.9
% Passing Math 75
% Passing Reading 86
% Overall Passing 65
Before Cleanup - PyCitySchools file

name-of-you-image

AFTER DATA CLEANUP

Average Math Score = 78.9
Average Reading Score = 81.9
% Passing Math 74.8
% Passing Reading 85.7
% Overall Passing 64.9
After Cleanup - PyCitySchools_Challenge file

name-of-you-image

OBSERVATION: Slight change in Math Score, including % Passing district averages, Comparing the two dataframes above, the average show the difference when the 9th grade student Math and Reading scores from Thomas High Schools were excluded from the District Summary.

How is the school summary affected?
BEFORE DATA CLEANUP

Thomas High School's % Overall Passing was 91, placing second
Before Cleanup - PyCitySchools file

name-of-you-image

AFTER DATA CLEANUP

Thomas High School's % Overall Passing was 65, placing eight
After Cleanup - PyCitySchools_Challenge file

name-of-you-image

OBSERVATION: Overall order change due to Thomas High School cleanup,

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
OBSERVATION: Replacing ninth graders’ math and reading scores affect Thomas High School’s performance between the other schools, Relative ranking for Thomas High School changed from 2nd place to 8th (see images above).

How does replacing the ninth-grade scores affect the following:
Analysis Below:

Math and reading scores by grade

Math and Reading Scores from Thomas High School 9th Grade set to "nan" and equivalent to 0.
Math and Reading Scores from Thomas High School 9th Grade means all of them failed (set to fail for analysis).
Doing that, the only significantly score affected was minimal in a very small in quantity.
Student count() Before THS Cleanup was: 1635
Student count() After THS Cleanup was: 1174
Scores by school spending

Thomas HS is in the spending bucket "$630-644"
Math and Reading Scores from Thomas High School 9th Grade means all of them failed (set to fail for analysis).
Doing that, the only significantly score affected was minimal in a very small in quantity.
Student count() Before THS Cleanup was: 1635
Student count() After THS Cleanup was: 1174
Before Cleanup - THS count()

name-of-you-image

After Cleanup - THS count()

name-of-you-image

Scores by school size
Removing Thomas High School 9th Grade reduces the "% Passing Math", "% Passing Reading" and "% Overall Passing" scores for size bucket.
In Addition

Removing Students from Thomas High School 9th Grade reduces the "% Passing Math", "% Passing Reading" and "% Overall Passing" scores for spending bucket "$630-644"
Thomas High School is allocated on Spending Bin "$630-644" (image below)
School Size"

name-of-you-image

THS Spending Bin "$630-644"

name-of-you-image

name-of-you-image

THS Before Cleanup on Spending Rank

name-of-you-image

Scores by school type
Thomas High School is in the "CHARTER" type
Removing Thomas High School 9th Grade scores reduces the "% Passing Math", "% Passing Reading" and "% Overall Passing", see below.
Before Cleanup - THS count()

name-of-you-image

After Cleanup - THS count()

name-of-you-image

Summary: Summarize the Average Math & Reading scores, % Passing Math and Reading scores, Overall Passing marks changes, changes that are reflected in the funding for each student (Difference each students funding is ~ $200).
All that by the updated School_District_Analysis Reading and Math Scores from Thomas High School 9th Grade have been replaced with NaNs.
