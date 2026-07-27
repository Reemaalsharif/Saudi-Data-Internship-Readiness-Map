# Initial Findings Report

## Project Overview

This project analyzes Saudi data-related job and internship postings to understand the tools, skills, role categories, cities, and experience levels commonly required in the Saudi data job market.

The goal of this project is to help Computer Science students and early-career learners understand the skills and knowledge areas they should focus on when preparing for data-related roles such as Data Analyst, Data Scientist, BI Analyst, AI/Data Analyst, and other analytics-related positions.

---

## Dataset Summary

The initial analysis was conducted using a dataset containing **25 Saudi data-related job and internship postings**.

The dataset included roles from different categories, such as:

- Data Analysis.
- Data Science.
- Business Intelligence.
- AI-related roles.
- Governance and data management.
- Internship and early-career opportunities.
- Other analytics-related roles.

During later project stages, the dataset was expanded to **45 job postings** to improve the reliability of market insights.

The cleaned dataset included analysis-ready columns such as:

- `city_cleaned`
- `experience_category`
- `role_category`

These cleaned columns improved consistency and made comparisons between different job categories easier.

---

## Tools Findings

The most frequently mentioned tools in the initial dataset included:

- SQL.
- Python.
- Excel.
- Power BI.
- Tableau.

These findings showed that Saudi data-related roles require a combination of programming, analysis, reporting, and visualization tools.

SQL and Python appeared as important technical foundations, while Excel, Power BI, and Tableau appeared frequently in roles related to reporting, dashboards, and business intelligence.

---

## Skills Findings

The most repeated skills in the initial analysis included:

- Data analysis.
- Reporting.
- Dashboard development.
- Data validation.
- Problem solving.
- Data visualization.
- Communication.
- Business understanding.

These findings suggest that data-related roles are not only focused on programming. They also require the ability to understand business problems, communicate insights, and create effective reports and dashboards.

---

## City Findings

Riyadh appeared as one of the most common cities in the initial dataset, followed by Jeddah and other locations.

Some postings listed the location only as Saudi Arabia, so these values were cleaned as **Not specified**.

This helped avoid treating the country name as a specific city and improved the accuracy of geographic analysis.

---

## Role Category Findings

The initial role category analysis showed that data-related careers include multiple pathways beyond only Data Analyst or Data Scientist roles.

The dataset included categories such as:

- Data Analysis.
- Data Science.
- Business Intelligence.
- AI-related roles.
- Governance.
- Internship opportunities.
- Other analytics-related roles.

Using `role_category` instead of the raw `role_type` column improved the analysis by grouping similar job titles into broader and more meaningful career categories.

---

## Experience Level Findings

The initial experience analysis showed different opportunity levels across the dataset, including:

- Internship opportunities.
- Entry-level roles.
- Mid-level positions.
- Senior roles.

The findings supported the project goal of helping students and early-career learners understand employer expectations.

The analysis showed that early-career data roles commonly require a combination of:

- SQL.
- Python.
- Excel.
- Dashboards.
- Reporting.
- Data analysis skills.

---

## Initial Readiness Takeaway

Based on the initial analysis, a Computer Science student preparing for Saudi data-related roles should focus on:

- SQL for querying and working with databases.
- Python for data analysis and basic automation.
- Excel for analysis, reporting, and business tasks.
- Power BI or Tableau for dashboards and visualization.
- Data analysis and reporting skills.
- Communication and problem-solving skills.
- Understanding how data supports business decisions.

The early findings showed that beginner-friendly data roles require more than programming skills. They also require practical analysis, reporting, visualization, and communication abilities.

---

## Next Steps

The next project stages focused on:

- Improving dataset quality and consistency.
- Expanding the dataset with additional job postings.
- Improving visualizations and insights.
- Performing deeper skills and tools analysis.
- Developing a career readiness roadmap based on market requirements.
