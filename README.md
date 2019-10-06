# School-District-Test-Score-Analysis

The goal of this project was to calculate and display various performance metrics for a school district based on collected data from student math and reading test results. Since the baseline data was provided in CSV format, Python with Pandas (through Jupyter Notebooks) was used to clean and process the data, as well as calculate the desired outputs.

## Questions

### District Summary

1. How many schools are included in the district?
2. How many total students are included in the district?
3. What is the combined total budget of all the schools in the district?
4. What is the average math test score of all the students in the district?
5. What is the average reading test score of all the students in the district?
6. What percentage of all students in the district have a passing math test score (70 or above)?
7. What percentage of all students in the district have a passing reading test score (70 or above)?
8. What is the overall percentage of students in the district passing the math and reading tests?

### School Summary

1. Which schools are included in the district?
2. What is the type of each school?
3. How many total students attend each school?
4. What is the total budget for each school?
5. What is the per student budget for each school?
6. What is the average math test score for all of the students in each school?
7. What is the average reading test score for all of the students in each school?
8. What percentage of the students in each school have a passing math test score (70 or above)?
9. What percentage of the students in each school have a passing reading test score (70 or above)?
10. What is the overall percentage of students in each school passing the math and reading tests?

### Top Performing Schools

1. Which schools are the top five in overall percentage of students passing the math and reading tests?
2. What is the type of each school?
3. How many total students attend each school?
4. What is the total budget for each school?
5. What is the per student budget for each school?
6. What is the average math test score for all of the students in each school?
7. What is the average reading test score for all of the students in each school?
8. What percentage of the students in each school have a passing math test score (70 or above)?
9. What percentage of the students in each school have a passing reading test score (70 or above)?
10. What is the overall percentage of students in each school passing the math and reading tests?

### Bottom Performing Schools

1. Which schools are the bottom five in overall percentage of students passing the math and reading tests?
2. What is the type of each school?
3. How many total students attend each school?
4. What is the total budget for each school?
5. What is the per student budget for each school?
6. What is the average math test score for all of the students in each school?
7. What is the average reading test score for all of the students in each school?
8. What percentage of the students in each school have a passing math test score (70 or above)?
9. What percentage of the students in each school have a passing reading test score (70 or above)?
10. What is the overall percentage of students in each school passing the math and reading tests?

### Math Test Scores by Grade

1. What is the average math test score for all 9th grade students in each school?
2. What is the average math test score for all 10th grade students in each school?
3. What is the average math test score for all 11th grade students in each school?
4. What is the average math test score for all 12th grade students in each school?

### Reading Test Scores by Grade

1. What is the average reading test score for all 9th grade students in each school?
2. What is the average reading test score for all 10th grade students in each school?
3. What is the average reading test score for all 11th grade students in each school?
4. What is the average reading test score for all 12th grade students in each school?

### Average Test Scores by School Spending

1. What per student budget spending range does each school fall into?
2. For each spending range, what is the average math test score for all students in the included schools?
3. For each spending range, what is the average reading test score for all students in the included schools?
4. For each spending range, what percentage of all students in the included schools have a passing math test score (70 or above)?
5. For each spending range, what percentage of all students in the included schools have a passing reading test score (70 or above)?
6. For each spending range, what overall percentage of all students in the included schools are passing the math and reading tests?

### Average Test Scores by School Size

1. What total student size range does each school fall into?
2. For each size range, what is the average math test score for all students in the included schools?
3. For each size range, what is the average reading test score for all students in the included schools?
4. For each size range, what percentage of all students in the included schools have a passing math test score (70 or above)?
5. For each size range, what percentage of all students in the included schools have a passing reading test score (70 or above)?
6. For each size range, what overall percentage of all students in the included schools are passing the math and reading tests?

### Average Test Scores by School Type

1. For each school type, what is the average math test score for all students in the included schools?
2. For each school type, what is the average reading test score for all students in the included schools?
3. For each school type, what percentage of all students in the included schools have a passing math test score (70 or above)?
4. For each school type, what percentage of all students in the included schools have a passing reading test score (70 or above)?
5. For each school type, what overall percentage of all students in the included schools are passing the math and reading tests?

## Datasets

1. https://github.com/mjknj18/School-District-Test-Score-Analysis/blob/master/School%20District%20Data/schools_complete.csv
2. https://github.com/mjknj18/School-District-Test-Score-Analysis/blob/master/School%20District%20Data/students_complete.csv

## Tasks

### District Summary

1. Import school data and student data CSV files as individual Pandas data frames.
2. Merge individual data frames into combined data frame based on school name.
3. Calculate the total number of schools in the district.
4. Calculate the total number of students in the district.
5. Calculate the average math test score of all students in the district.
6. Calculate the average reading test score of all students in the district.
7. Calculate the percentage of all students in the district that have a passing math test score.
8. Calculate the percentage of all students in the district that have a passing reading test score.
9. Calculate the overall percentage of students in the district that are passing the math and reading tests.
10. Output calculated values to district summary data frame.

### School Summary

1. Split combined data frame into groups by school name.
2. Extract the type of each school.
3. Extract the total number of students attending each school.
4. Extract the total budget for each school.
5. Calculate per student budget for each school.
6. Calculate the average math test score of all students in each school.
7. Calculate the average reading test score of all students in each school.
8. Calculate the percentage of all students in each school that have a passing math test score.
9. Calculate the percentage of all students in each school that have a passing reading test score.
10. Calcuate overall percentage of students in each school that are passing the math and reading tests.
11. Output extracted and calculated values to school summary data frame.

