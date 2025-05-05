# AI/ML Foundations: Heart Failure Data Exploration 

Welcome to my AI/ML Foundations project — a deep dive into Python, data wrangling, and exploratory data analysis, using real-world heart failure data from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/519/heart+failure+clinical+records).

This project is part of my foundational coursework in AI/ML and sets the stage for more advanced work in model development and healthcare analytics.

---

## Dataset

**Name**: Heart Failure Clinical Records  
**Source**: UCI ML Repository  
**Samples**: 299 patients  
**Features**: 15 clinical features + 1 binary target (diagnosis)

Features include:
- Age, ST-segment depression, exercise induced angina, maximum heart rate during exercise, etc.
- Target variable: 'Diagnosis of Heart Disease' (0 = no presence, 1-4 = presence)

---

## Skills Practiced

- Python basics (functions, loops)
- Pandas for data wrangling
- Exploratory Data Analysis (EDA)
- Visualization with seaborn & matplotlib
- Statistical analysis (correlation, distributions)
- 0Feature importance heuristics (basic)

---

## Project Structure

```bash
ai-ml-foundations/
├── data/
│   └── heart_failure_clinical_records_dataset.csv
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda.ipynb
│   ├── 03_stats_analysis.ipynb
├── README.md
└── .gitignore
