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

## Day 5 Progress

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

## Day 9 Progress

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

## Day 10 Progress

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

## Day 13 Progress

- Reviewed the GitHub repository structure.
- Checked that the main folders are organized: `data`, `notebooks`, and `docs`.
- Reviewed the uploaded notebooks from the first analysis phase.
- Checked that the cleaned dataset and analysis notebooks are available.
- Reviewed the main charts created during the visualization phase.
- Confirmed that the initial findings report is available inside the `docs` folder.
- Updated the README to include a link to the initial findings report.
- Reviewed the overall project flow from data collection to cleaning, analysis, visualization, and documentation.
- Confirmed completion of the Kaggle Data Visualization course.

## Day 13 Review Findings

The project is now more organized and easier to understand from a portfolio perspective.

The repository includes:
- Raw and cleaned datasets.
- Multiple analysis notebooks.
- Daily project notes.
- An initial findings report.
- Visual analysis covering tools, skills, cities, role categories, and experience levels.

The project now shows a clear workflow from collecting job postings to creating insights that can help Computer Science students prepare for Saudi data-related roles.

## Day 13 Documentation Notes

### Repository Review
Used to check that the main project files are uploaded and organized clearly.

### Notebook Review
Used to make sure the analysis notebooks are understandable and connected to the project goal.

### Chart Review
Used to check that the visualizations are readable and suitable for GitHub, LinkedIn, and future reporting.

### README Update
Used to make the initial findings report easier to find for anyone visiting the GitHub repository.

## Day 13 Next Steps

- Prepare a LinkedIn post about the most common tools in Saudi data-related roles.
- Summarize the second week of the project.
- Continue improving the project documentation.
- Start preparing for the next phase, which includes expanding the dataset with more job postings.

## Day 14 Progress

- Reviewed the second week of the Saudi Data Jobs project.
- Summarized the visualization and analysis work completed during Days 8 to 13.
- Confirmed that the main charts and analysis notebooks are available in the GitHub repository.
- Confirmed that the initial findings report is available inside the `docs` folder.
- Reviewed the most frequently mentioned tools in the dataset.
- Prepared a LinkedIn post about the most common tools in Saudi data-related roles.
- Completed the second week of the project.
- Prepared for the next phase, which will focus on expanding the dataset with more job postings.

## Day 14 Weekly Summary

During the second week, the project moved from basic analysis to clearer visual storytelling and documentation.

Completed work during Week 2:
- Improved charts using Seaborn.
- Analyzed tools in more detail.
- Analyzed cleaned role categories.
- Analyzed experience categories.
- Compared tools and skills by experience level.
- Created heatmaps to compare categories.
- Created the first mini report: `docs/initial_findings.md`.
- Reviewed the GitHub repository structure.
- Updated the README file.
- Completed the Kaggle Data Visualization course.

## Day 14 Main Findings

The second week showed that Saudi data-related roles often require a mix of technical, analytical, reporting, dashboarding, and communication skills.

The most frequently mentioned tools so far include:
- SQL
- Python
- Excel
- Power BI
- Tableau

The analysis also showed that data-related roles are broader than only Data Analyst or Data Scientist positions. They include BI, AI, Governance, Internship, and other analytics-related roles.

The experience analysis supports the project focus on students and early-career learners because many roles in the dataset are Entry Level or Mid-Level.

## Day 14 LinkedIn Notes

A LinkedIn post was prepared to summarize one of the early findings from the project: the most common tools in Saudi data-related roles.

The post focuses on the idea that beginner-friendly data roles are not only about programming. They also require reporting, dashboards, analysis, and communication skills.

## Day 14 Next Steps

- Start expanding the dataset with more Saudi data-related job postings.
- Collect additional job and internship postings.
- Update the raw dataset.
- Clean the new data and update the cleaned dataset.
- Re-run the analysis after expanding the dataset.
- Compare whether the same tool and skill patterns continue with a larger sample.

## Day 15 Progress

- Started the third week of the Saudi Data Jobs project.
- Expanded the raw dataset by adding 10 new Saudi data-related job postings.
- Increased the dataset size from 25 postings to 35 postings.
- Added the new postings to `data/saudi_data_jobs_dataset.csv`.
- Reviewed the new postings to avoid clear duplicates.
- Skipped postings that were likely duplicates or not directly relevant to the project scope.
- Kept the same original dataset column structure.
- Focused on roles related to data analysis, data science, AI, business intelligence, analytics, performance analysis, and AI data collection.
- Did not update the cleaned dataset yet, because cleaning will be done after collecting more postings.
- Started the third-week learning track with Kaggle Intro to Machine Learning.