### Top Performing Schools

1. Sort school summary data frame by best overall passing percentages.
2. Output summary data for top five performing schools in best schools data frame.

### Bottom Performing Schools

1. Sort school summary data frame by worst overall passing percentages.
2. Output summary data for bottom five performing schools in worst schools data frame.

### Math Test Scores by Grade

1. Split combined data frame into groups by grade level.
2. Split groups for each grade level into sub-groups by school name.
3. Calculate average math test scores for all students of each grade level in each school.
4. Output calculated values to math scores data frame.

### Reading Test Scores by Grade

1. Split combined data frame into groups by grade level.
2. Split groups for each grade level into sub-groups by school name.
3. Calculate average reading test scores for all students of each grade level in each school.
4. Output calculated values to reading scores data frame.

### Average Test Scores by School Spending

1. Define per student budget spending ranges and range labels.
2. Cut and bin school summary data frame based on per student budget spending ranges.
3. Split school summary data frame into groups by per student budget spending ranges.
4. Calculate the average math test score for all students in the schools within each spending range.
5. Calculate the average reading test score for all students in the schools within each spending range.
6. Calculate the percentage of all students in the schools within each spending range that have a passing math test score.
7. Calculate the percentage of all students in the schools within each spending range that have a passing reading test score.
8. Calculate the overall percentage of students in the schools within each spending range that are passing the math and reading tests.
9. Output calculated values for each spending range to per student budget summary data frame.

### Average Test Scores by School Size

1. Define school size ranges and range labels.
2. Cut and bin school summary data frame based on per student budget size ranges.
3. Split school summary data frame into groups by per student budget size ranges.
4. Calculate the average math test score for all students in the schools within each size range.
5. Calculate the average reading test score for all students in the schools within each size range.
6. Calculate the percentage of all students in the schools within each size range that have a passing math test score.
7. Calculate the percentage of all students in the schools within each size range that have a passing reading test score.
8. Calculate the overall percentage of students in the schools within each size range that are passing the math and reading tests.
9. Output calculated values for each size range to school size summary data frame.

### Average Test Scores by School Type

1. Split school summary data frame into groups by school type.
2. Calculate the average math test score for all students in the schools within each type category.
3. Calculate the average reading test score for all students in the schools within each type category.
4. Calculate the percentage of all students in the schools within each type category that have a passing math test score.
5. Calculate the percentage of all students in the schools within each type category that have a passing reading test score.
6. Calculate the overall percentage of students in the schools within each type category that are passing the math and reading tests.
7. Output calculated values for each type category to school type summary data frame.

## Results

1. https://github.com/mjknj18/School-District-Test-Score-Analysis/blob/master/School_District_Test_Analysis_Main.ipynb

### District Summary

<img src = "https://github.com/mjknj18/School-District-Test-Score-Analysis/blob/master/Results%20Screenshots/District%20Summary.JPG">

### School Summary

<img src = "https://github.com/mjknj18/School-District-Test-Score-Analysis/blob/master/Results%20Screenshots/School%20Summary.JPG">

### Top Performing Schools

<img src = "https://github.com/mjknj18/School-District-Test-Score-Analysis/blob/master/Results%20Screenshots/Top%20Performing%20Schools.JPG">

### Bottom Performing Schools

<img src = "https://github.com/mjknj18/School-District-Test-Score-Analysis/blob/master/Results%20Screenshots/Bottom%20Performing%20Schools.JPG">

### Math Test Scores by Grade

<img src = "https://github.com/mjknj18/School-District-Test-Score-Analysis/blob/master/Results%20Screenshots/Math%20Scores%20by%20Grade.JPG">

### Reading Test Scores by Grade

<img src = "https://github.com/mjknj18/School-District-Test-Score-Analysis/blob/master/Results%20Screenshots/Reading%20Scores%20by%20Grade.JPG">

### Average Test Scores by School Spending

<img src = "https://github.com/mjknj18/School-District-Test-Score-Analysis/blob/master/Results%20Screenshots/Scores%20by%20School%20Spending.JPG">

### Average Test Scores by School Size

<img src = "https://github.com/mjknj18/School-District-Test-Score-Analysis/blob/master/Results%20Screenshots/Scores%20by%20School%20Size.JPG">

### Average Test Scores by School Type

<img src = "https://github.com/mjknj18/School-District-Test-Score-Analysis/blob/master/Results%20Screenshots/Scores%20by%20School%20Type.JPG">


## Conclusions

The first conclusion that can be drawn is that charter schools with smaller total student headcounts had the highest overall passing rates for math and reading tests. In contrast, district schools with larger total student headcounts had the lowest overall passing rates for math and reading tests. Since the average budgets per student for both charter and district schools were roughly in the same range, a reasonable explanation is that the smaller student headcounts in charter schools allow for smaller class sizes and more personalized learning. This approach generally enables students to better learn and retain math and reading knowledge, and score higher on the tests. This would likely be more difficult in a district school with double or triple the student headcount.

A second conclusion that can be drawn from the data is that no correlation exists between a student's grade level and how they scored on the math and reading tests. For all fourteen schools included in this analysis, the average test scores for each subject were within two percentage points across the four grade levels. Within certain schools, the average test scores increased with grade level, in others they decreased, and some had no apparent trend. The school itself was definitely more of a defining factor in student test performance than what level a student was at within that school.

## Disclaimer

The baseline data used for this analysis was provided by a third party source and its accuracy in relation to actual school district test score data is unknown.