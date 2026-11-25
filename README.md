# HR Analytics Dashboard (Excel)

An interactive Excel dashboard built from a messy HR dataset of 290 employee records. It covers data cleaning, PivotTables, PivotCharts, KPI cards and slicers.
![Dashboard](dashboard.png)

## Objective
Turn raw HR data into a one-page dashboard that shows workforce size, pay, hiring trends and diversity at a glance.
## Dataset
Practice dataset (not real company data), 290 records. Personal fields (name, phone, email) are removed.

## Tools Used
- Microsoft Excel
- PivotTables and PivotCharts
- Slicers
- Formulas (`GETPIVOTDATA`, `IFERROR`, `IF`, `YEAR`)

## Steps
1. **Data cleaning:** standardised gender, city and department values, fixed spelling variants (e.g. Tiruchirappalli to Trichy), and handled blank ages, salaries and join dates.
2. **Helper columns:** created Age Group and Join Year.
3. **PivotTables:** built pivots for city, gender, join year, age group and department.
4. **KPI cards:** linked to a pivot so they respond to slicers.
5. **Charts:** employees by city, gender split, hiring trend, salary by age group, employees by department, average salary by department.
6. **Slicers:** Gender, City, Department and Join Year, connected to every pivot.

## KPIs
| KPI | Value |
|---|---|
| Total Employees | 290 |
| Average Salary | ₹54,601 |
| Total Salary Cost | ₹157.3 Lakh |
| Average Age | 39.3 |
| Female % | 42.4% |

## Key Insights
- Trichy has the most employees (47), followed by Bangalore and Coimbatore (38 each).
- Hiring peaked in 2016 (38) and 2022 (37), and was lowest in 2024 (17).
- IT has the highest average salary (₹59,930) and Sales the lowest (₹52,122).
- The workforce is 58% male and 42% female.
- Operations is the largest department (61 employees).

## Data Notes
- Blank values (22 ages, 2 salaries, 8 join dates) were left blank, not filled, and are excluded from averages.
- 16 employees have an unknown city.

## Files
- `HR_Dashboard.xlsx` is the Excel dashboard
- `dashboard.png` is the dashboard screenshot

## Author
**Miruthula**
Final-year ECE student | Aspiring Data Analyst
Skills: Python, SQL, MySQL, Excel, Power BI
GitHub: [miruthula53](https://github.com/miruthula53)
