# 👨‍💼 HR Analytics Dashboard | Power BI Project

## 📌 Project Overview

The HR Analytics Dashboard is an interactive Power BI solution designed to help Human Resources teams monitor workforce trends, employee attrition, and key HR metrics.

The dashboard provides management with a comprehensive view of employee demographics, attrition patterns, salary distribution, job roles, and workforce performance. It enables HR leaders to identify the root causes of employee turnover and make data-driven decisions to improve employee retention.

---

# 🎯 Business Problem

Employee attrition is one of the major challenges faced by organizations. High turnover leads to:

* Increased recruitment costs
* Loss of skilled employees
* Reduced productivity
* Increased training expenses
* Lower employee morale

The HR department needed a centralized dashboard to analyze workforce data and understand the factors contributing to employee attrition.

The goal was to identify trends and patterns related to employee turnover and support strategic workforce planning.

---

# 🚀 Project Objectives

The primary objectives of this project were:

* Monitor overall workforce statistics
* Measure employee attrition rate
* Identify high-risk employee segments
* Analyze attrition by age, salary, education, and job role
* Support employee retention initiatives
* Enable data-driven HR decision-making

---

# 🛠️ Tools & Technologies Used

* Power BI
* Power Query
* DAX
* Excel Dataset
* Data Modeling

---

# 📊 Dataset Overview

The dataset contains employee-related information including:

### Employee Information

* Employee ID
* Gender
* Age
* Department
* Job Role
* Education

### Employment Information

* Salary
* Years at Company
* Attrition Status
* Department

### Workforce Metrics

* Employee Count
* Attrition Count
* Attrition Rate
* Average Salary
* Average Age

---

# 🧹 Data Cleaning & Transformation

Data preprocessing was performed using Power Query.

### Transformations Applied

* Removed duplicate records
* Handled missing values
* Corrected data types
* Standardized department names
* Created calculated columns
* Optimized data model relationships

These transformations ensured accurate reporting and analysis.

---

# 📈 Key Performance Indicators (KPIs)

The dashboard provides a quick summary of workforce performance.

### Total Employees

**1470**

Represents the total workforce within the organization.

### Attrition Count

**237**

Represents employees who left the company.

### Attrition Rate

**16.1%**

Measures employee turnover percentage.

### Average Salary

**6.5K**

Represents the average employee salary.

### Average Age

**37 Years**

Provides an overview of workforce demographics.

### Average Years at Company

**7 Years**

Measures employee tenure within the organization.

---

# 📊 Dashboard Visual Analysis

## 1️⃣ Attrition by Gender

This visual compares attrition between male and female employees.

### Insights

* Male Attrition: 140 Employees
* Female Attrition: 79 Employees

### Business Value

Helps HR understand turnover trends across gender groups and evaluate workforce diversity initiatives.

---

## 2️⃣ Attrition by Education

This donut chart analyzes employee attrition based on educational background.

### Key Findings

* Life Sciences: 38%
* Medical: 27%
* Marketing: 15%
* Technical Degree: 14%

### Business Value

Identifies educational groups with higher turnover rates and helps improve retention strategies.

---

## 3️⃣ Attrition by Age Group

This chart categorizes attrition across different age ranges.

### Findings

| Age Group | Attrition |
| --------- | --------- |
| 26-35     | 116       |
| 18-25     | 44        |
| 36-45     | 43        |
| 46-55     | 26        |
| 55+       | 8         |

### Business Insight

Employees aged 26–35 experience the highest attrition rate, indicating potential career growth and job satisfaction concerns.

---

## 4️⃣ Attrition by Salary

This visual evaluates employee turnover across salary ranges.

### Findings

| Salary Range | Attrition |
| ------------ | --------- |
| Up to 5K     | 163       |
| 5K–10K       | 49        |
| 10K–15K      | 20        |
| 15K+         | 5         |

### Business Insight

Most attrition occurs among lower salary employees, suggesting compensation may be a contributing factor.

---

## 5️⃣ Attrition by Years at Company

This line chart analyzes attrition based on employee tenure.

### Findings

* Highest attrition occurs within the first few years of employment.
* Attrition decreases as tenure increases.

### Business Value

Helps HR identify onboarding and early-career retention challenges.

---

## 6️⃣ Attrition by Job Role

This visual highlights the job roles experiencing the highest employee turnover.

### Top Roles

| Job Role              | Attrition |
| --------------------- | --------- |
| Laboratory Technician | 62        |
| Sales Executive       | 57        |
| Research Scientist    | 47        |
| Sales Representative  | 33        |

### Business Insight

These roles require focused retention programs and workforce planning.

---

## 7️⃣ Job Role Attrition Matrix

The matrix provides a detailed breakdown of attrition across job roles and categories.

### Business Value

* Enables role-level workforce analysis
* Supports hiring strategies
* Helps identify departments with retention challenges

---

# 🎛️ Interactive Features

The dashboard includes department-level filters:

### Human Resources

Analyze HR department workforce trends.

### Research & Development

Monitor attrition and employee performance within R&D.

### Sales

Evaluate workforce metrics for the sales team.

These filters allow management to perform department-specific analysis.

---

# 🧮 Sample DAX Measures

### Total Employees

```DAX
Total Employees =
COUNT(Employee[EmployeeID])
```

### Attrition Count

```DAX
Attrition Count =
CALCULATE(
COUNT(Employee[EmployeeID]),
Employee[Attrition] = "Yes"
)
```

### Attrition Rate

```DAX
Attrition Rate =
DIVIDE(
[Attrition Count],
[Total Employees]
)
```

### Average Salary

```DAX
Average Salary =
AVERAGE(Employee[MonthlyIncome])
```

---

# 💡 Key Business Insights

The dashboard helps management:

* Monitor workforce trends
* Understand employee turnover patterns
* Improve retention strategies
* Analyze department-level attrition
* Identify high-risk employee segments
* Optimize workforce planning

---

# 📈 Business Impact

The HR Analytics Dashboard provides:

* Better workforce visibility
* Faster HR reporting
* Improved employee retention planning
* Data-driven HR decision-making
* Reduced employee turnover risks
* Enhanced talent management strategies

---

# 📚 Key Learnings

Through this project, I enhanced my skills in:

* Power BI Dashboard Development
* Data Modeling
* Power Query Transformations
* DAX Calculations
* HR Analytics
* Workforce Analysis
* Business Intelligence Reporting

---

# 📷 Dashboard Preview

<img width="2767" height="1600" alt="HR Analytics Dashboard" src="https://github.com/user-attachments/assets/469f96fa-9578-4b6f-a4a1-43f4a23a2237" />


---

# 👨‍💻 Author

**Satyajit Chavan**

Data Analyst | Power BI Developer

### Skills

* Power BI
* SQL
* Excel
* Python
* DAX
* Power Query

🔗 GitHub: https://github.com/Satya2975

🔗 LinkedIn: https://www.linkedin.com/in/satyajitchavan/

---

⭐ If you found this project useful, feel free to star the repository.
