# Project Notes

## Day 1 Progress

- Created the project repository
- Added the initial README file
- Created the project notes file
- Created the dataset CSV structure
- Collected and added the first 10 Saudi data-related job postings
- Included different role types: Data Analyst, Data Scientist, BI / Power BI Developer, Data / AI Analyst, Fraud Analytics, Operations Analytics, Business / Pricing Analytics, and Digital Marketing Analytics
- Completed the first Kaggle Pandas exercise: Creating, Reading and Writing

## Day 1 Dataset Summary

Collected 10 job postings from LinkedIn covering multiple data-related roles in Saudi Arabia.

Initial role types:
- Data Analyst
- Data Scientist
- BI / Power BI Developer
- Data / AI Analyst
- Fraud / Cybersecurity Analytics
- Performance / Operations Analytics
- Business / Pricing Analytics
- Digital Marketing Analytics

Initial tools observed:
- SQL
- Python
- Power BI
- Excel
- Tableau
- Looker Studio
- Machine Learning
- Generative AI
- DAX
- Power Query
- pandas
- NumPy
- GA4
- TensorFlow
- PyTorch

## Day 1 Notes

The first dataset sample shows that data-related roles in Saudi Arabia are not limited to the title "Data Analyst" or "Data Scientist". Several roles include analytics responsibilities under different titles, such as pricing analytics, operations performance, fraud protection, AI analysis, Power BI development, and digital marketing analytics.

This supports the project goal of analyzing data-related jobs broadly and identifying the skills most relevant for Computer Science students interested in Data Science and analytics careers.

## Day 1 Pandas Notes

### DataFrame
A table-like structure in Pandas.

### Series
A single column of data.

### CSV
A file format used to store tabular data.

### Column
A vertical field in a dataset.

### Index
The label or number used to identify rows.

### read_csv
Used to read a CSV file into a Pandas DataFrame.

### to_csv
Used to save a Pandas DataFrame as a CSV file.

## Day 1 Next Steps

- Continue learning Pandas basics
- Collect more Saudi data-related job postings
- Improve dataset quality and consistency
- Start identifying repeated skills and tools
- Prepare the first LinkedIn post about the project






## Day 2 Progress

- Collected and added 15 additional Saudi data-related job postings.
- Increased the dataset from 10 to 25 job postings.
- Reviewed the dataset for duplicate job postings.
- Removed duplicate entries for repeated roles from Infinite PL, MOZN, and DP World.
- Replaced duplicates with new non-duplicate roles from Riyad Bank, Master Works, and TAWAL.
- Finalized the first 25 job postings with no obvious duplicate job links or repeated job titles from the same company.
- Added more role diversity across AI, product analytics, research analytics, healthcare analytics, BI, operations performance, corporate performance, data governance, and internship/co-op opportunities.
- Continued focusing on Saudi data-related roles that can help identify the skills needed by Computer Science students interested in Data Science.

## Day 2 Dataset Summary

The dataset now includes 25 Saudi data-related job and internship postings.

Role types included so far:
- Data Analyst
- Data Scientist
- Data / AI Analyst
- BI / Power BI Developer
- BI / Business Intelligence
- Product Analytics
- Business / Pricing Analytics
- Market / Research Analytics
- Research / Quantitative Analytics
- Healthcare Analytics / AI
- Aviation Safety Analytics
- Fraud / Cybersecurity Analytics
- Digital Marketing Analytics
- Operations Performance Analytics
- Corporate Performance Analytics
- Data Management / Governance
- Data Governance / Data Stewardship
- AI / ML Engineering
- IT / Data-related Internship
- AI / Data-related Internship

## Day 2 Initial Observations

Several data-related roles in Saudi Arabia require a mix of technical, analytical, and communication skills.

Repeated technical tools and skills observed:
- SQL
- Python
- Power BI
- Excel
- Tableau
- Dashboards
- Reporting
- Data Quality
- Data Visualization
- Machine Learning
- Generative AI
- KPI Analysis
- Data Governance
- Business Intelligence

Repeated soft and business skills observed:
- Communication
- Stakeholder collaboration
- Problem solving
- Attention to detail
- Insight generation
- Reporting to management
- Translating data into business recommendations

## Day 2 Dataset Quality Notes

During collection, several roles were rejected because they did not match the current project focus.

Rejected role types included:
- Senior Data Engineer
- SQL / Oracle Database Engineer
- Data Analytics Manager
- Data & Business Intelligence Manager
- Data & AI Architect
- Reporting Specialist requiring 7+ years
- Software or application development roles not focused on analytics

The dataset was also reviewed for duplicates. Repeated entries were removed and replaced to improve dataset quality and role diversity.

## Day 2 Pandas Notes

### loc
Used to select data by labels.

### iloc
Used to select data by integer position.

### Column Selection
Used to select one column from a DataFrame.

### Row Selection
Used to select specific rows from a DataFrame.

### Assigning Values
Used to update or create values inside a DataFrame.

## Day 2 Next Steps

- Continue improving the dataset quality and consistency.
- Start identifying repeated skills and tools across the 25 collected postings.
- Prepare the first LinkedIn post about the project.
- Continue Kaggle Pandas practice.






## Day 3 Progress

