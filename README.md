# AI-Job-Market-Intelligence-Adzuna

# AI Job Market Intelligence & Hiring Trends System Analysis

## Project Overview
This project analyzes global job market trends using the **Adzuna Global Job Listings 2025 dataset**.  
The goal of this project is to explore **hiring demand, salary trends, employment types, and industry patterns** using Exploratory Data Analysis (EDA) and interactive visualizations.

The analysis helps understand the **structure of the job market and factors influencing hiring and salary distribution**.

---

## Dataset
**Dataset Name:** Adzuna Global Job Listings 2025  
**Source:** Kaggle

The dataset contains job postings with information such as:

- Job Title
- Company
- Job Location
- Job Category / Industry
- Contract Type
- Contract Time
- Minimum Salary
- Maximum Salary
- Job Description
- Geographic Coordinates (Latitude & Longitude)

---

## Project Objectives

- Analyze global job market hiring trends
- Identify industries with the highest hiring demand
- Study salary distribution and compensation patterns
- Compare employment types such as contract and permanent roles
- Identify geographic job distribution
- Generate insights using univariate, bivariate, and multivariate analysis

---

## Technologies Used

- Python
- Pandas
- NumPy
- Seaborn
- Plotly
- Matplotlib
- Jupyter Notebook

---

## Project Workflow

1. Data Collection
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis
4. Interactive Visualization
5. Insight Generation

---

## Data Processing Workflow

The workflow shows how raw job market data is transformed into a structured dataset ready for analysis.

Steps include:

- Import dataset
- Handle missing values
- Clean text data
- Create new features
- Remove duplicate records
- Prepare dataset for analysis

---

## Data Cleaning and Preprocessing

The following preprocessing steps were applied:

### Handling Missing Values
- Missing salary values were filled using median values.
- Missing company or location information was labeled appropriately.

### Salary Processing
- Created **average_salary** column from minimum and maximum salary.

### Duplicate Removal
- Removed duplicate job postings to ensure accuracy.

### Text Standardization
- Cleaned job titles and removed unnecessary characters.

### Feature Engineering
- Created additional variables such as **salary range**.

---

## Exploratory Data Analysis

### Univariate Analysis
- Distribution of salary variables
- Job distribution across countries
- Contract type distribution
- Contract time distribution

Key insight:
- **Contract-based jobs dominate the dataset**
- **Full-time jobs represent the majority of job postings**

---

### Bivariate Analysis
- Salary comparison across countries
- Salary variation by industry
- Contract type vs salary comparison

Key insight:
- Salary levels vary depending on **country and industry demand**.

---

### Multivariate Analysis
- Salary patterns across **country, contract type, and industry**
- Interaction between **job location, salary, and employment type**

Key insight:
- Salary levels are influenced by **multiple factors including location, industry, and employment type**.

---

## Key Insights

- Contract-based employment dominates the job postings.
- Full-time jobs represent the largest share of job opportunities.
- Salary distribution is right-skewed with few high-paying roles.
- Some industries show significantly higher hiring demand.
- Job opportunities are concentrated in specific regions.

---

## Dashboard Visualizations

Interactive visualizations were created using **Plotly**, including:

- Salary distribution
- Industry hiring demand
- Country-wise salary comparison
- Hiring trends over time
- Geographic job location map

---

## Author

**Student Name:** Khadeejath Ramseena KM  
**Course:** AI Driven Data Analytics  
**Institution:** Entri Elevate  
**Guide:** Anu George  

---

## Project Outcome

This project provides insights into **job market dynamics, salary trends, and hiring demand across industries and regions**. The analysis demonstrates how data analytics can help understand workforce trends and support data-driven decision making.