## Day 15 Dataset Expansion Notes

The dataset was expanded from 25 to 35 job postings.

The added roles included:
- Data Analyst
- Operations / Inventory Analytics
- Data Analyst Excel
- Data Scientist Expert
- Robotics Data Collector
- AI Trainer / Data Annotator
- Data Scientist
- Performance Analyst
- AI / ML Senior Analyst

Some postings were skipped because they were likely duplicates, too broad, too senior or managerial, or not strongly related to the project focus.

## Day 15 Next Steps

- Continue expanding the dataset with 10 more Saudi data-related postings.
- Increase the dataset from 35 to 45 postings.
- Continue Kaggle Intro to Machine Learning.
- Clean the expanded dataset after completing the collection phase.



## Day 16 Progress

- Continued expanding the Saudi Data Jobs dataset.
- Added 10 additional Saudi data-related job postings.
- Increased the raw dataset size from 35 postings to 45 postings.
- Focused on improving role diversity by adding Business Intelligence, Reporting, Fraud Analytics, Data Management, Commercial Performance, and Data Quality roles.
- Reviewed postings to avoid clear duplicates with the existing dataset.
- Skipped postings that were already included, not directly related to data, or too general for the project scope.
- Cleaned and simplified some LinkedIn job links to make the dataset easier to read and maintain.
- Kept the cleaned dataset unchanged for now.
- Prepared the dataset for the next cleaning phase.

## Day 16 Dataset Expansion Notes

The dataset was expanded from 35 to 45 job postings.

The new postings added included:
- Business Intelligence Analyst
- Control & Reporting Associate Analyst
- Fraud Risk Analyst
- Medical Fraud Senior Analyst
- AI & Data Trainee
- Data Management Specialist
- Commercial Performance Analyst
- Data Quality Analyst

The added roles improved the dataset by covering more areas such as:
- Business Intelligence
- Reporting
- Dashboarding
- KPI analysis
- Fraud analytics
- Data governance
- Data quality
- Commercial performance analytics

## Day 16 Data Quality Notes

After the second expansion:
- The raw dataset contains 45 job postings.
- The `job_id` values range from 1 to 45.
- The same 12-column structure was kept.
- The cleaned dataset was not updated yet.
- Cleaning will be done in the next step by updating:
  - `city_cleaned`
  - `experience_category`
  - `role_category`

## Day 16 Next Steps

- Clean the expanded dataset.
- Update the cleaned dataset from 25 rows to 45 rows.
- Re-create the analysis-ready columns.
- Check duplicates and missing values again.
- Re-run the main analysis using the expanded dataset.



## Day 17 Progress

- Cleaned the expanded Saudi Data Jobs dataset after increasing it to 45 job postings.
- Created a new cleaning notebook: `08_expanded_dataset_cleaning.ipynb`.
- Loaded the updated raw dataset from `data/saudi_data_jobs_dataset.csv`.
- Checked the dataset shape, columns, missing values, duplicate rows, duplicate job IDs, and duplicate job links.
- Confirmed that the raw dataset contains 45 job postings.
- Created updated analysis-ready columns for the expanded dataset:
  - `city_cleaned`
  - `experience_category`
  - `role_category`
- Saved the updated cleaned dataset as `data/saudi_data_jobs_cleaned.csv`.
- Kept the raw dataset and cleaned dataset as separate files because they serve different purposes.

## Day 17 Cleaning Notes

The raw dataset and cleaned dataset both contain 45 job postings, but they are not duplicates.

The raw dataset is:

`data/saudi_data_jobs_dataset.csv`

It contains the original collected job postings before cleaning.

The cleaned dataset is:

`data/saudi_data_jobs_cleaned.csv`

It contains the same job postings after adding cleaning and analysis-ready columns.

The cleaned dataset includes three additional columns:
- `city_cleaned`
- `experience_category`
- `role_category`

These columns make the dataset easier to analyze and visualize.

## Day 17 Data Quality Checks

During the cleaning process, I checked:

