# Pandas-Challenge
I am the new Chief Data Scientist for my city's school district. In this capacity, I'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, I've been asked to analyze the district-wide standardized test results. I'll be given access to every student's math and reading scores, as well as various information on the schools they attend. My task is to aggregate the data to showcase obvious trends in school performance.

## District Summary
Perform the necessary calculations and then create a high-level snapshot of the district's key metrics in a DataFrame.
Include the following:

-Total number of unique schools

-Total students

-Total budget

-Average math score

-Average reading score

-% passing math (the percentage of students who passed math)

-% passing reading (the percentage of students who passed reading)

-% overall passing (the percentage of students who passed math AND reading)
## School Summary
Perform the necessary calculations and then create a DataFrame that summarizes key metrics about each school.
Include the following:

-School name

-School type

-Total students

-Total school budget

-Per student budget

-Average math score

-Average reading score

-% passing math (the percentage of students who passed math)

-% passing reading (the percentage of students who passed reading)

-% overall passing (the percentage of students who passed math AND reading)

## Highest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in descending order and display the top 5 rows.

## Lowest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in ascending order and display the top 5 rows.

## Math Scores By Grade
Perform the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

## Reading Scores By Grade
Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

## Scores By School Spending
Create a table that breaks down school performance based on average spending ranges (per student).
Include the following metrics in the table:
-Average math score

-Average reading score

-% passing math (the percentage of students who passed math)

-% passing reading (the percentage of students who passed reading)

-% overall passing (the percentage of students who passed math AND reading)

## Scores By School Size
Create a DataFrame called size_summary that breaks down school performance based on school size (small, medium, or large).

## Scores By School Type
Use the per_school_summary DataFrame from the previous step to create a new DataFrame called type_summary.
This new DataFrame should show school performance based on the "School Type".


## PyCity School Analysis
- The dataset includes a total of 39,170 students across 15 schools. The total students average math score is 78.99 which is lower than the average reading score of 81.88. The passing math rate of 74.98% has a lower rate the reading pass rate of 85.81%. The overall passing rate is 65.17%. These findings indicate students perform better in reading comared to math.
- The bottom five schools are all district schools while the top five schools are all charter schools. The data also showed that district schools have more students than charter schools.
- In general, per student spending is higher in bottom performing schools than top performing.
- The students at Holden High School in grade 12 possess a higher average reading score (84.69). Students in grade 11 at Holden High School holds a higher math score (85) comparing all schools and grades.
- When the total number of students increases, the average math scores, the average reading scores, percent of passing math, percent of passing reading, and the overall passing rate decreases. From that, one can infer that when the student size rises, it negatively impacts student success.
