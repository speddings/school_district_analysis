# school_district_analysis

## Overview of School District Analysis
The school board wants to analayze performance trends on student funding and standardized test scores in math and reading for the entire district. The school board has asked for the following information:
 - A district summary
 - A school summary 
 - The top 5 and bottom 5 performing schools, based on the overall passing rate
 - The average math score for each grade level from each school
 - The average reading score for each grade level from each school
 - The scores by school spending per student, by school size, and by school type

## Resources
- Data source: students_complete.csv, schools_complete.csv
- Software: Python v 3.7, Anaconda, Jupyter Notebook

## School District Analysis Results
To uphold state-testing standards, the analysis was conducted twice. The first analysis included all students from 15 schools. The second analysis removed the 9th grade class of Thomas High School for potential academic dishonesty. This was accomplished by replacing math and reading test scores with 'Nan' (or Not a Number) for 461 students.

### 1 District Level Summary 
_District Summary - First Analysis_

![dataframe output](/resources/first_district_summary.png)
_District Summary - Second Analysis_

![dataframe output](/resources/second_district_summary.png)

Removing the scores of the 9th grade class of Thomas High School did not dramatically affect the district scores and percentages overall, dropping very little.  Only 461 out of 39,170 students were excluded.

### 2 School Summary & Thomas High School's Performance
_Top Schools - First Analysis_

![dataframe output](/resources/first_top_schools.png)
_Top Schools - Second Analysis_

![dataframe output](/resources/second_top_schools.png)
- School rankings were not affected by the second analysis
- Thomas High School scores and percentage numbers changed less than 1  percentage point in each category.  

  
### 3 Math and Reading Scores by Grade
_Math Scores - First Analysis_

![dataframe output](/resources/first_math_scores_by_grade.png)

_Math Scores - Second Analysis_

![dataframe output](/resources/second_math_scores_by_grade.png)

_Reading Scores - First Analysis_

![dataframe output](/resources/first_reading_scores_by_grade.png)

_Reading Scores - Second Analysis_

![dataframe output](/resources/second_reading_scores_by_grade.png)

Excluding the math and reading scores for Thomas High School 9th grade did not affect any other schools or grades. 

### 4 Scores by School Spending
_School Spending - First Analysis_

![dataframe output](/resources/first_spending_summary.png)

_School Spending - Second Analysis_

![dataframe output](/resources/second_spending_summary.png)

School spending did not change, even in the category that contains Thomas High School, $630-644.


### 5 Scores by School Size

_School Size - First Analysis_

![dataframe output](/resources/first_size_summary.png)

_School Size - Second Analysis_

![dataframe output](/resources/second_size_summary.png)

Thomas High School is categories as a medium size school.  The metrics for Medium size schools did not change. 

### 6 Scores by School Type

_School Type - First Analysis_

![dataframe output](/resources/first_type_summary.png)

_School Type - Second Analysis_

![dataframe output](/resources/second_type_summary.png)

Thomas High School is a charter school. The charter type scores and percentages show a minimal changg after excluding the ninth grade scores.

### __School District Analysis Summary__
To summarize the changes after math and reading scores were replaced for the Thomas High School ninth grade students:
- __Scores by Grade__: Excluding the math and reading scores did not affect any other schools or grades, only the ones replaced. 
- __School Spending__: School spending did not change.
- __School Size__: The metrics for Medium size schools did not change. 
- __School Type__: The charter type metrics show a minimal change after excluding the ninth grade scores.