- Dataset shape
- Column names
- Missing values
- Duplicate rows
- Duplicate job IDs
- Duplicate job links
- City values
- Experience level values
- Role type values

The goal was to make sure the expanded dataset is ready for updated analysis.

## Day 17 Main Takeaway

Today’s work focused on preparing the expanded dataset for analysis.

The dataset now has a clean version with 45 job postings and analysis-ready columns.

This step is important because future analysis should use the cleaned dataset instead of the raw dataset.

## Day 17 Next Steps

- Re-run the tools and skills analysis using the updated cleaned dataset.
- Re-create updated charts using 45 job postings.
- Compare the new results with the initial findings from the first 25 postings.
- Check whether the most common tools and skills changed after expanding the dataset.
- Update the project findings based on the larger dataset.



## Day 18 Progress

- Re-ran the main analysis using the expanded cleaned dataset.
- Used the updated cleaned dataset: `data/saudi_data_jobs_cleaned.csv`.
- Confirmed that the expanded cleaned dataset contains 45 Saudi data-related job postings.
- Checked the dataset shape, columns, missing values, duplicate rows, duplicate job IDs, and duplicate job links.
- Re-analyzed the most mentioned tools in the expanded dataset.
- Re-analyzed the most repeated skills in the expanded dataset.
- Re-analyzed job distribution by city.
- Re-analyzed job distribution by role category.
- Re-analyzed job distribution by experience category.
- Created updated analysis tables for the expanded dataset.
- Created updated charts for tools, skills, cities, role categories, and experience categories.
- Continued Kaggle Intro to Machine Learning with the Model Validation lesson.

## Day 18 Expanded Dataset Analysis Notes

Today’s work focused on running the main analysis again after expanding the dataset.

The dataset was expanded from the initial 25 job postings to 45 job postings.

The updated analysis included:
- Top tools
- Top skills
- Jobs by city
- Jobs by role category
- Jobs by experience category
- Tools by role category
- Skills by experience category

This step is important because the first analysis was based on a smaller sample.  
After expanding the dataset, the analysis gives a more reliable view of common tools, skills, cities, and role types in Saudi data-related job postings.

## Day 18 Kaggle Notes

Today I continued Kaggle Intro to Machine Learning and studied Model Validation.

Model validation is the process of checking how well a machine learning model performs on data it has not seen before.

The main idea is that a model should not only perform well on the training data.  
It should also perform well on new unseen data.

Main concepts learned:
- Training data
- Validation data
- Model performance
- Generalization
- Checking whether a model can make reliable predictions on new data

## Day 18 Main Takeaway

After expanding the dataset to 45 job postings, the project findings became stronger because the analysis is based on a larger sample.

The updated analysis helps check whether the early findings from the first 25 job postings still appear after adding more roles.

This prepares the project for the next step, which is comparing the initial 25-posting results with the expanded 45-posting results.

## Day 18 Next Steps

- Compare the initial 25-posting results with the expanded 45-posting results.
- Check whether the top tools changed after expanding the dataset.
- Check whether the top skills changed after expanding the dataset.
- Compare city distribution before and after expansion.
- Compare role category distribution before and after expansion.
- Continue Kaggle Intro to Machine Learning with Underfitting and Overfitting.



## Day 19 Progress

Compared the initial Saudi Data Jobs dataset containing 25 job postings with the expanded dataset containing 45 job postings.

Compared the results between both datasets to check whether the initial findings remained consistent after increasing the dataset size.

The comparison included:

- Role category distribution.
- Experience category distribution.
- Most mentioned tools.
- Most repeated skills.

Created comparison tables and visualizations to show the differences between the initial and expanded datasets.

Saved the comparison results to use for improving the final project analysis.

## Day 19 Comparison Findings

The comparison helped evaluate how the results changed after expanding the dataset from 25 to 45 job postings.

The expanded dataset provided more job postings and a broader view of Saudi data-related roles.

Comparing both datasets helped identify whether the main patterns observed in the initial analysis continued to appear after adding more data.

## Day 19 Data Analysis Notes

Dataset comparison is useful to understand how increasing the sample size affects analysis results.

A larger dataset can provide more reliable insights by reducing the impact of individual job postings.

Comparing percentages is also important because the two datasets have different sizes.

## Day 19 Next Steps

Update the final charts using the expanded dataset.

