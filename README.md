# Employee Data Cleaning & Analysis using Pandas

## Project Overview
This project focuses on cleaning and analyzing a real-world employee dataset using **Python and Pandas**.  
The objective is to handle missing values, inconsistent data formats, and invalid records, and then perform exploratory data analysis (EDA) to extract meaningful business insights.

This project demonstrates practical **data cleaning, preprocessing, and analysis skills** required for data analyst roles.

---

## Project Objective
- Clean raw employee data with missing and inconsistent values
- Standardize numeric and categorical fields
- Perform exploratory data analysis
- Generate insights related to employee demographics, salary, experience, and performance

---

## Dataset Description
- Dataset Type: Employee master data
- Data Format: Excel (`.xlsx`)
- Number of Records: ~200
- Key Columns:
  - Employee ID
  - Name
  - Age
  - Salary
  - Department
  - City
  - Experience
  - Joining Date
  - Manager
  - Performance Rating

---

## Tools and Technologies Used
- Python
- Pandas
- NumPy
- Jupyter Notebook / Google Colab
- GitHub (Version Control)

---

## Project Workflow
1. Imported raw employee data using Pandas
2. Performed initial inspection using `head()`, `info()`, and `describe()`
3. Identified data quality issues such as missing values and incorrect data types
4. Cleaned and standardized numeric and categorical columns
5. Handled missing values using appropriate techniques
6. Performed exploratory data analysis (EDA)
7. Derived business insights from cleaned data

---

## Data Quality Issues Identified
- Missing values in columns such as Salary, Department, City, and Experience
- Incorrect data types in numeric columns like Age and Salary
- Inconsistent categorical values (e.g., FINANCE, Finance, finance)
- Invalid values such as negative experience

---

## Data Cleaning Steps Performed
- Converted salary and age columns to numeric format
- Handled missing values using mean, median, or mode where appropriate
- Standardized department and city names
- Removed or corrected invalid records (e.g., negative experience values)
- Converted joining date to datetime format

---

## Key Analysis Performed
- Employee count by department
- Average salary by department
- Distribution of employee age
- Experience vs salary relationship
- Performance rating distribution

---

## Key Insights
- Most employees fall within the 25–45 age group
- Employees with higher experience generally earn higher salaries
- Certain departments have higher employee concentration
- Data quality issues were more frequent in specific columns, highlighting the importance of preprocessing

---

## Data Quality Improvement Summary

| Metric | Before Cleaning | After Cleaning |
|------|----------------|---------------|
| Missing Values | High | Minimal |
| Data Types | Inconsistent | Standardized |
| Categorical Values | Mixed case | Normalized |

---

## Project Structure


pandas-employee-data-analysis/
│
├── data/
│ └── raw/ # Raw employee dataset
│
├── notebooks/
│ └── employee_data_cleaning_analysis.ipynb
│
├── README.md




---

## How to Run the Project
1. Clone the repository
2. Open the notebook in Jupyter Notebook or Google Colab
3. Install required libraries:


4. Run the notebook cells sequentially to view the analysis

---

## Skills Demonstrated
- Python Programming
- Pandas Data Analysis
- Data Cleaning and Preprocessing
- Handling Missing Values
- Exploratory Data Analysis (EDA)
- Data Quality Assessment
- Business Insight Generation

---

## Future Improvements
- Add data visualizations using Matplotlib and Seaborn
- Perform advanced statistical analysis
- Extend analysis to employee attrition prediction
