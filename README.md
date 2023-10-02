# Title: Module 4 Challenge (UC Berkeley Data Analytics Bootcamp 2023)
# Author:  Michael Jardinico
# version: 1.0
# Date created: 10/1/23

## Description: 
The file called PyCitySchools_starter.ipynb was created using Pandas and Jupyter Notebook. It showcased some calculated report of high-level snapshot of the school district's key metrics in a DataFrame which includes the following: 
    1. Total number of unique schools
    2. Total students
    3. Total budget
    4. Average math score
    5. Average reading score
    6. % passing math (the percentage of students who passed math)
    7. % passing reading (the percentage of students who passed reading)
    8. % overall passing (the percentage of students who passed math AND reading)

The School Summary includes the following key metrics:
    1. School name
    2. School Type
    3. Total students
    4. Total school budget
    5. Per student budget
    6. Average math score
    7. Average reading score
    8. % passing math (the percentage of students who passed math)
    9. % passing reading (the percetnage of students who passed reading)
    10. % overall passing (the percentage of students who passed mant AND reading)

For the overall summary, the following were provided:
    1. Highest-performing schools (by % Overall Passing)
    2. Lowest-performing schools (by % Overall Passing)
    3. Math Scores by grade level (9th, 10th, 11th, 12th)
    4. Reading Scores by grader level (9th, 10ty, 11th, 12th)
    5. Scores by School Spending based on four cut-off range values
    6. Scores by School Size with based on three cut-off range balues.

# Dependencies
The script is written using Python 3.11 in Jupyter Notebook, although it may run using earlier versions of 3.x. The Python module and library used are Pandas and pathlib. 

# Installing
1. Create a new repository for this project called pandas-challenge. 
2. Clone the new repository to your computer.
3. Inside your local Git repository, create a folder called PyCitySchools and a README.md file
4. Inside PyCitySchools folder that you just created, add the following content: 
   a. A new file called PyCitySchool_starter.ipynb. This will be the main script of the report
   b. A sub-folder called "Resources", which contains two data files called schools_complete.csv and students_complete.csv
   c. The file named .gitkeep is optional. This file makes the Resources subfolder to be tracked in GitHub

# Getting Started
1. Open PyCitySchools_starter.ipynb with Jupyter Notebook.
2. Under the top level title "PyCity Schools Analysis", add dependencies such as pandas and pathlib
3. Create paths to the csv files using pathlib
4. Using Pandas DataFrame, read the two csv files
5. Combing the data into a single dataset using pd.merge left join.
6. Create a category "District Summary" that calculates the following: 
   * school_count 
   * student_count 
   * total_budget 
   * average_math_score
   * average_reading_score
   * passing_math_percentage
   * passing_reading_percentage
   * overall_passing_rate
   * Display the DataFrame in a variable called distric_summary
7. Create a category "School Summary" that calculates the following:
   * school_types
   * per_school_counts
   * per_school_budget_capita
   * per_school_math
   * per_school_reading
   * use groupby to get the students_passing_math per school
   * use groupby to get the students_passing_reading per school
   * using the provided code, calculate for number of students per school that passed both math and reading with 
     scores over 70 or higher
   * create DataFrame to show percentage passing in math, reading and overall passing
   * Set the type of school and create a DataFrame in a variable named per_school_summary
8. Create a category "Highest-Performing Schools (by % Overall Passing)" that sorts:
   * top_schools in descending order and display the top 5 rows
9. Create a category "Bottom Performing Schools (By % Overall Passing)" that sorts:
   * bottom_schools in descending order and display the bottom 5 rows.
10. Create a category "Math Score by Grade" using the code provided and display the result in a DataFrame (math_scores_by_grade)
11. Create a category "Reading Score by Grade" using the code provided and display the result in a DataFrame (reading_scores_by_grade)
12. Create a category "Scores by School Spending" and establish the bins and by using pd.cut display them in a variable school_spending_df
13. Create a category "Scores by School Size" and establish the bins and by using pd.cut display them in a variable size_summary
14. Lastly, create a category "Scores by School Type" and group the results in "Scores by School Spending" and "Scores by School Size" 
    categories and display in a DataFrame variable called type_summary.