Improve the visualization quality of the updated results.

Continue documenting the updated findings for the final project report.



## Day 20 Progress

- Created a new visualization notebook: `11_final_visualizations.ipynb`.
- Loaded the expanded cleaned dataset from `data/saudi_data_jobs_cleaned.csv`.
- Confirmed that the dataset contains 45 Saudi data-related job postings.
- Updated the main project visualizations using the expanded dataset.
- Created final charts for:
  - Top tools mentioned in the dataset.
  - Top skills mentioned in the dataset.
  - Job distribution by city.
  - Role category distribution.
  - Experience category distribution.
  - Tools requirements by role category using heatmap.
- Saved the final charts inside the `final_figures` folder.
- Prepared the updated visualizations for GitHub and future project documentation.

## Day 20 Final Visualization Notes

The final visualizations were created using the expanded cleaned dataset containing 45 job postings.

The updated charts provide a clearer view of:
- The most common tools required in Saudi data-related jobs.
- The most repeated skills mentioned in job postings.
- The distribution of roles and experience levels.
- The relationship between tools and different role categories.

These visualizations will help present the project findings more clearly and will be used later for dashboard development and final project reporting.

## Day 20 Visualization Techniques

During this stage, different visualization methods were used:

- Bar charts were used to compare tools, skills, cities, role categories, and experience categories.
- Heatmaps were used to compare tool requirements across different role categories.
- The final charts were saved as images for GitHub and future project presentation.

## Day 20 Main Takeaway

The expanded dataset helped create more representative visualizations compared to the initial analysis based on 25 job postings.

Updating the charts after expanding the dataset helped ensure that the final project visuals are based on the latest cleaned dataset.

## Day 20 Next Steps

- Start extracting the main technical skills and tools from the analysis.
- Build the readiness roadmap for Computer Science students interested in data-related roles.
- Continue improving project documentation.

## Day 21 Progress

- Reviewed the third phase of the Saudi Data Jobs project after completing the expanded dataset analysis and final visualizations.
- Reviewed the completed project notebooks and confirmed that the main analysis workflow is organized from data collection, cleaning, analysis, and visualization.
- Completed the remaining Kaggle learning tasks related to:
  - Pandas
  - Data Visualization
  - Intro to Machine Learning
- Completed the related Kaggle certificates and added them to the project achievements.
- Reviewed the project documentation structure and prepared the next phase focused on extracting skills, tools, and building the readiness roadmap.
- Organized the completed learning progress to support the project portfolio and LinkedIn updates.

## Day 21 Learning and Project Review Notes

The project reached an important milestone after completing the main data analysis stages.

Completed project foundations:

- Raw dataset collection.
- Data cleaning and preparation.
- Exploratory data analysis.
- Skills and tools analysis.
- Role category analysis.
- Experience category analysis.
- Dataset expansion from 25 to 45 job postings.
- Dataset comparison between initial and expanded samples.
- Final visualization updates.

The completed Kaggle certificates improved the ability to analyze, visualize, and work with real-world datasets using Python and data analysis techniques.

## Day 21 Main Takeaway

The project now has a complete analysis foundation, including a cleaned dataset, multiple analysis notebooks, visualizations, documentation, and completed learning milestones.

The next phase will focus on transforming the analysis results into practical insights and a readiness roadmap for Computer Science students interested in data-related careers.

## Day 21 Next Steps

- Extract the most important technical skills from the dataset.
- Analyze the most frequently mentioned tools.
- Analyze job responsibilities.
- Build beginner and intermediate skill roadmaps.


## Day 22 Progress

- Created a new technical skills analysis notebook: `12_technical_skills_analysis.ipynb`.
- Loaded the expanded cleaned dataset from `data/saudi_data_jobs_cleaned.csv`.
- Confirmed that the dataset contains 45 Saudi data-related job postings.
- Extracted and analyzed the skills column from the job postings.
- Split multiple skills into separate rows to allow individual skill analysis.
- Cleaned and standardized skill names to reduce duplicates and inconsistent naming.
- Removed duplicate skills within the same job posting to avoid repeated counting.
- Filtered the dataset to focus on technical skills only.
- Calculated the frequency of technical skills across the collected job postings.
- Created a ranking table for the most frequently mentioned technical skills.
- Created a bar chart showing the top technical skills in Saudi data-related jobs.
- Saved the technical skills analysis table and visualization for GitHub and future reporting.

