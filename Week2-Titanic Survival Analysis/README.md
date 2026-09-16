# Data Science with Python Internship – Task 2
### Titanic Dataset: Survival Analysis & Visualization
**Maincrafts Technology**

## Overview
This project analyzes the classic Titanic dataset to uncover survival patterns
based on gender, passenger class, and age, using Python, Pandas, Seaborn, and
Matplotlib.

## Files
- `Titanic_Survival_Analysis.ipynb` — Main Jupyter Notebook with data cleaning,
  analysis, and visualizations (fully executed with outputs).
- `titanic.csv` — Dataset used for the analysis.
- `survival_by_gender.png` — Bar chart of survival rate by gender.
- `survival_by_class.png` — Bar chart of survival rate by passenger class.
- `age_histogram.png` — Histogram of passenger ages.
- `survival_by_agegroup.png` — Bonus bar chart of survival rate by age group.

## Key Steps
1. **Load** the Titanic dataset.
2. **Clean** the data — filled missing `Age` values with the median, filled
   missing `Embarked` values with the mode, and dropped the sparsely populated
   `Deck` column.
3. **Analyze**:
   - Who survived more: males or females?
   - Did passenger class affect survival chances?
   - What was the survival rate by age group?
4. **Visualize** using Seaborn/Matplotlib:
   - Bar chart of survival by gender
   - Bar chart of survival by class
   - Histogram of passenger ages
   - (Bonus) Bar chart of survival by age group

## Key Insights
- **Gender:** Women survived at a much higher rate than men (~74% vs ~19%).
- **Class:** 1st class passengers had the highest survival rate; 3rd class the
  lowest.
- **Age:** Children had the best survival odds among all age groups.

## Tools Used
- Python (Pandas, NumPy)
- Seaborn / Matplotlib
- Jupyter Notebook / Google Colab
