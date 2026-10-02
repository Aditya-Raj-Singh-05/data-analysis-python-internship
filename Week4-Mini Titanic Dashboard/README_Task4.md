# Data Science with Python Internship – Task 4
### Mini Visualization Dashboard (Matplotlib + Seaborn) — Titanic Dataset
**Maincrafts Technology**

## Overview
A single-notebook mini dashboard that cleans the Titanic dataset, engineers
two simple features, and tells a visual data story using six charts (one
more than the required five), each followed by a short written insight.

## Dataset
Titanic dataset (`titanic.csv`), same schema as the Kaggle Titanic dataset.

## How to Run
1. Open `Titanic_Dashboard_Task4.ipynb` in Jupyter Notebook or Google Colab.
2. Make sure `titanic.csv` is in the same folder as the notebook (or update
   the path in the "Load the Dataset" cell).
3. Run all cells top to bottom. Charts are saved automatically into the
   `images/` folder as they're generated.

## Files
- `Titanic_Dashboard_Task4.ipynb` — Main notebook (data prep, features, 6
  charts, Markdown narration, fully executed with outputs).
- `titanic.csv` — Dataset used for the analysis.
- `images/` — Exported chart PNGs:
  - `01_age_histogram.png`
  - `02_survival_by_gender.png`
  - `03_fare_by_class_boxplot.png`
  - `04_age_vs_fare_scatter.png`
  - `05_correlation_heatmap.png`
  - `06_survival_facet_by_sex.png` (bonus facet grid)

## Data Prep
- Loaded CSV into pandas, standardized column names to the Kaggle convention.
- Filled missing `Age` with the median, missing `Embarked` with the mode.
- Dropped the sparsely populated `Deck`/`Cabin` column.
- Engineered `FamilySize` (`SibSp` + `Parch`) and `AgeGroup` (Child / Teen /
  YoungAdult / Adult / Senior).

## Dashboard Charts
1. **Histogram** — Age distribution
2. **Bar chart** — Survival rate by gender
3. **Boxplot** — Fare distribution by passenger class
4. **Scatterplot** — Age vs. Fare, colored by survival
5. **Heatmap** — Correlation of numeric columns
6. **(Bonus) Facet grid** — Survival by class, split by gender

## Key Insights
- **Gender** was the strongest survival factor — women survived far more
  often than men, at every class level.
- **Class/Fare** strongly correlate with survival — wealthier, higher-class
  passengers had a clear advantage.
- **Age** has a mild effect (children fared slightly better) but is weaker
  than gender or class.
- The class effect on survival is much steeper for men than for women.

## Tools Used
- Python (Pandas, NumPy)
- Seaborn / Matplotlib
- Jupyter Notebook / Google Colab
