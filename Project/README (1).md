# Data Jobs Analysis

## Overview

This project analyzes the data job market using Python and Pandas. The goal of this project is to understand which data roles are most common, which skills are most in demand, how skills are trending, and which skills can provide better career opportunities.

I used data job postings to explore job titles, skills, salaries, and skill demand. Through this analysis, I am developing my understanding of data cleaning, data manipulation, analysis, and visualization using Python.

---

# Questions

The main questions I wanted to answer through this project are:

1. What are the most demanded skills for the top 3 most popular data roles?
2. How are in-demand skills trending for Data Analysts?
3. How well do jobs and skills pay for Data Analysts?
4. What are the optimal skills for Data Analysts to learn?

---

# Tools & Technologies

The main tools and libraries used in this project are:

- **Python** – Used for data analysis and manipulation
- **Pandas** – Used for data cleaning, transformation, and analysis
- **NumPy** – Used for numerical operations
- **Matplotlib** – Used for data visualization
- **Seaborn** – Used for creating visualizations
- **Jupyter Notebook** – Used to perform and document the analysis
- **Visual Studio Code** – Used as my development environment
- **Git & GitHub** – Used for version control and portfolio development

---

# Data Preparation

Before starting the analysis, I cleaned and prepared the dataset to make it suitable for analysis.

### Data Cleaning

The main data preparation steps included:

1. Loading the dataset
2. Converting the `job_posted_date` column to datetime
3. Cleaning and converting the `job_skills` column
4. Filtering the dataset to focus on jobs in the United States
5. Preparing the data for further analysis

---

# Analysis

## 1. Most Demanded Skills for the Top 3 Data Roles

### Question

**What are the most demanded skills for the top 3 most popular data roles?**

### Methodology

1. Clean up the `job_skills` column
2. Identify the top 3 most popular data roles
3. Calculate the number of job postings for each skill
4. Calculate the percentage of job postings requesting each skill
5. Identify the top 5 skills for each role
6. Visualize the results



### Key Findings

- SQL, Python, Excel, and other analytical tools appear frequently across data roles.
- The skills required vary depending on the data role.
- Some roles have a stronger emphasis on programming and technical skills.

---

## 2. Skill Trends for Data Analysts

### Question

**How are in-demand skills trending for Data Analysts?**

### Methodology

1. Filter the dataset for Data Analyst roles
2. Group job postings by month
3. Analyze skill demand over time
4. Calculate the percentage of job postings requesting each skill
5. Identify the most in-demand skills
6. Visualize the trends


### Key Findings

The analysis shows how the demand for important Data Analyst skills changes over time. This helps identify which skills remain consistently important and which skills show changes in demand.

---

## 3. Salary Analysis

### Question

**How well do jobs and skills pay for Data Analysts?**

### Methodology

1. Filter the dataset for jobs in the United States
2. Analyze salary distributions for different data roles
3. Compare salaries across job titles
4. Analyze salaries associated with different skills
5. Compare high-paying and highly demanded skills
6. Visualize the results



### Key Findings

The analysis shows that salary can vary significantly depending on the role, seniority, and skills required. Some specialized skills are associated with higher salaries, while other foundational skills appear more frequently in job postings.

---

## 4. Optimal Skills for Data Analysts

### Question

**What are the optimal skills for Data Analysts to learn?**

For this analysis, I wanted to identify skills that provide a good balance between **high demand and high salary**.

### Methodology

1. Filter the data for Data Analyst roles
2. Calculate the demand percentage for each skill
3. Calculate the median salary associated with each skill
4. Compare skill demand and salary
5. Visualize the relationship using a scatter plot
6. Identify skills that have both strong demand and salary potential



### Key Findings

The analysis helps identify skills that can potentially provide a strong combination of employability and earning potential.

---

# What I Learned

Working on this project helped me strengthen my understanding of Python and data analysis.

Some of the key concepts I practiced include:

- Data cleaning
- Filtering DataFrames
- `loc` and `iloc`
- `value_counts()`
- `groupby()`
- `merge()`
- Working with lists and nested data
- Data aggregation
- Calculating percentages
- Creating Pivot tables
- Data visualization
- Using Pandas for exploratory data analysis
- Using Matplotlib and Seaborn for visualization

---

# Challenges I Faced

While working on this project, I encountered several challenges, particularly while learning how Pandas handles data structures and transformations.

Some of the areas I found challenging were:

- Understanding Series vs DataFrames
- Working with indexes
- Cleaning the `job_skills` column
- Handling nested data
- Grouping and aggregating data
- Understanding how different Pandas methods work together
- Creating meaningful visualizations from the analysis

Working through these challenges helped me develop a better understanding of how data is structured and manipulated in Python.

---

# Conclusion

This project helped me explore the data job market while building practical experience with Python and Pandas.

The analysis provided insights into:

- The most common data roles
- The skills most frequently requested by employers
- How skill demand changes over time
- Salary differences between data roles
- The relationship between skill demand and salary

More importantly, this project gave me hands-on experience working with a real-world dataset and strengthened my foundation in data analytics.

---

# Project Structure

```text
Project/
│
├── 1_skill_demand.ipynb
├── 2_skill_trend.ipynb
├── 3_salary_analysis.ipynb
├── 4_optimal_skills.ipynb
├── EDAIntro.ipynb
│
├── images/
│
└── README.md
