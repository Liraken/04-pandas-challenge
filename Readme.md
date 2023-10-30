# pandas-challenge

## Observed Trends:
- Between District Schools and Charter Schools the later tends to have higher averages for scores, but this is probably just due to having less than half the total number of students that District Schools in this data set.
- Despite the above point reading scores averages are rather close between charter and district schools, I could think of a couple reasons for this but I think the most likely reason for this is many more students having a natural inclination to reading than math and thus division of teacher attention between more students has less of an effect on reading scores. 
-Schools that spend less per student have higher averages but I think this is also just due to having less Students to teach, the schools that have move students do have a higher budget per student but not at an equvilent ratio to their increase of number of students.
- So my overall conclusion from analysising this data is enviroments with less students generally produce/attract better proforming students on average. If I was looking to decide where I was going to send a child of my own I'd probably look for some place that had less Students to divide the teachers attention and only when a School met that critera would I than look at their budget/quality.

## Instructions
Using Pandas and Jupyter Notebook, create a report that includes the following data. Your report must include a written description of at least two observable trends based on the data.

District Summary
Perform the necessary calculations and then create a high-level snapshot of the district's key metrics in a DataFrame.

Include the following:

Total number of unique schools

Total students

Total budget

Average math score

Average reading score

% passing math (the percentage of students who passed math)

% passing reading (the percentage of students who passed reading)

% overall passing (the percentage of students who passed math AND reading)

School Summary
Perform the necessary calculations and then create a DataFrame that summarizes key metrics about each school.

Include the following:

School name

School type

Total students

Total school budget

Per student budget

Average math score

Average reading score

% passing math (the percentage of students who passed math)

% passing reading (the percentage of students who passed reading)

% overall passing (the percentage of students who passed math AND reading)

Highest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in descending order and display the top 5 rows.

Save the results in a DataFrame called "top_schools".

Lowest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in ascending order and display the top 5 rows.

Save the results in a DataFrame called "bottom_schools".

Math Scores by Grade
Perform the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

Reading Scores by Grade
Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

Scores by School Spending
Create a table that breaks down school performance based on average spending ranges (per student).

Use the code provided below to create four bins with reasonable cutoff values to group school spending.

Use the following code to then calculate mean scores per spending range.

Include the following metrics in the table:

Average math score

Average reading score

% passing math (the percentage of students who passed math)

% passing reading (the percentage of students who passed reading)

% overall passing (the percentage of students who passed math AND reading)

Scores by School Size
Use the following code to bin the per_school_summary.

Create a DataFrame called size_summary that breaks down school performance based on school size (small, medium, or large).

Scores by School Type
Use the per_school_summary DataFrame from the previous step to create a new DataFrame called type_summary.

This new DataFrame should show school performance based on the "School Type".


### References
* For this I refrenced one git repository
	* https://github.com/jzhao0626/HW04_Pandas_Challenge
	* As well as refrencing some from class activities