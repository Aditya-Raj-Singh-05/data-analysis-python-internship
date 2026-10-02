# Data Science / Analysis with Python Internship - Maincrafts Technology

Internship tasks completed as part of the Data Science/Analysis with Python internship at Maincrafts Technology.

## Week 1 - Task 1: Student Performance Dataset

Explored the [Student Performance dataset](https://archive.ics.uci.edu/dataset/320/student+performance) (`student-mat.csv`) using pandas, matplotlib and seaborn.

**What's in this task:**
- Loading and cleaning the dataset (checked for missing values and duplicates)
- Analysis: average final grade, students scoring above 15, study time vs grade correlation, gender comparison
- Visualizations: histogram of grades, scatterplot of study time vs grades, bar chart of average grade by gender

**Files:**
- `student_analysis.ipynb` - the notebook with all the analysis
- `student-mat.csv` - the dataset used

**Tools used:** Python, pandas, numpy, matplotlib, seaborn, Jupyter Notebook

---

## Week 2 - Task 2: Titanic Survival Analysis

Analyzed the Titanic dataset to look at survival patterns by gender, class and age.

**What's in this task:**
- Cleaning: filled missing `Age` with the median, filled missing `Embarked` with the mode, dropped the sparsely populated `Deck` column
- Analysis: survival rate by gender, by passenger class, and by age group
- Visualizations: bar chart of survival by gender, bar chart of survival by class, histogram of passenger ages, bonus bar chart of survival by age group

**Files:**
- `Titanic_Survival_Analysis.ipynb` - the notebook with all the analysis
- `titanic.csv` - the dataset used
- `survival_by_gender.png`, `survival_by_class.png`, `age_histogram.png`, `survival_by_agegroup.png` - exported charts

**Tools used:** Python, pandas, numpy, matplotlib, seaborn, Jupyter Notebook

---

## Week 3 - Task 3: Titanic Mini EDA

A deeper exploratory pass on the Titanic dataset, building on Task 2 with new features and additional groupings.

**What's in this task:**
- Cleaning: filled missing `Age` with the mean, filled missing `Embarked` with the mode, dropped the `Deck`/`Cabin` column
- Feature engineering: `AgeGroup` (Child/Teen/Adult/Senior) and `FamilySize` (`SibSp` + `Parch` + 1)
- Analysis: survival rate by age group, by port of embarkation, and by family size
- Visualizations: histogram of ages, correlation heatmap of numeric features, bar chart of survival by family size

**Files:**
- `Titanic_Mini_EDA_Task3.ipynb` - the notebook with all the analysis
- `titanic.csv` - the dataset used
- `age_histogram_task3.png`, `correlation_heatmap.png`, `survival_by_family_size.png` - exported charts

**Tools used:** Python, pandas, numpy, matplotlib, seaborn, Jupyter Notebook

---

## Week 4 - Task 4: Titanic Mini Visualization Dashboard

A mini data-visualization dashboard in a single notebook, pulling together six chart types and short written insights under each one.

**What's in this task:**
- Data prep: filled missing `Age`/`Embarked`, dropped `Deck`/`Cabin`, engineered `FamilySize` (`SibSp` + `Parch`) and `AgeGroup` (Child/Teen/YoungAdult/Adult/Senior)
- Dashboard charts: histogram of age, bar chart of survival by gender, boxplot of fare by class, scatterplot of age vs fare colored by survival, correlation heatmap, bonus facet grid of survival by class split by gender
- Markdown narration throughout (Overview, Cleaning, Features, Visualizations, Insights, Conclusion) with a short takeaway under each chart

**Files:**
- `Titanic_Dashboard_Task4.ipynb` - the notebook with all the analysis
- `titanic.csv` - the dataset used
- `images/` - exported charts (`01_age_histogram.png` through `06_survival_facet_by_sex.png`)

**Tools used:** Python, pandas, numpy, matplotlib, seaborn, Jupyter Notebook

---

