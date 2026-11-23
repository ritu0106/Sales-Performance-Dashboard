# HR Analytics Dashboard | Employee Attrition Analysis

## 1. Project Overview

The HR Analytics Dashboard is a data analytics project focused on understanding employee attrition and analysing workforce trends within an organisation.

Employee attrition is an important concern for organisations because frequent employee turnover can affect productivity, increase recruitment costs, and create challenges in workforce management.

The main purpose of this project is to analyse employee information and identify the factors that may influence employees to leave an organisation. The analysis explores different aspects of employee data, such as age, gender, department, job role, monthly income, job satisfaction, overtime, work experience, and work-life balance.

Microsoft Excel is used for Pivot Table analysis, while Microsoft Power BI is used for data visualisation and dashboard development.

This project demonstrates how raw HR data can be transformed into meaningful insights that support better workforce planning and employee retention decisions.

## 2. Project Objectives

The major objectives of this project are:

1. **Analyse Employee Attrition:** Understand the number of employees who have left the organisation and the overall attrition rate.

2. **Identify Attrition Factors:** Explore how age, salary, job role, department, overtime, and job satisfaction relate to employee attrition.

3. **Understand Workforce Trends:** Analyse employee demographics, experience, income, and other workforce characteristics.

4. **Evaluate Employee Retention:** Identify employee groups with comparatively higher attrition rates.

5. **Create an Interactive Dashboard:** Present important HR metrics and findings through clear visualisations in Power BI.

6. **Support Business Decisions:** Provide data-driven recommendations to help improve employee satisfaction and retention.

## 3. Tools and Technologies Used

### Microsoft Excel
- Data exploration and analysis.
- Pivot Table creation.
- Employee categorisation and comparison.
- Summary of attrition by different categories.

### Microsoft Power BI
- Data visualisation.
- Dashboard development.
- KPI presentation.
- Interactive filtering and analysis.
- Visual comparison of employee attrition.

### CSV Dataset
- Used as the primary source of employee information.
- Contains employee demographics, job details, income, satisfaction, and attrition status.

## 4. Dataset Description

The project uses an HR Analytics dataset containing **1,480 employee records and 38 columns**.

Each row represents an employee, while the columns contain information about employee demographics, professional details, compensation, satisfaction, and employment history.

### Important Dataset Columns

| Column | Description |
|---|---|
| EmpID | Unique employee identification |
| Age | Employee's age |
| AgeGroup | Employee age category |
| Attrition | Whether the employee left the organisation |
| BusinessTravel | Employee's business travel frequency |
| Department | Department in which the employee works |
| DistanceFromHome | Distance between home and workplace |
| Education | Employee education level |
| EducationField | Employee's educational background |
| Gender | Employee gender |
| JobRole | Employee's job position |
| JobLevel | Employee's job level |
| JobSatisfaction | Employee satisfaction rating |
| MaritalStatus | Employee marital status |
| MonthlyIncome | Employee's monthly salary |
| SalarySlab | Monthly income category |
| OverTime | Whether the employee works overtime |
| TotalWorkingYears | Total professional experience |
| YearsAtCompany | Number of years spent at the organisation |
| WorkLifeBalance | Employee work-life balance rating |

Other columns provide additional information about performance, training, relationships, and employee experience.

## 5. Project Workflow

The project follows a systematic data analytics process.

### Step 1: Data Collection

The HR Analytics dataset was collected in CSV format. It contains employee-related information required to study workforce patterns and attrition.

### Step 2: Data Understanding

The dataset was explored to understand its structure, column names, data types, and important variables.

The main focus was on identifying the columns useful for analysing employee attrition.

### Step 3: Data Quality Checking

The dataset was checked for missing values and duplicate records.

The initial dataset contains 57 missing cells and 7 duplicate rows. These should be reviewed before finalising the analysis to maintain data quality.

### Step 4: Excel Analysis

Microsoft Excel was used to create Pivot Tables and summarise employee information.

The analysis includes:
- Employee attrition by age.
- Employee count by attrition status.
- Comparison of employees who stayed and employees who left.
- Employee distribution across different categories.

### Step 5: Power BI Dashboard Development

The dataset was used to develop an HR Analytics dashboard in Power BI.

The dashboard project file is included in the repository as `HR_ANALYTICS.pbix`.

### Step 6: Insights Generation

The results were analysed to understand the employee groups and workplace factors associated with higher attrition.

