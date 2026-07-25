# Database Concepts in the Project

## Overview

This project uses structured job posting data to analyze Saudi data-related internship and job market requirements.

The dataset workflow is connected to several database concepts, including data organization, storage, cleaning, transformation, and analysis.

---

# 1. Dataset as Structured Data

The project dataset is stored in CSV format, which represents structured tabular data.

Each row represents one job posting record, while each column represents a specific attribute.

Examples of columns:

- job_title
- company
- city
- role_category
- experience_category
- skills
- tools

---

# 2. Tables, Rows, and Columns

The dataset follows a table-based structure similar to relational databases.

- Rows represent individual job postings.
- Columns represent attributes of each posting.
- Each record contains information about a specific opportunity.

---

# 3. Data Cleaning and Transformation

Before analysis, the dataset went through data preparation steps.

These included:

- Removing duplicate records.
- Checking missing values.
- Standardizing city names.
- Creating new analysis columns.

Examples of created columns:

- city_cleaned
- experience_category
- role_category

These transformations improve data consistency and analysis quality.

---

# 4. Relational Database Concepts

The project analysis can be represented using relational database concepts.

Possible tables:

## Jobs Table

Contains general information about job postings.

Examples:

- job_id
- job_title
- company
- city

## Skills and Tools Information

Contains technical requirements extracted from job descriptions.

Examples:

- skills
- tools

## Classification Information

Contains categorized analysis fields.

Examples:

- role_category
- experience_category

---

# 5. Data Analysis Workload

The project performs analytical operations similar to database queries.

Examples:

- Counting job opportunities by city.
- Finding the most requested tools.
- Comparing role categories.
- Analyzing experience requirements.

These operations are similar to aggregation and filtering operations in SQL.

---

# 6. Power BI Connection

The prepared dataset was transformed into a Power BI-ready CSV file.

Power BI uses structured data to create:

- Interactive dashboards.
- Visual analysis.
- Business insights.

The final dataset supports analysis of:

- Skills.
- Tools.
- Roles.
- Cities.
- Experience levels.

---

# Conclusion

This project demonstrates how structured data can be collected, cleaned, transformed, and analyzed using data engineering and database concepts.

The workflow connects data preparation, database organization, analytics, and visualization into a complete data analysis pipeline.
