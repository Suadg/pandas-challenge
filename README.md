# pandas-challenge

## Background
You are the new Chief Data Scientist for your city's school district. In this capacity, you'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, you've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. Your task is to aggregate the data to showcase obvious trends in school performance.

## Requirements

### District Summary 
- Calculate the total number of unique schools 
- Calculate the total number of students 
- Calculate the total budget 
- Calculate the average (mean) math score 
- Calculate the average (mean) reading score 
- Use the code provided to calculate the percentage of students who passed math 
- Calculate the percentage of students who passed reading 
- Use the code provided to calculate the percentage of students that passed both math and reading 
- Create a new DataFrame for the above calculations called district_summary 

### School Summary 
Use the code provided to select the school type 
- Calculate the total student count 
- Use the code provided to calculate the per capita spending 
- Calculate the average test scores 
- Calculate the number of schools with math scores of 70 or higher 
- Calculate the number of schools with reading scores of 70 or higher 
- Use the provided code to calculate the schools that passed both math and reading with    scores of 70 or higher 
- Use the provided code to calculate the passing rates 
- Create a new DataFrame for the above calculations called per_school_summary 
- Highest-Performing Schools by Percentage of Overall Passing 
- Sort the schools by % Overall Passing in descending order 
- Save the results to a DataFrame called top_schools 
- Display the first 5 rows 
- Lowest-Performing Schools by Percentage of Overall Passing 
- Sort the schools by % Overall Passing in ascending order 
- Save the results to a DataFrame called bottom_schools 
- Display the first 5 rows 
- Math Scores by Grade 
- Use the code provided to separate the data by grade 
- Group by "school_name" and take the mean of each 
- Use the code to select only the math_score 
- Combine each of the scores above into single DataFrame called math_scores_by_grade 
- Reading Scores by Grade 
- Use the code provided to separate the data by grade 
- Group by "school_name" and take the mean of each 
- Use the code to select only the reading_score 
- Combine each of the scores above into single DataFrame called reading_scores_by_grade 
- Scores by School Spending 
- Use pd.cut with the provided code to bin the data by the spending ranges 
- Use the code provided to calculate the averages 
- Create the spending_summary DataFrame using the binned and averaged spending data 
- Scores by School Size 
- Use pd.cut with the provided code to bin the data by the school sizes 
- Use the code provided to calculate the averages 
- Create the size_summary DataFrame using the binned and averaged size data 
- Scores by School Type 
- Group the per_school_summary DataFrame by "School Type" and average the results 
- Use the code provided to select the new column data 
- Create a new DataFrame called type_summary that uses the new column data 