### Step 7: Business Recommendations

Based on the analysis, recommendations were identified to help organisations improve employee engagement and retention.

## 6. Key Performance Indicators (KPIs)

The following KPIs are important for understanding the organisation's workforce.

| KPI | Value |
|---|---:|
| Total Employees | 1,480 |
| Attrition Count | 238 |
| Active Employees | 1,242 |
| Attrition Rate | 16.08% |
| Average Age | 36.9 years |

### KPI Explanation

**Total Employees:** Represents the total number of employee records in the dataset.

**Attrition Count:** Represents the number of employees who left the organisation.

**Active Employees:** Represents employees who did not leave the organisation.

**Attrition Rate:** Measures the percentage of employees who left the organisation.

Formula:

`Attrition Rate = (Attrition Count / Total Employees) × 100`

Calculation:

`(238 / 1480) × 100 = 16.08%`

**Average Age:** Represents the average age of employees in the dataset.

## 7. Data Analysis and Key Findings

The dataset was analysed using employee demographics, department, job role, salary, overtime, and other employment-related attributes.

### 7.1 Overall Employee Attrition

Out of 1,480 employees:

- 238 employees left the organisation.
- 1,242 employees remained.
- The overall attrition rate is 16.08%.

This indicates that approximately 16 out of every 100 employees in the dataset left the organisation.

### 7.2 Attrition by Age Group

Age plays an important role in understanding workforce patterns.

| Age Group | Employees | Employees Left | Attrition Rate |
|---|---:|---:|---:|
| 18–25 | 123 | 44 | 35.77% |
| 26–35 | 611 | 116 | 18.99% |
| 36–45 | 471 | 43 | 9.13% |
| 46–55 | 228 | 27 | 11.84% |
| 55+ | 47 | 8 | 17.02% |

**Key Finding:** Employees aged 18–25 have the highest attrition rate at 35.77%. This suggests that younger employees may require better career development opportunities, guidance, and engagement initiatives.

### 7.3 Attrition by Department

| Department | Employees | Employees Left | Attrition Rate |
|---|---:|---:|---:|
| Human Resources | 63 | 12 | 19.05% |
| Research & Development | 967 | 133 | 13.75% |
| Sales | 450 | 93 | 20.67% |

**Key Finding:** The Sales department has the highest attrition rate at 20.67%, followed by Human Resources at 19.05%.

The organisation should investigate workload, employee satisfaction, targets, and working conditions in these departments.

### 7.4 Attrition by Job Role

| Job Role | Employees Left | Attrition Rate |
|---|---:|---:|
| Sales Representative | 33 | 39.29% |
| Laboratory Technician | 62 | 23.75% |
| Human Resources | 12 | 23.08% |
| Sales Executive | 58 | 17.63% |
| Research Scientist | 47 | 16.04% |
| Healthcare Representative | 9 | 6.82% |
| Manufacturing Director | 10 | 6.80% |
| Manager | 5 | 4.90% |
| Research Director | 2 | 2.50% |

**Key Finding:** Sales Representatives have the highest attrition rate at 39.29%. Laboratory Technicians also show a comparatively high attrition rate.

### 7.5 Attrition by Overtime

| Overtime | Employees | Employees Left | Attrition Rate |
|---|---:|---:|---:|
| Yes | 418 | 128 | 30.62% |
| No | 1,062 | 110 | 10.36% |

**Key Finding:** Employees who work overtime have a significantly higher attrition rate than employees who do not work overtime.

This indicates that workload management and work-life balance should be considered when developing employee retention strategies.

### 7.6 Attrition by Marital Status

| Marital Status | Employees | Employees Left | Attrition Rate |
|---|---:|---:|---:|
| Single | 473 | 120 | 25.37% |
| Married | 679 | 84 | 12.37% |
| Divorced | 328 | 34 | 10.37% |

**Key Finding:** Single employees have the highest attrition rate among the three marital-status categories.

### 7.7 Attrition by Job Satisfaction

The dataset contains job satisfaction ratings from 1 to 4.

| Job Satisfaction Rating | Employees | Employees Left | Attrition Rate |
|---|---:|---:|---:|
| 1 | 293 | 67 | 22.87% |
| 2 | 282 | 46 | 16.31% |
| 3 | 444 | 73 | 16.44% |
| 4 | 461 | 52 | 11.28% |

