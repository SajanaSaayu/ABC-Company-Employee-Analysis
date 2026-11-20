# ABC-Company-Employee-Analysis
Employee Data Analysis using Python, Pandas, NumPy, Matplotlib and Seaborn.


## Project Overview

This project focuses on analyzing employee data from ABC Company using Python. The dataset consists of 458 employee records and 9 columns.

The main objective of this project is to perform data preprocessing, exploratory data analysis (EDA), identify important patterns in employee distribution and salary expenditure, and represent the findings through graphical visualizations.

## Technologies and Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset Description

The dataset contains employee information with the following columns:

- Name
- Team
- Number
- Position
- Age
- Height
- Weight
- College
- Salary

**Dataset Size:** 458 rows and 9 columns.

## 1. Data Preprocessing

The following preprocessing step was performed:

- Imported the dataset using Pandas.
- Inspected the dataset and its columns.
- Identified inconsistent values in the Height column.
- Replaced the existing Height values with randomly generated integers between 150 and 180 using NumPy.
- Verified the updated Height column to ensure data consistency.

## 2. Analysis Tasks

### Task 1: Employee Distribution Across Teams

Calculated the number of employees in each team and their percentage contribution to the total workforce.

**Key Findings:**
- The dataset contains employees across 30 different teams.
- New Orleans Pelicans has the highest number of employees, with 19.
- Orlando Magic and Minnesota Timberwolves have the lowest number of employees, with 14 each.

**Visualization:** Bar Chart.

### Task 2: Employee Distribution Based on Position

Grouped employees based on their positions within the company and calculated the number of employees in each position.

**Key Findings:**
- The company has five different positions: SG, PF, PG, SF and C.
- SG has the highest number of employees, with 102.
- C has the lowest number of employees, with 79.

**Visualization:** Count Plot.

### Task 3: Predominant Age Group

Categorized employees into different age groups and identified the age group with the highest number of employees.

**Key Findings:**
- The predominant age group is 18–25 years.
- This age group contains 200 employees.
- The majority of employees belong to the younger age groups.

**Visualization:** Bar Chart.

### Task 4: Salary Expenditure Analysis

Calculated the total salary expenditure for each team and position to identify the team-position combination with the highest expenditure.

**Key Findings:**
- Los Angeles Lakers – SF has the highest salary expenditure.
- The total salary expenditure is $31,866,445.

**Visualization:** Horizontal Bar Chart.

### Task 5: Correlation Between Age and Salary

Investigated the relationship between employee age and salary using correlation analysis.

**Key Findings:**
- The correlation coefficient is approximately 0.214.
- There is a weak positive correlation between age and salary.
- Age alone does not determine an employee's salary.

**Visualization:** Scatter Plot with Regression Line.

## 3. Data Visualizations

The following graphical representations were created using Matplotlib and Seaborn:

1. Bar Chart – Employee distribution across teams.
2. Count Plot – Employee distribution based on positions.
3. Bar Chart – Employee distribution across age groups.
4. Horizontal Bar Chart – Salary expenditure across teams and positions.
5. Scatter Plot with Regression Line – Correlation between age and salary.

## 4. Overall Insights

- Employee distribution is relatively balanced across the 30 teams.
- SG is the most common employee position.
- The predominant employee age group is 18–25 years.
- Los Angeles Lakers – SF has the highest salary expenditure.
- Age and salary have a weak positive correlation.

## 5. Conclusion

This project provided an opportunity to understand employee data analysis using Python.

Through data preprocessing and exploratory data analysis, important insights were identified regarding employee distribution, positions, age groups and salary expenditure.

The visualizations helped represent the findings clearly and understand patterns within the dataset.

