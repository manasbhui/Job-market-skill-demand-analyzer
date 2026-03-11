# Job Market & Skill Demand Trends Analyzer

## Project Overview
The **Job Market & Skill Demand Trends Analyzer** is a data analytics project designed to analyze job market trends and identify the most in-demand skills across industries, companies, locations, and experience levels.

This project uses **Python for preprocessing and skill extraction**, and **Power BI for visualization** to transform raw job posting data into meaningful insights.

---

## Objective

The main objectives of this project are:

- Analyze job market trends across different locations
- Identify the most in-demand job roles
- Determine the most demanded skill categories
- Understand salary trends across experience levels
- Identify companies with the highest hiring demand

This project helps **job seekers and analysts understand current hiring patterns and skill demands.**

---

## Dataset

Source: **Kaggle – LinkedIn Job Postings Dataset (2023–2024)**

The dataset includes the following fields:

- Job Title
- Company Name
- Location
- Salary
- Experience Level
- Job Description
- Skills
- Posting Date

This dataset provides insights into real-world hiring trends.

---

## Tools & Technologies Used

### Python
Python was used for **data preprocessing and skill extraction**.

Libraries used:
- pandas
- numpy
- regex
- spaCy

Tasks performed:
- Data cleaning
- Handling missing values
- Skill extraction from job descriptions
- Feature engineering

---

### NLP (spaCy)

Natural Language Processing was used to extract skills from job descriptions.

Techniques used:
- Named Entity Recognition (NER)
- Keyword-based skill extraction
- Skill categorization

This helped convert unstructured job descriptions into structured skill data.

---

### Excel

Excel was used for:

- Initial data exploration
- Removing duplicate records
- Data validation
- Exporting structured CSV files

---

### Power BI

Power BI was used to build an **interactive dashboard** to visualize job market insights.

Visualizations created:

- Bar Charts
- Line Charts
- Skill demand analysis
- Experience-level salary trends
- Company hiring trends

---

## Project Workflow

### Step 1 – Data Collection
Job posting data was collected from the **Kaggle LinkedIn Job Postings Dataset (2023–2024)**.

---

### Step 2 – Data Cleaning & Preprocessing

The dataset was cleaned using Python and Excel.

Tasks included:

- Removing duplicates
- Handling missing values
- Standardizing location names
- Formatting experience levels
- Preparing the dataset for analysis

---

### Step 3 – Skill Extraction using Python

Python and NLP techniques were used to extract skills from job descriptions.

A predefined skill mapping categorized skills into groups such as:

- IT
- Finance
- Marketing
- Administrative
- Engineering

A new column **skills** was created containing extracted skill information.

---

### Step 4 – Data Modeling in Power BI

The cleaned dataset was imported into Power BI.

Steps performed:

- Data type correction
- Data transformation
- Data modeling
- Visualization preparation

---

### Step 5 – Dashboard Creation

The Power BI dashboard contains the following visuals:

**Job Postings Distribution by Location**
Shows locations with the highest job opportunities.

**Top Job Roles Based on Skill Frequency**
Displays the most common job roles.

**Salary Trends Across Experience Levels**
Shows salary trends across different experience levels.

**Companies with Highest Skill Demand**
Identifies companies hiring the most employees.

**Most In-Demand Skill Categories**
Highlights the most demanded skill categories.

**Skill Demand by Experience Level**
Shows how skill demand varies across experience levels.

---

## Key Insights

From the analysis, the following insights were discovered:

- Entry-level roles have the highest number of job postings
- Administrative and manufacturing skills show strong demand
- Companies such as **Amazon, Wells Fargo, and J. Galt** are actively hiring
- Certain locations dominate job opportunities
- Salary trends vary significantly across experience levels

---


## Author

**Manas Ranjan Bhui**

Data Analyst  
Python | SQL | Power BI | Data Visualization