## Day 22 Technical Skills Findings

The technical skills analysis identified the most frequently required technical skills in Saudi data-related job postings.

The top technical skills included:

- Data Analysis.
- Dashboard Development.
- Data Integrity.
- Data Governance.
- Data Validation.
- Machine Learning.
- Data Visualization.
- Business Intelligence.
- Data Quality.
- Data Modeling.

The results show that Saudi data-related roles require a combination of analytical, data management, visualization, and business intelligence skills.

## Day 22 Technical Skills Notes

During this stage, the following techniques were used:

- `explode()` was used to transform multiple skills stored in one cell into separate rows.
- `drop_duplicates()` was used to prevent counting the same skill multiple times within one job posting.
- `replace()` was used to standardize similar skill names.
- `value_counts()` was used to calculate the frequency of each technical skill.
- `barh()` was used to create a horizontal bar chart for easier comparison of skill frequencies.

## Day 22 Main Takeaway

The technical skills analysis shows that data careers are not only focused on programming, but also require strong skills in data analysis, data quality, governance, and visualization.

These findings will be used in the next project steps to analyze tools, responsibilities, and build a readiness roadmap for Computer Science students.

## Day 22 Next Steps

- Analyze the most frequently mentioned tools in Saudi data-related jobs.
- Compare tool requirements across different role categories.
- Continue building the readiness roadmap based on market requirements.


## Day 23 Progress

- Created a new tools analysis notebook: `13_tools_analysis.ipynb`.
- Loaded the expanded cleaned dataset from `data/saudi_data_jobs_cleaned.csv`.
- Confirmed that the dataset contains 45 Saudi data-related job postings.
- Extracted and analyzed the tools column from job postings.
- Split multiple tools into separate rows for individual analysis.
- Cleaned and standardized tool names.
- Removed duplicate tools within the same job posting to avoid repeated counting.
- Calculated the frequency of each tool across the collected job postings.
- Created a ranking table for the most frequently mentioned tools.
- Created a visualization showing the top tools required in Saudi data-related jobs.
- Compared tool requirements across different role categories using a heatmap.
- Saved the analysis tables and visualizations for GitHub and future project reporting.

## Day 23 Tools Findings

The tools analysis identified the most frequently mentioned tools in Saudi data-related job postings.

The results show that SQL is the most frequently requested tool, followed by Excel, Python, and Power BI.

The findings highlight that data roles require a combination of database skills, programming skills, spreadsheet analysis, and business intelligence tools.

The role-based comparison also shows that tool requirements vary depending on the career path, with different roles emphasizing different combinations of tools.

## Day 23 Visualization Notes

During this stage, different visualization methods were used:

- Bar charts were used to compare the frequency of tools across job postings.
- Heatmaps were used to analyze the relationship between tools and role categories.

These visualizations provide a clearer understanding of the tools required for different data career paths.

## Day 23 Main Takeaway

The tools analysis shows that successful data professionals need a balanced toolkit combining SQL, programming, analysis, and visualization platforms.

These results will support the next stages of the project, including responsibilities analysis and building the readiness roadmap.

## Day 23 Next Steps

- Analyze job responsibilities mentioned in Saudi data-related roles.
- Identify common tasks and responsibilities across different roles.
- Continue building the beginner and intermediate readiness roadmap.

- ## Day 24 Progress

- Created a new job focus analysis notebook: `14_job_focus_analysis.ipynb`.
- Loaded the cleaned Saudi Data Jobs dataset containing 45 job postings.
- Analyzed the `notes` column to extract common focus areas mentioned in Saudi data-related job descriptions.
- Cleaned and standardized job description text to prepare it for analysis.
- Created a list of important data-related focus keywords including:
  - Data Analysis.
  - Analytics.
  - Dashboard Development.
  - Reporting.
  - Business Intelligence.
  - Data Visualization.
  - Machine Learning.
  - SQL.
  - Python.
  - Data Governance.
- Calculated how frequently each focus area appeared across job postings.
- Created a ranking table showing the most common job focus areas.
- Created a bar chart to visualize the top focus areas in Saudi data-related jobs.
- Compared job focus areas across different role categories using role-based analysis.
- Created a heatmap to visualize the relationship between focus areas and job categories.
- Saved the final visualizations for GitHub and future project reporting.

