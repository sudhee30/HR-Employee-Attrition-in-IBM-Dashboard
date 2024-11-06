

# HR Employee Attrition Dataset

This repository contains the **HR Employee Attrition** dataset, which includes various features related to employee characteristics, job performance, and attrition status. The dataset is intended to help analyze employee retention and understand the factors influencing employee turnover.

## Dataset Overview

The **HR_Employee Attrition** dataset contains the following columns:

| **Column Name**            | **Description**                                                                 |
|----------------------------|---------------------------------------------------------------------------------|
| `EmpID`                     | Employee ID                                                                      |
| `Age`                       | Age of the employee                                                              |
| `AgeGroup`                  | Categorized age group (e.g., 20-30, 30-40, etc.)                                |
| `Attrition`                 | Whether the employee left the company (Yes/No)                                   |
| `BusinessTravel`            | Frequency of business travel (e.g., Non-Travel, Travel_Rarely, etc.)           |
| `DailyRate`                 | Daily rate paid to the employee                                                   |
| `Department`                | Department where the employee works                                              |
| `DistanceFromHome`          | Distance from the employee’s home to the workplace                               |
| `Education`                 | Education level (e.g., High School, Bachelors, Masters, etc.)                    |
| `EducationField`            | Field of education (e.g., Life Sciences, Medical, Technical, etc.)               |
| `EmployeeCount`             | Number of employees in the organization (usually 1)                              |
| `EmployeeNumber`            | Unique identification number for each employee                                   |
| `EnvironmentSatisfaction`   | Employee satisfaction with work environment (on a scale of 1-4)                  |
| `Gender`                    | Gender of the employee (Male/Female)                                             |
| `HourlyRate`                | Hourly rate paid to the employee                                                  |
| `JobInvolvement`            | Degree of involvement in the job (on a scale of 1-4)                             |
| `JobLevel`                  | Job level (e.g., Entry, Mid, Senior)                                             |
| `JobRole`                   | Role or title of the employee (e.g., Sales Executive, Software Engineer, etc.)   |
| `JobSatisfaction`           | Job satisfaction level (on a scale of 1-4)                                       |
| `MaritalStatus`             | Marital status (e.g., Single, Married, Divorced)                                 |
| `MonthlyIncome`             | Monthly income of the employee                                                   |
| `SalarySlab`                | Salary classification (e.g., Low, Medium, High)                                  |
| `MonthlyRate`               | Monthly rate paid to the employee                                                |
| `NumCompaniesWorked`        | Number of companies the employee has worked for                                 |
| `Over18`                    | Whether the employee is over 18 years old (usually "Y")                          |
| `OverTime`                  | Whether the employee works overtime (Yes/No)                                      |
| `PercentSalaryHike`         | Percentage increase in salary from the last review                               |
| `PerformanceRating`         | Performance rating of the employee (on a scale of 1-4)                           |
| `RelationshipSatisfaction`  | Satisfaction with work relationships (on a scale of 1-4)                        |
| `StandardHours`             | Standard working hours (usually 80)                                              |
| `StockOptionLevel`          | Level of stock options provided to the employee                                  |
| `TotalWorkingYears`         | Total number of years the employee has worked in their career                    |
| `TrainingTimesLastYear`     | Number of training sessions attended by the employee last year                   |
| `WorkLifeBalance`           | Work-life balance satisfaction (on a scale of 1-4)                               |
| `YearsAtCompany`            | Number of years the employee has been with the company                           |
| `YearsInCurrentRole`        | Number of years the employee has been in their current role                     |
| `YearsSinceLastPromotion`   | Years since the last promotion                                                   |
| `YearsWithCurrManager`      | Number of years the employee has worked with their current manager               |

## Purpose

This dataset can be used for various analyses, such as:

- Predicting employee attrition
- Identifying key factors influencing employee turnover
- Analyzing salary distribution across departments and job roles
- Analyzing employee satisfaction and performance metrics
- Building models to predict employee retention or attrition

## Getting Started

### Prerequisites

- **Power BI** or any data visualization tool
- **Python** for data analysis (if needed)
- **Libraries**: Pandas, NumPy (for analysis), and Matplotlib/Seaborn (for visualization)

### Loading the Dataset

To use the dataset in Power BI:

1. Open Power BI Desktop.
2. Go to **Home** → **Get Data** → **Excel** or any other source based on your dataset format.
3. Load the file and start visualizing the data using various charts, graphs, and tables.

### Example Insights

1. **Attrition by Age Group**: Plot the attrition rate based on different age groups to see if age plays a role in employee turnover.
2. **Satisfaction vs. Attrition**: Create a scatter plot of satisfaction ratings against attrition status to identify trends.
3. **Salary vs. Job Level**: Analyze the relationship between salary and job level to understand compensation disparities.
4. **Years at Company vs. Attrition**: Visualize how the number of years at the company correlates with attrition.
5. **Employee Count by Department**: Show how many employees are in each department.

