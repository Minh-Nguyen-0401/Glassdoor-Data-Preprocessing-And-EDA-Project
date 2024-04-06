# DS-Job-Postings-Glassdoor-Data-Preprocessing-&-Analysis-Project
## Project Overview

Welcome to the Glassdoor Data Science Job Postings Project! This project aims to explore a dataset focusing on data science job postings sourced from Glassdoor, a leading platform for job seekers and employers. The dataset provides comprehensive insights into various aspects of data science job postings, including job titles, salary estimations, job descriptions, company ratings, and more.

## Project Structure:

- **`README.md`**: An introductory document containing quintessential information on the project
- **`glassdoor preprocessing & analysis.ipynb`**: The main Jyputer Notebook containing the data retrieval, preprocessing, data manipulation, and Exploratory Data Analysis operations
- **`glassdoor_sql.db`**: A Database File generated during the programming session with SQLite to facilitate data manipulation 
- **`Analytic Figures`**: A Folder containing Reporting Figures for insights generated during EDA process.
- **`data-science-job-posting-on-glassdoor`**: Original dataset retrieved from source

## About the Dataset

<a href="https://www.kaggle.com/datasets/rashikrahmanpritom/data-science-job-posting-on-glassdoor">The dataset</a>, scraped from Glassdoor's website, presents a rich but initially unstructured and messy collection of data. It originally comprises several crucial columns:

- **`Job Title`**: Title of the job posting.
- **`Salary Estimation`**: Salary range for each specific job.
- **`Job Description`**: Detailed description of the job.
- **`Rating`**: Rating of the job post.
- **`Company`**: Name of the company.
- **`Location`**: Company's location.
- **`Headquarter`**: Company's headquarters location.
- **`Size`**: Total number of employees in the company.
- **`Type of Ownership`**: Description of the company's ownership type (e.g., non-profit, public, private).
- **`Industry, Sector`**: Field in which the applicant will work.
- **`Revenue`**: Total revenue of the company.

## Objectives and Guiding Questions

In this project, my preset primary objectives include:

1. **Data Cleaning and Structuring**: Prepare the dataset for analysis by cleaning and structuring the data.
2. **Insight Extraction from Job Descriptions**: Extract meaningful insights from job descriptions to understand the requirements and trends in the data science field.
3. **Dataset Manipulation and Enhancement**: Manipulate and enhance the dataset to create new features that can provide additional insights.
4. **Addressing Specific Guiding Questions**: Answer specific guiding questions, including:
   - Converting the salary column into integers.
   - Extracting useful information from job descriptions.
   - Removing numerical values from company names.
   - Creating new features, such as a state column from the location column.
5. **Gathering Insightful Information**: with respect to states, rates offered, ratings, industries, sectors, and JD through grouping, merging and aggregating relations.

## Languages/Tools Used
- Python, SQLite, SQL Magic

Through these objectives and guiding questions, we aim to gain deeper insights into data science job postings on Glassdoor and extract actionable information for job seekers and employers in the field. Let's embark on this journey into the exciting world of data science job opportunities!

---------------------------------------------------------------
## Key Insights & Conclusion from the Project:

In conclusion, there are a number of inferrence from the analysis procedures executed above:
- Glassdoor is an ideal job posting platform for data enthusiast and pursuer with nearly 700 jobs currently available<br><br>
- However, occupations are restricted within the United States, most of which belong to enterprises sharing the same headquarters with their posted working location<br><br>
- In terms of data positions, the platform is apparently most suitable for data scientist specifically with a whopping number of 455 jobs. Trailing this figure is the count for data analysis and enginerring position in exchange for the highest average rating received (over 4 stars) <br><br>
- The decision on which to apply is highly subject to one's preference or priority, which can be categorized as follows:
    + For **`Salary`**: Delaware (DE) and North Carolina (NC) are substantiatively the most ideal places for those putting compensation on the pedestal, whereas Alabama (AL) should be avoided herein as its average salary is mediocre yet the maximum offer is fairly low ($165k) as compared to other states. With that being said, the former two are supposed to be very competitive, especially in Delaware (DE), where only one position is currently open for application. <br><br>
    + For **`Experience`**, the following top 5 places should be taken into consideration, namely Delaware(DE), Wisconsin(WI), Connecticut(CT), New Hampshire(NH), Ohio(OH), or probably Tennessee(TN) with respectively 111, 100 down to around 90 years of operations. These places comprise of the most established enterprises which have the potential to be masters of conventional techniques (well-established methods of operations and R&D) as well as value cocreation <br><br>
    + For **`Highly Applicable Knowledge`**, firms in states like AL, SC, AZ and IA, despite being relatively younger to the playground, have already acquired great revenue record for the latest year (around 300 billion dollars). Even comapanies with below 20 years of establishment in OR or RI have gained corresponding revenues. These can be attributed to their sensitivity to state-of-the-art business approaches and technological application. <br><br>
    + For **`Industries`**: Those who pursue the background of Biotech & Pharmaceuticals would gain a competitive advantage when using this platform for job seeking <br> <br>

><strong><i>All in all, regardless of what your preferences/priorities are, practical experience accompanied with data & machine learning knowledge are undoubtedly most demanded aspects for successful job acquisition</i></strong>