## Day 24 Job Focus Findings

The analysis focused on understanding the main areas emphasized in Saudi data-related job descriptions.

The results provide insights into what employers focus on when describing data roles, including analytical tasks, reporting, dashboards, business intelligence, data visualization, and machine learning-related activities.

The role-based comparison helps identify how job focus areas differ between different career paths such as Data Analyst, Data Scientist, and BI-related roles.

These findings provide additional context beyond skills and tools by showing the practical areas where data professionals are expected to contribute.

## Day 24 Analysis Notes

During this stage, different data analysis techniques were applied:

- Text cleaning was used to standardize job description information.
- Keyword-based analysis was used to identify important focus areas within job descriptions.
- Frequency counting was used to measure how often each focus area appeared.
- Bar charts were used to compare the most common focus areas.
- Crosstab analysis was used to compare focus areas across role categories.
- Heatmaps were used to visualize relationships between job categories and focus areas.

## Day 24 Main Takeaway

The job focus analysis shows that Saudi data-related roles combine analytical, reporting, visualization, and business-oriented activities.

Understanding these focus areas helps identify not only the skills and tools required by employers, but also the practical responsibilities and expectations within different data career paths.

The results will support the next stage of the project by helping build a beginner and intermediate readiness roadmap.

## Day 24 Next Steps

- Build the beginner skill roadmap based on the analyzed skills, tools, and job focus areas.
- Identify the essential knowledge areas for students starting a data career.
- Create an intermediate roadmap for students aiming for advanced data roles.


## Day 25 Progress

- Created a new roadmap notebook: `15_beginner_readiness_roadmap.ipynb`.
- Used the findings from previous analysis stages to build a beginner-level data career roadmap.
- Combined insights from:
  - Technical Skills Analysis (Day 22).
  - Tools Analysis (Day 23).
  - Job Focus Analysis (Day 24).
- Created a structured learning path for Computer Science students interested in entering data-related careers.
- Organized the roadmap into progressive learning stages:
  - Programming Foundation.
  - Database Foundation.
  - Data Analysis.
  - Data Visualization.
  - Business Intelligence.
- Defined the main skills required for each stage, including:
  - Python Basics.
  - SQL.
  - Data Cleaning and Excel.
  - Pandas and Data Visualization.
  - Power BI and Dashboard Development.
- Assigned priority levels to identify the most important areas for beginners.
- Created a visual representation of the beginner learning roadmap.
- Saved the roadmap visualization for future documentation and project presentation.

## Day 25 Beginner Roadmap Notes

The beginner roadmap was created to transform the project analysis results into a practical learning path.

Instead of listing skills separately, the roadmap organizes the required knowledge in a logical order that helps beginners understand where to start and what to learn next.

The roadmap begins with programming and database fundamentals, then moves toward data analysis, visualization, and business intelligence skills.

This structure helps connect market requirements from Saudi data-related job postings with a practical preparation plan for students.

## Day 25 Roadmap Approach

The roadmap was designed based on the project findings:

- Skills analysis helped identify important knowledge areas.
- Tools analysis helped identify commonly requested technologies.
- Job focus analysis helped understand the main areas emphasized in job descriptions.

These insights were combined to create a beginner-friendly progression toward entry-level data roles.

## Day 25 Main Takeaway

The analysis results were converted from raw job market observations into an actionable learning roadmap.

The beginner roadmap provides a clear starting point for students who want to prepare for data-related careers and understand the recommended order of learning.

## Day 25 Next Steps

- Build an intermediate-level roadmap for students who already have basic data skills.
- Add more advanced technologies and concepts based on the Saudi data job market analysis.
- Continue improving the final career readiness roadmap.

- ## Day 26 Progress

- Created a new roadmap notebook: `16_intermediate_readiness_roadmap.ipynb`.
- Built an intermediate-level data career roadmap based on the findings from the previous project analysis stages.
- Used insights from:
  - Technical Skills Analysis (Day 22).
  - Tools Analysis (Day 23).
  - Job Focus Analysis (Day 24).
  - Beginner Readiness Roadmap (Day 25).
