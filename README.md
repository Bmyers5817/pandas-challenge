# pandas-challenge

I selected to work through the PyCitySchools project for the pandas challenge homework.

I was running into 1 challenge where the school type was not completed for each school.  Upon further research (via Google search), I found and tried use of the set_index function and this fixed my issue.  I kept and commented my original code to show where I started. This error in the original coding impacted the School Summary, Top Performing and Bottom Performing School summaries.

I am confident that my calcualtions and formats are producing what was expected.  

In the Scores by School Spending challenge, I maintained my calculation of overall passing of both math and reading as I had done in previous challenges.  However, the instructions state to average the given % Passing Math and % Passing Reading - which would not equate to the same rate.  Therefore, you will see that I calculate this using the percent of students who passed both and not an average of math and reading passing percentages.  I carried this calculation throughout this exercise, which I think is much more accurate.
___________________________________________________________________________________________________________________________________________
Analysis:

In reviewing the output of top and bottom performing schools, I can quickly see that there some corelation which impacts the overall passing percentages.  Meaning, the larger the school body, the percentage of overall passing both reading in math is quite low in comparison to smaller schools.  For the larger schools, there also appears to be quite a challenge with students' math scores.  However, math and reading scores were consistent from grade to grade by school.  This was further evidenced with the Scores by School Size summary table produced.

It was also interesting to see that larger budgets (specfically on a per student basis) did not necessarily assist with students' averages.  It appeared that the greater the budget per student, the worse averages became.

Lastly, it appears that Charter schools outperformed District schools.  However, it is import to note that Charter schools are generally smaller in size than District schools.


