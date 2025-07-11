# PyCitySchools Analysis

- There are 15 schools in the 2 school types Charter and District. In the analysis each school types' overall passing rate was calculate by the percentage of the students that have passed math and reading, per school. This analysis also compares the budget per student in each school to the overall passing rate.
- The mean of the schools that have the least total school budget per capita,  less than $585, have a higer overall passing rate by 90.4%. Whereas the mean of the  schools that have the highest total school budget per capita, $645-680, have the least overall passing rate by 53.5%.
- Therefore, the school type Charter has a higher overall passing rate by 90.4% with the least total school budget per school capita, and the District has the least overall passing rate of 53.7% with the highest total school budget per school capita.

---

# Analysis Objectives

## Overview

This project analyzes student performance alongside school budget data from the fictional PyCitySchools district. It focuses on how financial factors such as per student spending and total school budget correlate with academic outcomes like passing rates and test scores. The goal is to identify trends that reveal whether higher spending leads to better performance across different school types and grade levels.

### Key Goals

1. **Understand District-Wide Performance**:
   * Total number of students and schools
   * Total budget allocation
   * Average math and reading scores
   * Overall passing rate (students passing both math and reading)
2. **School-Level Performance**:
   * Average scores and passing percentages for each school
   * Comparisons based on school size, budget per student, and type (district vs. charter)
3. **Grade-Level Analysis**:
   * Breakdown of average math and reading scores by grade
4. **Spending and Size Metrics**:
   * Correlations between spending per student and performance.
   * Influence of school size on passing rates

---

## Key Features and Metrics

### District Summary

* Total schools, students, and budget
* Average math and reading scores
* Overall passing percentage

### School Summary

* Average math and reading scores per school
* Math and reading passing percentages
* Per-student budget comparisons

### Grade-Level Performance

* Average scores by grade for each school

### Spending and Size Analysis

* Performance grouped by spending ranges and school size
* Identification of trends and correlations

---

## Insights and Recommendations

* **Charter schools consistently outperform district schools** in terms of average passing rates and scores
* **Spending per student does not guarantee higher performance**, suggesting other factors like teaching methods and school culture play significant roles
* **Smaller schools tend to have higher passing percentages**, highlighting the benefits of personalized attention

---

### Tools and Technologies

* Programming Language: Python
* Data Analysis Library: Pandas
* Development Environment: Jupyter Notebook
* File Handling: Pathlib
* Data Source: CSV files (school and student data)

### Deliverables

* Merged Dataset: Combined school and student performance data
* Summary Tables: District-level, school-level, and grade-level performance metrics
* Spending and Performance Analysis: Grouped insights by school type, size, and per-student budget
* Notebook Documentation: Step-by-step analysis and code logic in Jupyter Notebook