- Designed a learning path for students who already have basic data skills and want to progress toward professional data roles.
- Organized the intermediate roadmap into advanced learning stages:
  - Advanced Data Analysis.
  - Advanced SQL and Databases.
  - Statistics and Modeling.
  - Machine Learning.
  - Advanced BI and Reporting.
  - Cloud and Data Platforms.
- Defined the main skills and concepts required for each stage, including:
  - Advanced Pandas and Data Manipulation.
  - Advanced SQL, Data Modeling, and Database Design.
  - Statistics, Probability, and Hypothesis Testing.
  - Machine Learning Fundamentals and Model Evaluation.
  - Advanced Power BI Features and Dashboard Design.
  - Azure Data Services and Cloud Data Concepts.
- Assigned learning priorities to highlight the most important areas for intermediate-level preparation.
- Created a visual representation of the intermediate learning roadmap.
- Saved the roadmap visualization for GitHub and future project documentation.

## Day 26 Intermediate Roadmap Notes

The intermediate roadmap was created to guide learners who already understand the basic concepts of data analysis and want to develop more advanced skills.

The roadmap focuses on moving from basic data handling toward professional-level capabilities by adding stronger SQL knowledge, statistical understanding, machine learning foundations, advanced business intelligence, and cloud data concepts.

The learning sequence was designed to follow a realistic progression from analytical foundations toward more advanced data career requirements.

## Day 26 Roadmap Approach

The roadmap was developed by connecting the previous project findings with a practical career progression:

- Skills analysis identified the important technical areas required by employers.
- Tools analysis highlighted commonly requested technologies.
- Job focus analysis showed the main areas emphasized in Saudi data-related job descriptions.
- The beginner roadmap provided the foundation for developing the next learning stage.

These insights were transformed into an intermediate roadmap that represents the skills needed to move toward more advanced data roles.

## Day 26 Main Takeaway

The intermediate roadmap extends the beginner path by introducing advanced analytical, technical, and professional skills.

It provides a structured progression for learners who want to move beyond entry-level preparation and become more competitive for data-related opportunities.

## Day 26 Next Steps

- Combine the beginner and intermediate roadmaps into a complete data career readiness framework.
- Create the final roadmap connecting Computer Science students with suitable data career paths.
- Prepare the final documentation and presentation of the project findings.



## Day 27 Progress

- Created a new final roadmap notebook: `17_final_data_career_roadmap.ipynb`.
- Combined the results from the previous project analysis stages to create a complete data career readiness framework for Computer Science students.
- Integrated insights from:
  - Technical Skills Analysis (Day 22).
  - Tools Analysis (Day 23).
  - Job Focus Analysis (Day 24).
  - Beginner Readiness Roadmap (Day 25).
  - Intermediate Readiness Roadmap (Day 26).
- Built a final learning roadmap showing the progression from beginner foundations to career preparation.
- Organized the roadmap into three main levels:
  - Beginner Level.
  - Intermediate Level.
  - Career Ready Level.
- Defined the recommended learning areas for each stage, including:
  - Python Programming Fundamentals.
  - SQL and Database Fundamentals.
  - Data Analysis and Data Cleaning.
  - Advanced Analytics and Data Modeling.
  - Machine Learning Fundamentals.
  - Business Intelligence and Dashboard Development.
  - Portfolio Building and Job Preparation.
- Created a final visualization representing the learning progression.
- Created a career path mapping table connecting data skills with possible career roles:
  - Data Analyst.
  - BI Analyst.
  - Data Scientist.
  - Analytics Engineer.
- Saved the final roadmap outputs for GitHub and future project reporting.

## Day 27 Final Roadmap Notes

The final roadmap combines the project findings into a structured preparation framework for students interested in data careers.

Instead of presenting isolated skills and tools, the roadmap organizes the required knowledge into a progressive learning path, starting from foundational concepts and moving toward advanced technical skills and career preparation.

The framework connects Saudi data job market requirements with practical learning steps that help Computer Science students understand how to prepare for different data-related roles.

## Day 27 Career Path Approach

The career path mapping was created to show how different skill combinations relate to different data career directions.

Examples:

- Data Analysts focus on SQL, Excel, Python, and visualization.
- BI Analysts focus on reporting, dashboards, and Power BI.
- Data Scientists focus on Python, statistics, and machine learning.
- Analytics Engineers focus on SQL, data modeling, and data pipelines.

This helps students understand that different data roles require different combinations of skills and tools.

