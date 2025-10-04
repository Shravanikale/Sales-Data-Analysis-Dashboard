# 🛍️ Sales Data Analysis Dashboard

## 📊 Project Overview

This project analyzes a company’s sales performance using **Python** (Pandas, Matplotlib) for data cleaning and exploration, and **Power BI** for interactive dashboard visualization.

The goal is to identify **sales trends**, **profitable regions**, and **top-performing products**, and to present these insights through an interactive dashboard.

---

## 🧠 Objectives

* Analyze sales data to find patterns and performance trends.
* Visualize **KPIs** such as Total Sales, Profit Margin, Top Products, and Regional Sales.
* Use **Python** for EDA (**E**xploratory **D**ata **A**nalysis).
* Create a **Power BI dashboard** for interactive insights.

---

## 🧰 Tools & Technologies

* **Python**: Pandas, NumPy, Matplotlib, Seaborn
* **Power BI**: Interactive dashboards & reports
* **Excel**: Initial data cleaning and formatting
* **GitHub**: Version control & project hosting

---

## 📁 Dataset

The dataset (`sales_data.csv`) contains 1,000+ sales records with columns like:

| Column Name | Description |
| :--- | :--- |
| Order ID | Unique order identifier |
| Date | Order date |
| Region | Region of sale |
| Product Category | Product group (Electronics, Furniture, etc.) |
| Product | Specific product name |
| Quantity | Units sold |
| Sales | Revenue generated |
| Cost | Cost incurred |
| Profit | Sales – Cost |

---

## 🔍 Key Insights

* **South Region** contributed **~40%** of total sales.
* **Electronics** category had the highest profit margin.
* Seasonal spikes during **November–December** due to festive demand.
* Recommended restocking top 5 products in high-demand regions.

---

## 📈 Python EDA Notebook

The `sales_analysis.ipynb` file contains:

* Data loading and cleaning using **Pandas**
* Exploratory Data Analysis (**EDA**) using **Matplotlib/Seaborn**
* Trend and profit analysis
* Export of cleaned dataset for Power BI dashboarding

---

## 📊 Power BI Dashboard

The dashboard includes:

* **KPI Cards**: Total Sales, Total Profit, Profit Margin
* **Charts**:
    * Sales by Region
    * Top 10 Products by Sales
    * Monthly Sales Trends
* **Filters (Slicers)**: Region, Category, Month

---

## 🚀 How to Run

1.  **Clone this repository**
    ```bash
    git clone [https://github.com/](https://github.com/)<your-username>/sales-data-analysis-dashboard.git
    cd sales-data-analysis-dashboard
    ```
2.  **Install dependencies**
    ```bash
    pip install pandas matplotlib seaborn
    ```
3.  **Open the notebook**
    ```bash
    jupyter notebook notebooks/sales_analysis.ipynb
    ```
4.  Open `sales_dashboard.pbix` in Power BI to view the dashboard.

---

## 🏆 Results

* Improved understanding of regional and product-based performance.
* Automated sales reporting and trend visualization.
* Enhanced decision-making with data-backed insights.

---

## ✨ Author

**Shravani Kale**
📍 Pune, India
📧 shravani.kale@email.com
