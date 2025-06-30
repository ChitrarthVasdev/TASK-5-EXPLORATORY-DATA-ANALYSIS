# TASK-5-EXPLORATORY-DATA-ANALYSIS

This repository contains an exploratory data analysis (EDA) project on the Titanic passenger dataset. The goal is to analyze, visualize, and understand the key factors influencing passenger survival using **Python (Pandas, Matplotlib, Seaborn)**.

---

## 📌 Objective

- Perform exploratory data analysis (EDA) on the Titanic dataset.
- Identify data quality issues (missing values, outliers).
- Understand variable distributions and relationships.
- Clean the data to prepare it for modeling.
- Generate insights for predictive modeling.

---

## 📦 Dataset

- `train.csv`: Passenger data with survival labels (used for EDA only).

---

## 🖥️ Platform Used

- **Google Colab**: Interactive Jupyter notebook environment for Python-based analysis.

---

## 📊 Tools & Libraries

- **Python** 3.x
- **Pandas** for data manipulation
- **NumPy** for numerical operations
- **Matplotlib** and **Seaborn** for visualization

---

## 📌 EDA Process

### 1️⃣ Data Loading
- Load Titanic dataset using Pandas.
- Inspect structure using `.info()` and `.head()`.

### 2️⃣ Data Cleaning
- Handle missing values:
  - Impute `Age` and `Fare` with median.
  - Fill `Embarked` with mode.
- Encode categorical features:
  - Convert `Sex` to numeric.
- Drop irrelevant or high-cardinality columns:
  - `Cabin`, `Name`, `Ticket`.

### 3️⃣ Data Exploration & Visualization
- Descriptive statistics using `.describe()`.
- Missing value summary.
- Value counts for categorical columns.
- Histograms of numerical features.
- Boxplots for outlier detection.
- Correlation heatmap.
- Pairplots to study relationships.
- Scatterplots of numerical features vs target (`Survived`).
- Countplots for categorical features.
- Boxplots comparing numerical features by survival status.

### 4️⃣ Insights & Report
- PDF-style written analysis summarizing:
  - Data quality
  - Feature distributions
  - Relationships with survival
  - Recommended preprocessing and modeling strategies

---

## ✅ Cleaned Dataset

After EDA and basic cleaning, the dataset is saved as:

titanic_cleaned_dataset.csv (ADDED IN REPOSITORY)

## AUTHOR : CHITRARTH VASDEV