**Key Finding:** Employees with the lowest job satisfaction rating have the highest attrition rate. This highlights the importance of improving employee experience and workplace satisfaction.

### 7.8 Attrition by Salary Slab

| Salary Slab | Employees | Employees Left | Attrition Rate |
|---|---:|---:|---:|
| Upto 5k | 753 | 163 | 21.65% |
| 5k–10k | 444 | 49 | 11.04% |
| 10k–15k | 150 | 21 | 14.00% |
| 15k+ | 133 | 5 | 3.76% |

**Key Finding:** Employees in the lowest salary category have the highest attrition rate, while the 15k+ category has the lowest.

## 8. Overall Business Insights

The analysis highlights several important observations:

1. The overall employee attrition rate is 16.08%.
2. Employees aged 18–25 have the highest attrition rate among age groups.
3. The Sales department has the highest attrition rate among departments.
4. Sales Representatives show the highest attrition rate among job roles.
5. Employees working overtime have a considerably higher attrition rate.
6. Employees with low job satisfaction show higher attrition.
7. Employees in the lowest salary slab have comparatively higher attrition.
8. Employees who left have a lower average tenure at the organisation than employees who stayed.

These findings help identify areas that may require further investigation by HR management.

## 9. Business Recommendations

Based on the findings, the following recommendations can help improve employee retention.

### 1. Improve Work-Life Balance
Review overtime requirements, manage workloads effectively, and encourage a healthy balance between professional and personal life.

### 2. Focus on Younger Employees
Introduce mentoring programmes, career development opportunities, and training programmes to support younger employees.

### 3. Improve Sales Department Retention
Review sales targets, incentives, workload, and employee support systems to understand the reasons behind higher attrition.

### 4. Enhance Employee Satisfaction
Conduct regular employee feedback surveys and take action to address workplace concerns.

### 5. Review Compensation
Evaluate salary structures and employee benefits to maintain competitive compensation.

### 6. Develop Employee Engagement Programmes
Introduce recognition programmes, learning opportunities, and regular communication between employees and management.

## 10. Project Files and Repository Structure

The repository contains the following project files:

```text
HR-Analytics-Dashboard/
│
├── HR_Analytics.csv
│
├── Piovt Table.xlsx
│
├── HR_ANALYTICS.pbix
│
├── images/
│   └── hr-analytics-dashboard.png
│
└── README.md
```

### File Description

- **HR_Analytics.csv:** Original employee dataset used for analysis.
- **Piovt Table.xlsx:** Excel workbook containing Pivot Table analysis and employee summaries.
- **HR_ANALYTICS.pbix:** Power BI project file containing the dashboard.
- **images/:** Folder for storing dashboard screenshots.
- **README.md:** Documentation explaining the project.

## 11. Dashboard Preview

The Power BI dashboard provides a visual overview of employee attrition and workforce-related information.

It is intended to help users understand important HR metrics and compare employee attrition across different categories.

To display the dashboard preview on GitHub, upload your actual Power BI dashboard screenshot into the `images` folder and use the following Markdown:

`![HR Analytics Dashboard](images/hr-analytics-dashboard.png)`

## 12. Learning Outcomes

Through this project, I gained practical knowledge and experience in:

- Understanding and analysing HR datasets.
- Working with CSV files and Excel workbooks.
- Exploring employee demographics and workforce information.
- Creating and analysing Pivot Tables in Excel.
- Understanding employee attrition and retention metrics.
- Developing interactive dashboards using Power BI.
- Presenting data through meaningful charts and visualisations.
- Identifying trends and patterns from employee data.
- Converting analytical findings into business recommendations.
- Improving data interpretation and problem-solving skills.

## 13. Conclusion

The HR Analytics Dashboard project demonstrates how data analytics can be used to understand employee attrition and workforce trends.

By analysing employee demographics, job roles, departments, salary slabs, job satisfaction, overtime, and work experience, the project identifies employee groups with comparatively higher attrition rates.

The findings highlight the importance of employee satisfaction, workload management, career development, and compensation in employee retention.

Microsoft Excel and Power BI make it easier to organise, analyse, and visualise HR data, helping organisations make informed decisions and develop better workforce management strategies.

This project has also strengthened my practical skills in Excel analysis, Pivot Tables, Power BI dashboards, data visualisation, and business insight generation.

---

**Project Category:** Data Analytics | HR Analytics | Business Intelligence

**Tools Used:** Microsoft Excel | Microsoft Power BI | CSV
