# 🧑‍💼 Employee Data Analysis Project

This project performs an in-depth analysis of an employee dataset from ABC Company, focusing on workforce distribution, salary trends, and critical role insights. It includes data preprocessing, statistical analysis, and data visualization to derive actionable insights for HR and organizational planning.

---

## 📂 Dataset Overview

The dataset contains **458 rows** and **9 columns**, with the following attributes:

| Column   | Description |
|----------|-------------|
| `Name`   | Employee's name |
| `Team`   | Department or team name |
| `Number` | Employee's unique identifier |
| `Position` | Job role or title |
| `Age`    | Employee's age |
| `Height` | Height in centimeters (corrected during preprocessing) |
| `Weight` | Weight in kilograms |
| `College` | College attended (optional in analysis) |
| `Salary` | Annual salary (with missing values handled) |

---

## 🛠️ Project Workflow

### 1. 🔍 Data Preprocessing
- **Height Correction**: Randomly corrected inconsistent height values (range: 150–180 cm)
- **Salary Imputation**: Filled missing salary values with the column mean
- **Duplicate Removal**: Removed exact duplicate rows for clean analysis

### 2. 📊 Analysis Tasks
- **Team Distribution**: Count and percentage of employees per team
- **Position Analysis**: Most common roles in the company
- **Age Group Trends**: Dominant employee age brackets
- **Salary Insights**: Top-paying teams and positions
- **Correlation Analysis**: Relationship between Age and Salary using correlation & regression

### 3. 📈 Visualizations
- **Bar & Pie Charts**: For team and position distribution
- **Heatmaps**: Display correlations among numeric variables
- **Grouped Bar Plots**: Salary expenditure by team and role
- **Scatter Plots**: Age vs Salary trends

---

## 💡 Key Insights

- 🔄 **Balanced Workforce**: Teams are fairly balanced with slight overrepresentation in a few
- 🧠 **Critical Roles**: SG and PF are the most frequent positions
- 🧒 **Young Talent**: Most employees are in the 26–35 age range
- 💸 **High Salary Roles**: Positions like PG and C have the highest pay
- 📉 **Age-Salary Dynamics**: Weak correlation found — younger employees can still earn high pay

--
