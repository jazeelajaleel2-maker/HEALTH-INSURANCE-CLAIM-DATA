# 🏥 Healthcare Insurance Fraud Analysis

## 📌 Project Overview

This project focuses on analyzing healthcare insurance claim data to identify patterns and relationships related to fraudulent and non-fraudulent claims using **Exploratory Data Analysis (EDA)**.

Python libraries are used to clean, analyze, and visualize the dataset to understand claim amounts, claim status, insurance types, and provider specialties.

## 🎯 Project Objectives

- Understand healthcare insurance claim data.
- Identify fraudulent and non-fraudulent claims.
- Analyze claim amounts and claim status.
- Examine factors related to insurance fraud.
- Identify patterns using data visualization.

## 🛠️ Technologies & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📂 Project Workflow

1. **Data Loading** – Imported the healthcare insurance dataset.
2. **Data Understanding** – Checked dataset information, shape, columns, and data types.
3. **Data Quality Checks** – Identified missing values, duplicate records, and invalid values.
4. **Data Cleaning** – Handled missing values using mode and a predefined value.
5. **Exploratory Data Analysis (EDA)**:
   - Univariate Analysis
   - Bivariate Analysis
   - Multivariate Analysis
6. **Data Visualization** – Created different charts to identify patterns and relationships.
7. **Data Exporting** – Saved the cleaned dataset as a CSV file.

## 📊 Key Analysis & Findings

- Out of 10,000 claims, 829 were fraudulent and 9,171 were non-fraudulent.
- The overall fraud rate was 8.29%.
- Most claim amounts were relatively low, with a few high-value claims.
- Medicare had the highest number of claims.
- Internal Medicine had the highest number of claims among provider specialties.
- Fraudulent claims generally showed a higher median claim amount.
- Emergency visits showed the highest fraud rate.
- General Practice showed the highest fraud rate among provider specialties.
- Claim Amount and Approved Amount showed a strong positive correlation of 0.94.

## 📈 Visualizations

The project includes:

- Count Plot
- Histogram
- Box Plot
- Bar Plot
- Scatter Plot
- Correlation Heatmap

## 💡 Recommendations

- Carefully verify high-value insurance claims.
- Monitor suspicious claim patterns.
- Review rejected and pending claims carefully.
- Monitor healthcare providers with unusual claim patterns.

## 📁 Project Files

- `Copy_of_first_project.ipynb` – Jupyter Notebook containing the complete analysis.
- `Insurance_Fraud_Cleaned.csv` – Exported cleaned dataset.

## 🏁 Conclusion

This project helped identify important patterns related to healthcare insurance fraud through Exploratory Data Analysis using Python. The analysis highlights relationships between claim amounts, claim status, visit types, and provider specialties.

**This project is focused on data analysis and visualization, not building a machine learning fraud prediction model.**

---

**Project Type:** Exploratory Data Analysis (EDA)  
**Domain:** Healthcare / Insurance  
**Created using:** Python
