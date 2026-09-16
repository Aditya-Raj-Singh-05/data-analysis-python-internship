# Data Science with Python Internship – Task 3
### Titanic Dataset: Mini Exploratory Data Analysis (EDA)
**Maincrafts Technology**

## Overview
A deeper mini-EDA on the Titanic dataset, building on Task 2. This adds feature
engineering (age groups, family size) and looks at survival patterns by age
group, port of embarkation, and family size, plus a correlation heatmap of
numeric features.

## Files
- `Titanic_Mini_EDA_Task3.ipynb` — Main Jupyter Notebook with cleaning, feature
  engineering, analysis, and visualizations (fully executed with outputs).
- `titanic.csv` — Dataset used for the analysis.
- `age_histogram_task3.png` — Histogram of passenger ages.
- `correlation_heatmap.png` — Correlation heatmap of numeric features.
- `survival_by_family_size.png` — Bar chart of survival rate by family size.

## Key Steps
1. **Load** the Titanic dataset.
2. **Clean** the data — filled missing `Age` values with the mean, filled
   missing `Embarked` values with the mode, and dropped the sparsely populated
   `Deck`/`Cabin` column.
3. **Engineer features**:
   - `AgeGroup` — Child / Teen / Adult / Senior buckets
   - `FamilySize` — `SibSp` + `Parch` + 1
4. **Analyze**:
   - Survival rate by age group
   - Survival rate by port of embarkation
   - Survival rate by family size
5. **Visualize**:
   - Histogram of passenger ages
   - Correlation heatmap of numeric features
   - Bar chart of survival by family size

## Key Insights
- **Age Group:** Children had the highest survival rate.
- **Port of Embarkation:** Cherbourg passengers survived at the highest rate,
  likely linked to a higher proportion of 1st class travelers.
- **Family Size:** Small families (2-4 members) survived more often than solo
  travelers or very large families.
- **Correlations:** `Pclass` and `Fare` show the strongest relationship with
  `Survived` among the numeric features.

## Tools Used
- Python (Pandas, NumPy)
- Seaborn / Matplotlib
- Jupyter Notebook / Google Colab
