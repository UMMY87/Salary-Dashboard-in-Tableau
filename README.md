# Salary Dashboard

This repository contains a Tableau joining and dashboard visualizing employee salary data, offering insights into various salary metrics. The dashboard provides a comprehensive view of employee salaries categorized by person, gender, job title, and job description.

## Dashboard Overview

### Visualizations

1. **Salary by Person**: A bar chart displaying salaries for individual employees.
2. **Salary by Gender and Job Title**: A stacked bar chart showing the distribution of salaries by gender and job title.
3. **Salary by Persons**: A pie chart breaking down the total salary by individual employees.
4. **Salary by Job Description**: A bar chart comparing salaries across different job descriptions.
5. **Additional Visualizations**: Various charts and graphs providing deeper insights into the salary data.

### Data Sources

The data for this dashboard is sourced from three Excel sheets:
- **Demographics**: Employee details like ID, name, age, and gender.
- **JobTitle**: Information about employee job titles.
- **Salary**: Salary details of employees.

### Data Join

The data is combined using joins in Tableau, where:
- **Demographics** is joined with **JobTitle** on `EmployeeID`.
- **Demographics** is joined with **Salary** on `EmployeeID`.

### Interactive Features

- Filters to view data based on specific job titles or employee names.
- Tooltips providing additional details on hover.

## How to Use

1. **Open in Tableau**:
   - Download and install Tableau Desktop.
   - Open the `.twbx` file in Tableau to view the dashboard.

2. **Interacting with the Dashboard**:
   - Use the filters to explore different aspects of the salary data.
   - Hover over the charts for detailed insights.

## Getting Started

To replicate or customize this dashboard:

1. **Prepare Your Data**: Ensure your data is formatted similarly to the fields mentioned above.
2. **Build Visualizations**: Use Tableau to create similar visualizations by dragging and dropping fields into the workspace.
3. **Customize and Enhance**: Add filters, tooltips, and additional visual elements to make the dashboard more interactive and informative.


---

![Screenshot 2024-07-04 190346](https://github.com/UMMY87/Salary-Dashboard-in-Tableau/assets/117314436/1c076f66-0616-4a54-828a-9ef7e4038fea)

This dashboard was created using Tableau to provide an interactive and insightful visualization of employee salary data.
