# PyCitySchools Analysis

Welcome to the PyCitySchools Analysis repository! This project showcases a comprehensive data-driven analysis of standardized test results across a city’s school district. The analysis was performed as part of my role as Chief Data Scientist, where I focused on deriving actionable insights to inform strategic decisions on school budgets and priorities.

## Project Background

As the newly appointed Chief Data Scientist, I was tasked with analyzing district-wide standardized test results. My objective was to identify trends in student performance across various schools and grades, providing a data-driven foundation for improving educational outcomes in the district.

This analysis involved aggregating student data, including math and reading scores, and school-specific information to create a detailed report on school performance. The findings are intended to support decision-making processes at the school board and mayoral levels.

## Key Features of the Analysis

### 1. **District Summary**
   - **Total Schools**: Aggregated the number of unique schools in the district.
   - **Total Students**: Counted the total student population.
   - **Total Budget**: Summarized the district's overall budget.
   - **Average Math and Reading Scores**: Calculated the district-wide average scores.
   - **Passing Percentages**: Determined the percentage of students passing math, reading, and both subjects.

### 2. **School Summary**
   - Generated a comprehensive DataFrame that captures essential metrics for each school, including:
     - School type (e.g., charter, public)
     - Student population
     - Budget per student
     - Average test scores
     - Passing rates for math, reading, and overall

### 3. **Performance Rankings**
   - **Top Performing Schools**: Identified and ranked the highest-performing schools based on overall passing percentages.
   - **Lowest Performing Schools**: Highlighted the schools that require the most attention, ranked by the lowest overall passing percentages.

### 4. **Grade-Level Performance**
   - Analyzed math and reading scores by grade level (9th-12th) for each school, offering insights into how performance varies across different stages of education.

### 5. **Impact of School Spending**
   - Investigated the relationship between per-student spending and academic performance, using spending categories to analyze trends in average scores and passing rates.

### 6. **Performance by School Size and Type**
   - **School Size**: Assessed how the total student population impacts performance by categorizing schools into small, medium, and large.
   - **School Type**: Compared performance between different types of schools, such as charter and public schools.

## Summary of Findings

- **Spending vs. Performance**: Schools with moderate spending per student ($630-$645) tend to perform better in both math and reading compared to those with the highest or lowest spending, suggesting diminishing returns at extreme ends of the spending spectrum.
- **School Size Influence**: Medium-sized schools (1000-2000 students) generally show higher overall passing rates, indicating that these schools might benefit from an optimal balance of resources and student engagement.
  
## Repository Structure

- **`PyCitySchools/`**: Main directory containing all project files.
  - **`PyCitySchools.ipynb`**: Jupyter Notebook with the full analysis.
  - **`Resources/`**: Contains input data files, including student scores and school data.
  - **`Output/`**: Generated outputs such as charts, tables, and summary files.
  
