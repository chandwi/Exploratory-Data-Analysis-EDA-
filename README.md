# 🧪 Exploratory Data Analysis (EDA) - Sales Dataset

This project performs Exploratory Data Analysis (EDA) on a retail sales dataset using **Python**, **Pandas**, **Seaborn**, and **Matplotlib**. The objective is to extract meaningful insights, detect trends, and visualize patterns in sales across different dimensions such as products, cities, months, and hours.

---

## 📁 Files

- `sales_data.ipynb` – Jupyter Notebook containing the step-by-step analysis and visualizations.
- `sales_data.pdf` – PDF version of the final analysis (includes graphs and observations).

---

## 📊 Dataset Overview

**Columns Analyzed:**

- `Product` (Categorical)
- `City` (Categorical)
- `Quantity Ordered` (Numerical)
- `Price Each` (Numerical)
- `Month` (Numerical)
- `Hour` (Numerical)
- `Sales` (Numerical, derived)

**Preprocessing:**

- ✔️ Removed **null values**
- ✔️ Dropped **141k duplicates**
- ✔️ Created new columns: `Month`, `Hour`, and `Sales`

---

## 📈 Key Insights

1. **December** had the highest number of orders, indicating peak sales during the holiday season.
2. **MacBook Pro Laptop** is the most expensive product at **$1700**.
3. **AAA Batteries (4-pack)** was the most sold item in quantity.
4. There’s a visible correlation between `Sales`, `Quantity Ordered`, and `Price Each`.
5. Product sales differ significantly by **city** and **hour of the day**.

---

## 📉 Visualizations

- Count plots of monthly sales
- Bar charts of product prices
- Correlation heatmap
- City-wise product demand comparison (clustered bar chart)

---

## 🛠️ Tools Used

- Python (Jupyter Notebook)
- Pandas
- Matplotlib
- Seaborn

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/titanic-eda.git
   cd titanic-eda
# Sales_EDA
