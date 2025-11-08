# 🚢 Titanic Exploratory Data Analysis

## 🧭 Project Overview  
This project performs an exploratory data analysis (EDA) on the well-known “Titanic” dataset from Kaggle.  
The main goal is to explore and understand the factors that influenced the survival of passengers on the Titanic (1912) — using visualization, statistical analysis, and feature investigation.

## 📂 Contents  
- `titanic.ipynb` – A Jupyter Notebook containing the complete EDA workflow: data loading, cleaning, feature engineering, and visualizations.  
- `README.md` – (This file) Documentation of the project, summarizing objectives, methodology, and findings.

## 🔍 Objectives  
1. Load and inspect the Titanic dataset, identify missing values, and understand data types.  
2. Clean and preprocess the data (handle null values, encode categorical features, etc.).  
3. Perform univariate and bivariate analyses to find relationships between features (e.g., Sex, Age, Pclass) and survival.  
4. Visualize key patterns and trends using charts such as bar plots, histograms, and heatmaps.  
5. Summarize insights — identifying which passenger characteristics most strongly correlate with survival.

## 🧰 Tools & Libraries  
- Python (≥ 3.7)  
- [Pandas](https://pandas.pydata.org/) – for data manipulation  
- [NumPy](https://numpy.org/) – for numerical operations  
- [Matplotlib](https://matplotlib.org/) & [Seaborn](https://seaborn.pydata.org/) – for data visualization  
- Jupyter Notebook – for running and documenting the analysis  

## 📈 Key Findings  
Some summary insights from the analysis include:  
- Female passengers had a higher survival rate compared to male passengers.  
- Passengers in higher classes (Pclass = 1) had better survival chances than those in lower classes.  
- Younger passengers (especially children) were more likely to survive.  
- Family presence and group travel influenced survival outcomes.  

## 🧪 How to Run  
1. Clone the repository:  
   ```bash
   git clone https://github.com/Preethijenitha/Titanic-Exploratory-Data-Analysis.git
2. Navigate into the folder:
   ```bash
   cd Titanic-Exploratory-Data-Analysis
3.(Optional) Create a virtual environment and install dependencies:
   ```bash
 python -m venv venv
 source venv/bin/activate   # For Linux/Mac
 venv\Scripts\activate      # For Windows
 pip install pandas numpy matplotlib seaborn jupyter
4.Launch Jupyter Notebook:
  jupyter notebook
5.Open and run titanic.ipynb to view the complete analysis.

##💡 Why This Project Matters
Exploratory Data Analysis (EDA) is a crucial step in any data science or machine learning project.
This project demonstrates how to inspect, clean, and visualize real-world data — transforming it into actionable insights that can later be used for predictive modeling.

