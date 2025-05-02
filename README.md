# Exploratory-analysis-EDA
# Titanic Dataset Exploratory Data Analysis (EDA)

This repository contains an exploratory data analysis (EDA) of the Titanic dataset, a popular dataset for practicing machine learning and data analysis techniques.

## 📁 Repository Structure

├── data/
│ └── titanic.csv
├── notebooks/
│ └── titanic_eda.ipynb
├── reports/
│ └── titanic_EDA.pdf
├── README.md


> Note: Please unzip the dataset if it's currently provided as a `.zip` file.

## 📌 Project Overview

The objective of this project is to perform an in-depth exploratory data analysis on the Titanic dataset to understand the underlying structure, identify patterns, and draw insights that could be helpful for predictive modeling.

## 📊 Dataset Description

- **Source:** [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic)
- **Features Include:**
  - `PassengerId`
  - `Survived` (Target variable)
  - `Pclass`
  - `Name`
  - `Sex`
  - `Age`
  - `SibSp`
  - `Parch`
  - `Ticket`
  - `Fare`
  - `Cabin`
  - `Embarked`

## 🛠️ Tools and Libraries Used

- Python
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🔍 Key Analysis Performed

- Handling missing values
- Univariate and bivariate analysis
- Correlation heatmaps
- Grouped statistics and pivot tables
- Feature-wise survival rate analysis
- Visualization using bar plots, histograms, and boxplots

## 📌 Key Insights

- Females had a significantly higher survival rate than males.
- Passengers in higher classes (`Pclass=1`) had better chances of survival.
- Children (`Age < 10`) had a higher survival rate than most adults.
- Embarked port and fare amount showed survival trends.

## 📎 Files

- `titanic.csv` – The dataset used for analysis
- `titanic_eda.ipynb` – Jupyter Notebook with all code and visualizations (recommended to add)
- `titanic_EDA.pdf` – PDF version of the report

## ▶️ How to Run

1. Clone the repository
2. Make sure you have Python and Jupyter installed
3. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
4.Open and run notebooks/titanic_eda.ipynb

📌 Author
Author: Ramya Badathala

GitHub: RamyaBadathala
