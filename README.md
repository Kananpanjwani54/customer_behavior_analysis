# customer_behavior_analysis
# Data Analytics Project

## Overview

This project demonstrates an end-to-end **data analytics workflow**, starting from raw dataset exploration and cleaning in Python, followed by SQL-based business analysis, and ending with an interactive Power BI dashboard and analytical report.

The project focuses on extracting meaningful insights from data and presenting them in a clear, business-friendly format.

---

## Project Workflow

**Dataset → Python → EDA & Data Cleaning → SQL Analysis → Power BI Dashboard → Report & Insights**

---

## Dataset

The project uses a structured dataset containing business-related records.

The dataset was first loaded into Python for:

* Understanding the dataset structure
* Checking data types
* Identifying missing values
* Detecting duplicate records
* Identifying outliers and inconsistencies
* Understanding distributions and relationships between variables

---

## Tools & Technologies

| Tool                            | Purpose                                     |
| ------------------------------- | ------------------------------------------- |
| **Python**                      | Data loading, exploration and cleaning      |
| **Pandas**                      | Data manipulation and preprocessing         |
| **NumPy**                       | Numerical operations                        |
| **Matplotlib / Seaborn**        | Exploratory Data Analysis and visualization |
| **Microsoft SQL Server (SSMS)** | SQL-based data analysis                     |
| **SQL**                         | Business queries and data analysis          |
| **Power BI**                    | Interactive dashboard and visualization     |
| **Microsoft Excel / CSV**       | Dataset storage and initial inspection      |

---

## Exploratory Data Analysis

EDA was performed using Python to understand the key characteristics of the dataset.

Key activities included:

* Dataset overview and descriptive statistics
* Missing-value analysis
* Duplicate detection
* Distribution analysis
* Categorical and numerical variable analysis
* Correlation analysis
* Identification of important trends and patterns

---

## Data Cleaning

The dataset was cleaned before performing further analysis.

steps included:

* Handling missing values
* Removing duplicate records
* Correcting data types
* Standardizing inconsistent values
* Handling invalid records
* Preparing the final dataset for SQL analysis and visualization

---

## SQL Analysis

The cleaned dataset was imported into **Microsoft SQL Server** and analyzed using SQL queries in SSMS.

The analysis included:

* Filtering and aggregations
* `GROUP BY` and `HAVING`
* `JOIN` operations
* Subqueries
* Common Table Expressions (CTEs)
* Window functions
* Business KPI calculations
* Identifying trends and top-performing categories

The SQL analysis was used to answer relevant business questions and generate insights for the dashboard.

---

## Power BI Dashboard

An interactive Power BI dashboard was created to present the major findings from the analysis.

The dashboard includes:

* Key Performance Indicators (KPIs)
* Trend analysis
* Category-wise performance
* Interactive filters and slicers
* Charts and visual comparisons
* Business-level insights

### Dashboard Preview


```
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/abbe5231-090d-4da3-8d7f-bac61ba7e28b" />


---

## Dashboard Results

The dashboard provides a consolidated view of the dataset and helps identify:

* Overall business performance
* Important trends over time
* Top and low-performing categories
* Key performance indicators
* Relationships between different business dimensions
* Areas requiring further attention

These insights can support **data-driven business decisions**.

---

## Project Structure

```text
Data-Analytics-Project/
│
├── dataset/
│   └── dataset.csv
│
├── python/
│   ├── data_loading.py
│   ├── eda.py
│   └── data_cleaning.py
│
├── sql/
│   └── analysis_queries.sql
│
├── powerbi/
│   └── dashboard.pbix
│
├── report/
│   └── analysis_report.pdf
│
└── README.md
```

---

## How to Run

### 1. Clone the Repository

```bash
git clone <repository-url>
cd Data-Analytics-Project
```

### 2. Install Python Dependencies

```bash
pip install pandas numpy matplotlib seaborn
```

### 3. Run Python Analysis

Open the Python scripts or Jupyter Notebook and run the data loading, EDA, and data cleaning steps.

### 4. SQL Analysis

1. Open **SQL Server Management Studio (SSMS)**.
2. Create or select the required database.
3. Import the cleaned dataset into SQL Server.
4. Open `analysis_queries.sql`.
5. Execute the queries to reproduce the analysis.

### 5. Power BI Dashboard

1. Open the `.pbix` file using Power BI Desktop.
2. Update the data source if required.
3. Refresh the dataset.
4. Explore the interactive dashboard.

---

## Key Skills Demonstrated

* Data Cleaning & Preprocessing
* Exploratory Data Analysis
* Python & Pandas
* SQL & Microsoft SQL Server
* Business Data Analysis
* KPI Development
* Data Visualization
* Power BI Dashboard Development
* Data Storytelling
* Business Insight Generation

---

## Conclusion

This project demonstrates the complete process of converting **raw data into actionable business insights** using Python, SQL, and Power BI.

It combines technical data analysis with business-oriented visualization to support better decision-making.

