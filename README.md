# Employee Data Analysis Project

## Project Overview

This project analyzes an employee dataset to gain meaningful insights into workforce distribution, salary expenditure, age demographics, and the relationship between employee age and salary. Python, Pandas, Matplotlib, and Seaborn were used for data preprocessing, analysis, and visualization.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## Data Preprocessing

The following preprocessing steps were performed before analysis:

* Imported the dataset using Pandas.
* Checked the dataset structure using `info()`, `describe()`, and `head()`.
* Identified and handled missing values where required.
* Replaced invalid or missing values in the **Height** column with randomly generated values between **150 cm and 180 cm**.
* Converted data types where necessary.
* Created age groups using `pd.cut()` for age-based analysis.
* Verified the cleaned dataset before performing analysis.

---

## Analysis Tasks

### 1. Employee Distribution Across Teams

* Counted the number of employees in each team.
* Calculated the percentage contribution of each team relative to the total number of employees.

**Visualization:** Bar Chart / Pie Chart

---

### 2. Employee Distribution by Position

* Grouped employees based on their positions.
* Counted the number of employees in each position.

**Visualization:** Bar Chart / Pie Chart

---

### 3. Predominant Age Group

* Divided employees into different age groups.
* Identified the age group with the highest number of employees.

**Visualization:** Bar Chart

---

### 4. Salary Expenditure Analysis

* Calculated the total salary expenditure for each Team and Position combination.
* Identified the Team-Position combination with the highest salary expenditure.

**Visualization:** Bar Chart

---

### 5. Correlation Between Age and Salary

* Calculated the correlation coefficient between Age and Salary.
* Visualized the relationship using a scatter plot with a regression line.

**Visualization:** Scatter Plot

---

## Insights Gained

* Employee distribution across teams is fairly balanced, with each team contributing a similar percentage of the total workforce.
* Workforce distribution across positions shows that some positions have more employees than others.
* The majority of employees belong to a specific age group, indicating the predominant age category within the organization.
* Salary expenditure differs across Team-Position combinations, with one combination accounting for the highest overall salary spending.
* Correlation analysis reveals the nature of the relationship between employee age and salary, helping determine whether salary tends to increase with age.

---

## Conclusion

This project demonstrates how data analysis techniques can be used to explore employee-related information effectively. By combining preprocessing, statistical analysis, and data visualization, meaningful insights were obtained regarding employee distribution, salary allocation, age demographics, and salary trends. These findings can assist organizations in workforce planning and data-driven decision-making.

---