## Day 27 Main Takeaway

The final roadmap transformed the collected Saudi data job market insights into an actionable career preparation framework.

The project moved from analyzing job requirements to creating a practical guide that helps Computer Science students understand the skills, tools, and learning progression needed for data-related careers.

## Day 27 Next Steps

- Review the completed roadmap and previous analysis results.
- Improve the overall project documentation.
- Prepare the project for the next stage, including dashboard development and final portfolio improvements.

## Day 28 Progress

- Reviewed the current progress of the Saudi Data Internship Readiness Map project.
- Reviewed the completed analysis stages, notebooks, README, and project documentation.
- Confirmed that the project moved from analyzing Saudi data job requirements into creating a practical career preparation framework.

- Reviewed the completed certifications and learning progress:
  - Kaggle Pandas.
  - Kaggle Data Visualization.
  - Kaggle Intro to Machine Learning.
  - Kaggle Intermediate Machine Learning.

- Reviewed the final Data Career Readiness Roadmap created from the previous project analysis stages.
- Created a documentation file for the roadmap:
  - `docs/readiness_roadmap.md`

- Added the final roadmap documentation including:
  - Beginner Level.
  - Intermediate Level.
  - Career Ready Level.
  - Data career path mapping.

- Added visual roadmap outputs to support the project documentation and improve GitHub presentation.
- Prepared LinkedIn content to present the final roadmap and explain how job market analysis was transformed into a practical learning path.

## Day 28 Final Review Notes

The project review showed the progress from collecting and analyzing Saudi data-related job postings to building a structured framework that helps Computer Science students understand the skills and learning steps required for data careers.

The final roadmap connects the project findings, including technical skills, tools, role categories, and experience requirements, into a practical preparation path.

This stage helped organize the project outcomes and improve the documentation before moving to the next development phase.

## Day 28 Documentation Approach

The documentation updates focused on making the project easier to understand by organizing:

- Project findings.
- Required skills and tools.
- Learning progression.
- Career path connections.

The roadmap documentation provides a clear explanation of how the analysis results were converted into actionable learning steps.

## Day 28 Main Takeaway

The project progressed from analyzing job market data to creating a practical career readiness framework.

The main achievement of this stage was transforming separate analysis results into a structured roadmap that can guide students preparing for data-related internships and early-career opportunities.

## Day 28 Next Steps

- Start preparing the Power BI dashboard stage.
- Organize the cleaned dataset for dashboard development.
- Continue improving project documentation and portfolio presentation.


## Day 29 Progress

- Prepared the cleaned dataset for the Power BI dashboard development stage.
- Created a new notebook:
  - `18_powerbi_data_preparation.ipynb`

- Loaded the final cleaned Saudi data jobs dataset and reviewed the dataset structure before importing it into Power BI.

- Checked the dataset quality by performing:
  - Dataset size verification.
  - Column review.
  - Data type inspection.
  - Missing values check.
  - Duplicate records check.

- Verified that the dataset contains the required analysis columns for dashboard development, including:
  - City information.
  - Role categories.
  - Experience categories.
  - Skills.
  - Tools.

- Created a separate Power BI-ready dataset:
  - `saudi_data_jobs_powerbi.csv`

- Prepared the final dataset version that will be used for creating interactive Power BI visuals and dashboards.

## Day 29 Data Preparation Notes

The purpose of this stage was to prepare the project data before moving into Power BI development.

Instead of directly importing the cleaned dataset, the data was reviewed and validated to ensure that the dashboard would be built using a reliable and structured dataset.

The Power BI dataset will be used to visualize the main project insights, including job distribution, required tools, skills, roles, and experience levels.

## Day 29 Preparation Approach

The preparation process focused on:

- Validating the cleaned dataset.
- Ensuring important columns are available for visualization.
- Creating a dedicated dataset for dashboard development.
- Maintaining a clear workflow between data analysis and visualization stages.

## Day 29 Main Takeaway

This stage connected the data analysis phase with the visualization phase by preparing a structured dataset ready for Power BI.

The project moved from analyzing job market data using Python into building interactive dashboards that present the findings in a clearer way.

## Day 29 Next Steps

- Import the Power BI-ready dataset into Power BI Desktop.
- Build the first dashboard page.
- Create initial visuals for jobs, roles, cities, and experience categories.
