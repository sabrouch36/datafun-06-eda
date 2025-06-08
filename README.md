#  Flights Dataset EDA Project

## 👤 Author
Sabri Hamdaoui

##  Date
June 2025

---

##  Project Overview

This project demonstrates a complete Exploratory Data Analysis (EDA) process using Python, pandas, seaborn, and matplotlib on the well-known `flights` dataset (available in seaborn). The goal is to identify long-term trends and seasonal patterns in international airline passenger traffic between 1949 and 1960.

---

##  Environment Setup

The project uses a local virtual environment and the following packages:

- pandas
- seaborn
- matplotlib
- jupyterlab
- pyarrow (dependency for pandas)

###  Installation Steps

```bash
# Create virtual environment
python -m venv .venv

# Activate environment (Windows)
.venv\Scripts\activate

# Or (Mac/Linux)
source .venv/bin/activate

# Install required packages
pip install pandas seaborn matplotlib jupyterlab pyarrow

# Save dependencies
pip freeze > requirements.txt

 Skills Practiced
Using Jupyter Notebooks for interactive analysis

Grouping, pivoting, and transforming data with pandas

Creating effective visualizations with seaborn and matplotlib

Feature engineering (renaming and creating new columns)

Storytelling through visual insights

 Visualizations Included
 Trend of Total Passengers per Year (Line chart)

 Average Monthly Passengers (Bar chart)

 Monthly Passenger Heatmap by Year (Heatmap)

 Project Files
sabri_eda.ipynb: Jupyter notebook with the full analysis

requirements.txt: Project dependencies

.gitignore: To avoid tracking unnecessary files

README.md: This documentation

 Dataset
Source: flights dataset from Seaborn

This dataset includes monthly totals of airline passengers from 1949 to 1960. It contains three columns:

year: Year of observation

month: Month of observation

passengers: Number of airline passengers (renamed to num_passengers)

 Project Status
 Completed and pushed to GitHub
 Follows the structure of Module 6 EDA specification
 Notebook runs without errors and visualizations render correctly


