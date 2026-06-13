# DATA-ANALYTICS-TASK2
# ApexPlanet Internship - Task 2: Exploratory Data Analysis (EDA) & Business Intelligence

## 📌 Project Overview
This repository contains the complete deliverables for **Task 2** of the Data Analytics track at ApexPlanet Software Pvt. Ltd. The primary objective is to take the cleaned dataset from Task 1 (`Cleaned_Sales_Dataset.xlsx`) and apply **Advanced Exploratory Data Analysis (EDA)** using Python, execute structural analytical queries via an **SQL Engine**, and assemble a professional **Executive BI Dashboard Mock-up**.

---

## 🛠️ Tech Stack & Dependencies
The entire automation and analytical pipeline were built using the following core tools:
* **Programming Language:** Python 3.10+
* **Libraries Used:** * `pandas` & `numpy` (Data manipulation and feature filtering)
  * `matplotlib` & `seaborn` (Statistical plotting and graphics compilation)
  * `sqlite3` (In-memory SQL Relational Database processing)
  * `python-pptx` (Automated programmatic PowerPoint layout construction)
* **IDE/Environment:** VS Code Terminal Ecosystem

---

## 📂 Repository Structure
```text
├── Cleaned_Sales_Dataset.xlsx         # Input Cleaned Dataset (1,000 transaction rows)
├── task2_complete_eda.py              # Main Python script for Univariate & Multivariate EDA
├── run_sql_queries.py                 # Automated SQL pipeline script executing SQL BI queries
├── generate_ppt.py                    # Programmatic layout generator for the PPT presentation
├── Dashboard_Mockup.pptx              # Programmatically compiled Executive BI Slide Deck
├── 1_sales_distribution_histogram.png # EDA Graph: Total Sales Distribution Histogram
├── 2_top_5_products_revenue.png       # BI Graph: Top 5 items ranking by total sales
└── 3_multivariate_correlation_heatmap # Multivariate Graph: Features Interaction Matrix Heatmap
