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

## Day 6 Progress

- Created a Google Colab notebook named `04_entry_level_role_analysis`.
- Loaded the cleaned Saudi data jobs dataset from GitHub.
- Analyzed job postings by role category.
- Created a bar chart showing job postings by role category.
- Analyzed job postings by experience level.
- Created a bar chart showing job postings by experience level.
- Filtered the dataset to focus on Entry Level job postings.
- Analyzed the most frequently mentioned tools in Entry Level data-related roles.
- Created a Top 10 Entry-Level Tools bar chart.
- Analyzed the most frequently mentioned skills in Entry Level data-related roles.
- Created a Top 10 Entry-Level Skills bar chart.
- Used `groupby` to compare role categories with experience levels.

## Day 6 Initial Findings

The dataset shows that data-related roles in Saudi Arabia include multiple categories such as Data Analysis, Data Science, BI, AI, Governance, Internship, and Other.

Most of the collected roles are Entry Level or Mid-Level, which supports the project focus on students and early-career learners.

For Entry Level data-related roles, the most relevant tools include SQL, Python, Excel, Power BI, and Tableau.

The most relevant skills include data analysis, reporting, dashboarding, data validation, problem solving, and insight generation.

## Day 6 Pandas Notes

### groupby
Used to group the dataset by one or more columns.

### reset_index
Used to convert grouped results back into a regular DataFrame.

### sort_values
Used to sort results by a selected column.

### str.split
Used to split comma-separated tools or skills into lists.

### explode
Used to turn list values into separate rows.

### value_counts
Used to count repeated tools, skills, and categories.

## Day 6 Next Steps

- Compare tools and skills by specific role category.
- Identify the most important skills for Data Analysis and BI roles.
- Start preparing project insights for a LinkedIn post.
- Continue Kaggle Pandas practice.


## Day 7 Progress

- Reviewed the first week of the Saudi Data Jobs project.
- Confirmed that the raw dataset and cleaned dataset are saved in the data folder.
- Reviewed the uploaded notebooks for exploration, cleaning, skills/tools analysis, and entry-level analysis.
- Continued Kaggle Pandas practice.
- Completed or continued the final Kaggle Pandas lessons.
- Prepared initial insights for a LinkedIn post about the project.

## Day 7 Weekly Review

During the first week, the project moved from a basic idea to a structured data analysis project.

Completed work:
- Created the project repository.
- Collected 25 Saudi data-related job postings.
- Cleaned the dataset.
- Created analysis-ready columns such as city_cleaned, experience_category, and role_category.
- Analyzed the most repeated tools and skills.
- Analyzed entry-level data-related roles.

## Day 7 Initial Project Insights

The first analysis shows that SQL, Python, Excel, Power BI, and Tableau are among the most repeated tools in Saudi data-related job postings.

Entry-level roles commonly require a mix of technical and business skills, including data analysis, reporting, dashboarding, validation, and problem solving.

The dataset also shows that data-related roles are broader than only Data Analyst or Data Scientist roles. They include BI, AI, Governance, Operations Analytics, and Internship opportunities.

## Day 7 Next Steps

- Start the visualization-focused week.
- Improve charts and visual presentation.
- Continue documenting insights clearly.
- Prepare a LinkedIn post summarizing the first week of the project.

## Day 8 Progress

- Created a Google Colab notebook named `05_visualization_improvements`.
- Loaded the cleaned Saudi data jobs dataset from GitHub.
- Used Seaborn to improve the visual presentation of the analysis.
- Created improved charts for the most mentioned tools.
- Created improved charts for the most mentioned skills.
- Created a city distribution chart.
- Created a role category distribution chart.
- Created an experience level distribution chart.
- Added short insights under each visualization.

## Day 8 Initial Findings

The improved visualizations made the project findings easier to read and compare.

The most frequently mentioned tools included SQL, Python, Excel, Power BI, and Tableau.

The most repeated skills included data analysis, reporting, dashboarding, validation, and problem solving.

Riyadh appeared as the most common city in the dataset, while some postings were labeled as Not specified because they did not mention a specific city.

The role category and experience level charts helped show that the dataset includes multiple data-related paths and is useful for students and early-career learners.

## Day 8 Visualization Notes

### Seaborn
Used to create cleaner and more readable charts.

### barplot
Used to compare counts across tools, skills, cities, role categories, and experience levels.

### Horizontal Bar Charts
Used to make long labels easier to read.

### whitegrid
Used to make charts cleaner and easier to interpret.

## Day 8 Next Steps

