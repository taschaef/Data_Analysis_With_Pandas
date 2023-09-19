# School District Data Analysis With Pandas

## How To Use
The folder PyCitySchools contains the Jupyter Notebook file of my analysis. At the top of the code file is my analysis of the school district data, and following that is the code for the analysis. 

## Background
You are the new Chief Data Scientist for your city's school district. In this capacity, you'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, you've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. Your task is to aggregate the data to showcase obvious trends in school performance.

## Instructions
Using Pandas and Jupyter Notebook, create a report that includes the following data. Your report must include a written description of at least two observable trends based on the data.

## District Summary
1. Perform the necessary calculations and then create a high-level snapshot of the district's key metrics in a DataFrame.
Include the following:
  - Total number of unique schools
  - Total students
  - Total budget
  - Average math score
  - Average reading score
  - % passing math (the percentage of students who passed math)
  - % passing reading (the percentage of students who passed reading)
  - % overall passing (the percentage of students who passed math AND reading)

<img width="636" alt="image" src="https://github.com/taschaef/School_District_Data_Analysis_With_Pandas/assets/124079708/9a5e6312-d19b-46d6-b0ea-1ca48e0ba981">

## School Summary
1. Perform the necessary calculations and then create a DataFrame that summarizes key metrics about each school.
Include the following:
  - School name
  - School type
  - Total students
  - Total school budget
  - Per student budget
  - Average math score
  - Average reading score
  - % passing math (the percentage of students who passed math)
  - % passing reading (the percentage of students who passed reading)
  - % overall passing (the percentage of students who passed math AND reading)

<img width="559" alt="image" src="https://github.com/taschaef/School_District_Data_Analysis_With_Pandas/assets/124079708/1e98a255-816e-4b44-80d7-b3afbbada28d">

## Highest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in descending order and display the top 5 rows.
Save the results in a DataFrame called "top_schools".

<img width="564" alt="image" src="https://github.com/taschaef/School_District_Data_Analysis_With_Pandas/assets/124079708/ce181b60-32e1-44cf-9a08-100a77cebbc3">

## Lowest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in ascending order and display the top 5 rows.
Save the results in a DataFrame called "bottom_schools".

<img width="554" alt="image" src="https://github.com/taschaef/School_District_Data_Analysis_With_Pandas/assets/124079708/0b10d692-96b5-4205-9d7f-b92dc69ed3ac">

## Math Scores by Grade
Perform the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

<img width="448" alt="image" src="https://github.com/taschaef/School_District_Data_Analysis_With_Pandas/assets/124079708/cfcb914d-c6a1-4117-980e-784e28113ede">

## Reading Scores by Grade
Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

<img width="492" alt="image" src="https://github.com/taschaef/School_District_Data_Analysis_With_Pandas/assets/124079708/b7274622-357e-46d4-8d41-e376899c2b83">

## Scores by School Spending
Create a table that breaks down school performance based on average spending ranges (per student).
Use pd.cut to categorize spending based on the bins.
Use the scores above to create a DataFrame called spending_summary.
Include the following metrics in the table:
  - Average math score
  - Average reading score
  - % passing math (the percentage of students who passed math)
  - % passing reading (the percentage of students who passed reading)
  - % overall passing (the percentage of students who passed math AND reading)

<img width="550" alt="image" src="https://github.com/taschaef/School_District_Data_Analysis_With_Pandas/assets/124079708/2ff65179-7a65-4719-9242-f15f107f1c15">
<img width="485" alt="image" src="https://github.com/taschaef/School_District_Data_Analysis_With_Pandas/assets/124079708/f8d42d83-342c-4103-821d-aff3a1334ed0">

## Scores by School Size    
Use pd.cut on the "Total Students" column of the per_school_summary DataFrame.
Create a DataFrame called size_summary that breaks down school performance based on school size (small, medium, or large).

<img width="532" alt="image" src="https://github.com/taschaef/School_District_Data_Analysis_With_Pandas/assets/124079708/8be6af22-8a39-4e78-bd2b-0a110fa6781b">

## Scores by School Type
Use the per_school_summary DataFrame from the previous step to create a new DataFrame called type_summary.
This new DataFrame should show school performance based on the "School Type".

<img width="492" alt="image" src="https://github.com/taschaef/School_District_Data_Analysis_With_Pandas/assets/124079708/b0136f16-ecfb-4396-b6c9-c8952df7fc0b">
