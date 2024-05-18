# Background
You are the new Chief Data Scientist for your city's school district. In this capacity, you'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.
As a first task, you've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. Your task is to aggregate the data to showcase obvious trends in school performance.

# Findings
1) Charted Schools have students that score much higher and pass more on average than District Schools. Particularly Math (with Charter schools having a 90% pass rate while 53% for District schools). This isnt sufficent to claim these schools produce better students as there needs to be further analysis in course content, grading criteria to compare the metrics.

2) Examining Spending ranges, the more funding a school gets the worse the passing rates are (90% at the lowest bucket while it gets proceedingly smaller going to 53% at the largest bucket). This isnt enough to speak on the relationship between the two. Firstly, the large funding could be more related to the district schools which ussually have medium to large capacity and thus demand larger funding. Additionally, the schools that are performing well with the funding they have should be further investigated for what programs they invest in and what really brings utility to the education process.

3) In conclusion, higher grades will be produced from a student in a Charter school with small class sizes. However further analysis is required if this means students are better educated underthese circumstances.

# Instructions
Using Pandas and Jupyter Notebook, create a report that includes the following data. Your report must include a written description of at least two observable trends based on the data.

## District Summary
Perform the necessary calculations and then create a high-level snapshot of the district's key metrics in a DataFrame.
## School Summary
Perform the necessary calculations and then create a DataFrame that summarizes key metrics about each school.
## Highest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in descending order and display the top 5 rows.
Save the results in a DataFrame called "top_schools".
## Lowest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in ascending order and display the top 5 rows.
Save the results in a DataFrame called "bottom_schools".
## Math Scores by Grade
Perform the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.
## Reading Scores by Grade
Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.
## Scores by School Spending
Create a table that breaks down school performance based on average spending ranges (per student).
## Scores by School Size
Create a DataFrame called size_summary that breaks down school performance based on school size (small, medium, or large).
## Scores by School Type
Show school performance based on the "School Type".


