# 📊 Pandas Mastery Projects

> *From raw, messy data to clean, insight-driven results — built entirely with Python & Pandas.*

---

## 🚀 Overview

This portfolio showcases two end-to-end data projects that demonstrate professional-grade data wrangling, exploratory analysis, and visualization skills. Each project reflects real-world workflows that data analysts encounter daily — handling dirty data and turning it into actionable intelligence.

---

## 📁 Projects

---

### 🧹 Project 1 — Data Cleaning with Pandas
**`Data_Cleaning_PANDAS.ipynb`**

> *"Garbage in, garbage out — unless you know how to clean it."*

A complete data cleaning pipeline applied to a real-world **Customer Call List** dataset. This project showcases the ability to transform an inconsistent, error-ridden raw dataset into a structured, query-ready format.

#### 🔧 What Was Done:
- **Duplicate Removal** — Identified and dropped redundant records to ensure data integrity
- **Column Pruning** — Eliminated irrelevant features to streamline the dataset
- **String Sanitization** — Used `str.strip()` to remove trailing characters (`/`, `_`, `...`) from name fields
- **Phone Number Formatting** — Applied regex and lambda functions to standardize numbers into `XXX-XXX-XXXX` format
- **Address Parsing** — Split a single compound address column into `Street_Address`, `State`, and `Zip_Code` using `str.split()` with `expand=True`
- **Value Standardization** — Normalized inconsistent categorical values (`Yes/No → Y/N`)
- **Null Handling** — Distinguished between `N/a` strings and true `NaN` values; handled both systematically
- **Targeted Row Filtering** — Used index-based loops to drop contacts marked as "Do Not Contact" and those with missing phone numbers
- **Index Reset** — Cleaned up the DataFrame index after all deletions

#### 💡 Key Skills Demonstrated:
`Pandas` · `Regex` · `Lambda Functions` · `String Methods` · `Data Integrity` · `ETL Logic`

---

### 🌍 Project 2 — Exploratory Data Analysis (EDA) with Pandas
**`EDA-PANDAS-Project.ipynb`**

> *"Data is only as valuable as the story you extract from it."*

A full exploratory analysis of a **World Population Dataset**, uncovering global demographic trends across decades using statistical summaries and rich visualizations.

#### 🔍 What Was Done:
- **Display Optimization** — Configured Pandas to suppress scientific notation for cleaner numeric output
- **Dataset Profiling** — Used `.info()`, `.describe()`, `.isnull().sum()`, and `.nunique()` for a complete structural audit
- **Ranking & Sorting** — Identified the world's most populated countries in 2022 using `.sort_values()`
- **Correlation Analysis** — Computed a full numeric correlation matrix to reveal relationships between population metrics across decades
- **Heatmap Visualization** — Rendered a `Seaborn` annotated heatmap for intuitive correlation interpretation
- **Continent-Level Aggregation** — Used `.groupby('Continent').mean()` to compare regional population averages
- **Time-Series Trend Lines** — Transposed continent-level data to plot multi-decade population growth curves per region
- **Box Plot Distribution** — Visualized population spread and outliers per decade using `.boxplot()`
- **Data Type Filtering** — Used `.select_dtypes()` to isolate numeric vs. categorical columns

#### 💡 Key Skills Demonstrated:
`EDA` · `Seaborn` · `Matplotlib` · `GroupBy Aggregations` · `Correlation Analysis` · `Data Visualization` · `Time-Series Trends`

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3 | Core language |
| Pandas | Data manipulation & cleaning |
| Matplotlib | Plotting & visualization |
| Seaborn | Statistical heatmaps |
| Jupyter Notebook | Interactive development environment |

---

## 📈 Why These Projects Matter

In any data-driven organization, the ability to **clean messy data** and **extract meaningful patterns** is foundational. These projects mirror exactly what a Data Analyst does on Day 1:

- Receive raw, imperfect data
- Apply systematic cleaning & transformation
- Surface insights through EDA
- Communicate findings through visuals

Every step in both notebooks reflects deliberate, production-minded thinking — not just making the code work, but making it *right*.

---

## 📬 Let's Connect

If you're looking for someone who can take data from chaos to clarity — let's talk.

---

*Built with curiosity, cleaned with precision, analyzed with purpose.*
