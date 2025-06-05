# 🛍️ Ecommerce Product Dashboard

## 📊 Overview

This project features a **visual dashboard** designed to provide a comprehensive view of business performance, focusing on pricing strategy, sales trends, and product-level insights. It highlights key metrics such as revenue by month, average price point, units sold, and product attributes to support strategic decision-making.

The dashboard addresses the following core business questions:

**How has our overall sales performance trended over the year?** 
**What does that reveal about customer purchasing behavior and product pricing effectiveness?**
**"What characteristics do our top-performing products share, and how can we use those insights to optimize future listings?"**

---

## 📁 How to Open the Dashboard

You can open the dashboard in Tableau in one of two ways:

1. [**Tableau Public**](https://public.tableau.com/app/profile/muneca001/viz/EcommerceProductDashboard/Dashboard)

2. **Use the direct file**:
   - Go to the `dashboard/` folder
   - Open the file: `Ecommerce Product Dashboard.twbx`

---

## Project Structure

```
project-root/
│
├── dashboard/
│   ├── Ecommerce Product Dashboard.twbx       # Main Tableau dashboard
│   └── ~dashboard1__15868.twbr                # Tableau auto-generated backup file
│
├── data/
│   ├── cleaned_shein_sample.csv               # Cleaned dataset used in the dashboard
│   ├── dates.csv                              # Supplementary data (new)
│   └── shein_sample_5000.csv                  # Original sample from Kaggle
│
└── scripts/
    └── cleaning.ipynb                         # Jupyter Notebook for data cleaning
```
---

## 🧹 Data Cleaning

Data cleaning and preparation were done in **Python** using `pandas` in the `cleaning.ipynb` notebook. This step included:

- Feature Engineering  
- Handling missing values
- Checking for duplicate values
- Standardizing column names and types  
- Adding dates   

This cleaned data was then exported and used to build the dashboard in Tableau.

---

## 📈 References 

The data used in this project is from **Kaggle**, specifically the ["SHEIN E-commerce Dataset"](https://www.kaggle.com/datasets/trainingdatapro/shein-e-commerce-dataset).

Due to size limitations on GitHub, only the **first 5,000 rows** of the dataset were used. 

Some code from a [Kaggle contributor](https://www.kaggle.com/code/creativepixel/e-commerce) was referenced to help load the dataset.

