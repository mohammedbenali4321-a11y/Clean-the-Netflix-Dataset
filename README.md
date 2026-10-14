# Clean-the-Netflix-Dataset
Clean the Netflix Dataset use python
# Analysing Netflix Data Cleaning

![Python](https://img.shields.io/badge/Python-Data%20Analysis-blue?style=for-the-badge)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Cleaning-purple?style=for-the-badge)
![Matplotlib](https://img.shields.io/badge/Visualization-Matplotlib-orange?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-red?style=for-the-badge)

A data cleaning and preprocessing project focused on preparing the Netflix dataset for analysis using **Python, Pandas, and Jupyter Notebook**.

This project demonstrates real-world data cleaning workflows including handling missing values, fixing mixed data types, and transforming raw data into analysis-ready datasets.

---

## Project Overview

Raw datasets are rarely clean.  
This project focuses on transforming messy Netflix content data into a structured and usable format suitable for analytics and visualization.

Key objectives:

- Identify and handle missing values  
- Fix inconsistent/mixed-type columns  
- Convert date columns into datetime format  
- Create derived analytical features  
- Prepare clean dataset for further analysis

---

## Tech Stack

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

## Project Structure

```md
Analysing-Netflix-Data-Cleaning/
│
├── data/
│ ├── netflix_titles.csv
│ └── cleaned-data.csv
│
├── notebook/
│ └── netflix_data_cleaning.ipynb
│
└── README.md
```

---

## Data Cleaning Workflow

```mermaid
flowchart LR
    A[Raw Netflix Dataset] --> B[Data Inspection]
    B --> C[Handle Missing Values]
    C --> D[Fix Mixed-Type Columns]
    D --> E[Convert Date Columns]
    E --> F[Feature Engineering]
    F --> G[Cleaned Dataset Ready]

    style A fill:#1f77b4,color:#fff
    style B fill:#9467bd,color:#fff
    style C fill:#2ca02c,color:#fff
    style D fill:#ff7f0e,color:#fff
    style E fill:#17becf,color:#fff
    style F fill:#e377c2,color:#fff
    style G fill:#d62728,color:#fff
```

## Cleaning Steps Performed

### 1️Missing Values Handling

- Filled categorical columns using **"Unknown"** or **mode values**
- Verified null counts **column-wise**
- Ensured dataset consistency after imputation

---

### Mixed-Type Column Fix

- Cleaned the `duration` column by splitting into:
  - **Numeric duration value**
  - **Duration type** (Minutes / Seasons)
- Standardized data types for analysis readiness

---

### Datetime Conversion

- Converted `date_added` into proper **datetime format**
- Extracted new analytical features:
  - `year_added`
  - `month_added`
  - `month_name`

---

### Data Validation

- Verified column datatypes
- Removed inconsistencies and formatting issues
- Saved a fully cleaned dataset for downstream analysis

---

## Output

A cleaned and structured dataset ready for:

- Exploratory Data Analysis (EDA)
- Data Visualization
- Dashboard Creation
- Business Insights

---

## Project Source

This project is inspired by the learning project from **roadmap.sh**:

</> <https://roadmap.sh/projects/cleaning-netflix-dataset>

Implementation and analysis were completed **independently** as part of learning real-world data analytics workflows.

---

## Future Improvements

- Content trend analysis
- Genre popularity insights
- Dashboard using **Power BI / Tableau**
- Time-series visualization

---

## Learning Outcome

This project strengthened understanding of:

- Real-world data preprocessing
- Pandas data transformation
- Analytical thinking
- Structuring analytics projects for GitHub portfolios

---

## Report

This project is created only for educational and analytical purposes.  
All analysis, visualizations, and insights are independently performed using publicly available datasets and tools.  

Plagiarism is strictly prohibited.  

---

## Connect

If you have feedback or suggestions, feel free to **connect** or open an **issue** in this repository!

⭐ If you found this project helpful, consider giving it a star!
