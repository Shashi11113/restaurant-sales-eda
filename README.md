# Restaurant Sales Data Cleaning & EDA

This project demonstrates an end-to-end **data cleaning and exploratory data analysis (EDA)** workflow using a dirty restaurant sales dataset from Kaggle.

The emphasis is on **correct data reasoning**, not just visualization.

---

## Project Overview

**Objectives**
- Clean a real-world messy dataset
- Handle missing data logically
- Perform exploratory data analysis
- Visualize insights using pandas-only plotting

**Dataset**
- ~17,500 original rows
- Reduced to clean, analysis-ready transactions after validation

---

## Data Cleaning Summary

1. Standardized column names
2. Audited missing values at the row level
3. Dropped unrecoverable rows
4. Filled categorical values using group-aware logic
5. Derived missing numeric values mathematically
6. Ensured correct data types

All steps are documented in the notebook.

---

## Exploratory Data Analysis

The notebook explores:
- Revenue by category
- Order volume by category
- Revenue vs quantity (clustered bars)
- Monthly revenue trends
- Price distributions
- Price comparison by category
- Price vs quantity relationship

---

## Repository Structure

```
├── restaurant_sales_cleaning_eda.ipynb
├── README.md
├── requirements.txt
```

---

## Setup Instructions

```bash
pip install -r requirements.txt
jupyter notebook
```

Open `restaurant_sales_cleaning_eda.ipynb`.

---

## Tools & Libraries

- Python
- pandas
- numpy
- matplotlib
- jupyter
- kagglehub

---

## Author
Sadam Hashi
