# pandas-challenge
Module 4 Challenge

#  pandas-challenge contents
PyCitySchools folder that contains:
        ** Resources - These folders contains the "schools_complete.csv" and "students_complete.csv" files
        ** PyCitySchools.ipynb (Jupyter notebook to be graded)

# Aim of project 
   This project is a demonstration of my Pandas skillset thus far in the Data Analytics certification program.
   The following are the objectives of this assignment:
   
PyCitySchools Background:
   To create a Pandas script that analyzes district-wide standardized test results for math, reading, as well as both math and reading scores from various schools around the district. This analysis will help the school board and mayor to make strategic decisions regarding funding and budget distribution for students in those schools.

District Summary Calculations:

        ** Total schools
        ** Total students
        ** Total budget
        ** Average math score
        ** Average reading score
        ** % passing math (the percentage of students who passed math)
        ** % passing reading (the percentage of students who passed reading)
        ** % overall passing (the percentage of students who passed math AND reading)

School Summary Calculations:

        ** School name
        ** School type
        ** Total students
        ** Total school budget
        ** Per student budget
        ** Average math score
        ** Average reading score
        ** % passing math (the percentage of students who passed math)
        ** % passing reading (the percentage of students who passed reading)
        ** % overall passing (the percentage of students who passed math AND reading)

Highest-Performing Schools (by % Overall Passing) Calculations:

        ** School name
        ** School type
        ** Total students
        ** Total school budget
        ** Per student budget
        ** Average math score
        ** Average reading score
        ** % passing math (the percentage of students who passed math)
        ** % passing reading (the percentage of students who passed reading)
        ** % overall passing (the percentage of students who passed math AND reading)

Lowest-Performing Schools (by % Overall Passing) Calculations:

        ** School name
        ** School type
        ** Total students
        ** Total school budget
        ** Per student budget
        ** Average math score
        ** Average reading score
        ** % passing math (the percentage of students who passed math)
        ** % passing reading (the percentage of students who passed reading)
        ** % overall passing (the percentage of students who passed math AND reading)

Math Scores by Grade Calculations:

        ** Create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school

Reading Scores by Grade Calculations:

        ** Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school

Scores by School Spending Calculations:

        ** Average math score
        ** Average reading score
        ** % passing math (the percentage of students who passed math)
        ** % passing reading (the percentage of students who passed reading)
        ** % overall passing (the percentage of students who passed math AND reading)

Scores by School Size Calculations:

        ** Create a table that breaks down school performance based on school size (small, medium, or large)

Scores by School Type Calculations:

        ** Create a table that breaks down school performance based on type of school (district or charter).

# Analysis of PyCitySchools data

## Conclusion #1: 
        
        ** By looking at the top and bottom five schools, the top five schools are those that are charters which generally have approximately greater than 90% overall passing scores.

        In contrast, the bottom five schools are those that are a district type and generally have very low passing scores of approximately 53%.

## Conclusion #2: 

        ** By comparing the math and reading scores by grade, it seems to be the case that all schools perform much better with reading than math. In each Spending Ranges(Per Student) category, the Passing Reading is greater than % Passing Math. For example, looking at the spending_summary table, when considering the Spending Ranges(Per Student) to be <$585, the % Passing Reading is almost 3% higher than % Passing Math. 

## Conclusion #3:

        ** There seems to be a negative correlation between Spending Ranges (Per Student) and the Average Math Score and % Overall Passing. 
                
        ** Comparison of the Spending Ranges (Per Student) of <$585 has a % Overall Passing of 90% and $645-680 has a % Overall Passing of 53%. This means that the greater the amount of spending per student, the lower the % Overall Passing. 
                
        ** Considering the per_school_summary table, typically the larger school size, the greater the funding which intuitively makes sense a large student size needs more funding. Generally, charter schools are much smaller than district schools, which means that students are able to gain more one-on-one interaction with their teachers. This one-on-one interaction allows studnets to have more opportunities to have their pressing questions answered with less limitations from other students taking precedence in terms of teacher attention. Additionally, teachers have a smaller class size, therefore, a smaller grade load and may not be as overwhelmed with workload. This means that the teachers are possibly more well-rested and prepared to provide quality education.



        