- Created a Google Colab notebook named `01_data_exploration`.
- Loaded the Saudi data jobs dataset from the GitHub raw CSV link.
- Verified the dataset shape and confirmed it contains 25 job postings.
- Checked for duplicate rows.
- Checked for duplicate job links.
- Checked for duplicate job title and company combinations.
- Confirmed that the dataset has no obvious duplicate entries.
- Explored job postings by city.
- Explored role type diversity.
- Explored experience level distribution.
- Counted the most mentioned tools across the dataset.
- Created initial visualizations for tools, cities, role types, and experience levels.
- Wrote initial insights inside the notebook.

## Day 3 Initial Findings

The first exploratory analysis showed that SQL is the most frequently mentioned tool in the collected job postings, followed by Python, Power BI, Excel, and Tableau.

Riyadh appeared as the most common city in the sample, while some postings listed the location only as "Saudi Arabia", which means the city column needs cleaning later.

The role types are highly diverse, which supports the idea that data-related opportunities in Saudi Arabia are not limited to job titles such as "Data Analyst" or "Data Scientist".

The experience level column also needs simplification because the labels are inconsistent and include different formats such as entry level, internship/co-op, mid-level, and specific years of experience.

## Day 3 Next Steps

- Clean unclear city values such as "Saudi Arabia".
- Create a simplified experience category column.
- Group similar role types into broader categories.
- Continue analyzing repeated skills and responsibilities.
- Save the exploration notebook and connect it clearly to the GitHub project.

## Day 4 Progress

- Created a Google Colab notebook named `02_data_cleaning`.
- Loaded the Saudi data jobs dataset from the GitHub raw CSV link.
- Reviewed the dataset columns and confirmed the main columns used for cleaning:
  - `city`
  - `experience_level`
  - `job_title`
  - `role_type`
- Cleaned the city values by creating a new column named `city_cleaned`.
- Replaced unclear city values such as `Saudi Arabia` with `Not specified`.
- Created a simplified experience category column named `experience_category`.
- Grouped inconsistent experience labels into clearer categories:
  - Entry Level
  - Mid-Level
  - Internship
- Created a simplified role category column named `role_category`.
- Grouped job titles into broader role categories such as Data Analysis, Data Science, BI, AI, Governance, Internship, and Other.
- Checked the cleaned columns using value counts.
- Exported the cleaned dataset as `saudi_data_jobs_cleaned.csv`.
- Added the cleaned dataset to the `data` folder.
- Added the data cleaning notebook to the `notebooks` folder.

## Day 4 Cleaning Summary

The raw dataset was cleaned and prepared for deeper analysis.

Main cleaning steps:
- Standardized unclear city values.
- Simplified experience levels into fewer categories.
- Grouped similar job titles into broader role categories.
- Kept the original dataset unchanged and created a separate cleaned dataset for analysis.

The cleaned dataset now includes the original job posting information plus new analysis-ready columns:
- `city_cleaned`
- `experience_category`
- `role_category`

## Day 4 Initial Findings

Riyadh appeared as the most common city in the dataset, followed by Jeddah and other locations.

Some job postings listed the location only as `Saudi Arabia`, so these were changed to `Not specified` to avoid treating the country name as a city.

Most roles in the dataset are Entry Level or Mid-Level, which supports the project focus on opportunities relevant to students and early-career Computer Science learners.

The role categories show that data-related jobs in Saudi Arabia include more than traditional Data Analyst and Data Scientist roles. The dataset also includes BI, AI, data governance, operations analytics, and internship opportunities.

## Day 4 Dataset Quality Notes

The cleaned dataset was saved separately from the raw dataset.

Raw dataset:
- `data/saudi_data_jobs_dataset.csv`

Cleaned dataset:
- `data/saudi_data_jobs_cleaned.csv`

This keeps the original data available while allowing analysis to continue using a cleaner version.

## Day 4 Pandas Notes

### replace
Used to replace specific values in a column.

### apply
Used to apply a function to each value in a column.

### value_counts
Used to count how many times each value appears in a column.

### Function
Used to create reusable cleaning logic.

### New Column
Created by assigning results to a new DataFrame column.

### to_csv
Used to export the cleaned DataFrame as a CSV file.

## Day 4 Next Steps

- Use the cleaned dataset for analysis.
- Analyze the most repeated skills and tools.
- Compare skills by role category.
- Create clearer charts from the cleaned columns.
- Start preparing insights for the first LinkedIn project post.
- Continue Kaggle Pandas practice.

- ## Day 5 Progress

- Created a Google Colab notebook named `03_skills_tools_analysis`.
- Loaded the cleaned Saudi data jobs dataset from GitHub.
- Analyzed the most frequently mentioned tools in the dataset.
- Created a Top 10 Tools bar chart.
- Analyzed the most frequently mentioned skills in the dataset.
- Created a Top 10 Skills bar chart.
- Wrote initial insights about the most important tools and skills for Saudi data-related roles.

## Day 5 Initial Findings

SQL was the most frequently mentioned tool, followed by Python, Excel, and Power BI.

The most repeated skills included trend analysis, data validation, data analysis, data governance, reporting, problem solving, dashboard development, and data accuracy.

These findings suggest that students interested in Saudi data-related roles should prioritize SQL, Python, Excel, Power BI, data analysis, reporting, and dashboarding skills.

## Day 5 Pandas Notes

### str.split
Used to split comma-separated values inside a column.

### explode
Used to turn list values into separate rows.

### str.strip
Used to remove extra spaces from text values.

### value_counts
Used to count repeated tools and skills.

### plot
Used to create simple charts from Pandas results.

## Day 5 Next Steps

- Compare tools and skills by role category.
- Analyze which skills are most common for Entry Level roles.
- Improve charts and insights for the final project report.
- Continue Kaggle Pandas practice.
