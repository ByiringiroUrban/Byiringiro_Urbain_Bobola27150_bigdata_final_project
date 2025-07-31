# Byiringiro_Urbain_Bobola27150_bigdata_final_project

# Health Analytics  
**Course:** INSY 8413 | Introduction to Big Data Analytics  
**University:** Adventist University of Central Africa (AUCA)  
**Lecturer:** Eric Maniraguha  
**Student:** Byiringiro Urbain Bobola  

---

##  Table of Contents

- [ Project Overview](#project-overview)
- [ Dataset Description](#dataset-description)
- [ Python Analysis (Jupyter)](#python-analysis-jupyter)
- [ Power BI Dashboard](#power-bi-dashboard)
- [ How to Run This Project](#how-to-run-this-project)
- [ Repository Structure](#repository-structure)
- [ Academic Integrity](#academic-integrity)

---

##  Project Overview

This project focuses on **predicting student injuries and dropouts** using historical health data collected from multiple years. Using both Python and Power BI, the analysis:
- Identifies key causes and severities of student injuries
- Segments the population by age and risk category
- Applies machine learning to predict patterns and groupings
- Offers actionable insights through interactive dashboards

**Sector:** Education + Health  
**Goal:** Enable data-driven decision-making for student health and dropout prevention.

---

##  Dataset Description

- **Format:** CSV (structured)
- **Size:** 3,094 rows × 13 columns
- **Source:** Cleaned public dataset (non-Kaggle) containing injury records

**Main Columns:**
- `Period`: Year or date range of incident
- `Data_value`: Numeric value of indicator
- `Cause`, `Severity`, `Age`, `Population`: Categorical descriptors
- `Lower_CI`, `Upper_CI`: Confidence interval values

---

##  Python Analysis (Jupyter)

All exploratory data analysis and machine learning was done in Python.

###  Key Steps:
- Data Cleaning (handling nulls, types)
- Descriptive Stats (`df.describe()`)
- Visual Analysis:
  - Correlation Heatmap
  - Distribution Plots
- Feature Scaling & Train-Test Split
- Model Training:
  - Logistic Regression
  - Random Forest Classifier
- Model Evaluation:
  - Accuracy & Confusion Matrix
  - Feature Importance Ranking
- KMeans Clustering:
  - Segments student risk profiles
  - Visualized using PCA

---

##  Power BI Dashboard

An interactive **Power BI dashboard** was created to visualize key insights.

###  Dashboard Features:
- KPIs: Total, Average, Max, Min `Data_value`
- Line Chart: Trends over `Period`
- Bar Chart: Injury `Cause` by Severity
- Pie: Age distribution
- Matrix: Cause vs Severity Table
- Slicers: Filter by Age, Cause, Severity, Period

**File:** `analysis.pbix`

---

##  How to Run This Project

###  Run Python Notebook:
1. Clone this repo
2. Open `analysis.ipynb` in Jupyter
3. Run cells sequentially (requires `pandas`, `sklearn`, `matplotlib`, `seaborn`)

   ---

##  Some project screenshoot images 

![image2](https://github.com/user-attachments/assets/56b78b5f-43ce-4c6c-8315-fa7fd4bec530)
![image9](https://github.com/user-attachments/assets/c9dae531-a372-4501-ab4f-5a1f6bf3a2e5)
![image8](https://github.com/user-attachments/assets/326d9217-77a7-4eee-8b54-ec01eeada823)
![image5](https://github.com/user-attachments/assets/5fd98a78-daf8-41d9-b323-9890f2e11173)
![visual4](https://github.com/user-attachments/assets/28cb0575-b7e2-4770-a059-e6e9e2ebdfe0)

```bash
pip install pandas scikit-learn matplotlib seaborn
