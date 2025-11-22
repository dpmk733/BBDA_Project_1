# BBDA Project 1: Employee Salary Analytics

![Project Status](https://img.shields.io/badge/Status-Development-yellow)
![Branch](https://img.shields.io/badge/Branch-dev-blueviolet)
![Language](https://img.shields.io/badge/Python-Jupyter-blue)

## 📖 Executive Summary
This project serves as the inaugural data analysis initiative for BBD (BBDA Project 1). It focuses on the end-to-end analysis of **Employee Salary Data**, encompassing the full data lifecycle from extraction to final exploratory analysis.

The codebase represents a consolidated workflow, merged from distinct feature branches (`data_extraction`, `data_transformation`, `data_visualization`) into a unified execution pipeline.

### 🎯 Key Analytical Objectives
* **Data Ingestion:** Loading and validating raw employee records.
* **Data Wrangling:** Cleaning and transforming the "Big Blue Dataset" for analytical readiness.
* **Exploratory Data Analysis (EDA):** Visualizing salary distributions and correlations.
* **Orchestration:** Executing the full pipeline via a central runner.

---

## 📂 Repository Structure
The project is currently organized as a flat directory containing all analysis notebooks and the raw dataset.

```text
BBDA_Project_1/
│
├── 📄 employee_salary_dataset.csv                   # Raw Data Source
│
├── 📓 BBDA_Project_1 - Data Extraction Branch.ipynb # Step 1: Ingestion Logic
├── 📓 bigbluedataset.ipynb                          # Step 2: Transformation & Cleaning
├── 📓 Exploration.ipynb                             # Step 3: Visualization & EDA
├── 📓 main_run.ipynb                                # 🟢 ENTRY POINT: Pipeline Orchestrator
│
└── 📝 README.md                                     # Project Documentation