- Continue Kaggle Data Visualization practice.
- Improve chart labels and formatting if needed.
- Save important charts for future reports and LinkedIn updates.
- Start analyzing tools in more detail in the next project step.

- ## Day 9 Progress

- Continued working in the Google Colab notebook named `05_visualization_improvements`.
- Focused on analyzing the most frequently mentioned tools in more detail.
- Used the cleaned Saudi data jobs dataset.
- Split the `tools` column so each tool appears in a separate row.
- Cleaned and normalized tool names to reduce duplicates and inconsistent naming.
- Counted the most frequently mentioned tools across the dataset.
- Created a bar chart showing the top tools mentioned in Saudi data-related job postings.
- Created a line chart to show how tool frequency decreases by rank.
- Compared top tools by role category using a heatmap.
- Compared top tools by experience level using a heatmap.
- Saved charts inside the `reports/figures` folder.
- Saved analysis tables inside the `reports/tables` folder.
- Continued Kaggle Data Visualization practice with Line Charts.

## Day 9 Initial Findings

The detailed tools analysis showed that SQL, Python, Excel, Power BI, and Tableau are among the most frequently mentioned tools in the dataset.

This suggests that Saudi data-related roles require a mix of programming, data analysis, reporting, dashboarding, and business intelligence skills.

The line chart helped show the frequency drop-off between the most common tools and the lower-ranked tools.

The heatmaps helped compare how tool requirements differ across role categories and experience levels. This made it easier to see that some tools are more common in Data Analysis and BI roles, while others are more connected to Data Science or AI-related roles.

## Day 9 Visualization Notes

### lineplot
Used to create a line chart showing the drop-off in tool frequency by rank.

### barplot
Used to compare the most frequently mentioned tools.

### heatmap
Used to compare tool mentions across role categories and experience levels.

### crosstab
Used to create comparison tables between tools and categories.

### savefig
Used to save charts as image files for GitHub, reporting, and future LinkedIn posts.

### to_csv
Used to save analysis tables as CSV files.

## Day 9 Next Steps

- Continue Kaggle Data Visualization practice.
- Study Bar Charts in the next visualization lesson.
- Analyze role categories in more detail.
- Compare tools and skills by broader role categories.
- Continue saving important charts and tables for the final report.
- Prepare stronger insights for the upcoming mini report.

- ## Day 10 Progress

- Continued working on the visualization-focused analysis.
- Focused on analyzing cleaned role categories instead of raw role types.
- Compared the raw `role_type` column with the cleaned `role_category` column.
- Counted job postings by role category.
- Created bar charts to show the distribution of role categories.
- Calculated the percentage of each role category.
- Compared role categories with experience levels.
- Saved role category charts inside the `reports/figures` folder.
- Saved role category analysis tables inside the `reports/tables` folder.
- Continued Kaggle Data Visualization practice with Bar Charts.

## Day 10 Initial Findings

The role category analysis showed that data-related jobs in Saudi Arabia are broader than only Data Analyst or Data Scientist roles.

The cleaned role categories made it easier to compare different paths such as Data Analysis, Data Science, BI, AI, Governance, Internship, and Other.

Using `role_category` instead of raw `role_type` made the analysis cleaner because similar job titles were grouped into broader and more understandable categories.

The comparison with experience levels helped show which role categories are more common for Entry Level, Mid-Level, and Internship opportunities.

## Day 10 Visualization Notes

### barplot
Used to compare the number of job postings across cleaned role categories.

### countplot
Used to count role categories directly from the dataset.

### crosstab
Used to compare role categories with experience levels.

### melt
Used to reshape the comparison table into a format suitable for grouped bar charts.

### savefig
Used to save charts as image files for GitHub and future reporting.

## Day 10 Next Steps

- Continue Kaggle Data Visualization practice.
- Analyze experience categories in more detail.
- Compare tools and skills by role category.
- Add stronger insights for the mini report.
- Continue preparing charts for GitHub, LinkedIn, and the final project report.


## Day 11 Progress

- Created a Google Colab notebook named `07_experience_category_analysis`.
- Loaded the cleaned Saudi data jobs dataset.
- Focused on analyzing the cleaned `experience_category` column.
- Counted job postings by experience level.
- Calculated the percentage of each experience category.
- Created a bar chart showing jobs by experience level.
- Created a percentage bar chart for experience categories.
- Compared experience levels with role categories using a crosstab table.
- Created a heatmap showing experience level by role category.
- Analyzed top tools by experience level.
- Created a heatmap for top tools by experience level.
- Analyzed top skills by experience level.
- Created a heatmap for top skills by experience level.
- Created a simple scatter plot for experience level rank and job count.
- Saved charts inside the `reports/figures` folder.
- Saved analysis tables inside the `reports/tables` folder.
- Continued Kaggle Data Visualization practice and worked on the Heatmaps / Scatter Plots lesson.

