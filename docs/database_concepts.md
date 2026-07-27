# Database Concepts in the Project

## Overview

This project uses structured job posting data to analyze Saudi data-related job market requirements.

The dataset workflow is connected to database concepts including data organization, storage, cleaning, transformation, and analytical processing.

---

## 1. Dataset as Structured Data

The project dataset is stored in CSV format, which represents structured tabular data.

Each row represents one job posting record, while each column represents a specific attribute related to that opportunity.

Examples of columns:

- `job_id`
- `job_title`
- `company`
- `city`
- `role_category`
- `experience_category`
- `skills`
- `tools`

---

## 2. Tables, Rows, and Columns

The dataset follows a table-based structure similar to relational databases.

- Rows represent individual job posting records.
- Columns represent attributes of each record.
- Each record contains information about a specific data-related opportunity.

This structure allows data to be stored, filtered, transformed, and analyzed efficiently.

---

## 3. Data Cleaning and Transformation

Before analysis, the dataset went through several data preparation steps.

These included:

- Checking missing values.
- Checking duplicate records.
- Standardizing city names.
- Creating new analysis-ready columns.
- Transforming raw job information into structured categories.

Examples of created columns:

- `city_cleaned`
- `experience_category`
- `role_category`

These transformations improve data consistency and support more reliable analysis.

---

## 4. Relational Database Concepts

The project can be represented using relational database concepts.

Possible table design:

### Jobs Table

Contains general information about job postings.

Examples:

- `job_id`
- `job_title`
- `company`
- `city`

### Skills and Tools Information

Contains technical requirements extracted from job postings.

Examples:

- `skills`
- `tools`

### Classification Information

Contains categorized analysis fields.

Examples:

- `role_category`
- `experience_category`

This separation represents how data can be organized into related tables in database systems.

---

## 5. Data Analysis Workload

The project performs analytical operations similar to database queries.

Examples:

- Counting job opportunities by city.
- Finding the most requested skills and tools.
- Comparing different role categories.
- Analyzing experience requirements.

These operations are similar to SQL aggregation, filtering, and grouping operations.

---

## 6. Power BI Connection

The cleaned dataset was prepared as a Power BI-ready CSV file:

`saudi_data_jobs_powerbi.csv`

Power BI uses this structured data to create visual analysis and dashboards.

The dashboard analyzes:

- Skills.
- Tools.
- Roles.
- Cities.
- Experience levels.

---

## Conclusion

This project demonstrates how structured data can be collected, cleaned, transformed, and analyzed using concepts related to databases and analytics.

The workflow connects data preparation, structured data organization, analytical processing, and visualization into a complete data analysis pipeline.
