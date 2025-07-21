# 💎 Diamond Dataset Analysis

**Author**: Liron Shpiegel  
**Project**: FIT – Final Project  
**Tool**: Jupyter Notebook (Python)  
**Dataset**: diamonds.csv (from seaborn)

---

## 📌 Project Overview

This project presents an in-depth data analysis of a diamond dataset. It includes univariate and multivariate analysis to understand how different attributes (like cut, color, clarity, and carat) affect the price of diamonds.

The notebook also provides visual insights into which characteristics are most influential in pricing and how different combinations of features interact.

---

## 📊 Objectives

- Perform initial data cleaning and inspection.
- Analyze distributions of each feature (univariate analysis).
- Explore interactions between features (multivariate analysis).
- Identify key variables affecting diamond price.
- Visualize the relationships using various graphs.

---

## 📁 Files

- `project 3 by Liron Shpiegel.ipynb`: Main Jupyter notebook with full analysis and visualization.
- `diamonds.csv`: Dataset used for the analysis (includes ~54,000 diamond records).

---

## 📈 Key Features Analyzed

- `carat`: Weight of the diamond.
- `cut`: Quality of the cut (Fair, Good, Very Good, Premium, Ideal).
- `color`: Diamond color, from D (best) to J (worst).
- `clarity`: A measurement of how clear the diamond is.
- `depth`, `table`: Physical dimensions of the diamond.
- `price`: Price in US dollars.
- `x`, `y`, `z`: Length, width, and depth measurements (in mm).

---

## 🔍 Key Insights

- Carat and price have a strong positive correlation.
- Cut, clarity, and color have clear effects on price but interact with carat size.
- Premium and Ideal cuts are the most common and tend to command higher prices.
- Visualizations such as box plots, scatter plots, and heatmaps were used to uncover trends.

---

## 🧹 Data Cleaning

- Checked and handled missing values (if any).
- Converted categorical variables for plotting.
- Filtered unrealistic measurements (e.g., x=0 or z=0).

---

## 🖥️ Tech Stack

- Python 3.x
- pandas
- matplotlib
- seaborn
- numpy

---

## ▶️ How to Run

1. Clone the repository or download the `.ipynb` file.
2. Make sure the `diamonds.csv` file is in the same directory.
3. Open the notebook in Jupyter Notebook / JupyterLab.
4. Run all cells in sequence to see the full analysis.

---

## ✍️ Author

Liron Shpiegel  
Open University | Data Analysis and Visualization  
July 2025

---