## Day 11 Initial Findings

The experience category analysis showed that most collected data-related roles are focused on Entry Level and Mid-Level opportunities.

This supports the project goal because the dataset is useful for Computer Science students and early-career learners who want to understand what Saudi data roles require.

The comparison between experience levels and role categories helped show which role types are more common for Entry Level, Mid-Level, and Internship roles.

The tools and skills heatmaps showed that early-career data roles often require a mix of SQL, Python, Excel, dashboards, reporting, and analysis skills.

## Day 11 Visualization Notes

### barplot
Used to compare the number and percentage of job postings across experience levels.

### heatmap
Used to compare experience levels with role categories, tools, and skills.

### crosstab
Used to create comparison tables between experience categories and other columns.

### scatterplot
Used to create a simple visual comparison between experience level rank and job count.

### savefig
Used to save charts as image files for GitHub and future reporting.

### to_csv
Used to save analysis tables as CSV files.

## Day 11 Kaggle Notes

Today I continued Kaggle Data Visualization practice.

The lesson focused on using visualizations such as heatmaps and scatter plots to compare relationships in data.

Key points learned:
- Heatmaps are useful when comparing two categories at the same time.
- Heatmaps make patterns easier to notice than reading raw tables.
- Scatter plots are useful for showing relationships between two numerical values.
- Choosing the right chart type depends on the question being answered.
- Clear titles, labels, and readable formatting make charts easier to understand.

## Day 11 Next Steps

- Continue Kaggle Data Visualization practice.
- Start writing the first mini report inside the `docs` folder.
- Summarize the main findings from tools, skills, roles, cities, and experience levels.
- Create `docs/initial_findings.md`.
- Prepare clearer insights for GitHub, LinkedIn, and the final project report.


## Day 12 Progress

- Created a mini report file named `initial_findings.md` inside the `docs` folder.
- Summarized the main findings from the analysis completed so far.
- Wrote an overview of the project goal and dataset.
- Summarized initial findings for tools, skills, cities, role categories, and experience levels.
- Added an initial readiness takeaway for Computer Science students interested in Saudi data-related roles.
- Connected the findings to practical preparation steps such as learning SQL, Python, Excel, Power BI, Tableau, reporting, and communication skills.
- Continued organizing the project documentation for GitHub.
- Completed the Kaggle Data Visualization course.

## Day 12 Initial Findings

The first mini report shows that Saudi data-related roles require a mix of technical, analytical, reporting, and communication skills.

The most important tools observed so far include SQL, Python, Excel, Power BI, and Tableau.

The findings also show that data-related roles are broader than only Data Analyst or Data Scientist positions. They include BI, AI, Governance, Internship, and other analytics-related roles.

The experience analysis supports the project focus on students and early-career learners because many roles in the dataset are Entry Level or Mid-Level.

Completing the Kaggle Data Visualization course helped improve the quality of the project charts and made the findings easier to explain through visualizations.

## Day 12 Documentation Notes

### initial_findings.md
Used to summarize the first major findings of the project in a readable report format.

### Project Overview
Used to explain the purpose of the project.

### Dataset Summary
Used to describe the current dataset size and cleaned columns.

### Tools and Skills Findings
Used to explain the most repeated tools and skills.

### City, Role, and Experience Findings
Used to summarize where roles are located, how they are categorized, and what experience levels are commonly required.

### Readiness Takeaway
Used to connect the analysis results to practical preparation steps for Computer Science students.

### Kaggle Data Visualization
Completed to improve chart creation skills using Seaborn and to apply clearer visualizations to the project.

## Day 12 Kaggle Notes

Completed the Kaggle Data Visualization course.

Main topics practiced:
- Hello, Seaborn
- Line Charts
- Bar Charts
- Heatmaps
- Scatter Plots and other visualization techniques

Main learning outcome:
The course helped me understand how to choose suitable chart types, improve chart readability, and communicate data findings more clearly.

## Day 12 Next Steps

- Review the quality of the charts and notebooks.
- Check that all important files are uploaded to GitHub.
- Prepare a LinkedIn post about the most common tools in Saudi data-related roles.
- Start the next review step for improving documentation, charts, and GitHub structure.
- Prepare for expanding the dataset in the next project phase.
- 
