# 🌍 Life Expectancy & Health Indicators

**Exploring global health data using BigQuery, clustering, and PCA to uncover patterns in life expectancy.**

---

## 📌 Project Overview

This project analyzes life expectancy and public health indicators across countries and years. Using Python, BigQuery, and machine learning techniques like PCA and KMeans clustering, it aims to uncover key trends and regional patterns in global health outcomes.

The project was designed as a portfolio piece for data engineering internships, with a focus on both analysis and end-to-end data pipeline skills.

---

## 🧰 Tools & Technologies

- Google BigQuery (SQL queries + dataset hosting)
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (PCA, KMeans)
- Jupyter Notebook
- GitHub (project versioning)
- Google Cloud Platform

---

## 📊 Key Highlights

- Cleaned and transformed a global health dataset using SQL and Python
- Ran regression analysis to understand relationship between GDP and health indicators
- Built a PCA-based clustering model to segment countries by health traits
- Used correlation matrix and visualizations to draw out insights
- Exported clustered data back to BigQuery to demonstrate end-to-end pipeline skills

---

## 🔍 Insights

- Countries with higher **income composition** and **schooling years** tend to have higher life expectancy.
- Some low-GDP countries cluster together based on shared health challenges such as higher HIV/AIDS rates and lower BMI.
- Clustering revealed 3 major groups of countries based on BMI, mortality, HIV/AIDS, schooling, and income composition.

---

## 🚀 How to Explore

You can view the full Jupyter notebook in this repo.  
To explore the data or rerun the analysis:

1. Clone the repo  
2. Open the `.ipynb` file in Jupyter  
3. Replace credentials to connect to your own BigQuery project if needed

---

## 👤 Author

Ganbold Bold — *Data Engineering & Analytics student*  
This project was built as part of a portfolio to apply for data engineering roles, including at League (GCP-based health platform).

