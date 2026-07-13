# Initial Findings Report

## Project Overview

This project analyzes Saudi data-related job and internship postings to understand the tools, skills, role categories, cities, and experience levels commonly required in the Saudi data job market.

The goal of this project is to help Computer Science students and early-career learners understand what they should focus on when preparing for data-related roles such as Data Analyst, Data Scientist, BI Analyst, AI/Data Analyst, and other analytics-related positions.

## Dataset Summary

The current dataset includes 25 Saudi data-related job and internship postings.

The dataset includes roles from different categories, such as:
- Data Analysis
- Data Science
- Business Intelligence
- AI-related roles
- Governance and data management
- Internship and early-career opportunities
- Other analytics-related roles

The cleaned dataset includes analysis-ready columns such as:
- `city_cleaned`
- `experience_category`
- `role_category`

These cleaned columns helped make the analysis clearer and easier to compare.

## Tools Findings

The most frequently mentioned tools in the dataset included:

- SQL
- Python
- Excel
- Power BI
- Tableau

This shows that Saudi data-related roles often require a mix of programming, analysis, reporting, and dashboarding tools.

SQL and Python appeared as important technical tools, while Excel, Power BI, and Tableau appeared frequently in roles related to reporting, dashboards, and business intelligence.

## Skills Findings

The most repeated skills included:

- Data analysis
- Reporting
- Dashboarding
- Data validation
- Problem solving
- Data visualization
- Communication
- Business understanding

These findings suggest that data-related roles are not only about coding. They also require the ability to understand business problems, communicate insights, and create clear reports or dashboards.

## City Findings

Riyadh appeared as the most common city in the dataset, followed by Jeddah and other locations.

Some postings listed the location only as Saudi Arabia, so these were cleaned as `Not specified`.

This helped avoid treating the country name as a specific city and made the city analysis more accurate.

## Role Category Findings

The role category analysis showed that data-related jobs are broader than only Data Analyst or Data Scientist roles.

The dataset included multiple paths such as:

- Data Analysis
- Data Science
- Business Intelligence
- AI
- Governance
- Internship
- Other analytics-related roles

Using `role_category` instead of the raw `role_type` column made the analysis cleaner because similar job titles were grouped into broader and easier-to-understand categories.

## Experience Level Findings

The experience category analysis showed that many roles in the dataset are focused on Entry Level and Mid-Level opportunities.

This supports the project goal because the dataset is useful for students and early-career learners who want to understand what Saudi data roles require.

The analysis also showed that early-career roles often require a combination of SQL, Python, Excel, dashboards, reporting, and analysis skills.

## Initial Readiness Takeaway

Based on the initial analysis, a Computer Science student preparing for Saudi data-related roles should focus on:

1. SQL for querying and working with databases.
2. Python for data analysis and basic automation.
3. Excel for analysis, reporting, and business tasks.
4. Power BI or Tableau for dashboards and visualization.
5. Data analysis and reporting skills.
6. Communication and problem-solving skills.
7. Understanding how data supports business decisions.

The early findings show that beginner-friendly data roles are not only about programming. They also require practical reporting, dashboarding, analysis, and communication skills.

## Next Steps

The next steps of the project are:

- Review the quality of the dataset and charts.
- Improve the wording of insights.
- Finish or continue Kaggle Data Visualization practice.
- Prepare a LinkedIn post about the most common tools in Saudi data-related roles.
- Later, expand the dataset with more job postings to make the findings more reliable.
