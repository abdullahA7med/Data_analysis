# 🏀 Basketball Players Data Analysis

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-2.x-green?logo=pandas)](https://pandas.pydata.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> 🔍 A comprehensive exploratory data analysis (EDA) project on basketball player statistics using Python, Pandas, and Seaborn.

---

## 📋 Table of Contents

- [📌 Overview](#-overview)
- [✨ Key Analysis Steps](#-key-analysis-steps)
- [🛠️ Technologies Used](#️-technologies-used)
- [🚀 Getting Started](#-getting-started)
- [📁 Project Structure](#-project-structure)
- [📊 Key Insights](#-key-insights)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [📬 Contact](#-contact)

---

## 📌 Overview

This project performs an end-to-end exploratory data analysis on a **basketball players dataset** to uncover patterns, detect anomalies, and extract actionable insights about player performance, positions, and geographical distribution. The analysis is documented in a Jupyter Notebook for reproducibility and transparency.

🎯 **Objectives:**
- Assess data quality (missing values, duplicates)
- Understand statistical distributions of player metrics
- Identify outliers and correlations between features
- Visualize player position distributions and performance by country
- Highlight top-performing players based on attack rating

---

## ✨ Key Analysis Steps

| Step | Description | Visualization/Method |
|------|-------------|---------------------|
| 1️⃣ | 🔍 **Data Quality Check** | `isnull().sum()`, `duplicated().sum()` |
| 2️⃣ | 📊 **Summary Statistics** | `describe()`, `info()` |
| 3️⃣ | 📦 **Outlier Detection** | Box plots for numerical features |
| 4️⃣ | 🔗 **Correlation Analysis** | Heatmap + `corr()` method |
| 5️⃣ | 🔀 **Multivariate Relationships** | Pairplot for feature interactions |
| 6️⃣ | 📈 **Position Distribution** | Countplot of player positions |
| 7️⃣ | 🥧 **Position Composition** | Pie chart showing % per position |
| 8️⃣ | 🌍 **Performance by Country** | `groupby('country')` + mean attack rating |
| 9️⃣ | 🏆 **Top Performers** | Bar plot of top 10 players by attack rating |

---

## 🛠️ Technologies Used

```yaml
Languages:
  - Python 3.8+

Libraries:
  - pandas      # Data manipulation
  - numpy       # Numerical operations
  - matplotlib  # Basic plotting
  - seaborn     # Statistical visualizations
  - jupyter     # Interactive notebook environment

Environment:
  - VSCode / Jupyter Notebook
  - pip / conda for dependency management