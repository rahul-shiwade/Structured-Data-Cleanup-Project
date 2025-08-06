
#  Structured Data Cleanup Project

This project demonstrates the process of cleaning and preprocessing a structured dataset using Python and popular data science libraries such as `pandas`, `seaborn`, and `scikit-learn`.

##  Objective

The goal of this project is to transform raw, messy tabular data into a clean and analysis-ready format. It involves identifying and addressing common data quality issues such as missing values, inconsistent data types, duplicate records, and outliers.

---

##  Key Steps Performed

###  1. Initial Data Exploration
- Loaded the dataset using `pandas`
- Previewed rows, data types, and summary statistics
- Identified missing data and irregular patterns

###  2. Data Cleaning
- **Handled Missing Values**:
  - Visualized with heatmaps
  - Used `ffill`, `bfill`, and `SimpleImputer` (mean, median, mode)
- **Removed Duplicates**
- **Fixed Incorrect Data Types**

###  3. Outlier Detection
- Created boxplots (e.g., on `Quantity`)
- Used IQR method to detect and flag extreme values

###  4. Feature Scaling
- Applied `StandardScaler` or `MinMaxScaler` to normalize numerical features

---

##  Tools & Libraries

- `pandas` for data manipulation
- `seaborn` & `matplotlib` for visualization
- `scikit-learn` for imputation and scaling

---

## Outcome

- The cleaned dataset is free from missing values, outliers, and formatting issues.
- It’s saved as `cleaned_dataset.csv` and is ready for analysis or machine learning workflows.

---

##  Files Included

- `Structured Data Cleanup Project.ipynb` — Jupyter notebook with full workflow
- `cleaned_dataset.csv` 
- `README.md` 

---



This project is suitable for anyone learning about data preprocessing, especially those preparing datasets for modeling or analysis in Python.

