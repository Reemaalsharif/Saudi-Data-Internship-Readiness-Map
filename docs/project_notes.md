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


## Day 4 - Data Cleaning

Completed data cleaning for the Saudi Data Jobs dataset.

Tasks completed:
- Cleaned the city column and replaced general locations such as Saudi Arabia with Not specified.
- Created a new city_cleaned column.
- Created a simplified experience_category column.
- Created a simplified role_category column.
- Exported the cleaned dataset as saudi_data_jobs_cleaned.csv.
- Added the cleaned dataset to the data folder.
- Added the data cleaning notebook as 02_data_cleaning.ipynb.
